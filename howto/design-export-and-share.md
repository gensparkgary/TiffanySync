# Genspark Design — Export, Present & Share

> For Buddy Agent internal use.
> type: howto | feature: genspark-design | keywords: Present, presentation, Build it, export, Handoff, PDF, Standalone HTML, Share, sharing, Duplicate, Remix, PPTX, MP4, Canva
> User loop: Design complete → Present in fullscreen → Build it to export code / PDF → Share for collaboration

## Why You Need These Features

Finishing a design isn't the end. Present lets you show it fullscreen, Build it exports runnable code, and Share generates a link to invite collaborators. These features work across all design types.

## Present — Fullscreen Presentation

Works for **all design types** (websites, posters, slide decks, videos, etc.), not just slide decks.

### Steps

1. Click the **"Present"** button in the Canvas top bar
2. Enter fullscreen presentation mode
3. For multi-page designs (Slide deck / Flipbook / Paged Book), use arrow keys or click to switch pages
4. The bottom shows a "Slide X / Y" page indicator

![Present fullscreen mode (arrow keys to flip pages, page indicator 01/03)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34397/5f96b0e2.png)

### Speaker Notes (Slide deck only)

When presenting a slide deck, you can open the Speaker Notes panel:

- Each page has its own speaker notes
- Edit notes in advance; changes save automatically
- Only you can see them while presenting

![Speaker Notes panel (per-page, auto-saved)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34397/52dff6c7.png)

## Build it — Code Export

Export any design as runnable code. Not limited to websites — videos, documents, and posters can all be built.

### Steps

1. Click the **"Build it"** button in the Canvas top bar
2. Choose an export target:

| Target | Description |
|------|------|
| **Website** | Opens a runnable website in a new tab |
| **App** | Generates an app code package |

3. The AI prepares the code (status: Preparing → Ready)
4. Click **"Open"** or **"Download"**. Once ready, you're also offered to open the handoff package in **Genspark Code** (Genspark's coding agent) to keep building from your design

> The Build it button only lights up after the AI finishes the design. You can cancel the preparation at any time.

**Download button**: To the right of Build it there is a standalone **"Download"** button that downloads all project files as a ZIP in one click (no need to open the Build it menu).

![Build it dropdown (Website / App) with the independent Download button](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/51135/a74a94d8.png)

## Handoff to Developer

When you need a more professional code delivery:

1. In the chat, say "Handoff to developer" or "Package this for developer handoff"
2. The AI organizes the code structure, adds documentation, and packages it in a developer-friendly format

## Export Formats

### Save as PDF

Export your design as a PDF:

1. In the chat, say "Save as PDF" or "Export as PDF"
2. The AI opens print view and brings up the browser's print dialog — choose "Save as PDF" to save

> Great for sending posters to print, distributing documents, and more. All design types are supported.

### Export PPTX (Slide deck only)

Export a slide deck to PowerPoint format, with two modes:

- **Editable PPTX**: An editable PowerPoint file that preserves the editability of text, shapes, and other elements
- **Screenshots PPTX**: Each page is embedded as an image, keeping the visuals exactly the same

Steps:
1. In the chat, say "Export as PPTX" or "Download as PowerPoint"
2. The AI generates a .pptx file and downloads it automatically
3. Open it in PowerPoint / Google Slides / Keynote

### Export MP4 (Video only)

Export a video/animation as MP4:

1. Click the export video button on the Canvas, or say "Export as MP4" in the chat
2. Choose parameters in the popup: resolution (1080p / 4K), frame rate (24 / 30 / 60 FPS)
3. The AI renders and downloads it automatically

### Export Image / Export PSD (Posters, etc.)

Export visual designs like posters as an image or a layered source file. Poster projects have an **"Export"** dropdown in the Canvas top bar:

- **Export image**: export as a PNG image
- **Export PSD**: export as a layered Photoshop file — each poster layer becomes a Photoshop layer, and text stays as editable text layers

You can also say "Export as image" or "Download as PNG" in the chat, and the AI generates the image and downloads it automatically.

### Send to Canva

Send your design to Canva to keep editing:

1. In the chat, say "Send to Canva"
2. The AI exports the design and opens the Canva editor

### Standalone HTML

Export as a single file that opens in any browser with a double-click — no internet deployment required:

1. In the chat, say "Save as standalone HTML"
2. The AI generates and downloads the HTML file

> Great for offline presentations or sharing by email.

## Share & Reuse

### Share Link

Click the share icon in the Canvas top bar. In the popup, you can:

- **Choose what to share**: **"Just the design"** (share only the final design pages) or **"The whole process"** (share the whole workspace including the conversation). With Just the design, for designs with multiple pages, you can expand a page picker (with per-page thumbnails); single-page designs always share as "full design · 1 page" to select specific pages and copy links for several pages at once
- **Email invite**: Enter an email address to invite someone, as a **Viewer** or an **Editor** — Editors can edit the design project directly
- **People with access**: Manage existing collaborators and their role permissions
- **Anyone with the link**: When enabled, generates a public link so others can view the design in their browser

![Share popup: access permission levels (Restricted / Anyone with the link)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34397/1d70e0dd.png)

### Duplicate Project

Click the share icon in the Canvas top bar. In the popup, you can:

| Action | Description |
|------|------|
| **Create design system from this project** | Extracts a Design System from the current design |
| **Duplicate project** | Fully duplicates the project (including all files and conversations) |

![Share/duplicate menu: Create design system from this project / Duplicate project](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/51135/d9968a50.png)

The **⋮ menu** in the Canvas top bar includes: **Bookmark** and **Add to Hub**.

![Top bar ⋮ menu: only Bookmark and Add to Hub](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34397/9f8502a5.png)

### Remix

When you see a design someone else has shared, you can **Remix** it to create your own version. Remix copies the design files but does not include the original conversation history.

## FAQ

### Can the code generated by Build it go live directly?

It runs as-is, but we recommend having a developer review it before going to production. Features involving data storage or form submission still need a developer to implement them.

### What if I want to undo a change?

Tell the AI in the chat which changes you want to undo, and it can help you restore them.
