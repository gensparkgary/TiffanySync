# Genspark Code — Getting Started

> For Buddy Agent internal use.
> type: howto | feature: ai-developer | keywords: start, build app, starting point, template, generate, What are you building
> User loop: Enter Genspark Code → pick a starting point or template → describe your needs → AI generates → see your first working app

## Why start here

The quality of what Genspark Code produces depends on how you choose your starting point and how you describe your needs. Picking the right starting point determines how the AI builds your app (a lightweight page vs. a full app with a backend), and describing your needs clearly lets it build the right thing on the first try with less rework — saving you both time and credits.

## Entering Genspark Code

Go to `https://www.genspark.ai/code/` (login required; the older address `https://www.genspark.ai/ai_developer/` still works), or from the homepage **BUILD SUITE** group click the **Code** card. Once inside, you'll see the starting-point home page titled "What are you building?".
![Genspark Code starting-point home (What are you building? + category tabs + starting-point cards)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35762/d9ce3791.png)

## 1. Pick a starting point

At the top of the page there are 4 category tabs (Web / Mobile Apps / E-commerce / Existing code), with starting-point cards below. Each starting point corresponds to a type of app (names match the card titles in the live product):

- **Simple Website or Web App** — quick prototypes, landing pages, lightweight sites with a built-in database
- **Full-Stack Websites or App** — complete web apps with a backend, authentication, and a database (the card description notes it's optimized for Cloudflare Pages deployment)
- **Native App Development** — build cross-platform mobile apps with Flutter
- **Shopify Development And Manager** — Shopify store/theme development
- **Existing GitHub Project / Bring Your Own SSH Server** — connect your existing code (see [Working with Existing Code](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-developer-existing-code.md))

Not sure which to pick: for a front-end-only display, choose **Simple Website or Web App**; if you need a backend and database, choose **Full-Stack Websites or App**. Both web starting points can be published from the workspace with one click.
![Starting-point cards (Simple Website or Web App / Full-Stack Websites or App / Native App Development / Shopify, etc.)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35762/ddd516cc.png)

## 2. Or start from a template

If you want an even faster start, the home page also has a template library — filter ready-made templates by category, pick one, and remix it straight into your own project. Creating from a template doesn't consume credits.
![Template library (template cards filtered by category)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35762/bdd9fcee.png)

## 3. Describe what you want to build

Once you're in the chat workspace, describe the app you want in plain language. Describe the outcome, not the technical details — the AI decides how to implement it.

**Good descriptions**:
> "Build a coffee shop landing page with a menu display, business hours, a map location, and a reservation form"

> "Build a personal expense-tracking tool that can add income/expense records, summarize by month, and show a category pie chart"

**Bad descriptions**:
> "Build a website" (too vague — the AI has no idea what you want)

| Tip | Description |
|------|------|
| Describe features and content | Spell out which pages, which features, and what content goes where |
| Say it all at once | Describing your core needs in one go is more efficient than adding them step by step |
| Share references if you have them | If you have a style you like, reference sites, or existing content (copy/images), mention them too |

## 4. Watch the AI work and wait for generation

After you send, the AI shows its work process — which files it's writing, what commands it's running, and the current progress. Complex apps take multiple steps, so be patient while it finishes. Once generation is done, a previewable app appears in the workspace.
![AI generation process (showing file writes / command execution / progress)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35762/432706ce.png)

Generation consumes credits (billed by usage). We recommend checking your balance once before and once after generation to get a feel for roughly how much it costs.

## 5. Return to a previous project

On the left there's a task/session drawer (titled **Task List**, with a **Search Chats** search box at the top). Click the menu icon at the top to expand it, where your recent chats / projects are listed — click back into any of them anytime to continue.

## FAQ

**I can't write code — can I really use this?**
Yes. All you do is clearly describe the app you want in plain language; writing the code, testing, and running it are all handled by the AI.

**Which starting point should I pick?**
Front-end-only pages/prototypes → Simple Website or Web App; complete apps that need login, a database, or backend logic → Full-Stack Websites or App; mobile apps → Native App Development (Flutter); connecting existing code → see [Working with Existing Code](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-developer-existing-code.md).

**How long does generation take?**
It depends on the app's complexity. Simple pages are faster; complete apps with a backend and multiple features need more rounds of generation, so be patient while it runs.

**How many credits will it cost?**
Generation and edits are billed by usage, with no fixed unit price. Describing things clearly and minimizing rework saves the most credits. Preview, download, and deployment themselves cost nothing extra.

## Next steps

- [Preview and Edit](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-developer-preview-and-edit.md) — run a preview, select elements to change, and iterate until you're happy
- [Deploy and Export](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-developer-deploy-and-export.md) — deploy live / download code / connect GitHub
- [Working with Existing Code](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-developer-existing-code.md) — GitHub repo / SSH server / Shopify
- Want the big picture first? See the [Product Overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-developer-overview.md)
