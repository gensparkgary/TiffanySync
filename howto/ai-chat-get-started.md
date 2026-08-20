# AI Chat — Getting Started

> For Buddy Agent internal use.
> type: howto | feature: ai-chat | keywords: AI Chat, getting started, conversation, sending messages, model selection, web search, file upload, voice input, Speakly, copy, regenerate, edit message, share conversation
> User loop: Open AI Chat → pick a model (optional) → type your question (optionally enable web search / attach files / use voice) → send → copy/regenerate/edit to get a usable answer

## Why Start Here

The AI Chat experience comes down to how you use a few key toggles: picking the right model, turning on web search when you need it, and letting it see your files. Master these and you'll get to the point in one shot — fewer detours, fewer wasted credits.

## Opening AI Chat

Select **AI Chat** from the central input box on the Genspark home page, or go directly to `https://www.genspark.ai/agents?type=ai_chat`.
![AI Chat input box with model selection entry point](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35958/d7719a03.png)

## 1. Pick a Model (Optional)

Above the input box there's a **model selection dropdown**. Open it to switch among **dozens of mainstream models** (whatever the interface shows), or choose **Mixture-of-Agents (auto-blend multiple models)** to have several models collaborate on the answer.

You don't have to pick one — it'll use the default model. For which model fits which scenario and whether to use MoA, see [Models and MoA](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-chat-models-and-moa.md).

**Note**: Once you send the first message, the model gets **locked** — clicking the dropdown again will gray it out with the prompt "you need to start a new conversation to switch models." To change models, click New Chat in that prompt. (The web search toggle isn't affected by this lock — see Step 2 below.)

## 2. Enable Web Search (Optional)

The web search toggle sits in the **fixed area at the bottom of the model dropdown**, labeled **"Search Web / Retrieve from Internet"**, and is **ON by default**. When enabled, answers are based on web search results and cite their sources. If your question needs the latest information (news, recent data, real-time content), just leave it on.

Since it's on by default, keep this in mind the first time you use it: every message triggers a web search (which is slightly pricier on the Free tier). Turn it off in the dropdown when you don't need it. This toggle **isn't tied to the model lock** — you can change it anytime, even after a conversation has started. The system remembers your last toggle state. Some models may not support web search, in which case the toggle is unavailable.

## 3. Upload Files / Images (Optional)

Click the **attachment button ("+")** next to the input box. By default you'll see two upload sources: **Browse Local Files** and **Choose from AI Drive** (the menu also includes New Chat). If you've already connected Google Drive, SharePoint, or OneDrive, those sources appear too; they don't show if you haven't connected them.

Once uploaded, you can have the AI answer based on the file's content. **Tip**: If you upload an image, choose a model that supports vision, otherwise a text-only model will ignore the image.

## 4. Use Voice Input (Optional)

The input box has a **microphone button** (i.e. **Speakly** voice dictation, with the tooltip "Don't type, just Speakly"). Click it and speak, and the system transcribes your speech into the input box. Requires browser microphone support.

## 5. Send and Use the Answer

After typing your question and sending it, the answer streams in. A persistent action bar sits below each answer:

| Action | Description |
|------|------|
| **Copy** | Copy the answer content with one click (shows a "Copied" toast) |
| **Thumbs up / down** | Give feedback on the answer |
| **"…" More** | Actions like *Save to Notion*, etc. |

**Edit your question**: Hover over **a message you sent** and copy and edit (pencil) buttons appear — save your edits and the AI re-answers based on the new question (the old answer is replaced).

**Regenerate**: Appears only when an answer **fails**, to retry; it doesn't show for normal answers.

For some accounts or scenarios, **follow-up suggestions** also appear below the answer — click one to keep asking (not visible to all accounts).

## FAQ

**Q: How many credits does sending a message cost?**
Free users are billed by the usage of the chosen model; MoA (multi-model collaboration) costs more. For Plus / Pro users, core conversations are unlimited and don't consume credits (with anti-abuse time-window throttling).

**Q: Is there a size/length limit on uploaded files?**
There's a cap. If a file is very large or long, trim it down before uploading, or split it across multiple questions.

**Q: Why does it seem like my uploaded image wasn't recognized?**
The model you chose may be text-only and doesn't read images. Switch to a vision-capable model and try again.

**Q: Can I export the conversation to PDF or share it?**
**Sharing: yes** — the **Share** button in the top bar generates a shareable link for the conversation (Restricted by default; you can change access scope, copy the link, invite collaborators). Each answer's "…" menu also offers *Save to Notion*. **Export to PDF: no** — AI Chat focuses on conversation and doesn't offer PDF export. If you need a finished file, use the relevant dedicated product or Super Agent.

## Next Steps

- To figure out which model to pick and when to use MoA → [Models and MoA](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-chat-models-and-moa.md)
- To understand AI Chat's overall positioning and boundaries → [Product Overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-chat-overview.md)
