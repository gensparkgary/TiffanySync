# AI Slides — Export, Share & Reuse

> For Buddy Agent internal use.
> type: howto | feature: ai-slides | keywords: Export, Share, PDF, PPTX, Google Slides, Make a Copy, Save as Skill, Presentation View
> User loop: Finish deck → Export at the top to PDF/PPTX/Google Slides → Share link → ⋮ menu Make a Copy to duplicate / Save as Skill to store a reusable Skill

## Why export and share

Finishing a deck isn't the end goal — it's meant to be used:
- **Export to PDF**: send it to people who don't use Genspark; a universal format anyone can open
- **Export to PPTX**: when you need to keep editing in PowerPoint, or your company requires submissions in PPTX format
- **Export to Google Slides**: for teams collaborating in Google Workspace
- **Share link**: the fastest way to share — the recipient views it online, no download needed
- **Save as Skill**: made a great deck? Save it as a Skill to generate a similar style in one click next time

## Prerequisites

- A deck has been generated and you're in the Slides workspace
- The **Export** button and the **⋮** menu are visible at the top of the workspace
- Exporting requires a **Plus, Pro, or Team membership** (see the note under Export below)

## Export

Click the **"Export"** button at the top of the workspace to open the export dialog and choose your format:
- **PDF** — universal sharing format
- **PPTX** — keep editing in PowerPoint
- **Google Slides** — export directly to Google Slides

> Exporting an already-generated deck **uses no extra Credits** — the file is saved straight to AI Drive. (Credits are consumed by the earlier AI generation/editing; the export itself adds no charge.)
>
> **Membership required**: the Export dialog states **"Export features are available for Plus, Pro, and Team members"**. Free-tier accounts cannot export — this gate is about membership, not credit balance.

![Export dialog on a Free-tier account — membership banner at the bottom with "Upgrade to Plus"](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/51105/d0aed6c0.png)

The dialog also lets you choose the export range: **All Pages** or **Custom Range** (a custom page-number range).

Once the export is done, the file is first saved to **AI Drive**, and a success message appears with two options: **View in AI Drive** (view online) and **Download** (download to your device).

![Export format selection dialog](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36121/4ba219a9.png)

![Export range selection (All Pages / Custom Range)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36121/f96db962.png)

When exporting to PPTX, **speaker notes** are written into the file; and if you've run Verify content, the **verification records are included in the corresponding slides' notes** too — whoever receives the file can see the evidence behind every number.

## The ⋮ menu (Presentation View / Make a Copy / Save as Skill)

The **⋮** menu at the top right of the workspace holds three deck-level actions:

### Presentation View

Opens a **shareable slideshow page** in a new tab (scroll through all slides; includes "Play Slides" for fullscreen playback).

Best for: sending a slideshow link to others, or previewing the final result. See [Presenting](https://page.gensparksite.com/manual/buddy-guides/v1/en/slides-present.md) for details.

### Make a Copy

Click **"Make a Copy"** → creates a full, independent copy of your presentation as **a new project** — all content and design included; edits to the copy never touch the original. You can also simply tell the AI **"make a copy"** in the conversation.

Best for: adapting the deck for a different client, translating it into another language, or experimenting boldly without touching the original.

### Save as Skill

Click **"Save as Skill"** → the Agent distills the current conversation and deck into a reusable Skill.

The saved Skill appears in the "My Skills" tab of the Skill Gallery, ready to pick the next time you create.

Best for: when you've made a great template and want to reuse it quickly next time.

Note: you need to have generated at least one slide before you can use this feature.

## Share

Click the **"Share"** button at the top of the page to generate a share link.

Note: the default share permission is **Restricted** (only invited people can access). If you want anyone with the link to view it, switch **General Access** to **"Anyone with the link"** in the Share dialog.

![Share dialog](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36121/b6da3ea8.png)

## Editing in other tools (Canva / Figma / Google Slides)

AI Slides currently has no direct integration with Canva or Figma. If you need to keep editing in these tools, here's the recommended workflow:

| Target tool | Steps |
|---------|---------|
| **Canva** | Export → PPTX → open Canva → Import → upload the PPTX file |
| **Google Slides** | Export → Google Slides (direct export, no intermediate step) |
| **PowerPoint** | Export → PPTX → open and edit in PowerPoint |
| **Keynote** | Export → PPTX → open in Keynote (auto-converted) |
| **Figma** | Export → PDF → Import the PDF in Figma (as a reference layer) |

> After exporting to PPTX, the slides' structure and layout are preserved as much as possible, but some complex animations or custom fonts may look slightly different when opened in other tools.

## Common features (the `...` three-dot menu)

The `...` menu in the top-right corner offers:
- **Bookmark** — save the project to My Bookmarks
- **Add to Hub** — add the project to a Hub workspace

These two features are common to all Agent projects and aren't specific to Slides.

![Three-dot menu (Bookmark / Add to Hub)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36121/401bb170.png)

## FAQ

**Does exporting use Credits?**
No — the export itself is not charged, and the file is saved straight to AI Drive. Credits are consumed by the earlier AI generation and editing steps. Note, however, that Export requires a **Plus, Pro, or Team membership**: Free-tier accounts are blocked from exporting regardless of their credit balance.

**Why do others see "no permission" when they open my share link?**
Share links are **Restricted** by default (only invited people can access). To let anyone view it with the link, change **General Access** to **"Anyone with the link"** in the Share dialog.

**The Save as Skill button is grayed out?**
You need to generate at least one slide first before you can save it as a Skill.

**Where did the old "View & Export" button go?**
The workspace redesign split it up: **Export** is now its own button at the top, while Presentation View, Make a Copy, and Save as Skill moved into the **⋮ menu** at the top right.

**The exported PPTX looks different in PowerPoint than the original?**
Structure and layout are preserved as much as possible, but some complex animations or custom fonts may look slightly different when opened in other tools — this is normal.

## Next steps

- Want to present fullscreen right in the browser without exporting a file? See [Presenting](https://page.gensparksite.com/manual/buddy-guides/v1/en/slides-present.md)
- Made a mess and want to recover an earlier version? See [Version History](https://page.gensparksite.com/manual/buddy-guides/v1/en/slides-version-history.md)
