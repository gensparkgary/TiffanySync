# AI Audio — Voices & Options

> For Buddy Agent internal use.
> type: howto | feature: ai-audio | keywords: voice, voice, timbre, auto-assignment, emotion, emotion, tone, speed, speed, pitch, pitch, language, language, multilingual, duration, duration, multi-character, dialogue, dialogue, narration, narration, sound effect, sound effect, voice clone, voice clone, model selection, Auto-select Models, tier, Standard, multi-model comparison
> User loop: Write your voice preference / emotion / speed / language / character into the prompt (or use the model selector) → let AI generate audio to your specifications
> Help Center: None

## Why use Voices & Options

- **Precise control**: From "just read it" to "use a calm male voice, slightly slower, as narration" — the more specific you are, the closer the result.
- **Multi-character / multilingual**: Give different characters different voices in one dialogue, or read in another language — all in one go.
- **Save time**: State your preferences clearly upfront and avoid redo loops.

## Prerequisites

- You're already in AI Audio: `https://www.genspark.ai/agents?type=audio_generation_agent`
- **Most preferences go straight into the prompt** — there's no separate Voice selector; voices are auto-assigned by the system based on the model. If you want a particular kind of voice, just describe it in text.
- The only generation-related toolbar selector is **Auto-select Models** (the model selector, automatic by default); there's also a **Standard ▾** model-tier dropdown inside the input box.

## How to control the voice

### 1. Voice / timbre (auto-assigned, no separate selector)

AI Audio **has no Voice selector** — you don't pick, and you don't need to pick, a specific timbre. **Voices are auto-assigned by the system based on the model**: by default it fans out to multiple TTS models at once, each with its own set of voices (e.g. one model gives Jane, another Charon, another Alice). In the results, each card is a version from a different model with a different voice — just listen through and pick your favorite.

To bias toward a certain voice, **write your request into the prompt**, e.g. "use a calm male voice" / "a gentle female voice" / "a lively young female voice" — the AI will try to match your description during auto-assignment (subject to the chosen model's capabilities).

> Which voices each model offers, and which one ends up being used, are **whatever the UI shows** (this changes with product updates).

### 2. Emotion / tone

State the emotion and tone in your request, e.g. "happy and energetic" / "sad and somber" / "a professional broadcast tone." In multi-character dialogue, you can also tag lines with emotions (e.g. `[curious]` / `[focused]`). Some models support emotions like happy, sad, excited, surprised, neutral, and more.

> Exactly which emotions are supported varies by model — **go by what the UI shows**.

### 3. Speed / pitch / volume

State the speed in your request (e.g. "speak slowly" / "a bit faster"); some models also support pitch and volume adjustments.

### 4. Language

AI Audio supports reading in multiple languages (Chinese, English, Japanese, Korean, and more). Just write your text in the target language, or state which language to use, and the AI will use a voice in that language.

> Exactly which languages are supported is **whatever the UI shows** (varies by model).

### 5. Duration

For sound effects and music, you can state a rough duration in your request (e.g. "a 10-second whoosh sound effect"). **For plain TTS, duration is determined by the length of the text** — the longer the text, the longer the audio; the actual usable duration cap varies by model.

### 6. Multi-character dialogue (each speaker gets a different voice per model)

To create a conversation between multiple characters, write your text using **`Character: line`** format, and the AI will **assign a different voice to each character** and keep it consistent:
```
Alex: Hey, did you finish the report?
Bob: Almost — just need ten more minutes.
```
- The character names are **the roles in your script** (e.g. Alex, Bob), not voice-actor names — you write the character name, and the AI automatically gives each speaker a different voice.
- By default, each fanned-out model assigns a different voice to each of the two speakers (e.g. one model uses Alex=Alexandra / Bob=Mark, another uses Alex=Leda / Bob=Charon).
- You can also do a "narration + character dialogue" mix; the AI will use different voices for the narrator and each character, and can apply emotion tags like `[curious]` / `[focused]`.
![Multi-character dialogue: each speaker gets a different voice per model](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36123/f9a97f79.png)

### 7. Sound effects

The same entry point can also generate sound effects — describe the sound you want in your request, e.g. "a short whoosh transition sound" / "rain on a window, ambient." Sound effect clips are usually short.

### 8. Voice clone

Some models support **cloning a timbre from a voice sample**, then reading your text in that cloned voice. You'll need to provide a reference audio clip that's long enough; if reference audio is missing, the AI will **tell you what's missing first** before continuing.

> Voice cloning is a heavier one-off operation that **consumes relatively more** — go by what the UI shows.

### 9. Model selection / multi-model comparison

- **Default (multi-model fan-out)**: Leave the settings alone and the AI uses **Auto-select Models** (Mixture-of-Agents) to call multiple TTS models at once, **with each model producing its own version** — the result is several cards side by side for comparison.
- **Manual model selection**: Open the **Auto-select Models** selector in the toolbar and pick a specific model (useful when you want fewer versions and to spend fewer credits).
- **Model tier**: The **Standard ▾** inside the input box is the model-tier dropdown.

> The exact options shown when the model selector is expanded are **whatever the UI shows** (this changes with product updates).

## FAQ

**How do I make the AI use a specific voice?**
Just describe it in your request ("calm male voice / lively female voice / a bit gentler") — AI Audio has no separate Voice selector; voices are auto-assigned by the system based on the model, and your prompt description guides the assignment.

**How do I write multi-character dialogue?**
Use the `Character: line` format, one line at a time (`Alex: ...` / `Bob: ...`), and the AI will give each character a different voice, assigned by each model.

**Can I switch languages?**
Yes. Just write your text in the target language, or state which language to use, and the AI will read in that language. Supported languages are whatever the UI shows.

**How many versions are produced by default?**
By default, **multiple versions at once** — the AI automatically produces one version per model. To get fewer versions and save credits, manually pick a specific model in the Auto-select Models toolbar.

**What do I need for voice cloning?**
A reference audio clip that's long enough. If reference audio is missing, the AI will prompt you first. Cloning consumes relatively more — go by what the UI shows.

## Next steps

- Create from a block of text → [Create audio](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-audio-create.md)
- Listen, download, compare versions, regenerate → [Listen & download](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-audio-play-and-download.md)
