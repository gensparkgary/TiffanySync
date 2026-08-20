# AI Pods — Creating a Podcast

> For Buddy Agent internal use.
> type: howto | feature: ai-pods | keywords: create podcast, generate pods, one-sentence generation, topic, upload file, YouTube, news briefing, video version, cover
> User loop: Go to /agents?type=podcasts_agent → enter a one-sentence request (optionally attach a topic/file/link) → generate in a few minutes → get a ready-to-listen podcast
> Help Center: https://www.genspark.ai/helpcenter/ai-pods

## Why use Create

- **Finished product from one sentence**: Spell out what you want to cover, and the AI automatically researches, writes the script, voices it, adds music, and creates a cover — in a few minutes you get a podcast you can listen to right away.
- **Works with any source**: A topic, an article/web page, a YouTube video, or an uploaded PDF/document — they can all become a podcast.
- **No recording or editing needed**: Even without a microphone or editing skills, you can produce a professional podcast with hosts in conversation.

## Prerequisites

- Login required
- Entry: `https://www.genspark.ai/agents?type=podcasts_agent`, or find **AI Pods** under **All Agents** on the home page
- Generating a podcast consumes credits (covering research + scripting + voicing + cover); if you're short on credits, you'll be prompted to purchase

## Steps

### 1. Open AI Pods

Find **AI Pods** under **All Agents** on the home page, or open `https://www.genspark.ai/agents?type=podcasts_agent` directly.
![AI Pods landing page: ① Prompt input box ② For You community-recommended podcasts](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36052/06b36753.png)

The middle of the landing page is a prompt input box (placeholder text "Enter your pods request here"), with **For you** community-recommended podcasts below — click any of them to listen and get inspiration.

### 2. Enter your podcast request

In the input box, describe the podcast you want in one sentence — you can include the content, language, number of hosts, and style all at once. For example:
- "Give me a daily news briefing podcast on today's tech headlines"
- "Create a podcast explaining the research paper I uploaded"
- "Make a workout motivation podcast with upbeat music and commentary"

Different **content sources** all work:
- **Any topic**: Just describe the topic and the AI automatically researches it online
- **Upload files**: Upload PDF / DOCX / TXT and let the AI generate based on the file content
- **YouTube video / web page link**: Put the link in your request and the AI will read the content

### 3. Wait for generation

After you submit, the AI researches, writes the script, synthesizes host voices, and generates a cover in sequence. The process is shown on the right and **usually takes a few minutes (the interface estimates 5–15 minutes)** — keep the page open during this time.
![AI Pods generating: task progress for Research → Read → Create Podcast](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36052/909eab08.png)

By default a **cover image** is automatically added, and the podcast is presented as a conversation between two hosts.

### 4. Listen to the result

Once generation is complete, the right side shows the built-in player: play/pause, skip forward/back 15 seconds, change speed, and favorite (★); click **Script** to see the full transcript. (**Fullscreen** is only available in the video-version player; the audio player has no fullscreen.)
![AI Pods result: ① Cover ② Player (play/speed/±15s) ③ Script transcript](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36052/59530deb.png)

After listening, you can publish, share, or export — see [Publishing and Exporting](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-pods-publish-and-export.md) for details.

### 5. (Optional) Generate a video version

By default only audio is produced. If you **explicitly request a video version** (a podcast with visuals) in your request, the AI first generates slides visuals, then assembles the visuals along the script's timestamps into a video and merges it with the audio. The video version consumes additional credits.

> Advanced: the music-radio style lets you insert music/sound-effect clips into the script — you need to prepare the audio assets first and mention this in your request.

## FAQ

**How long does generation take?**
Usually a few minutes; the interface estimates around 5–15 minutes. Keep the page open during generation, and you'll be notified when it's done (you'll also get a completion email).

**Can it be based on a file I uploaded?**
Yes. Upload a PDF / DOCX / TXT and say in your request "generate a podcast based on the file I uploaded" — the AI will read the file content to write the script.

**How many hosts by default? Can I change it?**
The default is a two-host conversation. You can request a single narrator in your request, or specify a language and style — see [Languages and Creation Options](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-pods-voices-and-options.md) for details.

**Can I change the generated podcast if I'm not satisfied?**
You can regenerate the cover; for other content, you currently regenerate with an updated prompt. See [Languages and Creation Options](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-pods-voices-and-options.md) for details.

## Next steps

- Specify language/hosts/style, regenerate cover → [Languages and Creation Options](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-pods-voices-and-options.md)
- Publish to the community / share / export MP3 → [Publishing and Exporting](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-pods-publish-and-export.md)
