# AI Audio — Product Overview

> For Buddy Agent internal use.
> type: concept | feature: ai-audio | keywords: AI Audio, audio, voice, voice-over, narration, voice-over, narration, TTS, text to speech, text-to-speech, read aloud, multi-character, dialogue, dialogue, multilingual, voice, voice, emotion, emotion, voice clone, voice clone, sound effect, download audio, MP3
> Entry: from the homepage **All Agents** find **AI Audio**, or `/agents?type=audio_generation_agent`
> Help Center: none

## Why use AI Audio

You want to turn text into speech — a product narration, video voice-over, audiobook, multi-character dialogue, an alert sound. Doing it yourself means either recording it, hiring a voice actor, or learning audio software — a high barrier and a long turnaround. AI Audio lets you **hand the text straight to the AI to read out loud**: pick a voice or don't, ask for narration, multiple characters talking, different languages and emotions — and get a piece of audio you can **listen to and download directly** in seconds to minutes.

Core value: **Turn any text into ready-to-use speech — read-aloud, voice-over, multi-character dialogue, different languages and emotions all handled by AI, with listenable, downloadable audio in seconds to minutes, no recording gear, no voice actors, no editing software.**

## What it can do

- **Text-to-speech (TTS)**: read any text as natural speech — this is the default behavior; just paste text and it generates
- **Narration / voice-over**: professional narration for videos, presentations, and audio content
- **Multi-character dialogue**: give different characters different voices in one conversation (write `Character: line` in the text and the AI assigns voices automatically)
- **Multilingual**: speech in Chinese, English, Japanese, Korean, and more
- **Voice / emotion / pace**: the voice is assigned automatically by the system per model (no standalone Voice selector); to steer toward a certain voice, emotion (happy/sad/excited…), pace, pitch, or volume, write it into the prompt
- **Sound effects**: the same entry can also generate ambient sounds / sound effect clips
- **Voice clone**: clone a voice from a voice sample, then use it to read aloud (supported by some models)
- **Multi-model fan-out comparison**: by default it uses several TTS models at once, each producing one version (one model per card, e.g. a 2×2 grid), making it easy to compare side by side; to save credits, manually pick a single model
- **Audio processing**: it can also merge, split, transcribe, extract audio from video, and more (advanced capabilities — ask the AI as needed)
- **Built-in player + download**: listen right after generating (play / ±15s / playback speed / volume / timeline), download, and results flow automatically into the Assets panel on the right

## How AI Audio differs from making audio elsewhere

| What you want to do | Which one to use |
|--------|--------|
| Turn **written text** into speech/narration/voice-over, multi-character dialogue, or sound effects (TTS) | **AI Audio** |
| **Generate an original song from one prompt** (composing + arranging + vocals/instrumentals) | AI Music |
| **A full podcast episode with host dialogue** (auto research + scriptwriting + voice-over + scoring) | AI Pods |

Not sure → if you want to "read text aloud / narration / voice-over / dialogue / sound effects," use **AI Audio**; for "a song / a piece of background music," use AI Music; for "a full podcast episode," use AI Pods.

## About credits

**Generating audio consumes credits** — it's a real AI generation (understanding your request, fetching model info, calling a speech/audio model to synthesize). Credits are **deducted when the generation reaches its final state (settlement on completion)**; if a generation fails due to a technical issue, **you are not charged**; and **there is no cost estimate or confirmation dialog before you submit**. Consumption **grows with text length**, and since it fans out to multiple TTS models by default — each producing a version — **a single run consumes a multiple based on the number of versions** (to save credits, manually pick a single model). After generating, **listening, scrubbing the progress bar, downloading, and comparing across multiple result cards are all free**; **regenerating** with a follow-up prompt **consumes again**. **Voice cloning** is a separate, heavier operation that consumes relatively more.

> Actual consumption, available models, and the list of selectable voices/emotions/languages are whatever the interface shows. Short text takes a few seconds; long content or multiple characters may take a few minutes.

## Quick guides by scenario

| What you want to do | Read this |
|--------|--------|
| A piece of text → generate speech (enter, input, wait, listen) | [Create audio](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-audio-create.md) |
| Pick voice/emotion/pace/language/length, multi-character dialogue, sound effects, voice clone | [Voices and options](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-audio-voice-and-options.md) |
| Listen, download, save, compare versions, regenerate | [Listen and download](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-audio-play-and-download.md) |

## FAQ

**How is this different from hiring a voice actor or recording it myself?**
Doing it yourself needs recording gear, a voice actor, or audio software. AI Audio reads your text aloud directly, producing a listenable, downloadable piece of audio in seconds to minutes — and it can do multiple characters, multiple languages, and switch emotions, with no recording or editing experience needed.

**Will it change my text on its own?**
No. By default, what you provide is exactly what it reads, and the AI reads it as-is without adding or removing anything. It only declines to generate when you're clearly asking a question or requesting a settings change. See [Create audio](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-audio-create.md).

**Can it do multi-character dialogue?**
Yes. In the text, use the `Character: line` format (e.g. `Alex: Hello` / `Bob: Hi`), and the AI will assign different voices to different characters. See [Voices and options](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-audio-voice-and-options.md).

**Is this the same as AI Music?**
No. AI Audio is for "reading text into speech/voice-over/dialogue/sound effects"; AI Music is for "composing — generating an original song." For narration and voice-over, use AI Audio; for a song or background music, use AI Music.
