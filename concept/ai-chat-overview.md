# AI Chat — Product Overview

> For Buddy Agent internal use.
> type: concept | feature: ai-chat | keywords: AI Chat, conversation, large language model, Mixture-of-Agents, MoA, multi-model, model selection, web search, difference from Super Agent, unlimited, share conversation, Save to Notion
> User loop: Understand what AI Chat is → Know what it can and can't do → Understand Mixture-of-Agents → Know how to choose between it and Super Agent → Know the cost and quota for conversations

## Why use AI Chat

You want to talk directly to top-tier large language models and get answers fast — you don't need it to run multi-step tasks for you or generate files; you just want Q&A, writing, research, and text editing. AI Chat gives you **a clean, direct conversation window**: pick a model you trust, or let the system blend multiple models' answers into a more reliable one, and just send your message.

Core value: **Switch between the industry's top models anytime in the same chat box, and let multiple models collaborate for a more solid answer — you get a high-quality, vetted response without having to open several tools and try each one yourself.**

## What is AI Chat

AI Chat is the product in Genspark for **talking directly to large language models**. You can:

- Pick one model from **dozens of mainstream models** to answer (the available options depend on what's shown in the UI)
- Choose **Mixture-of-Agents (MoA, automatic multi-model blending)** to have the system answer with several models at once and then synthesize them into a single answer
- Toggle **web search** on or off to ground answers in the latest information from the web
- **Upload files / images** to support your question
- Use **voice dictation** (Speakly) instead of typing

Entry point: `https://www.genspark.ai/agents?type=ai_chat`, or select AI Chat from the central input box on the home page.

## What is Mixture-of-Agents (MoA)

MoA is Genspark's multi-model collaboration capability, and it's **a model option** within AI Chat (not a separate product). Once you select it, your single question gets **answered separately by multiple models**, and the system then **performs a layer of aggregation and synthesis to produce one answer** — you can see each model's individual answer and the final synthesis process in the UI. It's good for questions where you want a more comprehensive, more dependable answer: multiple models cover for each other and are less likely to miss key points than a single model.

For detailed selection advice, see [AI Chat Models and MoA](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-chat-models-and-moa.md).

## What AI Chat doesn't do (capability boundaries)

AI Chat is intentionally kept "light," focused on conversation itself. The following are **not in AI Chat**:

| What you want to do | Where to go |
|---------|--------|
| Have AI automatically run multi-step tasks and use tools on its own to finish an entire job | Super Agent |
| Generate images | Image generation product |
| Generate video / music | The corresponding video / audio product |
| Make slides / sheets / documents | Slides / Sheets / Docs |
| Export a conversation to PDF | Not offered in AI Chat (use the corresponding dedicated product if you need a finished file) |

## A few actions beyond conversation

While AI Chat focuses on conversation, it also offers a few lightweight actions:

- **Share conversation**: the **Share** button in the top bar — defaults to Restricted (only people with access can open it via the link); you can change it to General Access, copy the link, or invite collaborators.
- **Save to Notion**: the **"…"** menu on each answer has *Save to Notion*.
- **Bookmark / Add to Hub**: the **"…"** menu in the top bar has *Bookmark* and *Add to Hub*, making it easy to find later or bring into a persistent workspace.

These are the actions available within AI Chat; it still does **not** offer PDF export, nor does it generate images/videos/slides.

## How to choose between AI Chat and Super Agent

Both are accessed from the home page input box; the difference is how they work:

| | AI Chat | Super Agent |
|---|---------|-------------|
| Best for | Direct Q&A, writing, text editing, research | Handing off an entire task with a single sentence |
| How it works | You pick the model, it answers directly | It plans the steps itself, calls tools, and dispatches specialized agents |
| Output | Conversation answers | Finished deliverables like reports / slides / sheets / images / real-world actions |

When in doubt: **just want an answer → AI Chat; want a finished deliverable → Super Agent.**

## Cost and quota

- **Free users**: conversations consume credits, billed by the selected model; choosing MoA (multiple models collaborating) consumes more than a single model. Web search isn't charged separately — it's folded into and settled with that message.
- **Plus / Pro users**: core AI Chat conversation is **unlimited and consumes no credits**; to prevent abuse there's time-window-based usage throttling — when you hit the limit it pauses and automatically resumes after a while.

Uploading files and voice dictation are themselves free; the message they support is billed normally as part of the conversation.

## FAQ

**Q: The old link was moa_chat — does it still work?**
Yes. `moa_chat` is the old entry point that AI Chat replaced, not a standalone product. Starting a new conversation from an old link will **automatically redirect to AI Chat**; only historical projects with a specific conversation id still open in their old form for you to view. New conversations all happen in AI Chat.

**Q: What's the difference between MoA and picking a single model?**
Single model = one model answers; MoA = multiple models answer separately and then synthesize into one. MoA answers are more comprehensive but consume more. See [Models and MoA](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-chat-models-and-moa.md) for details.

**Q: Can AI Chat generate images or make slides?**
No. AI Chat focuses on conversation. To generate images/videos or make slides/sheets, use the corresponding dedicated product, or hand it off to Super Agent.

## Quick guide

| I want to… | Read this |
|-------|--------|
| Start a conversation and use web search / upload / voice | [Get Started](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-chat-get-started.md) |
| Figure out which model to pick and whether to use MoA | [Models and MoA](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-chat-models-and-moa.md) |
