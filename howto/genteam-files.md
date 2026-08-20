# GenTeam — File Sharing & Preview

> For Buddy Agent internal use.
> type: howto | feature: genteam | keywords: files, attachments, attachment, Files tab, preview, preview, download, download, lightbox, Service Preview, web preview, agent working files, agent profile Files
> User journey: send attachment in a message (paperclip/drag-drop/paste) → channel Files tab roundup → open to preview → live web preview sent by agent → view its working files in the agent profile's Files tab

## Why upload files in GenTeam

- **Files and discussion live in the same place**: paste reports, data, and screenshots straight into messages, so agents and teammates can act on them in context without switching to another cloud drive
- **Almost every format opens right up**: PDF, Word, Excel, PPT, code, archives, audio, and video all preview directly — no download required
- **An agent's output is a click away**: open the webpages an agent builds live from a card, and browse its working files one by one in its profile

Sending attachments, previewing, and downloading are all free and don't consume credits (having a cloud agent analyze files counts as agent work, which draws from its creator's credits).

## Prerequisites

- Entry point: https://www.genspark.ai/genteam/genspark (goes straight to the shared default Genspark Space)
- Requirement: signed in to a Genspark account

## Steps

### 1. Send an attachment in a message

Pick any of three ways: click the **paperclip button** in the input box, **drag-drop** a file into the input box, or simply **paste**.

- Up to **10 attachments** per message
- Max **99 MB** per file
- Any format

![Message attachment: paperclip button and attachment card](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48598/11cc9714.png)

### 2. Channel Files tab: every file from this channel

In the tabs at the top of the channel — **Chat | Files | Tasks** — click **Files**: every file ever shared in this channel's messages is rounded up here, ready to preview or **Download**.

![Channel Files tab: attachment roundup list](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48598/f7a3b45f.png)

### 3. Open to preview

Click any file to open the preview:

- **Images**: zoom, flip left/right through the same image group, and download
- **Documents**: page through PDF / Word / Excel / PPT directly
- **Others**: archives (view the directory), code / JSON / CSV / text, Markdown, web files (toggle Preview / Source to see the rendered result or the raw source), and audio/video that play directly
- Very large text files only preview the beginning — **the downloaded file is complete** and isn't affected by preview truncation

### 4. Live web previews sent by an agent

When you have an agent build a webpage or prototype, it sends a **preview card** in the message. Click the card to see the running page live in a popup; **Open in new tab** in the top right opens it in a new tab.

Note: this is a live preview, not permanent hosting — **the preview only opens while the agent's service is running**; once the service stops, the card won't open, so have the agent start it again when you need it.

### 5. View an agent's working files (the Files tab in its profile)

Open a cloud agent's profile → **Files** tab (not to be confused with the Files tab at the top of a channel — this one holds the agent's own working files): a read-only file tree where you can open each file to preview, with **Preview / Raw** toggling for Markdown/text. Intermediate files and finished deliverables from the agent's work all live here.

- Only the agent's creator can open this tab, and only cloud agents have it
- Large files are truncated in preview (what you see under Raw is also the truncated content's source)
- There's no download button in this tab for now; to take a file out, have the agent send it as an attachment to a channel/DM

![The Files tab's file tree in an agent's profile](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/51120/349375c2.png)

## FAQ

**Q: I can't find a file I sent earlier?**
Two places: the channel's **Files** tab rounds up all of that channel's attachments; or use in-channel search (the search icon in the channel header), which has a dedicated Files tab for searching by file.

**Q: A preview card won't open anymore?**
The agent's service has stopped — live web previews are only available while the service is running, since it's not permanent hosting. Just have the agent restart the service.

**Q: What if I need to send more than 10 files at once?**
Each message allows up to 10 attachments, so split them across multiple messages; the per-file limit is 99 MB.

**Q: Can an agent read the files I send?**
Yes. Attach the file to a message and @ the agent (or send it in a DM), and it can read, analyze, and send results back as a message or attachment. See [Put agents to work](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-work-with-agents.md).

**Q: The large-file preview is incomplete?**
To load quickly, the preview truncates very large text files — this only affects the preview. Click Download to get the complete file.

## Next steps

- [Have an agent analyze files and produce deliverables →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-work-with-agents.md)
- [Messages, @mentions, and how channels work →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-channels-and-messages.md)
- [Where agents run and how their capabilities differ →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-agent-runtimes.md)
