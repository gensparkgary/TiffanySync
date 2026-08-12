# Skills — Parameterized Links (Quick Links)

> For Buddy Agent internal use.
> type: howto | feature: skills | keywords: Quick Links, Deep Link, URL parameters, try, owner, just_installed, links
> Buddy use case: Trigger Skill installation and trial directly via parameterized URLs, reducing user steps

## Why Use Parameterized Links

- **One step to done**: After clicking the link, users go straight into trying a Skill — no manual search or install needed
- **Recommended scenario**: When a user asks "Is there a tool that does XX?", Buddy can hand them a link they click to try it out
- **Sharing & distribution**: Share the link in an email, doc, or chat, and the recipient lands right where they need to be

## Supported URL Parameters (Code-Verified)

### `try` + `owner` — Install and Try a Skill

```
/skills?try={skill-slug}&owner={cogen-id}
```

| Parameter | Description | Example |
|------|------|------|
| `try` | The Skill's slug (kebab-case name) | `competitor-analysis` |
| `owner` | The cogen ID of the Skill owner | `cog-abc123` |

**Behavior**:
1. If the Skill isn't installed → auto-install
2. The Skill is automatically selected in the SkillBar
3. The input box is pre-filled with a generic template: `"I just added the {name} skill. Can you demo it with some great examples?"`
4. The URL parameters are automatically removed after being consumed (one-time use)

![try + owner parameters in effect: Skill selected and prompt pre-filled](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34216/335ed58d.png)

**Both parameters must be present together** — missing either one renders it ineffective.

![Missing owner parameter has no effect](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34216/6cf13788.png)

**Known limitations**:
- For Community Skills (where the owner is `system-pipeline`), installation may fail due to a catalog loading timing issue (showing "Couldn't install"). Already-installed or personal Skills are unaffected.

![Community Skill install failure: "Couldn't install"](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34216/4ca35667.png)
- The URL parameters are removed before the action executes, so if installation fails, refreshing the page won't retry it — you'll need to rebuild the link.

**Example**:
```
/skills?try=weekly-report&owner=cog-42
```

### `just_installed` — Pre-fill for a Just-Installed Skill

```
/skills?just_installed={skill-slug}
```

| Parameter | Description | Example |
|------|------|------|
| `just_installed` | The slug of the just-installed Skill | `email-summarizer` |

**Behavior**:
1. Doesn't trigger installation (the Skill is already installed)
2. Expected to select the Skill in the SkillBar and pre-fill an example prompt
3. The parameter is automatically removed after being consumed

**Known limitation**: On a cold page load, the SkillBar component may not yet be mounted, causing the selection and pre-fill to silently fail (the page displays normally but the SkillBar still shows "Select a skill first"). It works fine when navigating from within the page (non-cold load).

![just_installed parameter fails on cold load: not selected / not pre-filled](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34216/19b935d3.png)

**Use case**: After a user installs a Skill from a Public Share page (`/skills/share/{token}`), they're automatically redirected to this URL.

### Public Share Page Parameters

```
/skills/share/{token}?auto_install=1
```

| Parameter | Description |
|------|------|
| `auto_install` | When set to `1`, installation is automatically triggered after the page loads |

**Use case**: A logged-out user accesses a Public Share link → is redirected to log in → returns with `auto_install=1` after logging in → the Skill auto-installs.

## Settings Not Controllable via URL Parameters

The following features **cannot** be controlled through URL parameters:
- Tab switching (Community / Team / My Own)
- Filters (Publisher / Role / Output)
- Search keywords
- Selecting multiple Skills simultaneously in the SkillBar

![tab=team parameter has no effect](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34216/053bb27e.png)

---

## Screenshot Checklist

| # | Screenshot ID | Capture Location | Required Visible Content | Purpose |
|---|---------|---------|-------------------|------|
| 1 | `quicklink-try-result` | After `/skills?try=xxx&owner=yyy` loads | SkillBar with Skill selected, input box with pre-filled prompt | Verify the try parameter works |
| 2 | `quicklink-just-installed` | After `/skills?just_installed=xxx` loads | SkillBar with Skill selected | Verify the just_installed parameter works |
