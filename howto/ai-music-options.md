# AI Music — Creation Options

> For Buddy Agent internal use.
> type: howto | feature: ai-music | keywords: vocals, instrumental, instrumental, custom lyrics, lyrics, genre, genre, duration, duration, model selection, multi-model, comparison, background music, soundtrack
> User loop: Specify vocals/instrumental, lyrics, genre, duration, and model in the prompt and toolbar → let AI generate based on your preferences
> Help Center: none

## Why use creation options

- **Precise control**: Going from "just give me a song" to "about 2 minutes, with vocals, using my lyrics, jazz style" — the more specific you are, the closer the result is to what you want.
- **Save credits and time**: Spell out your preferences upfront to avoid redo detours.
- **Multi-model comparison**: When you're not sure which model to use, generate multiple versions at once and pick the best.

## Prerequisites

- You're already in AI Music: `https://www.genspark.ai/agents?type=music_agent`
- Most preferences go straight into the prompt; model and genre can also be chosen from the toolbar above the input box

## What you can specify

### 1. Vocals or instrumental

Make it clear in your request whether you want vocals:
- **Songs with vocals**: Say "with vocals" / "a song about…" and AI will write lyrics and sing by default
- **Pure instrumental / background music / soundtrack**: Say "instrumental" / "background music" / "cinematic score" for no vocals

### 2. Lyrics: auto-written or your own

- **Auto-written lyrics** (default): For songs with vocals, AI first generates lyrics based on the theme/mood and **shows them to you before continuing to generate**.
- **Use your own lyrics**: Just include the lyrics in your request.

> ⚠️ **Some music models don't support custom lyrics** (they can only do pure instrumental or auto-written lyrics). Per the code, if you provide lyrics but the selected model doesn't support them, AI will **tell you first** what will happen and **wait for your confirmation** on whether to continue or switch to a model that supports custom lyrics before starting generation.

### 3. Genre

Two ways to specify the genre:
- **Genre selector**: Click the genre button above the input box (shows **Auto Genre** by default, meaning AI decides), open it, and pick a specific genre.
- **Write it into the prompt**: Just say "jazz" / "lo-fi" / "epic orchestral", etc.

> The list of available genres **follows what's shown in the UI** (it changes with product updates).

### 4. Duration

State the approximate duration in your request (e.g. "around 2 minutes"). **The actual available duration varies by model** — most models support shorter clips, while a few can produce longer music of around 5 minutes.

### 5. Model selection / multi-model comparison

- **Auto-select Models (default, auto-mix)**: The default button shows **Auto-select Models**, which uses Mixture-of-Agents to pick models automatically, **calling multiple models in one go, each producing a track**.
- **Manual model selection**: Open the model selector and pick a specific music model (use this when you only want one track or want to save credits).
- **Multi-model comparison**: Use the default MoA or request multiple models in your prompt, and AI will generate each separately. The result is **one track card per model**, side by side for comparison — **not a V1/V2 version toggle**.

> The list of available models and their names **follows what's shown in the UI** (it changes with product updates).

### 6. Assets (results library)

The third item in the toolbar is **Assets** (with a `>` arrow), the entrance to the results/asset library — generated music is automatically collected here (and also synced to AI Drive). There's also a **Standard** tier dropdown at the bottom of the input box. **There is no control named "Settings" in the toolbar.**

## FAQ

**How do I get AI to use lyrics I wrote?**
Just include the lyrics in your request. Note that some models don't support custom lyrics — in that case AI will first prompt you to switch models or use auto-written lyrics instead.

**What's the difference between Auto Genre and manually selecting a genre?**
Auto Genre lets AI decide the style based on your description; manual selection locks in a specific genre. When in doubt, use Auto.

**How long can the music be?**
It depends on the model — most are shorter, while a few can go up to around 5 minutes. Write your target duration into the request, and AI will get as close as possible within the model's limit.

**How many credits does multi-model comparison consume?**
The default **Auto-select Models** (MoA) calls multiple models in one go, each producing a track, so it **consumes more**; there's no cost estimate before submitting. To save credits, manually select one specific model to produce a single track. Credits are deducted when generation reaches a terminal state — follow what's shown in the UI for specifics.

## Next steps

- Create from scratch in one sentence → [Create music](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-music-create.md)
- Listen, download, switch versions, regenerate → [Listen and download](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-music-play-and-download.md)
