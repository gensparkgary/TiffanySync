# Speakly — Product Overview

> For Buddy Agent internal use.
> type: concept | feature: speakly | keywords: Speakly, Genspark Speakly, voice input, dictation, dictation, speech-to-text, talk-to-type, Hands-free, Agent Mode, custom instructions, Meeting Notes, Live Translation
> Entry: https://speakly.ai (download & intro); use inside the desktop app after downloading and installing

## Why use Speakly

Typing can never keep up with your thoughts — especially with long emails, long messages, and meeting notes, where the content is in your head but your hands can't keep pace. Speakly turns **what you say directly into usable text** (official claim: up to 4x faster than typing on a keyboard): press and hold one key and speak in any app, and when you let go, what appears at your cursor isn't a pile of spoken fragments but a polished result with filler words removed and phrasing cleaned up into written form — ready to send. You just talk; the AI handles the rest.

Typical scenarios: replying to emails (dictate and let AI polish it into a professional tone), drafting documents (talk as you think to quickly produce a first draft), turning ideas into an outline before a meeting, jotting things down on the fly, cross-language communication (speak your native language, get text in the target language), and using the Terminal Helper instruction to turn natural language into runnable terminal commands.

## What is Speakly

Speakly (shown in the app as "Genspark Speakly") is an **AI voice input desktop app**, available on both mac and Windows. Core usage: press and hold the trigger key and speak in any app (default **Fn** on mac, default **Right Alt** on Windows, both changeable), and when you let go, the AI-polished text appears right at your cursor. It requires an internet connection, and you sign in with your Genspark account.

Beyond dictation, it also includes: Agent Mode (hand what you say off to Genspark to process), custom instructions, a personal dictionary, **Meeting Notes recording transcription**, and **Live Translation real-time subtitle translation**.

## Four voice modes

| Mode | How to trigger | What you get | Default state |
|------|---------|---------|---------|
| **Dictation** | Press and hold the trigger key, speak, release | Polished text inserted at your cursor | On |
| **Agent Mode** | Quickly double-tap the dictation key | An "Ask Genspark..." input bar pops up; after confirming, opens the browser to Super Agent to handle the task | On (can be turned off) |
| **Hands-free** | Click the assigned key to start / press again to stop | Long passages without holding — speak, then it polishes and inserts | Off (need to set a key first) |
| **Custom Instructions** | Press and hold a custom key (preset Option+1..9 on mac / Right Ctrl+1..9 on Windows) and speak | Text processed per the instruction you set (e.g. translated straight to English) | Templates all off by default |

**Recommendations**: everyday input → dictation is enough; long dictation where you don't want to hold the key → set up a Hands-free key first; recurring processing needs (translation, rewriting into a professional tone) → custom instructions; want Genspark to actually do work rather than just type → Agent Mode.

**Selected-text rewrite** is a cross-mode capability: first select a passage of text, then use any voice mode to speak an instruction (e.g. "Turn it into a professional email"), and the AI will rewrite based on the selected content. If nothing is selected, it prompts "Please select some text first".

**"Translation" is not a standalone mode**: it consists of two parts — the Translation Language in Settings (choose the target language) and the built-in Translate to English instruction. See [Custom Instructions & Dictionary](https://page.gensparksite.com/manual/buddy-guides/v1/en/speakly-custom-instructions-and-dictionary.md) and [Settings & Account](https://page.gensparksite.com/manual/buddy-guides/v1/en/speakly-settings-and-account.md) for details.

## Billing: word count and credits, two separate lines

| Line | Which features it covers | Rules |
|----|------------|------|
| **Word quota** (no credits deducted) | Dictation, Hands-free, custom instructions, selected-text rewrite | Free users get **4,000 words/week** (resets every Monday); paid members (Plus/Pro/Team/Enterprise) get **unlimited**; new users get a **1-week** unlimited trial |
| **Credits** | Agent Mode, Meeting Notes (recording/import, by duration), Live Translation (by duration), AI summaries | Paid member perk: recording transcription within 24 hours per day is credit-free (excess counted at normal credit rates); summary features are entirely free for members |

Note: **the trial only covers the word quota line**, not the credits line — during the trial, Meeting Notes transcription and the like are still counted under the credit rules.

## Platform differences

| | mac | Windows |
|---|-----|---------|
| Default dictation key | **Fn** (changeable) | **Right Alt** (changeable) |
| Permissions | Requires Accessibility + microphone permissions; recording system audio requires system audio permission (optional); Settings has a Permissions page | No extra system audio permission needed; Settings has no Permissions page |
| Closing the window | Can be set to hide the Dock icon | Can be set to minimize to the tray |

**Mobile version**: there's also a Speakly app for iPhone / Android (downloadable from the App Store / Google Play); an in-app button triggers speaking, and there's no global shortcut.

## Privacy

Your entire dictation history is stored on your own device; voice data is transmitted and processed over an encrypted channel, and the cloud does not permanently store your original audio. See the full terms in the [speakly.ai Privacy Policy](https://speakly.ai/privacy).

## Relationship with AI Meeting Notes (web version)

The Meeting Notes in the Speakly client and the web-version AI Meeting Notes are the **same data**: meeting notes recorded in the client can be viewed and managed on the web too, once signed in to the same Genspark account. For recording, importing, editing, and exporting within the client, see [Meeting Notes & Live Translation](https://page.gensparksite.com/manual/buddy-guides/v1/en/speakly-meeting-notes-and-live-translation.md); for the web-side Meeting Bot, AI follow-up questions, and deep share exports, see the [AI Meeting Notes guide](https://page.gensparksite.com/manual/buddy-guides/v1/en/meeting-notes-overview.md).

## Quick guide by scenario

| What you want to do | Read this |
|--------|--------|
| Download & install, first dictation | [Get Started](https://page.gensparksite.com/manual/buddy-guides/v1/en/speakly-get-started.md) |
| Master dictation / Hands-free / Agent Mode / selected-text rewrite | [Dictation & Voice Modes](https://page.gensparksite.com/manual/buddy-guides/v1/en/speakly-dictation-and-modes.md) |
| Set up custom instructions, maintain your personal dictionary | [Custom Instructions & Dictionary](https://page.gensparksite.com/manual/buddy-guides/v1/en/speakly-custom-instructions-and-dictionary.md) |
| Record meetings, import audio/video, real-time subtitle translation | [Meeting Notes & Live Translation](https://page.gensparksite.com/manual/buddy-guides/v1/en/speakly-meeting-notes-and-live-translation.md) |
| Change settings, check usage, upgrade, give feedback | [Settings & Account](https://page.gensparksite.com/manual/buddy-guides/v1/en/speakly-settings-and-account.md) |

## FAQ

**Can I use it offline?**
No. Voice polishing is done online by AI, so you must be connected to the internet.

**How much can I use for free?**
Free users get a 4,000-word dictation quota per week, resetting every Monday; new users also get a 1-week unlimited trial. Meeting Notes, Live Translation, and the like are counted in credits and don't consume the word quota.

**Can I speak Chinese? Which languages are supported?**
Yes. Speakly supports dictation in **100+ languages**, and non-English content is likewise polished by AI into clearly structured text; Chinese and English also have specific variants you can choose in Settings (go by the options shown in the interface).

**Can I mix Japanese and English in one sentence?**
Yes. Speakly can handle multiple languages mixed within the same sentence, automatically recognizing and correctly transcribing each — no need to manually switch languages.

**Which apps can I use it in?**
Speakly is a system-level tool, usable almost anywhere you can enter text — browsers, Office suites, Slack, various CRMs, Zoom / Teams chat boxes, and 100+ apps.

**How does it relate to the web-version AI Meeting Notes?**
Same account, same data. Speakly is the desktop recording entry point, and the web version is the management and advanced-features surface; records sync across both.

**Can I use it on my phone?**
Yes — there are apps for both iPhone / Android, where you press a button in the app to speak (there's no global shortcut).
