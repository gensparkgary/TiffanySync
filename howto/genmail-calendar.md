# Calendar: View your schedule, join meetings, RSVP, and let AI handle scheduling

> For Buddy Agent internal use.
> type: howto | feature: genmail-calendar | keywords: calendar, Calendar, week view, multiple calendars, Meet, Teams, Zoom, RSVP, invitations, AI scheduling, Manage with AI
> User loop: Open Calendar → See this week's schedule → Click an event detail card → One-click join / RSVP → Handle with AI or auto-schedule

## Why use Calendar

- **See everything in one place**: Calendars from multiple Gmail and Outlook accounts are layered onto a single week view, so you don't have to bounce between your inbox, calendar, and meeting links—when you're busy, who you're meeting with, and where to join are all clear at a glance.
- **Just one step from "seeing a meeting" to "joining it"**: If an event includes a Google Meet / Teams / Zoom link, one click takes you in—no more digging through emails for a meeting number. For meeting invitations you receive, you can accept or decline right there, and the sender gets your response instantly.
- **No need to figure out timing yourself**: Hand off chores like "book me 30 minutes with so-and-so" to AI—it reads your open slots, their invitation, and the email thread, and schedules the meeting at the right time for you.

## Prerequisites

- Entry: Calendar isn't a URL. First finish installing and signing in to GenMail—download and install the desktop client → launch it → sign in with your Genspark account (this opens your system browser to complete) → connect your Gmail / Outlook mailbox for the first time. Once done, click **Calendar** in the left nav rail to enter the calendar workspace.
- Your calendar follows the mailbox accounts you connect: connect a mailbox, and you'll see the calendar under that mailbox. **Both connecting and calendar authorization are done in Settings → Mail Accounts.** If you haven't authorized a calendar for any mailbox yet, the calendar area shows a "Connect a calendar" prompt—follow it to Settings and click **Authorize calendar** for the account.
- Viewing your schedule, joining meetings, and RSVP are all free; credits are only used when you have AI handle something or auto-schedule for you.

## Steps

### 1. Open Calendar and see this week's schedule

Click **Calendar** in the left nav rail. Calendar offers a **week view**: at the top you can page back and forth between weeks and jump to **Today** in one click, so you can clearly see what's happening at each hour of every day this week and where your open slots are. The mini month calendar on the left is a **date picker**—click any date to jump quickly to that week.

![GenMail Calendar (week view): ① New event · ② Today plus week paging · ③ the week grid; shows a "Connect a calendar" prompt when no calendar is connected](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/39202/79274ffb.png)

### 2. Layer multiple calendars into one view

If you've connected multiple mailboxes (say one Gmail and one Outlook), their calendars are **layered onto the same view**, with different sources distinguished by color.
To add a new calendar source, go to **Settings → Mail Accounts**: add the mailbox account there and authorize calendar access for it. Once authorized, it stays valid long-term, and the calendar updates automatically.

### 3. Open an event to see the details

Click any event in the view to pop up its **event detail card**, which shows the title, time, location, participants, and (if present) the meeting link and your RSVP status.

### 4. Join an online meeting in one click

If the event carries a **Google Meet, Microsoft Teams, or Zoom** meeting link, a join button appears on the event card—one click takes you straight into the meeting, no need to go back to your email to find the meeting number or link.

### 5. Respond to a meeting invitation (RSVP)

For a meeting someone else initiated, the event card has **RSVP** options: **Accept / Tentative / Decline**. Pick one, and your response syncs back to the organizer so they can see whether you're coming.

### 6. Edit or delete your own events

For events you created and have permission to change, the event card lets you **edit** (change the title, time, etc.) or **delete**. Changes sync back to the corresponding mailbox calendar.

### 7. Handle meeting invitations directly in your email

Many meetings arrive in your inbox as emails first. When an email contains a meeting invitation, GenMail shows a **calendar invitation card** inside the email, and you can **RSVP right there—Accept / Tentative / Decline—without jumping to the calendar first**. Your response still syncs to the organizer.

### 8. Handle an event with AI (Manage with AI)

The event card has a **Manage with AI** entry. Open it and use natural language to have AI act on the event for you—for example, "move this meeting to tomorrow afternoon," "send everyone a delay notice," or "put together pre-meeting talking points based on the email thread." This step calls AI and **uses credits**.

### 9. Let AI auto-schedule meetings (rolling out)

GenMail can also let AI **auto-schedule**: just say "book me 30 minutes with so-and-so next week," and AI reads your open slots, their availability, and the relevant emails, then schedules the meeting at a suitable time and sends the invitation.
This feature is **rolling out gradually and needs to be enabled for your account**—whether it's available depends on what the UI actually shows. It calls AI and **uses credits**.

## FAQ

**Q: Why is my calendar empty / why can't I see events from a certain mailbox?**
Your calendar follows the mailbox accounts you've connected and authorized. Go to Settings → Mail Accounts and confirm the mailbox has been added and that you've **authorized calendar access** for it. Once authorized, it stays updated long-term.

**Q: How do I view a different week / jump to a specific day?**
At the top you can page back and forth between weeks and jump to **Today** in one click; to jump straight to a specific day, click that date in the mini month calendar on the left and it switches to that week.

**Q: If I click "Accept" in an email, will the meeting automatically show up in my calendar?**
Yes. The calendar invitation card in the email and the calendar view share the same data—after you RSVP in the email, the event status syncs to the calendar, and the organizer can see your response too.

**Q: What if the join button doesn't appear?**
The join button only shows when the event itself carries an online meeting link like Meet / Teams / Zoom. In-person-only meetings or events without an attached meeting link won't have this button.

**Q: I don't see the AI auto-scheduling entry on my end?**
This feature is rolling out gradually and needs to be enabled for your account, subject to what the UI actually shows. Until it's available, you can still use **Manage with AI** on the event card to manually have AI change the time or send notices for you.

## Next steps

- [Handle emails and tasks with AI: Super Agent →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-super-agent.md)
- [Compose, reply, and forward emails →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-compose-and-reply.md)
- [Read and manage emails →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-read-and-manage.md)
- [GenMail overview: your inbox now has a brain →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-overview.md)
