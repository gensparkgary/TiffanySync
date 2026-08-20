# Speakly — Dictation & Voice Modes

> For Buddy Agent internal use.
> type: howto | feature: speakly | keywords: dictation, dictation, Keep my wording, Deep AI polish, Hands-free, Agent Mode, selection rewrite, FloatBar, History, undo, ESC
> User loop: Hold the trigger key and speak → optionally pick a speaking style / Hands-free / Agent Mode / selection rewrite → the polished text is inserted at the cursor; retrieve anything anytime from History

## Why use these modes

- **You set the pace**: pick "Keep my wording" for your exact words, or use the default "Deep AI polish" for ready-to-send prose — one key, two outputs.
- **Long dictation without hand strain**: Hands-free starts recording with one press and stops when you're done, so you don't have to hold the key while dictating a full page.
- **Speech does more than type**: select a passage and speak a command to rewrite it; double-press to hand the task straight to Genspark.

## Prerequisites

- Speakly installed and signed in, with first-run onboarding completed (see [Get Started](https://page.gensparksite.com/manual/buddy-guides/v1/en/speakly-get-started.md))
- Dictation, Hands-free, and selection rewrite all draw from your **word quota** (4,000 words/week on free, unlimited on paid) and don't cost credits; Agent Mode tasks are billed by credits

## Steps

### 1. Everyday dictation

In any app, place your cursor where you want to type, **hold** the trigger key (default Fn on Mac / Right Alt on Windows, configurable) and speak. **Release** it, and the polished text is inserted at the cursor.

### 2. Pick a speaking style

Dictation output comes in two styles; choose one in Settings → General:

- **Deep AI polish** (default): removes filler words and turns speech into polished written prose — great for content you'll send as-is
- **Keep my wording**: preserves your exact words and processes faster — great when you want a verbatim record

### 3. Misspoke? Cancel and undo

While dictating, press **ESC** to cancel the current dictation. The FloatBar shows **"Transcript cancelled"** and offers **Undo**.

### 4. Selection rewrite: command existing text

First **select** a passage of text, then hold any voice key and speak a command like "Turn it into a professional email" — the AI rewrites based on the selection. If no text is selected, you'll see **"Please select some text first"**.

Translate, rewrite, summarize, and reformat all work; **chained commands** are also supported — for example, say "polish it first, then translate into English" and the two steps run in order.

### 5. Hands-free: long dictation without holding

Hands-free is off by default; before using it, assign it a dedicated key in settings. Once set: **click** the key to start recording, **press again** to stop, and the AI-polished text is inserted at the cursor. Clicking the **FloatBar** also drops you straight into Hands-free recording.

While recording, the FloatBar offers **✓** (finish), **✗** (discard), and **Undo**. Hands-free has no wake word — you can only start it with the key or by clicking the FloatBar.

### 6. Agent Mode: hand the task to Genspark

**Quickly double-press** the dictation key to pop up the **"Ask Genspark..."** input bar. Speak or type your task and confirm, and it **opens the browser** to run in Genspark Super Agent — view the results in the browser (nothing is inserted back into your current app).

Agent Mode is on by default; turn it off in settings if you want to avoid triggering it by accident. Tasks run in Super Agent and consume credits per Super Agent's billing rules.

Agent Mode and dictation **share the same trigger key** (hold = dictation, double-press = Agent Mode); change the key for one and the other follows. Hands-free uses a separate key. All three modes can be toggled individually on the Shortcuts page.

### 7. The FloatBar

The FloatBar shows on screen by default, normally prompting "Click or hold {key} to dictate," switching to the matching state during dictation/recording, and occasionally showing usage tips. If you don't want it, turn it off in Settings → General.

### 8. Retrieve what you said from History

The main window's Home page shows your recent dictations (Copy directly). Click **See more** to open **History**: search, expand to view the App you were in and the Selected Text at the time, and for each entry use **Copy / Export Audio (WAV) / Delete / Retry**.

All history is stored on your own device.

## FAQ

**The dictated text doesn't match what I said?**
The default "Deep AI polish" actively rewrites speech into polished prose. To keep it verbatim, switch to "Keep my wording." If a proper noun keeps coming out wrong, add it to your personal dictionary — see [Custom Instructions & Dictionary](https://page.gensparksite.com/manual/buddy-guides/v1/en/speakly-custom-instructions-and-dictionary.md).

**Does dictation cost credits?**
No. Dictation, Hands-free, and selection rewrite draw from your word quota (4,000 words/week on free, resetting every Monday; unlimited on paid). Only Agent Mode tasks are billed per Super Agent's credit rules.

**Where do Agent Mode results go?**
In the browser. Agent Mode opens the browser to run the task in Super Agent, and results are not inserted back into your current app.

**Can I undo what I just said?**
Press ESC while dictating to cancel; once finished, use Undo on the FloatBar, or delete the entry in History.

**Why isn't Hands-free working?**
It's off by default — you need to assign it a key in settings first (or just click the FloatBar to start).

**Is it suitable for long, continuous dictation?**
Yes. A single recording has no hard time limit — as long as there's continuous audio, the session stays active, so long documents and scripts are no problem. Note that extended silence (about 60 seconds with no audio) may end the session automatically.

## Next steps

- Turn recurring processing needs (translation, professional rewriting) into one-tap commands → [Custom Instructions & Dictionary](https://page.gensparksite.com/manual/buddy-guides/v1/en/speakly-custom-instructions-and-dictionary.md)
- All settings — trigger keys, styles, language, microphone, and more → [Settings & Account](https://page.gensparksite.com/manual/buddy-guides/v1/en/speakly-settings-and-account.md)
- Recording and live translation for meetings → [Meeting Notes & Live Translation](https://page.gensparksite.com/manual/buddy-guides/v1/en/speakly-meeting-notes-and-live-translation.md)
