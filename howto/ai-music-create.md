# AI Music — Create Music

> For Buddy Agent internal use.
> type: howto | feature: ai-music | keywords: create music, generate music, write a song, one-sentence generation, model selection, Genre, genre, wait for generation, listen
> User loop: Go to /agents?type=music_agent → enter a one-sentence request (optional model/genre) → generate in a few minutes → get music you can listen to and download
> Help Center: none

## Why use Create

- **A finished track from one sentence**: describe the style, mood, and tempo, and the AI composes, arranges, and (if needed) writes lyrics and sings — in a few minutes you get music you can play right away.
- **No instrument skills needed**: create original music even without music theory or any arranging software.
- **Any type**: songs with vocals, pure instrumentals, background music, scores, and sound effects are all possible.

## Prerequisites

- Login required
- Entry: `https://www.genspark.ai/agents?type=music_agent`, or find **AI Music** under **All Agents** on the homepage
- Generating music consumes credits, **deducted when generation reaches its final state (settlement complete)**; there is **no cost estimate or confirmation dialog before submission**. The default **Auto-select Models** (MoA) calls multiple models at once, each producing a track, which **may consume more credits in a single run** — to save credits you can manually pick a single model. Actual consumption is as shown in the UI.

## Steps

### 1. Open AI Music

Find **AI Music** under **All Agents** on the homepage, or open `https://www.genspark.ai/agents?type=music_agent` directly.

In the center of the landing page is a prompt input box (placeholder text "Describe the music or sound effect you want to create"), with a row of controls above it — **3 items** in total: **Auto-select Models** (music model selector, defaults to MoA auto-selecting models), **Auto Genre** (genre selector, defaults to auto-determining the genre), and **Assets** (entry to results/asset library, with a `>` arrow); at the bottom of the input box there's also a **Standard** tier dropdown. **There is no control named "Settings".**

![AI Music landing page: prompt input box + toolbar ① model selector Auto-select Models ② genre Auto Genre ③ Assets](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36111/48d6178c.png)

### 2. (Optional) Pick a model and genre

Before submitting, you can adjust two toolbar entries (no need to set them — just describe your request clearly):
- **Music model**: the button defaults to **Auto-select Models** (uses Mixture-of-Agents to auto-select models, calling multiple models at once, each producing a track for comparison). Click to switch to a specific music model. **The available models are as shown in the UI.**
- **Genre**: the button defaults to **Auto Genre** (let the AI determine the genre). Click to pick a specific genre; **the list of available genres is as shown in the UI** (it changes with product updates).

> No need to set these — just describe your request clearly, and the AI will choose based on the description (model Auto-select / Genre Auto Genre).

### 3. Enter your music request

In the input box, describe in one sentence the music you want, including type, style, mood, tempo, instruments, and whether you want vocals. For example:
- "Write an upbeat pop song about summer road trips, with vocals"
- "Generate a calm lo-fi instrumental for studying, around 2 minutes"
- "Make an epic cinematic score for a battle scene"

To use **your own lyrics** or control vocals/instrumental, duration, and genre, see [Creation options](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-music-options.md). The lyrics workflow for songs with vocals (AI writes the lyrics first, then continues) is as described in code and **was not tested in this verification round**.

### 4. Wait for generation

After submitting, the AI understands the request, (if needed) writes lyrics, and calls music models to compose and arrange. The generation process is shown on the right (you'll see tool-call steps like **Get Model Info** and **Audio Generation**), and **usually takes a few minutes** — keep the page open during this time. With the default **Auto-select Models** (MoA), the AI **calls multiple models at once, each producing a track** (one track card per model); to get just one track, manually pick a specific model.

![MoA generation flow: multiple models + Get Model Info / Audio Generation tool calls](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36111/0452f1a4.png)

### 5. Listen to the result

Once generation completes, the audio cards appear on the right, **one track card per model** (with the default MoA you'll see several side by side for comparison). Each card has a built-in player to play/pause and scrub, and you can **download**. The generated results are **automatically collected into the Assets panel / AI Drive on the right** — the top-right corner of each card is a **multi-select checkbox**, and **there is no separate "Add to library" button**. To get another version / regenerate, there's also **no dedicated "Regenerate" button**: AI Music is conversational, so just send a follow-up request in the input box at the bottom.

![Generated result: built-in player + one track card per model + Assets panel](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36111/5d350a27.png)

After listening, you can download, compare across track cards from different models, or regenerate with a follow-up prompt — see [Play and download](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-music-play-and-download.md).

## FAQ

**How long does generation take?**
Usually a few minutes, depending on the model and duration. Keep the page open during generation.

**Do I have to pick a model and genre first?**
No. Just describe your request clearly and the AI will choose automatically (model Auto, Genre Auto). Pick manually if you want precise control.

**How many tracks are generated by default?**
The default **Auto-select Models** (MoA) calls multiple models at once, each producing a track (several track cards side by side for comparison). To get just one track, manually pick a specific model.

**How many credits does generation consume?**
Generation consumes credits, **deducted when it reaches the final state (settlement complete)**, with no cost estimate or confirmation dialog before submission. MoA calls multiple models at once, so it **consumes more**. Actual consumption is as shown in the UI.

## Next steps

- Vocals/instrumental, custom lyrics, genre/duration/model selection → [Creation options](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-music-options.md)
- Download, compare multi-model track cards, regenerate with a follow-up prompt → [Play and download](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-music-play-and-download.md)
