# Hub — Set Up Your Hub

> For Buddy Agent internal use.
> type: howto | feature: hub | keywords: Hub, create, upload files, Custom Instructions, workspace, setup
> User loop: More → Hub → create a Hub → upload your go-to files → write a fixed instruction → send your first prompt inside the Hub and watch the answer pick up this context automatically

## Why set up your Hub first

Configure your project's materials and rules once, and every conversation inside that Hub will automatically carry them—no more re-uploading files or re-explaining context each time. You jump straight into work.

## Prerequisites

- Entry: `https://www.genspark.ai/hub` (or **More → Hub** in the left sidebar)
- Requirement: just sign in to your account

## Steps

### 1. Open Hub

In the left sidebar, click **More → Hub**, or go directly to `/hub` to reach the "Your Hubs" list. The first time you arrive with no Hubs yet, you'll see an empty-state prompt to create one.
![Hub list page (Your Hubs + New hub create prompt)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35760/37792993.png)

### 2. Create a Hub

Click **New hub** (the empty-state prompt button; once you already have Hubs, click **+ New** in the top-right of the list), then fill in the create dialog:
- **Name**—the field is shown as a guiding question: "What are you working on?"
- **Color Theme**—pick one of 12 color swatches (it appears as a dot on the Hub card and next to the title)
- **Description**—the field's question: "What are you trying to achieve?"

Once filled in, click **Create hub**.
![Create Hub dialog (What are you working on? / Color Theme 12 colors / What are you trying to achieve?)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35760/4829817f.png)

> The name and description help you and your team recognize this Hub—make it clear what the space is for.

### 3. Upload files

Inside the Hub, click **Files → Add Files** and add files from **your computer (Browse Local Files)** or **AI Drive (Choose from AI Drive)**. These files are available across all conversations in that Hub—Genspark automatically parses the file content, and after upload it shows a one-line content summary on the file row so you can confirm the file was understood; conversations then reference it as needed.
![Add files (Browse Local Files / Choose from AI Drive)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35760/702d0fde.png)

Supported files: documents (doc, docx, pdf, md, txt, ppt, pptx, xls, xlsx, csv, etc.), code (py, js, ts, java, go, html, css, json, yaml, etc.), images (png, jpg, jpeg, webp, etc.). Audio, video, and archives (zip/rar/7z) are not supported. The per-file limit is 10MB, and each Hub holds up to 100 files. Uploading a file over the limit is clearly rejected with the specific size noted (e.g. "File size (11 MB) exceeds the maximum allowed size of 10 MB").

> More files isn't better: conversations in the Hub reference file content on demand, so more files means a larger context and higher credit consumption. Keep only the materials that truly matter, give them clear filenames (e.g. `brand_guidelines_2024.pdf` rather than `document1.pdf`), and call out which file to use when you ask.

### 4. Set Custom Instructions

Open it from the **⋯ menu → Custom instructions** in the top-right of the Hub detail page, write a set of rules that every conversation in this Hub must follow, and click save.
![Custom Instructions dialog](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35760/69726420.png)

What you can write:
- Specify the domains or topics to focus on
- Define the tone, style, and output format of answers
- Explain team terminology or internal company concepts (e.g. "Sparkle = the Q4 product launch codename")
- Set file usage priorities (e.g. "Prefer the logo.png in this Hub")

> Once written, test it with a prompt before locking it in.

### 5. Send your first prompt inside the Hub

Ask your question directly in the input box on the Hub detail page. After sending, you'll enter a Super Agent session (the address bar becomes `/agents?id=<session id>`, still within this Hub's context), and the answer will automatically pick up the files and instructions you just configured—no need to re-explain the background. Try sending "Summarize the file I uploaded," and the answer will reference the content of the file you just uploaded. Hubs use Super Agent by default; you can also use `@` to switch to specialized Agents like AI Slides, AI Sheets, or AI Docs. When the conversation ends, return to the Hub detail page and this task will appear under **Recent Tasks**.

## Edit a Hub

From the top-right **⋯ → Edit Hub**, you can change the Hub's name, color theme, and description, then click **Update** to save.

## FAQ

**Why is the file limit 10MB? What if my file is too big?**
Large files consume a lot of credits and produce lower-quality analysis. If a file is too big: pull out only the relevant sections, summarize it before uploading, or split it into a few smaller, more focused files.

**How many files can a Hub hold?**
Each Hub holds up to 100 files, with a 10MB limit per file. Files are stored permanently, with no time limit.

**Does setting up a Hub cost credits?**
Creating a Hub, uploading files, and setting Custom Instructions are all free. Credits are only consumed when you have a conversation inside the Hub.

## Next steps

- [Working in a Hub](https://page.gensparksite.com/manual/buddy-guides/v1/en/hub-work.md) — Recent Tasks, referencing history across projects, managing project ownership, downloading files
- [Team collaboration](https://page.gensparksite.com/manual/buddy-guides/v1/en/hub-collaborate.md) — invite members, share the space
- [Hub product overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/hub-overview.md)
