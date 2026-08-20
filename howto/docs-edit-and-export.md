# AI Docs — Editing & Exporting

> For Buddy Agent internal use.
> type: howto | feature: ai-docs | keywords: editing, AI editing, manual editing, export, PDF, Word, DOCX, Markdown, web, sharing
> User loop: Open the generated document → AI edit or manual edit → roll back with Save Point → export (options vary by document format) or share via Share

## Why this step matters

An AI-generated first draft usually needs a few more rounds of revisions and a different delivery format. AI Docs lets you have AI make changes, edit things yourself, and then export to whatever format the other party needs with a single click.

## Editing the document

### AI editing (uses credits)

**Select a passage of text in the document** and an **AI Rewrite** context bar pops up at the bottom. Type into "Ask Genspark to improve writing…" to describe how you want it changed, and the AI replaces/refines that passage. There's also an inline edit pencil next to section titles for direct edits.

AI editing consumes credits (based on the AI's workload; in our tests a single rewrite used a few dozen credits).
![Select text → AI Rewrite context bar at the bottom](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35537/8eec8a73.png)

### Manual editing

There's a rich-text editor toolbar at the top of the document that works just like an ordinary document editor:
- Heading levels, font, font size, **B / I / U / S**, text color + highlight color
- 4 alignment options, ordered / unordered lists, indent / outdent, line spacing
- Insert images, links, tables
- **Undo / Redo** — back out if you make a mistake

**Manual editing does not consume credits** (verified: balance unchanged before and after inserting/editing text). For Markdown documents, you edit the Markdown source directly.
![Rich-text editor toolbar: formatting + Undo/Redo](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35537/7014eed3.png)

### Version history (Save Point)

The Canvas top bar has a **`Save Point-N ▾`** dropdown — each AI generation/edit automatically creates a snapshot with a timestamp and instruction label (SP-1 for the initial generation, SP-2/SP-3 for subsequent AI edits).

Click an older Save Point → preview that older version → at the bottom you'll see **Rollback to…** (revert to that version) / **Back to latest version** (return to the latest). **You can actually roll back, not just view.**

> Note: when there's only 1 version (just generated, no AI edits yet), the `Save Point` dropdown won't appear; it shows only after at least one AI edit, once there are 2 or more versions.
![Save Point dropdown: version list + old-version preview + Rollback](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35537/0e685418.png)

## Exporting

Click the **View & Export** menu in the Canvas top bar. **The export options vary by document format** — the menu is dynamic, not one fixed list:

| Document format | View & Export menu options |
|------|------|
| **Word (DOCX)** | **Download Word Document** / **Export as PDF** / **Make a Copy** |
| **Markdown** | **Export as Markdown** (listed first) / **Export as Word Document** / **Export as PDF** / **Open in separate browser** / **Make a Copy**  |
| **Web Doc** | HTML export is available for the **Web Doc** format only  |

> Note: **neither DOCX nor Markdown documents have an "Export as HTML" option** — HTML export belongs to the Web Doc format only. "Open in separate browser" appears for Markdown documents; DOCX documents don't have that item. Google Docs is currently **not supported**, and there's no "Save to AI Drive" option. When you need Google Docs, export Word (DOCX) first and then upload it.
![View & Export menu on a Markdown doc: Export as Markdown / Word Document / PDF / Open in separate browser / Make a Copy](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/51190/a1f097a2.png)

## Sharing

Sharing uses the **Share** button at the top right of the Canvas top bar (this is different from exporting — Share gives you a share link, while the Export options give you downloadable files).
![Share button (separate from exporting)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35537/df79553f.png)

## FAQ

### How do I choose between AI editing and manual editing?
For small changes (fixing typos, adjusting formatting), edit them yourself manually — **it's free and fast**; for big changes (rewriting a passage, adding content), select the text and have the AI make the change (uses credits). If something gets messed up, roll back with Save Point.

### Do the exported PDF and Word have consistent layout?
Both are converted from the same document, so the layout is preserved as much as possible, but complex styles may look slightly different when opened in different software.

### Can a Markdown document export a .md file?
Yes. Markdown-format documents get an extra **Export as Markdown** option in the **View & Export** menu (listed first), which exports the Markdown source file.

### What's the difference between exporting and sharing?
The **Export** options download a file to your computer (Word / PDF, plus .md for Markdown documents — the exact options depend on the document format); the **Share** button generates a share link for others to view. Use Share to send it to someone, use Export to archive it locally.

### Next steps
- Haven't created a document yet → [Create a document](https://page.gensparksite.com/manual/buddy-guides/v1/en/docs-create.md)
- Learn about AI Docs' overall capabilities → [Product overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/docs-overview.md)
