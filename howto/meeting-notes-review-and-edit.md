# AI Meeting Notes — Viewing & Editing

> For Buddy Agent internal use.
> type: howto | feature: meeting-notes | keywords: notes, transcript, transcript, summary, action items, speaker, rename, edit, Chat, Q&A, search, Notes, Transcript
> User loop: Open meeting detail → Read Notes/Transcript → Edit notes → Rename speakers → Ask AI follow-ups → Search to locate

## Why use Viewing & Editing

- **Grasp a whole meeting at a glance**: summary, key points, action items, and transcript are laid out in sections, so you don't have to replay the recording from the start.
- **Make it editable**: edit the notes yourself or have the AI edit them for you; speakers can be renamed to their real names, making the notes ready to use as-is.
- **Ask follow-ups**: ask the AI about meeting details directly instead of scrolling through the transcript yourself.

## Prerequisites

- Sign-in required
- Entry point: `https://www.genspark.ai/meetingnotes/home`, then open any generated note
- Viewing, editing, renaming speakers, and search are free; asking follow-ups (Chat) uses standard conversation credits

## Steps

### 1. Open the meeting detail

Click a meeting note in the home-page list, and it opens in a **new tab**: the AI chat for this meeting is on the left, and the notes panel is on the right.
![Meeting detail page overview (QA-annotated screenshot): opens in a new tab with the AI chat on the left and the notes panel on the right; **Export** / **Share** / ⋯ at the top; **Notes** / **Transcript** tabs (Transcript carries a red "New" badge; a Highlights tab appears only for notes jotted during recording)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/51140/d979ee7f.png)

The top of the notes panel shows the title and meeting date, with the content area below. A **Participants** section also appears there, but **only when the meeting has participant data** (typically meetings recorded by the Meeting Bot) — notes from imported files or local recordings without participants don't show this section.

### 2. Switch between Notes / Transcript

The notes panel has two tabs:
- **Notes**: AI-generated notes (summary, key points, action items)
- **Transcript**: the full transcript (the tab carries a red "New" badge)

If you wrote notes in the notes box while recording, an extra **Highlights** tab appears showing what you jotted down.

### 3. Edit the notes

Under the **Notes** tab, click anywhere in the notes area to edit directly.

You can also **have the AI edit for you**: select a passage in the notes, then describe the change in the chat on the left (rewrite, expand, fix speaker attribution, etc.), and the AI updates the notes panel directly.

> The editor itself has no undo button or version-history panel; however, when the **AI edits the notes via chat**, the previous version is preserved first, and you can ask the AI in chat to restore an earlier version. Before manual edits, copy a backup of anything important.

The Transcript **cannot be edited directly**, but you can copy the full text with one click.

### 4. Rename speakers

In the transcript, the AI automatically distinguishes different speakers (Speaker 1, Speaker 2…). Click a speaker name to change it to the real name.
![Transcript tab: ① in-transcript search box ② speaker name render area—click to rename in multi-speaker notes (with ✏️ Edit speaker name)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35882/896aa190.png)

### 5. Ask AI follow-ups (Chat)

Ask about this meeting in the chat on the left of the page. When you just ask questions, answers appear only in the chat stream and **do not overwrite** your original notes; the AI only changes the notes panel when you explicitly ask it to edit (and the previous version is preserved first — see step 3).

### 6. Search

- **Home search box**: search the title and summary across all meetings to quickly find a specific one
- **In-transcript search**: search a keyword within a transcript and jump to where it appears

### 7. Delete a note

On desktop, click the three-dot menu (⋯) on the right of a list item and choose **Delete**.

## FAQ

**Can I undo edits to my notes?**
There's no undo button in the editor. However, when the AI edits the notes via chat, the old version is preserved, and you can ask the AI in chat to restore an earlier version. Before manual edits, copy a backup of anything important.

**Will asking the AI follow-ups change my notes?**
Plain questions won't — answers only appear in the chat stream. The AI only changes the notes panel when you explicitly ask it to edit, and the previous version is preserved before any change.

**Why can't the transcript be edited directly?**
The transcript is preserved as a faithful record of what was said, so direct editing isn't available—but you can copy the full text with one click for other uses. Renaming speakers is supported.

**How do I delete a note on mobile?**
Swipe left on the item and choose Delete.

## Next steps

- Send the notes to participants or export → [Sharing & Exporting](https://page.gensparksite.com/manual/buddy-guides/v1/en/meeting-notes-share-and-export.md)
- Record another meeting or upload audio → [Recording & Importing](https://page.gensparksite.com/manual/buddy-guides/v1/en/meeting-notes-record-and-import.md)
