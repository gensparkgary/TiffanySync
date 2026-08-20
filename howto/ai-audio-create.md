# AI Audio — Create Audio

> For Buddy Agent internal use.
> type: howto | feature: ai-audio | keywords: create audio, text-to-speech, TTS, generate voice, read aloud, narration, voiceover, enter text, wait for generation, listen
> User loop: go to /agents?type=audio_generation_agent → paste in the text you want read aloud → generate directly (by default produces 4 model versions at once) → get listenable, downloadable audio
> Help Center: none

## Why use Create

- **Paste in, get voice out**: hand the text you want read aloud straight to the AI, and it reads it as natural speech automatically — no recording, no voice actors.
- **Zero setup, generate directly**: no need to pick a model or a voice — once you submit, multiple TTS models each generate a version by default, with voices auto-assigned by model.
- **Any type**: narration, voiceover, multi-character dialogue, multiple languages, and sound effects all start here.

## Prerequisites

- Sign-in required
- Entry point: `https://www.genspark.ai/agents?type=audio_generation_agent`, or find **AI Audio** under **All Agents** on the home page
- Generating audio consumes credits, **deducted when generation reaches a terminal state (settlement on completion)**; failures aren't charged; **there's no cost estimate or confirmation dialog before submitting**. A normal request fans out to multiple TTS models by default (each producing a version), so **a single run consumes credits multiplied by the number of versions**; consumption increases with text length. Listening / scrubbing the progress bar / downloading / reading your balance are all free. Actual consumption is whatever the interface shows.

## Steps

### 1. Open AI Audio

Find **AI Audio** under **All Agents** on the home page, or open `https://www.genspark.ai/agents?type=audio_generation_agent` directly.
![AI Audio landing page: text input box + toolbar (Auto-select Models / Assets) + send](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36123/0207c993.png)

The landing page has an input box in the center (placeholder text **"Enter the text you want to convert to speech"**), with the page headline **"Transform your text into natural, lifelike speech"**. The toolbar above the input box has only **2 items**: **Auto-select Models** (model selector, defaulting to automatic model selection / Mixture-of-Agents) and **Assets** (entry to the results asset library). The input box itself also has `+`, `Standard ▾` (model tier dropdown), a microphone, and a send button. **There's no standalone Voice selector** — voices are auto-assigned by the system based on the model.

### 2. (Optional) Adjust model selection

The toolbar has only one generation-related selector, which you can adjust before submitting (or leave alone — just paste the text):
- **Auto-select Models**: defaults to automatic model selection (Mixture-of-Agents); click to open and manually pick specific models. **Available models are whatever the interface shows.**
- **Standard ▾** (inside the input box): the model tier dropdown.

**There's no standalone Voice selector** — you don't need to, and can't, pick a specific voice in the toolbar; **voices are auto-assigned by the system based on the model** (each model has its own voice). To lean toward a particular voice, just write the requirement into your text request (e.g., "use a calm male voice").

> Setup isn't required — just paste the text, and the AI will generate using the auto-selected model, with voices auto-assigned by model. To control voice preference / emotion / speaking rate / language or do multi-character dialogue, see [Voices and options](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-audio-voice-and-options.md).

### 3. Enter the text to convert to speech

In the input box, **paste or type the text you want read aloud directly**, and the AI will read it as speech. For example:
- "Welcome to our product demo. Today we'll walk you through the key features." (product demo narration)
- "Read this Chinese aloud: 欢迎使用我们的服务，祝你有美好的一天。" (Chinese TTS)
- For multi-character dialogue, use the `Character Name: line` format (see [Voices and options](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-audio-voice-and-options.md))

> By default, the AI treats the text you provide **directly as the content to read aloud** and won't ask "do you want to generate this?". It only refrains from generating when you're clearly asking a question ("What voices are available?") or requesting a settings change.

### 4. Wait for generation

After you submit, the AI **starts generating directly with no second confirmation**, running through the tool steps **Get Model Info → Audio Generation** in sequence, with the process shown on the right. **Short text takes a few seconds, long content / multi-character may take a few minutes**; keep the page open during this time (you can click Stop to abort while generating).

**By default it fans out to multiple TTS models, each producing a version** — a normal request usually yields **multiple audio cards (in a 2×2 grid)**, each card being a version from a different model (e.g., ElevenLabs / Gemini TTS / MiniMax / VibeVoice), making it easy to compare side by side and pick your favorite. **This is the default behavior; you don't need to specifically request "multiple versions".** The actual models and number of versions are whatever the interface shows.
![Generate directly with no confirmation: tool steps Get Model Info + Stop abort button](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36123/1971c89d.png)

### 5. Listen to the results

After generation completes, the right side shows multiple audio cards, each with a built-in player whose controls include **play / back 15s / forward 15s / playback speed 1x / volume / timeline**, so you can play each one to compare different model versions. The results are also **automatically collected into the Assets panel on the right** (each card has a **Download Audio** button, card density toggle, and Upload) — no need to manually "add" anything. To get a different version or regenerate, **there's no dedicated "Regenerate" button**: AI Audio is conversational, so just send a follow-up request in the bottom input box.
![Results: 4 TTS model cards by default + built-in player (play / seek / 1x / volume)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36123/b2c2b32c.png)

After listening, you can download, save, or regenerate with a follow-up prompt — see [Listen and download](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-audio-play-and-download.md).

## FAQ

**Will it ask me "do you want to generate this?"**
No. By default the text you provide is the content to read aloud, and the AI generates directly. It only refrains from generating when you're clearly asking a question or requesting a settings change (e.g., "use a different female voice").

**How long does generation take?**
Short text takes a few seconds; long content or multi-character dialogue may take a few minutes. Keep the page open during generation.

**How many versions are generated by default?**
By default it **produces multiple versions in one run** — the system automatically uses multiple TTS models, each generating a version (one model per card), so you can compare side by side and pick your favorite, without specifically requesting "multiple versions". The actual models and number of versions are whatever the interface shows.

**Do I have to pick a model or voice first?**
No. Just paste the text — the model is auto-selected by default (Auto-select Models), and **voices are auto-assigned by the system based on the model** (there's no standalone Voice selector). To lean toward a particular voice, just write the requirement into your text request.

## Next steps

- Pick voice / emotion / speaking rate / language, multi-character dialogue, sound effects, voice cloning → [Voices and options](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-audio-voice-and-options.md)
- Download, compare versions, regenerate with a follow-up prompt → [Listen and download](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-audio-play-and-download.md)
