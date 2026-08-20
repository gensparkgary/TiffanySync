# AI Docs — Product Overview

> For Buddy Agent internal use.
> type: concept | feature: ai-docs | keywords: AI Docs, document, Web Doc, Markdown, DOCX, Word, export, edit
> Entry point: the **AI Docs** tile in the **Office Suite** category on the home page, or `/ai_docs`

## Why use AI Docs

Writing a formal document—a PRD, a cover letter, an itinerary, meeting notes—usually means starting from a blank page and figuring out the structure as you write. AI Docs turns that into a conversation: describe what you want in a single sentence, or hand it a link or file, and it generates a fully structured document you can keep editing.

Core value: **draft from a single sentence, with both AI editing and manual editing supported, and your choice of Word / Web Doc / Markdown output formats**.

## What it can do

- **Generate a document** from a sentence, a link, a web page, or a file
- After generating, **let the AI revise it** or **edit it yourself manually**
- Choose among three output formats: **Word (DOCX) / Web Doc / Markdown** 
- Export as a **PDF / Word (DOCX) file** — the export options vary by document format: Markdown documents can also export a .md file, and HTML export is available for the Web Doc format only — or share via a Share link  

## Three document formats

| Format | Best for | Notes |
|------|------|------|
| **Word (DOCX)** | Formal scenarios that require a .docx deliverable | Generates a real Word file you can download directly; this format is **selected by default** on the landing page  |
| **Web Doc** | Polished business, marketing, and external documents | Rich-document format: when creating, the AI first asks one layout question—a regular web page (scrolling), or a printable paginated layout (A4 / US Letter, with page numbers, better suited for exporting to Word/PDF afterward)  |
| **Markdown** | Technical docs, READMEs, notes | Lightweight markup format, easy to copy into code repos and the like |

> Not sure which to pick → if the recipient wants a Word file, use the default Word (DOCX); for a polished web page or printable layout → Web Doc; sharing with an engineering team or putting it in a code repo → Markdown. The exact options are as shown in the UI.

## Three generation modes

The mode selector in the input box controls which tier of AI capability is used, letting you trade off speed against quality as needed:

| Mode | Orientation |
|------|------|
| **Lite** | Faster and more credit-efficient, good for simple documents |
| **Standard** | Balances speed and quality, the everyday default |
| **Ultra** | More powerful and thorough, good for complex or demanding documents (consumes more credits) |

> The exact tiers and their corresponding capabilities are as shown in the interface.

## What you can do after creating

| Capability | Description |
|------|------|
| **AI editing** | Select a passage and have the AI rewrite or continue it |
| **Manual editing** | Edit text and adjust formatting directly, like a regular editor |
| **Export** | Options vary by document format: DOCX documents export Word (DOCX) / PDF; Markdown documents also export .md (listed first) and can open in a separate browser; HTML export is available for the Web Doc format only   |
| **Research enhancement** | During generation the AI can automatically search, scrape web pages, add images, and summarize long documents |
| **Version history** | Save Point automatically creates snapshots so you can roll back to earlier versions |
| **Multiple chats** | Open multiple chats within a project via New Chat in the "+" menu |

## Credit consumption

Generating documents and having the AI edit both **consume credits** (charged by the AI's actual workload). **Editing text manually does not consume credits** (verified). If generation uses enhancement tools like search, scraping, or image generation, those tools are each billed separately. Refer to your credit balance before and after the operation for specifics.

## Quick guides by scenario

| What you want to do | Read this |
|---------|-------|
| Create a document from scratch | [Create a document](https://page.gensparksite.com/manual/buddy-guides/v1/en/docs-create.md) |
| Create from an existing template (resume / report / form…) | [Create from a template](https://page.gensparksite.com/manual/buddy-guides/v1/en/docs-templates.md) |
| Edit, polish, export, share | [Edit and export](https://page.gensparksite.com/manual/buddy-guides/v1/en/docs-edit-and-export.md) |

## Template library

Besides generating from a one-sentence description, AI Docs also has a **template library**—hundreds of ready-made templates spanning job hunting, business, reports, forms, and more. You can browse by category and create from a template (a blank document option is also available). See [Create from a template](https://page.gensparksite.com/manual/buddy-guides/v1/en/docs-templates.md) for details.

## FAQ

### How is AI Docs different from AI Slides and Genspark Design?
AI Docs produces **text documents** (PRDs, reports, letters, etc.); AI Slides produces presentation slides; Genspark Design produces websites, posters, and visual designs. To write a formal document, use AI Docs.

### Can I export to Word?
Yes. Choose the DOCX format, or select Word when exporting, and it generates a real .docx file.

### How do I choose between Web Doc and Word?
Web Doc produces a beautifully laid-out rich document; when creating one you choose either a regular web-page layout or a printable paginated layout (the printable layout also exports cleanly to Word/PDF). Word (DOCX) produces a .docx file from the start. If you must deliver a Word file, pick Word; if you want a polished online document first, pick Web Doc.

### Can I export directly to Google Docs?
Exporting to Google Docs is not currently supported (there is no Google Docs option in the export menu). You can export as Word (DOCX) and then upload it to Google Docs.
