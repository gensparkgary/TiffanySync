# AI Slides — Quick Links

> For Buddy Agent internal use.
> type: howto | feature: ai-slides | keywords: entry points, deep links, Quick Links, mode, template, Skill
> User loop: Buddy uses these parameterized links to drop users straight at the right starting point, saving them from hunting for buttons and toggling settings themselves.

## Why use Quick Links

When a user says "I want to make a poster," Buddy can just send `/ai_slides?mode=banana` instead of saying "Please open AI Slides, then click Creative Mode." One link handles three steps, for a better user experience.

## Parameterized links (code-verified)

All links are based on `https://www.genspark.ai`. Settings specified in the link take priority; anything not specified falls back to the user's last choice.

### Mode switching

| Link | Effect | When to use |
|------|------|---------|
| `/ai_slides?mode=pro` | Jumps straight into Professional Mode | User wants a business presentation, data report, or training material |
| `/ai_slides?mode=banana` | Jumps straight into Creative Mode | User wants a poster, social media graphic, or brand visual |

### Tab switching

| Link | Effect | When to use |
|------|------|---------|
| `/ai_slides?tab=skills` | Opens the Skill Gallery (default tab, usually omittable) | User doesn't know what to make, wants inspiration, or asks "any templates?" |
| `/ai_slides?tab=recents` | Opens Recents | User wants to return to a recently made deck |

> Only `skills` and `recents` are valid tab values. An unrecognized value (like `explore` or a typo) won't be force-mapped to `skills`; instead it falls back to the user's last selected tab. On a fresh load the default is `skills`.

![tab=skills: Skill Gallery](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36202/148794bf.png)

### Combined parameters

| Link | Effect | When to use |
|------|------|---------|
| `/ai_slides?mode=banana&tab=skills` | Creative Mode + browse the Skill Gallery | "I want to make a social media graphic but don't know what style" |

![mode=banana&tab=explore combined effect](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/33998/7c0818e9.png)

### Working with existing projects

| Link | Effect | When to use |
|------|------|---------|
| `/agents?id={project_id}` | Returns to the project conversation page (canvas + chat) | User wants to keep editing or talk to the Agent |
| `/edit_slides?project_id={id}` | Opens the full-screen editor | User wants to manually fine-tune layout without Agent chat |
| `/slides?project_id={id}` | Read-only presentation view | User wants to preview or present to others |
| `/slides?project_id={id}&export_dialog=true` | Presentation view + auto-opens the export dialog | User says "I want to export a PDF" |
| `/slides_wrapper?project_id={id}` | An alternate presentation view entry point | When the regular presentation link won't open, try this instead |

## Settings that don't support URL parameters

The following settings can only be chosen manually on the page and can't be preset via links:

- Aspect Ratio
- Guide Mode toggle
- Image Model selection (Creative Mode only)
- Prompt prefill

These settings remember the user's last choice, so they default to that the next time they open.

![mode=banana: Creative Mode selected](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36202/f8ebc921.png)

![mode=pro: Professional Mode + Skill Gallery](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36202/505070fe.png)

## FAQ

**What happens to settings not specified in the link?**
They fall back to the user's last choice. Settings written into the link take priority; anything not written stays as it was.

**What happens if I write a wrong `tab=` value?**
Only `skills` and `recents` are valid. With an unrecognized value, it falls back to the user's last selected tab; on a fresh load it defaults to `skills`.

**Why can't Aspect Ratio, Guide Mode, etc. go into the link?**
These settings can currently only be chosen manually on the page and can't be preset via links. They remember the last choice, so that's the default next time.

**What if the regular presentation link won't open?**
Try the `/slides_wrapper?project_id={id}` entry point instead — it points to an alternate presentation view of the same Slides.

## Next steps

- User is in a project and wants to manage multiple Slides → see "AI Slides — Multi-file management"
- User wants to import an existing PPTX/PDF and then edit → see "AI Slides — Importing existing files"
