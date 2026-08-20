# AI Slides — Managing Multiple Files

> For Buddy Agent internal use.
> type: howto | feature: ai-slides | keywords: multi-file, Deck, Tabs, Files, switch, project
> User loop: Generate several Slides in one project → switch with the deck tabs at the top → browse all files in the Files view → return to Slides and keep editing

## Prerequisites

- You've generated Slides in a project
- The project contains multiple `.slides` files (from multiple conversations or imports)

## Why multi-file projects

- **One topic, many forms**: generate a pitch deck + one-pager + executive summary in the same conversation — everything shares the same context and stays stylistically consistent
- **No new project needed**: skip re-describing the topic and re-uploading material
- **Centralized management**: all related files live in one project instead of being scattered

## About multi-file projects

An AI Slides project can contain multiple Slides files. For example, generate a pitch deck first, then ask the Agent for a one-pager — both decks live in the same project.

## Steps

### 1. Switch decks with the tabs at the top

When a project has multiple Slides files, **deck tabs** appear across the top of the canvas — one tab per deck; click a tab to switch to that deck.

Note: by default the Agent **appends new content to the current deck**. To create a separate new deck, say so explicitly in your prompt (e.g. "create a separate new deck").

### 2. Open the Files view

Click the **Files button** (folder icon) in the canvas's top tool area to switch to the project file browser, where you can see the project's full directory — every deck's content, image assets, and related resources. Click a file to preview it.

Click the button again (or click a deck tab) to return to the Slides editing view.

## FAQ

**I asked the Agent to generate another set — why did it overwrite the original deck?**
By default the Agent appends new content to the current deck. For a separate new deck, say so explicitly in the prompt, e.g. "create a separate new deck".

**How do I know how many Slides sets are in the project?**
The deck tabs at the top of the canvas list every deck in the project — one tab per deck.

**What's the benefit of keeping several Slides sets in one project?**
They share the same conversation context, so the style stays consistent — and you skip re-describing the topic and re-uploading material.

## Next steps

- Want to import an existing PPTX/PDF into this project and keep editing → see "AI Slides — Importing Existing Files"
- Conversation getting long and credits getting pricier → see "AI Slides — Memory Management & New Chat"
