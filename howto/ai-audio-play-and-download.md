# AI Audio — Listening & Downloading

> For Buddy Agent internal use.
> type: howto | feature: ai-audio | keywords: play, listen, player, rewind 15s, forward 15s, playback speed, volume, download, download, Download Audio, Assets, asset library, save, multiple versions, multiple models, compare, Regenerate, regenerate, regenerate
> User loop: generation complete → listen in the player (multiple model cards by default) → download file / save in Assets panel / compare versions / regenerate with a follow-up prompt
> Help Center: none

## Why this page

Once your audio is generated, what you really want is to **listen, keep, and use** it: play it back to confirm the result, download it as a file, compare versions when needed, or regenerate with a follow-up prompt if you're not happy. This page covers everything you can do after generation.

## Prerequisites

- You've already generated at least one audio clip with AI Audio (see [Creating Audio](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-audio-create.md))
- Listening, scrubbing, downloading, and comparing across result cards are **free**; regenerating with a follow-up prompt consumes credits again (deducted when generation reaches a terminal state; the default multi-model fan-out consumes credits proportionally to the number of versions)

## Steps

### 1. Listen (built-in player)

Once generation completes, every audio card on the right has its own built-in player. The controls include **Play / Rewind 15s / Forward 15s / Playback speed 1x / Volume / Timeline** — so you can play and pause, scrub, jump, and adjust speed and volume. By default you'll get multiple cards (one version per model), so just play through them one by one to compare.

### 2. Download

Click **Download Audio** on a card to save the audio file locally. Each model card has its own download button.

> What you download is an audio file, which you can use for videos, presentations, audio content, personal listening, and more.

### 3. Save in the Assets panel

Generated audio is **automatically collected into the Assets panel on the right** — no manual "add" needed. Each card in the panel has **Download Audio**, and you can also switch card density and Upload your own audio. When you want to reuse it, grab it from here or download it directly.

### 4. Compare versions

**Multiple versions are the default** — a regular request produces one version from each of several TTS models, displayed as **one separate card per model** side by side (e.g. a 2×2 grid). Just play through them one by one and pick your favorite. If you want fewer versions, go to the **Auto-select Models** option in the toolbar and manually pick a specific model.

> Listening and comparing across the multiple generated cards **doesn't consume credits** — they're all results from the same single generation.

### 5. Regenerate / get another version

AI Audio is conversational, so there's **no dedicated "Regenerate" button**: when you're not happy with a result, send a follow-up request in the input box at the bottom (e.g. "Read it again with a deeper male voice" / "Slow down the pace") and the AI will regenerate. **Regenerating consumes credits again** (it has to run generation anew, deducted on successful settlement).

## About covers, publishing, and sharing

AI Audio focuses on **generating + listening + downloading**: the result is an audio file, and there's **no "publish to community feed" and no audio-specific Share button** (the top bar only has the project-level Share common to all agents, which defaults to a Restricted link). When you want to use the audio elsewhere, just **download the file** — the result is also already saved automatically in the Assets panel / AI Drive.

## FAQ

**What format is the download?**
You get an audio file you can save locally to play or use in videos / presentations / audio content (the exact format is whatever the downloaded file is).

**Does comparing versions cost credits?**
No. The multiple cards are all results from the same single generation, so listening and comparing is free. Only regenerating with a follow-up prompt consumes credits again.

**Can I save the audio for later use?**
Yes. Generated audio is automatically saved in the Assets panel / AI Drive on the right, and you can also download it as a file directly.

**Can I publish or share it?**
AI Audio's result is an audio file, with no community publish button or audio-specific Share — to share it, download the file and send it out (the project-level Share in the top bar is the Restricted link common to all agents).

## Next steps

- Reset voice / emotion / pace / language / role → [Voice & Options](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-audio-voice-and-options.md)
- Make a new clip from scratch → [Creating Audio](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-audio-create.md)
