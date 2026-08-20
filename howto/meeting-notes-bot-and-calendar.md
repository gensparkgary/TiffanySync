# AI Meeting Notes — Meeting Bot & Calendar

> For Buddy Agent internal use.
> type: howto | feature: meeting-notes | keywords: Meeting Bot, Calendar, Connect Calendar, Google Calendar, Outlook, Auto-join, Zoom, Teams, Google Meet, Coming up, Auto-share
> User loop: Connect calendar → Turn on Auto-join or manually Join Meeting → Bot joins and records automatically → Notes generated automatically after the meeting

## Why use Meeting Bot

- **No manual work for online meetings**: Connect your calendar once, and the Bot automatically joins and records any scheduled meeting that has a meeting link — you don't even have to open the app.
- **Notes are ready the moment a meeting ends**: After recording, the Bot automatically transcribes and generates notes. Turn on Auto-share and it'll even email the notes to all attendees automatically.
- **See your schedule**: Once your calendar is connected, you can view your meetings for the next few days and tell at a glance which ones to take notes for.

## Prerequisites

- Sign-in required
- Entry point: `https://www.genspark.ai/meetingnotes/home`
- Turning on Auto-join / Auto-share requires connecting Google Calendar or Outlook; pasting a meeting link for the Bot to join does not require a calendar
- Meeting Bot recording consumes credits based on **actual recording time**; you'll be prompted to purchase more if your credits run low
- When joining automatically via the calendar, the Bot can only join meetings whose **calendar invite contains a meeting link**

## Steps

### 1. Connect your calendar

On the AI Meeting Notes home page, click **Connect calendar** and choose to connect **Google Calendar** or **Outlook**.

Once connected, the home page's **Coming up** section shows your public meetings for the next few days (roughly the coming week; private events aren't shown).

### 2. Turn on Auto-join

Click the settings button in the top-right corner, go to **Settings → AI Meeting Notes**, and in the **Meeting Bot** section turn on **Auto-join** (auto-join and record all meetings).
![Settings → AI Meeting Notes: ① Connect Calendar (Google / Outlook) ② Meeting Bot Auto-join ③ Auto-share (all require connecting a calendar first; grayed out until connected)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35882/61de4846.png)

Once on, the Bot will automatically join and record any calendar meeting where it detects a meeting link.

You can also change the **Bot name** (the name shown in the meeting room); the default is "Genspark Meeting Bot". Changing the Bot name **doesn't require a connected calendar** — the calendar is only a prerequisite for Auto-join (the Meeting Bot section reads "Connect your calendar to enable auto-join.").

### 3. Manually have the Bot join a specific meeting

If you don't want every meeting joined automatically, you can do it manually for a single meeting: in **Coming up**, click that meeting, then click **Join meeting**.

You can also paste a meeting link directly to have the Bot join: click the arrow on the right of the **New note** button at the top of the home page and choose **Add meeting URL**. In the **Add Meeting URL** dialog, paste the link (placeholder "Paste a meeting URL here"), then click the **+** on the right of the input box to recognize it — the platform name + link appear, along with a **Meeting Name (Optional)** field. Only then do the two buttons show up: have the Bot join right away (**Add Bot Now**) or enter a start time to schedule it (**Schedule**).

As the Bot joins, its status will progress through: Bot Joining → In Waiting Room → In Call → Recording → Processing.

**Supported meeting platforms**: Zoom, Google Meet, Microsoft Teams, Webex, and GoToMeeting.

### 4. Auto-share after the meeting (optional)

Go to **Settings → AI Meeting Notes**, and in the **Meeting Bot** section turn on **Auto-share** (Auto-share notes with other attendees). After a meeting ends, the notes will automatically be emailed to all attendees — no manual steps needed.

> **Prerequisite**: Just like Auto-join, the Auto-share toggle is **disabled (grayed out) until you connect a calendar** — you need to connect Google Calendar or Outlook first before you can turn it on.

## FAQ

**Why didn't the Bot join my meeting?**
Check each of these: Is your calendar connected (Google or Outlook)? Is Auto-join turned on in Settings? Does the calendar invite contain a meeting link (Zoom / Meet / Teams, etc.)? Does your account have enough credits? If everything checks out, try disconnecting and reconnecting your calendar.

**My "Coming up" meetings suddenly disappeared and the Bot stopped joining automatically — why?**
This usually means your calendar authorization has expired (Outlook access tokens in particular have a time limit). Go to AI Meeting Notes → Connect Calendar, disconnect the current calendar and reconnect it, and Coming up and auto-join will be restored.

**Does Bot recording cost anything?**
Yes — it consumes credits based on actual recording time. Refer to what's shown in the interface for specifics.

**Can I use the Bot for meetings without a meeting link?**
No. The Bot needs a meeting link to join — either from the calendar invite, or pasted manually via Add meeting URL. For in-person meetings, use [live recording](https://page.gensparksite.com/manual/buddy-guides/v1/en/meeting-notes-record-and-import.md).

## Next steps

- After the Bot finishes recording, view notes, ask follow-up questions, and edit speakers → [Review and edit](https://page.gensparksite.com/manual/buddy-guides/v1/en/meeting-notes-review-and-edit.md)
- Manually share or export notes → [Share and export](https://page.gensparksite.com/manual/buddy-guides/v1/en/meeting-notes-share-and-export.md)
