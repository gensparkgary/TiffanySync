# Skills — Discover and Use a Community Skill

> For Buddy Agent internal use.
> type: howto | feature: skills | keywords: Community Skills, discover, filter, install, run, Publisher, Role, Customize
> User loop: /skills → browse Community Skills → filter (Publisher/Role/Output) → click a card → install → return to home → select in SkillBar → enter prompt → see results

## Why Start with Community Skills

- **No need to build your own**: 100+ verified Skills covering marketing, research, sales, development, and more
- **Recommended by role**: Pick your role (Sales / Marketer / Product manager / Researcher, etc.) and the system recommends the most relevant Skills
- **One-click install and go**: Click Add & Use → it's ready to use back on the home page, no configuration needed

## Prerequisites

- Login required
- Entry point: `/skills` or the Skills icon in the sidebar

## Steps

### 1. Open the Skills Home Page

Open `/skills`.

The home page shows three tabs:
- **Community Skills** — platform picks (shown by default)
- **Team Skills** — Skills published by your team
- **My Own Skills** — Skills you've created

The home page also shows a **"Recently viewed"** area listing Skills you looked at recently, for one-step recall.

![Skills home page with three tabs: Community / Team / My Own](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34211/4a853875.png)

### 2. Browse and Filter

Community Skills offer three filter dimensions:

| Filter Dimension | Example Options |
|---------|---------|
| **Publisher** | Anthropic (50+) / OpenAI (8) / Genspark (22+) |
| **Role** | Sales / Marketer / Product manager / Researcher / Engineer / Designer / Operations / Founder / Creator / General |
| **Output** | Document / Research / Data / Chart / Code... |

Click filter tags to combine them. You can also use the search box at the top to search by Skill name or keyword.

![Three-dimension filter panel: Publisher / Role / Output](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34211/6727a52a.png)

### 3. View Skill Details

Click a Skill card you're interested in to open its details. In the details you can see:
- The Skill's description and purpose
- Preview media (image/video/audio)
- Publisher info and Category
- Example usage (Examples)
- The **Add & Use** button (one-click install and use)
- The **Customize** button (make your own editable copy of this Skill — see "Customize" below)

![Skill detail dialog: preview, Publisher info, Add & Use button](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34211/2084e490.png)

### 4. Install the Skill

Click the **"Add & Use"** button to install the Skill. Once installed, the Skill appears in your installed list and can be selected from the SkillBar. An installed Skill shows an **"Uninstall"** option on its detail page.

![Installed: Added badge, 1 skill in use, prefilled input box](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34211/d5be9573.png)

### 4b. Customize — Turn a Community Skill into Your Own

If a curated Skill is close to what you need but you want changes (different output format, data source, or rules), click **"Customize"** in its detail:

1. A confirmation dialog (**"Make your own copy of {name}"**) appears — click **"Create & open editor"**
2. The system creates your own copy and opens an editing chat where you describe changes in plain language
3. The copy is saved in **My Own Skills**, labeled **"from you"** on the card; it's an independent copy and won't receive updates to the original
4. Once you've customized a Skill, its detail no longer shows Customize — it shows **"Edit"** instead (to keep editing your copy directly)

### 5. Run the Skill

Return to the Skills home page. In the SkillBar area:
1. Click **"Select a skill first"** or the name of an installed Skill
2. Choose the Skill you just installed from the dropdown
3. Enter your specific request in the input box (e.g., "Analyze last quarter's sales data")
4. Click send

![SkillBar dropdown: list of installed Skills with In Use status](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34211/4c492569.png)

### 6. View the Results

The Skill runs in the Sandbox, where you can see:
- Real-time execution steps (searching, generating files, running code, etc.)
- Streaming text output
- Deliverable files (previewable and downloadable)

![Skill running: execution steps and streaming output](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34211/b78f1d5a.png)

## Notes

- Running a Skill consumes credits
- Some Skills require connecting Connectors first (e.g., a Skill that reads Gmail needs your Google account connected first)
- You can use the `/` shortcut in the SkillBar to search and select Skills

![Slash command search panel](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34211/7864dfc4.png)

---

## Screenshot Checklist

| # | Screenshot ID | Capture Location | What Must Be Visible | Purpose |
|---|---------|---------|-------------------|------|
| 1 | `discover-community-tab` | `/skills` Community Tab | Community Skills count, Skill card list | Show the Community Skills entry point |
| 2 | `discover-filters` | Filter panel | Publisher/Role/Output filter tags | Show filtering options |
| 3 | `discover-skill-detail` | Skill detail dialog | Description, preview, Add & Use button, Customize button | Show pre-install information |
| 4 | `discover-customize-dialog` | Customize confirmation dialog | "Make your own copy of …" title, "Create & open editor" button | Show the customize flow |
| 5 | `discover-skillbar-select` | SkillBar dropdown | Installed Skill list, selection state | Show how to select an installed Skill |
| 6 | `discover-running` | Skill running | Execution steps, streaming output, deliverable files | Show the run process and results |
