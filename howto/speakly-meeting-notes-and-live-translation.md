# Speakly — Meeting Notes & Live Translation

> For Buddy Agent internal use.
> type: howto | feature: speakly | keywords: Meeting Notes, meeting notes, recording, import, Import File, Live Translation, live translation, subtitle, Subtitle, AI Smart Summary, speaker
> User loop: Record or import via the sidebar Meeting Notes → get an editable, exportable, shareable set of meeting notes; Live Translation shows translated subtitles live and generates a one-click summary

## Why record meetings in Speakly

- **Just listen and talk during the meeting**: record directly on desktop (you can even capture the other party's audio from the system), and editable notes are generated automatically afterward — no need to get distracted taking notes mid-meeting.
- **Keep up even if you don't understand**: turn on Live Translation for foreign-language meetings and get real-time translated subtitles floating on your screen, plus a one-click summary at the end.
- **Available everywhere once recorded**: notes recorded in the client share the same data as the web AI Meeting Notes, so you can keep asking follow-ups and manage them in depth on the web.

## Prerequisites

- Speakly installed and signed in (see [Get Started](https://page.gensparksite.com/manual/buddy-guides/v1/en/speakly-get-started.md))
- Entry points: **Meeting Notes** / **Live Translation** in the main window sidebar (once signed in, the tray menu also has a Meeting Notes entry)
- Recording "system audio" (the other party's voice) on mac requires system audio permission; Windows needs no extra permission
- Billing: recording/import transcription and Live Translation **consume credits based on duration**; paid members get up to 24 hours of recording transcription per day credit-free, and AI Summary is fully free for members. Note: **trials do not cover credits**, they only cover the transcription word-count allowance

## Steps

### 1. Record a meeting (New Note)

Go to **Meeting Notes** in the sidebar and click **New Note** to **start recording immediately** (mic only by default). The transcription overlay during recording has an **audio source dropdown** where you can switch between three sources at any time:
- **Mic** (default): mic only (in-person meetings, dictating to yourself)
- **System**: system audio only (listening to an online share/meeting without speaking yourself)
- **Mic + System**: both (online meetings where you also speak)

Because it records system and microphone audio, it's **not tied to any meeting platform** — Zoom, Teams, Google Meet, or any audio/video call works, and so do in-person meetings, phone calls, and podcast recording. During recording you can also open the floating subtitle window to follow the live transcription, pick a target language to see the original + translation — same behavior as Live Translation below.

### 2. Let Speakly remind you to record

When it detects a Zoom / Google Meet / Teams meeting starting, Speakly pops up a reminder asking whether to start recording; it also reminds you when the meeting ends.

### 3. Import existing audio/video (Import File)

If you already have a recording/video file, use **Import File** to upload it. Common audio and video formats are supported (M4A, MP3, MP4, WAV, etc. — refer to the import window for the exact list), with a **1GB max per file**. When your available allowance is insufficient, the prompt includes an **Upgrade** button.

### 4. Wait for processing to finish

Once recording ends or an import completes, transcription and note generation run automatically. Processing usually takes **about 3–5 minutes**, and you'll get an **email notification** when it's done, with the notes appearing in the list.

### 5. View and edit notes

Open a set of notes to enter the detail page, which has two parts:
- **Notes**: the AI-generated notes, editable directly as text
- **Transcript**: the verbatim transcript, which automatically distinguishes multiple speakers with timestamps; you can **rename** speakers (change Speaker 1 to a real name)

The desktop detail page **has no AI chat and no visualization view** — to ask follow-up questions about the meeting content, open the same set of notes on the web, see [Review and Edit (Web)](https://page.gensparksite.com/manual/buddy-guides/v1/en/meeting-notes-review-and-edit.md).

### 6. Export and share

On the detail page you can **export** the notes as Markdown / Word (docx) / plain text (txt) / PDF, and you can also generate a **share link** to send to attendees.

The web version offers more sharing options such as sending by email and saving to Notion, see [Share and Export (Web)](https://page.gensparksite.com/manual/buddy-guides/v1/en/meeting-notes-share-and-export.md).

### 7. Live Translation real-time subtitles

Go to **Live Translation** in the sidebar, choose the **audio source** (Mic / System / Mic + System) and **Translate to** (target language), then start — the **recognition language is auto-detected**, so there's no need to pick a source language. Two display modes:
- **Transcript mode**: the translation is shown inside the app window
- **Subtitle mode**: floating subtitles overlaid on the screen, ideal for keeping Zoom open while you watch

The original text and translation can be **toggled independently** — show only the original, only the translation, or both side by side — great for cross-language meetings, foreign-language lectures, and watching foreign-language videos.

When it ends, you can use **AI Smart Summary** to generate a summary of the session (about 30 seconds); the summary language is selectable (refer to the interface).

## FAQ

**What's the relationship with the web AI Meeting Notes?**
Same account, same data: notes recorded here are also visible and manageable in AI Meeting Notes on the web at `genspark.ai`; for web features like automatic Meeting Bot join and AI follow-ups, see the [AI Meeting Notes guide](https://page.gensparksite.com/manual/buddy-guides/v1/en/meeting-notes-overview.md).

**Can I record the other party's voice (in an online meeting)?**
Yes — set the audio source to **System** or **Mic + System**. On mac you first need to grant system audio permission (Settings → Permissions); Windows needs no extra setup.

**Does recording meetings cost anything?**
Recording and import transcription consume credits based on duration; paid members get up to 24 hours of recording transcription per day credit-free. Note that trials only cover the transcription word count, not the credit consumption here.

**Why is processing taking so long / never finishing?**
Transcription and generation usually take 3–5 minutes, longer for long recordings; you'll get an email notification when it's done. Keep your network stable and check back on the list status a bit later.

**Where can I ask the AI follow-up questions about the notes?**
The desktop detail page has no AI chat. Open the same set of notes on the web to ask follow-ups, see [Review and Edit (Web)](https://page.gensparksite.com/manual/buddy-guides/v1/en/meeting-notes-review-and-edit.md).

## Next steps

- Web Meeting Bot auto-join and calendar connection → [Meeting Bot and Calendar](https://page.gensparksite.com/manual/buddy-guides/v1/en/meeting-notes-bot-and-calendar.md)
- View, edit, ask follow-ups, and search on the web → [Review and Edit](https://page.gensparksite.com/manual/buddy-guides/v1/en/meeting-notes-review-and-edit.md)
- Quotas, membership perks, and upgrading → [Settings and Account](https://page.gensparksite.com/manual/buddy-guides/v1/en/speakly-settings-and-account.md)
