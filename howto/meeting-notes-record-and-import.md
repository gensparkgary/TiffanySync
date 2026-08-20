# AI Meeting Notes — Recording & Uploading

> For Buddy Agent internal use.
> type: howto | feature: meeting-notes | keywords: recording, record, upload audio, Import Audio, transcription, generate notes, New Note, Notes language
> User loop: Go to /meetingnotes/home → record live or upload audio/video → transcribe and generate → get notes with full transcript and summary

## Why use Recording & Uploading

- **No need to take notes during the meeting**: Tap record on-site, focus on the discussion, and the notes are generated as soon as it ends.
- **Existing recordings work too**: Already have an audio or video file? Just upload it to turn it into notes.
- **Automatic language detection**: No need to set the language in advance—transcription auto-detects based on what's actually spoken, capturing every line even when multiple languages are mixed.

## Prerequisites

- Sign-in required
- Entry point: `https://www.genspark.ai/meetingnotes/home`, or the **AI Meeting Notes** tile on the home page
- Recording/upload transcription consumes credits (based on duration, with free minutes included); if you're low on credits, you'll be prompted to purchase

## Steps

### 1. Open AI Meeting Notes

Click the **AI Meeting Notes** tile on the home page, or go directly to `https://www.genspark.ai/meetingnotes/home`.
![AI Meeting Notes home page: the New note split button with its menu open (Start recording / Capture with Speakly / Add meeting URL / Import file), plus the Notes list and Search box](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/51140/d0772c75.png)

At the top right of the page you'll find a search box (placeholder text "Search"), a **New note** button, and a settings gear; the main area is your list of meeting notes, with the recording duration shown under each entry's title. If you've connected a calendar, you'll also see "Coming up" for upcoming meetings.

Above the list there is also a **Source** filter that lets you filter notes by origin: **All Notes / SecondBrain Note / Meeting Notes**.

### 2. Record live

Click **New note** at the top right to start a new recording and enter the recording screen. **New note** is a split button: clicking it directly starts recording right away; clicking the arrow on its right opens a menu with **four** items: **Start recording**, **Capture with Speakly** (subtitled "Voice dictation app — with smarter Meeting Notes built in", tagged "FREE FOR PLUS & PRO"), **Add meeting URL** (paste an online-meeting link for the Bot to join), and **Import file** (upload a file).

If a dialog titled **"Record with Speakly for the best experience"** appears after you click record (its primary CTA is **Download Speakly**), click the secondary **Continue in browser** option to keep recording in the browser.

The recording screen provides:
- **Start / Pause / Resume / End** controls + a live timer + a sound waveform
- A **title** and a **notes input box**: jot down notes while recording (placeholder text "Feel free to write notes here"); these notes serve as extra context to help the AI generate more accurate summaries

Recording notes:
- **No length limit**—record for as long as you need
- Records only the device's **microphone**, not the sound played by the system
- If interrupted partway, it automatically resumes; on the web, if generation fails, click **Resume** on that recording entry to re-upload

### 3. End the recording to generate notes

Click **End** to stop and upload. While uploading, **keep the page open until the progress passes 50%** to avoid upload failures.

The system automatically transcribes and generates notes (full transcript + summary + key points + action items). Once generated, it appears in your notes list—just open it to view.

### 4. Upload existing audio/video

If you already have a recorded file, click the arrow on the right of **New note** and choose **Import file**. An upload dialog titled **Import Audio** pops up; select your file to upload.
![Import Audio upload dialog: drag-and-drop area + "Max 1GB per file" hint (the UI doesn't list specific formats; common audio/video formats are supported)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35882/9febfdad.png)

The dialog only shows a drag-and-drop upload area and a **"Max 1GB per file"** hint, with **no visible format list**—but it accepts common audio/video formats (M4A, MP3, MP4, AAC, WAV, OGG, Opus, FLAC, MOV, AVI, MKV, WebM, etc.). Just pick a file. **Maximum 1GB per file.**

After uploading, keep the page open to finish the upload; you'll be notified once transcription is complete.

### 5. Set the notes language (optional)

The transcript **always auto-detects the actual spoken language**. The language used to generate notes can be set separately: go to **Settings → AI Meeting Notes → Notes Language**.

- **Auto detect (default)**: The AI generates notes in the main language of the transcript—no configuration needed
- **Manually select a language**: No matter what language is spoken in the meeting, the notes are generated in the language you choose

## FAQ

**Why is generating notes from a recording so slow / why did it fail?**
The usual cause is an unstable network during upload or closing the page too early. We recommend ensuring a stable connection before uploading and keeping the page open until the progress passes 50%. If it has already failed, check your network and reopen AI Meeting Notes to trigger a re-upload; on the web, you can also click Resume on the recording entry to re-upload.

**No sound after recording on the web / empty transcript?**
This usually means the wrong microphone device was selected. Confirm you've picked the correct microphone before recording, and check whether the waveform moves once recording starts; if there's no waveform, stop recording, switch the microphone in your browser settings, and try again.

**Can I edit the transcript directly?**
The transcript can't be edited directly, but you can copy the full text with one click. The notes section is editable—see [Review & Edit](https://page.gensparksite.com/manual/buddy-guides/v1/en/meeting-notes-review-and-edit.md) for details.

**Can it handle meetings with mixed languages?**
Yes. The transcript captures each language line by line based on what's actually spoken, and the notes are then generated in the language you set.

## Next steps

- View, edit, ask follow-ups, and search after notes are generated → [Review & Edit](https://page.gensparksite.com/manual/buddy-guides/v1/en/meeting-notes-review-and-edit.md)
- Send notes to attendees or export → [Share & Export](https://page.gensparksite.com/manual/buddy-guides/v1/en/meeting-notes-share-and-export.md)
- Don't want to record manually? Let a Bot auto-join online meetings → [Meeting Bot & Calendar](https://page.gensparksite.com/manual/buddy-guides/v1/en/meeting-notes-bot-and-calendar.md)
