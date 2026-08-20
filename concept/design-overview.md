# Genspark Design — Product Overview

> For Buddy Agent internal use.
> type: concept | feature: genspark-design | keywords: Design, Design, Overview, Lite, Ultra, Design System, Website, Poster, Video, PPT, Prototype
> User loop: Understand what Genspark Design is → Know which types of work you can design → Understand the Lite / Ultra difference → Learn about Design System and Verifier

## Why use Genspark Design

The traditional design workflow requires design-software skills, lots of layout tweaking, and repeated back-and-forth. Genspark Design turns this process into a **conversation**: describe what you want → AI generates a complete design → fine-tune the details visually → export or hand off.

Core value: **From a single sentence to an interactive, ready-to-deliver design—the concept, layout, color, and imagery are all handled by AI. You don't need any design-software expertise; you just describe and fine-tune.**

## What is Genspark Design

Genspark Design is an AI-powered design tool that supports many design types including websites, mobile apps, posters, presentations, and animated videos. You simply describe what you need in words, and the AI generates a complete, interactive design.

Entry point: go directly to `https://www.genspark.ai/agents?type=design`.

![Design home page overview: input box, POPULAR TASKS, My Designs gallery](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35108/542c57fd.png)

## What you can design

Genspark Design supports the following design types:

### 4 main types

Just say which type you want in the conversation (e.g. "make a pitch deck," "design an event poster"):

| Type | Best for | Examples |
|------|---------|------|
| **Prototype** | Interactive app prototypes with real buttons, inputs, and navigation | Mobile app prototype, SaaS dashboard prototype |
| **Slide deck** | Multi-page slides with full-screen presentation and Speaker Notes | Fundraising pitch, training decks, quarterly reports |
| **Poster** | AI-image-driven posters and print materials | Event posters, social media images, flyers |
| **Video** | Timeline-based animation and video | Product intro animation, logo motion, ad spots |

### 6 extended capabilities (just ask in the conversation)

| Type | Description |
|------|------|
| **Frontend design** | Aesthetics-focused interface design exploration |
| **Wireframe** | Wireframes and storyboards for quickly exploring multiple options |
| **Make tweakable** | Generate visual fine-tuning controls (Tweaks) for an existing design |
| **Save as PDF** | Export a design to a print-ready PDF |
| **Save as standalone HTML** | Export to a single-file, offline-ready HTML |
| **Handoff to developer** | Package the code to hand off to developers |

### More design formats

Beyond the menu options above, the Genspark Design AI also has these design capabilities built in:

| Type | Description | Best for |
|------|------|---------|
| **Flipbook** | A visual work you flip through one page at a time | Picture books, photo collections, recipes, lookbooks, product catalogs |
| **Paged Book** | Long-form text automatically paginated and laid out | Textbooks, white papers, academic papers, technical manuals |
| **Frame Movie** | Complex video composed from a multi-frame timeline | Multi-shot ad spots, narrative animation, product demos |
| **Short Film** | A narrative short film with AI-generated footage and sound design | Brand story films, concept shorts, creative storytelling |

> You don't need to specify a type in advance—just describe the design you want in words, and the AI will automatically pick the best way to make it.

## Home page guidance (POPULAR TASKS and My Designs)

Below the input box on the left side of the home page is **POPULAR TASKS**—a few curated example tasks (such as a landing page for a notes app, multiple screens for a meditation app, jazz concert posters, a 30-second year-in-review video). Clicking one fills the complete example prompt into the input box (it won't send automatically), so you can edit it first and then click send to start generating.

![POPULAR TASKS: clicking a task fills the example prompt into the input box](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35108/13870047.png)

On the right is the **My Designs** gallery: it shows your past design work, with category tabs at the top (My Designs / For You / Website / Mobile Design / Marketing / Social / Video / Poster / Document) you can switch between to browse.

![My Designs gallery and category tabs: click a tab to switch what's shown](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35108/e2cdb8dd.png)

## Generation modes (Lite / Ultra)

There are two public generation modes, switchable in the mode selector next to the input box — trade off speed against quality as needed:

- **Lite** — faster and more economical, good for everyday or high-volume design.
- **Ultra** (recommended, default) — stronger reasoning and quality, longer context, best for complex, high-stakes work.

> The exact speed, quality, and cost of each mode are shown in the UI.

## Design System (brand design system)

A Design System lets the AI follow your brand style when designing. Once you create a Design System, the AI automatically uses your brand colors, fonts, and design guidelines.

### When you need a Design System

- Your company/brand has a consistent visual style
- You need multiple designs to stay stylistically consistent
- You want the AI to reference your existing design assets

### Core capabilities

- **Brand description**: tell the AI your brand style and tone
- **Import design assets**: connect a repo from GitHub, upload .fig files, Import Codebase, Upload Assets
- **Asset review**: the AI automatically extracts colors, fonts, and components, which you can confirm or modify one by one
- **Shared across projects**: one Design System can be bound to multiple design projects

For the detailed creation and management flow, see [Create a design](https://page.gensparksite.com/manual/buddy-guides/v1/en/design-create.md).

## Automatic verification (Verifier)

After the AI finishes a design, it automatically launches a separate **verification Agent** as part of the normal generation flow, checking design quality in the background:

- Whether the design loads correctly and the visuals match your description
- Whether interactions work (buttons, links, etc.)
- Whether resources are complete (images, fonts, etc.)

The verification result appears next to the message:

| Indicator | Meaning |
|------|------|
| 🟢 Green pill | Verification passed, design quality meets the bar |
| 🟠 Amber pill | Changes needed; the AI will automatically try to fix them |

## Workspace layout

Once you're in a design project, the interface is split into two areas:

| Area | Location | Function |
|------|------|------|
| **Chat panel** | Left | Talk to the AI, upload references, switch between Lite / Ultra |
| **Canvas** | Right | View the design and fine-tune it with the toolbar |

### Canvas toolbar

The top bar includes:
- **Design System** tab — view the current DS's colors, fonts, and components
- **Design Files** tab — browse all files in the project
- **Present** — full-screen presentation
- **Build it** — deliver as runnable code
- **Download** — download the whole project as a ZIP (next to Build it)
- **Share menu** — create a Design System from the project / duplicate project

Top-right toolbar:
- **Tweaks** — visual parameter fine-tuning (appears only when the design has Tweaks controls)
- **Edit** — edit design elements directly
- **Comment** — annotate comments on elements
- **Draw** — pen annotations

For detailed operations, see [Canvas tools](https://page.gensparksite.com/manual/buddy-guides/v1/en/design-canvas-tools.md).

## Quick guide by scenario

| I want to... | Go to... |
|-----------|--------|
| Create a new design / template / Design System from scratch | [Create a design](https://page.gensparksite.com/manual/buddy-guides/v1/en/design-create.md) |
| Website or app design | [Design websites and apps](https://page.gensparksite.com/manual/buddy-guides/v1/en/design-website-and-app.md) |
| Posters, social media images, marketing assets | [Design visual content](https://page.gensparksite.com/manual/buddy-guides/v1/en/design-visual-content.md) |
| PPT presentations, flipbooks, long documents | [Design presentations and docs](https://page.gensparksite.com/manual/buddy-guides/v1/en/design-presentation-and-doc.md) |
| Animated videos | [Design videos](https://page.gensparksite.com/manual/buddy-guides/v1/en/design-video.md) |
| Fine-tune / annotate (Tweaks / Edit / Comment / Draw) | [Canvas editing tools](https://page.gensparksite.com/manual/buddy-guides/v1/en/design-canvas-tools.md) |
| Present / export / share | [Export, present, share](https://page.gensparksite.com/manual/buddy-guides/v1/en/design-export-and-share.md) |
