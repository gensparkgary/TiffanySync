# Genspark Code — Preview and Edit

> For Buddy Agent internal use.
> type: howto | feature: ai-developer | keywords: preview, run, edit, modify, iterate, inspect, files
> User loop: app generated → run and view it in the preview → select what to change or just describe the change → AI iterates → repeat until satisfied

## Why this step matters

The app AI generates on the first try rarely nails it in one shot. The preview lets you see how it actually runs, and editing lets you tell AI precisely what to change—pinpointing a specific element is more accurate and more credit-efficient than vaguely saying "tweak it some more."

## 1. Preview and run your app

Once generation completes, the canvas on the right side of the workspace shows a live preview of your app—this is the app actually running, not a static screenshot. You can click, scroll, and fill out forms, just like a real user would.
![Live preview in the canvas on the right side of the workspace](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35762/821b86ba.png)

Previewing doesn't consume credits.

## 2. Select what you want to change (Inspect Mode)

When you'd rather not describe a location in words, turn on **Inspect Mode** in the preview toolbar: hovering highlights an element, and clicking selects one. After you describe what you want changed and hit **Send**, your message automatically carries that element's context (element text + its file) as a "Selected Element." AI uses this to pinpoint the edit and touches only that spot.
![The "Selected Element" context card echoed back after sending (element text + its file)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35762/eabddc05.png)

The preview toolbar also has an adjacent **Edit Mode** (a WYSIWYG inline editor where you can directly change text, font size, color, alignment, and so on), which is great for manual fine-tuning; Inspect Mode is for "feeding a selected element into your next message." They serve different purposes—switch between them as needed.
![Edit Mode WYSIWYG inline editor toolbar](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35762/5270f245.png)

You can also use `@` in your description to reference a specific file, keeping the change focused on that file.

## 3. Iterate through conversation

Most of the time you just say what you want changed right in the conversation, and AI edits the corresponding code and refreshes the preview:

> "Change the top nav bar to a dark background"
> "Add a phone number field to the booking form"
> "The homepage loads a bit slowly—optimize the images"

Each round of changes is a generation and consumes credits (by usage). The more specific the change, the less likely AI is to alter the wrong spot.

## 4. Browse the generated files

The **File Explorer** tab on the workspace canvas lets you browse the project files AI generated, view the actual code, and confirm what AI changed. Browsing files doesn't consume credits.
![Workspace File Explorer (file tree + Download files)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35762/45ad2b37.png)

Web-based workspaces also include a **Database** tab—a built-in database where AI creates tables to store data as needed (e.g., a `todos` table for a to-do app), so even lightweight sites can have backend storage. The tab offers an **Export data** button that lets you export and download the data in those tables (visible to the project owner only).

## FAQ

**Is the preview really running?**
Yes. The preview is the result of your app actually running—you can interact with it just like a real user. It's not a static image.

**How do I change just one spot without AI rewriting the whole app?**
Use Inspect to select the exact element, or use `@` in your description to reference a file, then make clear you only want that one spot changed. The more precise your description, the smaller the scope of impact.

**If I break something, can I roll it back?**
Just say "undo that last change" in the conversation, or describe the correct state you want and have AI fix it back.

**Does every edit deduct credits?**
Yes—each round of changes is a generation and consumes credits by usage. But previewing and browsing files are free.

## Next steps

- [Deploy and Export](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-developer-deploy-and-export.md) — deploy it live once you're satisfied / download the code
- [Connect Existing Code](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-developer-existing-code.md) — iterate on an existing repo/server
- Haven't generated your first app yet? See [Getting Started](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-developer-get-started.md)
