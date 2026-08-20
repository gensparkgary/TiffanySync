# AI Write and AI Reply: Let AI Draft Your Emails

> For Buddy Agent internal use.
> type: howto | feature: genmail-ai-write | keywords: AI Write, AI Reply, voice input, dictation, tone, Simplify, Professional, Friendly, custom instructions, Cmd+K, consumes credits
> User loop: Open "AI Write" in the compose box → state your intent in a sentence or by voice → AI drafts the body → accept or discard → adjust tone / use AI Reply suggestions to reply quickly

## Why use AI Write

- **Go straight from "what I want to say" to a finished email**: you just give the key points (or even a single sentence), and AI fills in the wording, structure, and courtesies—saving you the time of picking over phrasing in a blank email box.
- **Never get stuck on "how do I start" when replying**: open an incoming email, and once AI understands the context, it hands you a ready-to-send reply draft—just pick one, tweak a couple of lines, and send.
- **When typing isn't convenient, just speak**: voice dictation lets you dictate your email content, perfect for long emails, mobile scenarios, or replying on the go.

## Prerequisites

- Entry: In the installed and signed-in GenMail desktop client, open the compose view—new email, reply, reply all, or forward all open the rich text editor. For how to use the compose view, see [Compose, Reply & Forward →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-compose-and-reply.md).
- Requirements: signed in with a Genspark account, with at least one email account connected.
- **Consumes credits**: AI Write and AI Reply suggestions both call AI and are credit-consuming features. Voice dictation is billed by duration and has its own separate quota pool (see below).

## Steps

### 1. Open "AI Write" in the body

Place your cursor in the email body area. There are three ways to launch AI Write:

- Click the **AI Write** button in the editor.
- Press **Cmd+K** directly in a blank spot in the body (on Windows, use the corresponding shortcut shown in the UI).
- When the body is empty, a placeholder hint **"Write, press 'space' for AI"** appears—just follow it to trigger AI Write.

![AI Write in the compose view: ① the AI Write entry in the toolbar · ② AI writes content straight into the body, then you accept / discard](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/39196/a4d0fc12.png)

### 2. State what you want to write in one sentence

In the input box that pops up, describe your intent in natural language, for example:

> "Politely decline this collaboration invitation, keep a friendly tone, and add a line about staying in touch for future opportunities."

The more specific you are (recipient, purpose, tone, key info), the closer the draft will be to what you want. If you're replying to an incoming email, AI automatically uses the original message as context, so you don't need to restate it.

### 3. Watch AI write into the body in real time

After you submit, the body is **written out word by word in real time**, and you can watch it take shape. You can stop the generation at any point.

### 4. Accept or discard

When generation finishes, confirmation actions appear:

- **Accept**: commits the generated content to the body, after which you can keep editing it manually like any regular text.
- **Discard**: abandons this generation and restores the body to its original state, so you can restate your intent and try again.

### 5. Adjust tone in one click

Once the body is written (whether by hand or by AI), you can have AI quickly rewrite the tone of the whole passage. Common options include:

- **Simplify**: make the content more concise and direct.
- **Professional**: shift to more formal, professional wording.
- **Friendly**: shift to a warmer, more relaxed tone.

Each rewrite is an AI call and consumes credits.

### 6. Reply quickly with AI Reply suggestions

After opening an incoming email, click **Reply** or **Reply All**, and GenMail gives you several **AI Reply suggestions** (a set of clickable suggestions) based on the incoming content. AI provides suggestions **on demand**—informational emails that don't need a reply may have none. Click one, and the matching reply draft fills into the compose box; tweak it and send.

### 7. Don't want to type? Just speak (voice input dictation)

When typing isn't convenient, you can use **voice input** in the compose view to dictate your email content, and AI turns your words into text in the body. Ideal for long emails or scenarios where typing is awkward.

> **Quota note**: Voice dictation and text-based AI (Write / Reply suggestions / tone adjustment) are **billed differently**—voice is billed by **usage duration** and has its **own separate quota pool**, only consuming credits once that's used up; text-based AI consumes credits directly. Refer to the UI for actual quotas and usage.

### 8. Set your go-to writing instructions (AI Write custom instructions, coming soon)

Save the same kinds of requests you give AI every time (like "always write in English, add my signature at the end, no exclamation marks") as **custom instructions** so AI Write automatically writes to your preferences—this capability is **coming soon** and isn't yet available in the current version's settings. Once it launches, you can find how to use it here.

For the settings entry and a full explanation of each preference, see [Settings & Account Management →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-settings-and-accounts.md).

## FAQ

**Q: How many credits does AI Write cost me?**
AI Write, AI Reply suggestions, and tone adjustment are all credit-consuming AI features, and each generation or rewrite consumes one use. We don't list exact numbers in the docs—refer to your account's real-time usage. Pure manual writing, sending, and saving drafts don't call AI and don't consume credits.

**Q: Is voice dictation billed the same way as AI Write?**
No. Voice dictation is billed by **usage duration** and has its **own separate free quota pool**, only consuming credits after that quota runs out. It and text-based AI use two separate meters that don't draw from each other.

**Q: Can I edit the generated content?**
Yes. Once you click "Accept," the generated text becomes regular body text that you can edit, add to, delete, and reformat however you like. If you're not happy, just "Discard" and rewrite.

**Q: Does tone adjustment touch parts I didn't select?**
Tone rewrite applies to the body content you're currently working on. If you only want to change one paragraph, select it first, then click Simplify / Professional / Friendly.

**Q: I want AI to always write in a fixed style—what do I do?**
For now, state your fixed requirements (language, signature, banned phrases, etc.) clearly in each intent. The ability to save these as custom instructions that AI Write follows automatically is coming soon.

## Next steps

- [Compose, Reply & Forward: editor, attachments, signature, scheduled send →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-compose-and-reply.md)
- [Settings & Account Management: accounts, signature, AI preferences, shortcuts →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-settings-and-accounts.md)
- [Super Agent: run tasks with email as context →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-super-agent.md)
- [GenMail Overview: your inbox now has a brain →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-overview.md)
- [How credits are consumed →](https://page.gensparksite.com/manual/buddy-guides/v1/en/membership-credits.md)
