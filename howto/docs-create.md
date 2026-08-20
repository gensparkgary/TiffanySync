# AI Docs — Create a Document

> For Buddy Agent internal use.
> type: howto | feature: ai-docs | keywords: create, AI Docs, document, template, Web Doc, Markdown, DOCX, PRD
> User loop: Open AI Docs → describe what you need or pick a template → choose format/mode → generate → get an editable document

## Why start here

Describe the document you want in a single sentence, and AI generates a well-structured, editable first draft — no more staring at a blank page.

## Prerequisites

- Entry point: the **AI Docs** tile under the **Office Suite** category on the homepage, or go straight to `/ai_docs`
- Generating a document consumes credits (in our tests, one Standard generation costs about 100 credits — check your balance before and after to confirm)

## 1. Open AI Docs

From the homepage **Office Suite**, click the **AI Docs** tile to enter (lands on `/ai_docs`). The landing page is titled **"What would you like to write?"**, with an input box and starter quick tasks below it; the right-hand panel shows the template library by default.
![AI Docs landing page: input box + starter quick tasks + template library on the right](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35537/6cd5676f.png)

## 2. Describe the document you want

Two ways to start:

> Want a ready-made layout (hundreds of finished templates for resumes, reports, forms, and more)? The **template library** is faster — see [Create from a template](https://page.gensparksite.com/manual/buddy-guides/v1/en/docs-templates.md). This article covers creating from a one-sentence description.

**Option 1 — Pick a starter quick task**: next to the input box on the landing page are a few common quick tasks. Click one to fill its example request into the input box; you can edit it or send it as-is (this is not the same as the template library above — quick tasks are example prompts, while the template library is a collection of finished layouts):

| Template | Use |
|------|------|
| A one-page PRD for a new feature | One-page product requirements doc |
| A cover letter for a senior role | Cover letter |
| A 7-day trip itinerary with budget | Itinerary with budget |
| Action items from a meeting transcript | Turn a meeting transcript into action items |

**Option 2 — Describe it yourself**: write what you want in the input box using natural language. Beyond a plain text description, you can also:
- Paste a **link / web address** for AI to reference
- Upload a **file** as source material

> When generating, AI can automatically search, scrape web pages, add images, and summarize long documents — so the more specific the material you provide, the better the first draft fits.
![Starter quick tasks: click to fill the input box](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35537/1f5d959b.png)

## 3. Choose a format (optional)

The **Output format** cards near the input box on the landing page offer three document formats — pick based on your delivery scenario:

- **Word (DOCX)** — **selected by default**; formal scenarios that require delivering a .docx file 
- **Web Doc** — a polished rich document; after picking it, the AI first asks you to choose a layout: a regular web page (scrolling), or a printable paginated layout (A4 / US Letter, with page numbers, better suited for exporting to Word/PDF afterward). The layout choices also include an **Other** option, and there's a **Skip** button if you'd rather not choose. Note: the layout question only appears when the AI decides your request calls for a formal document — a very short content request (e.g. "write a paragraph") is answered directly in the chat, with no layout question and no document created  
- **Markdown** — technical docs, notes, or content for a code repository

You don't have to change anything — Word (DOCX) is selected by default on the landing page and generation follows it; you can switch anytime before sending. The exact card wording is as shown in the UI.

## 4. Choose a mode (optional)

The mode selector in the input box: **Lite** (fast, economical) / **Standard** (default) / **Ultra** (more powerful, uses more credits). Use Lite for simple documents and Ultra for complex or demanding ones.

![Input box bottom bar: format selector + mode selector](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35537/d9377b7d.png)

## 5. Send and wait for generation

After you click send, AI starts drafting. When it's done:
- The right-hand Canvas displays the full document (directly editable)
- The left side shows the **document outline** and **Design highlights** (AI's notes on the document's design)

![Generation complete: outline/AI chat on the left + editable Canvas on the right](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35537/600a309c.png)

## 6. Use "+" to add materials or start a new chat

The **"+"** menu on the left of the input box:
- **Browse Local Files** — upload a local file
- **Choose from AI Drive** — pick a file from AI Drive
- **New Chat** — start **a new conversation** within the current project (multiple chats, kept separate)

## 7. Keep refining

Once generation is complete, you can edit, export, and share — see [Edit and export](https://page.gensparksite.com/manual/buddy-guides/v1/en/docs-edit-and-export.md) for details.

## FAQ

### Can I generate from an existing file?
Yes. Upload a file or paste a link when entering your request, and AI will use it as source material for the draft.

### Can I change the generated document?
Yes. You can have AI change it (rewrite/continue selected content) or edit it manually yourself. See [Edit and export](https://page.gensparksite.com/manual/buddy-guides/v1/en/docs-edit-and-export.md).

### What happens if I don't choose a format?
Word (DOCX) is selected by default on the landing page, and generation follows it unless you change it; you can also switch to Web Doc or Markdown before sending.

### Why does the AI ask me a question after I pick Web Doc?
Web Doc supports both a regular web-page layout and a printable paginated layout, so the AI asks you to choose between them once (the printable layout also comes in A4 / US Letter; the menu also offers an **Other** option and a **Skip** button) before generating. If you plan to export to Word/PDF later, the printable layout is the better fit. Note that the layout question only appears when the AI decides to generate a formal document — very short content requests are answered directly in the chat without it.

### Next steps
- Want a ready-made template → [Create from a template](https://page.gensparksite.com/manual/buddy-guides/v1/en/docs-templates.md)
- Edit, polish, export, share → [Edit and export](https://page.gensparksite.com/manual/buddy-guides/v1/en/docs-edit-and-export.md)
- Unsure about AI Docs' overall capabilities → [Product overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/docs-overview.md)
