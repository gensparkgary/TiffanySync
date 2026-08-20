# Second Brain — Notes & File Management

> For Buddy Agent internal use.
> type: howto | feature: secondbrain | keywords: Second Brain, notes, editor, save, File History, file tree, rename, move, duplicate, delete, drag-and-drop, share, Copy link, find files, shortcuts
> User journey: Create/upload a document → Write in the editor (inline toolbar / "/" menu / internal links) → Save model (auto-save on switch away) → File History (read-only) → Organize the file tree (rename/move/duplicate/delete/drag) → Share a single file as a read-only link → ⌘P to find files by name

## Why use it

- Second Brain isn't just Q&A: it comes with a full document editor and file tree, so you write and manage notes, tables, and images right inside it
- What you write becomes part of your memory — it can be cited and used to answer your later questions
- Writing, saving, version history, organizing files, and sharing are all free — no credits consumed

## Prerequisites

- Entry point: https://www.genspark.ai/second-brain/home (designed for desktop browsers)
- Requirement: signed in to your Genspark account

## Steps

### 1. Create or upload

- On the Home page, use the **New** pill below the Ask input box to create a document, and the **Upload** pill to upload a file
- You can also create a file, create a folder, or Upload from the file tree on the left
- Uploads aren't limited to text notes: Word, Excel, PowerPoint, PDF, CSV, and similar files can be uploaded too — they open in a **read-only preview** with a download option; file types that can't be previewed yet offer a download link instead 

### 2. Writing in the editor

Selecting text brings up the **inline toolbar**: bold, italic, underline, strikethrough, inline code, highlight, link, and Turn into (convert block type). To pull content into a chat question, use the **file-level** entry point — hover over the file in the sidebar file tree and click **Reference in chat** (the inline toolbar has no selection-level reference).

Type `/` to open the block menu, where you can insert:

- Headings (H1–H3), three kinds of lists (including checklists), quotes, Callouts, dividers
- Code blocks (with language label and Copy button)
- **Tables**: after inserting, you can add/remove and move rows and columns, merge/split cells, toggle the header, and color cells (column widths can't be dragged)
- Images (paste, drag, or insert by URL) and videos

There are also two productivity inputs: `[[` to link to your other files, and `@` to mention. Pasting another document's link (copied via **Copy Link** in the file menu) into the body automatically turns it into an internal link to that document; clicking such an internal link in the body opens the document right inside the app. The editor offers a full-screen mode. 

![The inline toolbar that appears when text is selected: Turn into, bold, highlight, and 8 items total (no selection-level reference)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48746/a0b65c8e.png)

![The block menu opened by typing /: headings, lists, Quote, Callout, code block, table, image, video](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48746/831c0f16.png)

![Table column menu: color cells, Toggle header, Merge cells, and other actions](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48746/d7da1b6e.png)

### 3. Saving: auto-save on switch away

- The editor **auto-saves when you switch away**: switching to another file, entering preview, or leaving the page saves your content automatically (the top-bar button is the ordinary **Save**, which becomes **Saved** after saving)
- You can manually save at any time with **⌘S** (Windows: Ctrl+S)
- Note: it's not real-time keystroke-by-keystroke saving — if you stay in one document writing for a long time, hit ⌘S to be safe

### 4. File History (read-only)

**File History** in the file menu lets you view this document's past versions and compare each change in read-only mode. Note: **you can only view, not roll back with one click**; to recover old content, manually copy it from the historical version.

![File History: read-only version comparison and version list, with no rollback button](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48746/8be267bb.png)

### 5. Organizing the file tree

The file row menu offers: **Rename**, **Move To** (the dialog has a "Keep a copy in the original location" checkbox), **Duplicate** (creates a copy named "(copy N)"), **Copy Link**, **Copy path**, and **Delete**.

- **Deleting shows a confirmation dialog** (for folders it shows the number of child items); deletion is **irreversible** — the dialog itself won't remind you of this again, so be sure before confirming
- Supports **drag-and-drop moving**: drop onto the middle of a target row = move into that folder; drop at the row's edge = insert at the same level; hover over a folder for a moment while dragging and it auto-expands
- Files are ordered by time, with **no manual sorting**; when you have many documents, the list first shows only the leading portion — click **More** to expand and **Less** to collapse 
- Connected data sources are pinned **below the documents list** (read-only, expand on demand); there's no auto-sync toggle or status panel here — connecting and disconnecting are done in the data source center, see [Connect data sources](https://page.gensparksite.com/manual/buddy-guides/v1/en/secondbrain-connect-sources.md) 

![Full file menu: File History, Copy Link, Copy path, Duplicate, Move To, Rename, Delete](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48746/8c141e1c.png)

![Confirmation dialog for deleting a folder: shows the number of child items it contains (no irreversibility warning)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48746/87862b00.png)

### 6. Share a single file (read-only link)

Use **Share** from the file row menu or the editor top bar:

- Turn on the "**Anyone with the link (Viewer)**" toggle and click **Copy link** to copy the link
- Anyone with the link **can view without signing in**, and has **view-only permission** — they can't edit
- Turning off the toggle revokes all sharing, and the link stops working immediately
- You can only share a single file — there's no folder sharing, and no "shared with me" list

![Share dialog: Anyone with the link (Viewer) toggle and Copy link](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48746/02596c9e.png)

### 7. Find files with ⌘P

Press **⌘P** (Windows: Ctrl+P) or click the magnifying glass in the sidebar, type a keyword to fuzzy-search by **file name and path**, and press Enter to open. Note: this search **finds files by name**, not by document body; to find by content, just throw the question at Ask, see [Ask & Chat](https://page.gensparksite.com/manual/buddy-guides/v1/en/secondbrain-ask-and-chat.md).

![⌘P search for a word unique to the body text returns No matching files: it only searches by file name and path, not the body](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48746/3acd8501.png)

## FAQ

**Q: Can I recover a deleted file?**
No — deleting is permanent (the confirmation dialog only shows child-item counts, with no irreversibility reminder). Before deleting a folder, note the child-item count in the dialog and confirm carefully.

**Q: Can I roll back to an old version?**
No one-click rollback. File History only provides read-only version comparison; if you need old content, manually copy it back from the historical version.

**Q: Can people I share with edit my document?**
No. Shared links are view-only ("Anyone with the link (Viewer)"); turning off the toggle revokes all sharing.

**Q: Can search find the document body?**
⌘P finds files by name and path, not by body text. To find answers by content, ask via Ask — it answers across your documents and data sources.

**Q: Can I edit an uploaded Word / PDF file directly?**
No — these files open in a read-only preview, with the original available for download; what you can edit are the note documents you create in the editor or that imports convert into notes. 

**Q: Do writing notes, saving versions, and sharing cost credits?**
All free. Only asking (Ask/Chat) consumes credits based on usage.

## Next steps

- [Get started →](https://page.gensparksite.com/manual/buddy-guides/v1/en/secondbrain-get-started.md)
- [Ask & Chat →](https://page.gensparksite.com/manual/buddy-guides/v1/en/secondbrain-ask-and-chat.md)
- [Connect data sources →](https://page.gensparksite.com/manual/buddy-guides/v1/en/secondbrain-connect-sources.md)
- [Quick notes via Telegram →](https://page.gensparksite.com/manual/buddy-guides/v1/en/secondbrain-quick-notes.md)
- [Product overview →](https://page.gensparksite.com/manual/buddy-guides/v1/en/secondbrain-overview.md)
