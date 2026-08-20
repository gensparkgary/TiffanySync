# Genspark Design — Creating a Design

> For Buddy Agent internal use.
> type: howto | feature: genspark-design | keywords: create, new, start, Examples, Design System, Figma, screenshot, codebase, context
> User loop: Open the Design page → choose Examples or start from scratch → add context → AI generates your first design

## Why start here

The Genspark Design creation flow determines how deeply the AI understands your needs. The more background you provide (brand style, reference designs, codebase), the more closely the AI's generated design matches your expectations.

## Entering Design

Entry point: go directly to `https://www.genspark.ai/agents?type=design`

Once inside: the left side is the input area with **POPULAR TASKS** example tasks, and the right side defaults to the **For You** gallery of ready-made design examples (organized by category: Website / Mobile / Marketing / Social / Video / Poster / Document) — click any example to open it as a starting point. **My Designs** is a separate tab that holds your own past designs.

![Design home page: input area, POPULAR TASKS, My Designs gallery](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35108/542c57fd.png)

## Option 1: Start from POPULAR TASKS

Below the input box are a few curated example tasks (a landing page for a notes app, multiple screens for a meditation app, jazz concert posters, a 30-second year-in-review video, and more). Click one and the full example prompt fills the input box (it won't send automatically), so you can tweak it as needed and then hit send to start generating.

![POPULAR TASKS example tasks area](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35108/13870047.png)

Once started, you can describe changes directly in the chat box, or use the Canvas toolbar for visual fine-tuning.

## Option 2: Start from scratch

### 1. Enter a description

Use natural language in the left input box to describe the design you want.

### 2. Specify the design type in your description (optional)

When you want to be explicit about the type, just write it into your description: **Prototype** (interactive prototype), **Slide deck** (presentation), **Poster**, **Video**, plus extended capabilities like **Frontend design**, **Wireframe**, **Make tweakable**, **Save as PDF**, **Save as standalone HTML**, and **Handoff to developer** — for example, "make a Wireframe for a mobile app."

> Not specifying a type is fine too — the AI will automatically determine the most appropriate design approach based on your description.

### 3. Choose a generation mode (Lite / Ultra)

Switch between the two public modes in the mode selector next to the input box: **Lite** is faster and more economical, good for everyday or high-volume design, while **Ultra** (recommended, default) offers stronger reasoning and quality with longer context, best for complex, high-stakes work. The exact speed, quality, and cost of each mode are shown in the UI.

![The mode selector next to the input box](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34395/0ca783ed.png)

### 4. Send and wait for the AI to generate

After you click send, the AI starts designing. During this process:

- **The AI may ask questions first**: If your description isn't specific enough, the AI will pop up questions for you to clarify (shown in the Questions panel). After you answer, the AI continues designing.
- **Task list**: While working, the AI displays task progress, e.g. "Tasks: 3/5 done," so you can track where things stand.
- **Design complete**: The Canvas on the right shows the finished design. The AI automatically validates design quality on completion and will display the validation status (green/amber pill).

![AI asking questions: the Questions panel pops up with clarifying questions](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34395/44070743.png)

## Add context (Start with context)

To help the AI better understand your needs, you can add the following context before sending your message:

### Design System (brand design system)

Make the AI follow your brand style. Click **Design System** below the input box to select or create one.

**Create a new Design System**:

1. Click **"Create New Design System"**
2. Enter a brand description (required) and style notes (optional)
3. Import design assets (optional, multiple sources supported):
   - **GitHub**: connect a code repository to import design assets
   - **Upload .fig file**: upload a Figma design file
   - **Import Codebase**: import a codebase
   - **Upload Assets**: upload design resource files
4. The AI automatically extracts design assets like colors, fonts, and components
5. Confirm or modify each one in the review panel

**Use an existing Design System**:

Click the **"No design system"** selector below the input box to open the "Choose a design system" dialog — it supports search, Active/All filtering, and lets you select an existing DS or **Create new design system**. Management actions like setting a default and archiving are supported.

![Choose a design system dialog: No design system / Create new options](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35108/1377c18e.png)

![Create New Design System dialog: brand description + import assets (GitHub / .fig / Codebase / Assets)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34395/179b721f.png)

### Add screenshot (add a reference screenshot)

Upload a reference image so the AI can draw on an existing visual style.

### Attach codebase

Upload a code folder or connect a GitHub repository so the AI can read your existing project code and generate matching designs.

### Drag in a Figma file

Drag a .fig file into the chat area, and the AI will parse the structure and elements of the Figma design.

## Attaching content to a message

Beyond the initial context, you can attach content to each message too. Click the **"+"** button on the left of the input box to add:

- **Browse Local Files**: upload local files
- **Choose from AI Drive**: select a file from AI Drive
- **Reference another design**: reference another design of yours
- **Upload .fig file**: upload a Figma file (with a **How to download** guide alongside)
- **Connect GitHub**: connect a GitHub repository
- **Grab web element**: grab an element from a web page as reference
- **Link code folder**: link a code folder
- **Skills and design systems**: select a Skill or Design System
- **New Chat**: start a new chat

![Click the + button to expand the attachment menu (9 items)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35108/1f6f1415.png)

## Referencing your other Genspark projects

Beyond the attachment menu, you can also paste links to your own other Genspark projects (meeting notes, AI Chat, presentations, etc.) directly into a message, and the AI can read their content as design context. You can also just describe what you're looking for (e.g. "use the notes from my product meeting last week"), and the AI can find your relevant past projects.

## Managing multiple chats

You can create multiple chats within one design project:

- **"+"** in the top left to start a new chat
- The 🕐 icon to view the chat history list
- Each chat has independent memory and won't interfere with the others

> Multiple chats are great for exploring different directions within the same project — for example, one chat for the homepage design and another for inner pages.

![Workspace: top bar + top-right toolbar + multi-chat button](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34395/316cfa81.png)

## Past design projects

On the landing page you can view your past design projects, and click to keep editing.

## Next steps

Once your design is created, you can:

- [Canvas editing tools](https://page.gensparksite.com/manual/buddy-guides/v1/en/design-canvas-tools.md) — Tweaks / Edit / Comment / Draw / Make Tweakable
- [Export, present, share](https://page.gensparksite.com/manual/buddy-guides/v1/en/design-export-and-share.md) — Present / Build it / PDF / PPTX / MP4 / Share
- Dive deeper by scenario:
  - [Designing websites and apps](https://page.gensparksite.com/manual/buddy-guides/v1/en/design-website-and-app.md)
  - [Designing visual content](https://page.gensparksite.com/manual/buddy-guides/v1/en/design-visual-content.md)
  - [Designing presentations and documents](https://page.gensparksite.com/manual/buddy-guides/v1/en/design-presentation-and-doc.md)
  - [Designing videos](https://page.gensparksite.com/manual/buddy-guides/v1/en/design-video.md)
