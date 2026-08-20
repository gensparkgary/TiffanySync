# AI Music — Product Overview

> For Buddy Agent internal use.
> type: concept | feature: ai-music | keywords: AI Music, music, AI music, generate music, write a song, song, vocals, instrumental, instrumental, background music, soundtrack, soundtrack, lyrics, lyrics, genre, genre, sound effect, sound effect, download MP3
> Entry: From the homepage **All Agents**, find **AI Music**, or `/agents?type=music_agent`
> Help Center: none

## Why use AI Music

Want a song, a piece of background music, or a soundtrack for a video? Making it yourself means knowing how to compose, arrange, and sing — or hiring someone to score it. High barrier, long turnaround. AI Music lets you describe what you want in **just one sentence**: style, mood, tempo, with or without vocals. The composing, arranging, and singing (if needed) are all handled by AI, and a few minutes later you get an original track you can **listen to and download right away**.

Core value: **One sentence in, a finished track out — composing, arranging, and vocals/instrumental are all automated, and in a few minutes you get original music you can listen to and download. No instrument skills, no music software required.**

## What it can do

- **Generate from one sentence**: describe style, mood, tempo, and instruments, and AI composes accordingly
- **Songs with vocals**: AI writes and sings the lyrics automatically, or uses your own lyrics (some models support custom lyrics)
- **Pure instrumental / background music / soundtrack**: generate music without vocals — great for video, presentations, and game soundtracks
- **Sound effects**: the same entry can also generate sound effect clips
- **Pick a genre**: the Genre selector in the toolbar lets you choose a specific style or leave the default (Auto Genre)
- **Pick a model / auto-mix**: defaults to **Auto-select Models** (Mixture-of-Agents auto model selection, calling multiple models at once to each produce a track); you can also manually pick a specific model
- **Built-in player**: listen right after generating
- **Multi-model comparison**: with Auto-select / when requesting multiple models, the results appear as **one track card per model** side by side (not V1/V2 version switching)
- **Download / save**: download the audio file; results are automatically collected into the Assets panel on the right / AI Drive

## How AI Music differs from making audio elsewhere

| What you want | Which to use |
|--------|--------|
| **Generate an original track from one sentence** (composing + arranging + vocals/instrumental) | **AI Music** |
| Turn **already-written text** into speech/narration (TTS, voice cloning) | AI Audio (text to speech) |
| Generate **a full podcast episode with hosted dialogue** from one sentence (auto research + scriptwriting + voiceover + scoring) | AI Pods |

Not sure → for "a song / a soundtrack / a piece of background music" use **AI Music**; for "narration that reads text aloud" use AI Audio; for "a full podcast episode" use AI Pods.

## About credits

**Generating music consumes credits** — it's a complete AI creation (understanding the request, writing lyrics when needed, calling the music model to compose and arrange), and credits are **deducted when generation reaches its final state (settlement on completion)**. There's **no cost estimate or confirmation dialog before submitting**; the default **Auto-select Models** (MoA) calls multiple models at once and produces one track each, so **a single run may consume a lot of credits** — to save credits, manually pick a single model. After generating, **listening, downloading, and comparing across multiple track cards are all free**; **regenerating** with a follow-up prompt **consumes credits again**.

> Actual consumption, available models, and the genre list all follow what's shown in the UI. Generation usually takes a few minutes.

## Quick guides by scenario

| What you want | See this |
|--------|--------|
| Generate a track from one sentence (pick model/genre, wait, listen) | [Create music](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-music-create.md) |
| Vocals or instrumental, use your own lyrics, pick genre/duration/model | [Creation options](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-music-options.md) |
| Listen, download, save, switch versions, regenerate | [Listen and download](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-music-play-and-download.md) |

## FAQ

**How is this different from making music myself with music software?**
Making it yourself requires knowing how to compose, arrange, and sing — or hiring someone to score it. AI Music does all of this from one sentence, producing an original track you can listen to and download in a few minutes, with no music theory or software background needed.

**Can I use my own lyrics?**
Yes — just include the lyrics in your request. Some music models can only auto-write lyrics or produce pure instrumental; per the code, if the model you chose doesn't support custom lyrics, AI will let you know first and ask whether to continue (the vocals/lyrics workflow wasn't tested in this round of verification). See [Creation options](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-music-options.md).

**How many tracks per generation? Can I request multiple versions?**
The default **Auto-select Models** (MoA) calls multiple models at once, with each model producing one track (multiple track cards compared side by side, not V1/V2 version switching). To get just one track, manually pick a specific model. See [Listen and download](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-music-play-and-download.md).

**Can I edit a track after generating?**
There's no dedicated Regenerate button — just send a follow-up request in the input box at the bottom to have AI regenerate (this consumes credits again).
