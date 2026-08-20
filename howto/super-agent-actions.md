# Super Agent — Real-World Actions: Make Calls / Send Emails / Save Files

> For Buddy Agent internal use.
> type: howto | feature: super-agent | keywords: make a call, Call For Me, send email, Gmail, Outlook, AI Drive, save file
> User loop: Give a real-world action command in chat → complete the first-time connection/verification → AI makes the call / sends the email / saves the file for you

## Why use it

Super Agent doesn't just produce content — it can actually **do things** for you: make a reservation call, send an email, or save generated files to your drive. You can trigger these actions right in the conversation.

## Make a call (Call For Me)

### 1. Tell it what call you want to make in the conversation

> "Call Sunset Bistro for me to book a table for 6 this Friday at 7:30 PM"

Super Agent will usually pop up a few rounds of clarification cards first (to confirm details, party size, time, and the matched restaurant), then invoke the calling tool to start an AI Call For Me.

### 2. First-time use requires completing call setup

The first time you use the calling feature, you need to complete **3 items** in call settings before you can dial: set your caller ID display name (set name), **verify phone number**, and choose an AI voice. If these aren't done, you'll be stopped and prompted to go to settings; the settings entry is `/agents?type=phone_call` — just follow the prompts to fill everything in.

### 3. View the call results

Once setup is complete, the AI makes the call, and afterward returns the call record and a results summary.

**You can also schedule a call**:
> "Schedule a call to [number] tomorrow at 3 PM to confirm the meeting time"

**Credit**: Making calls consumes credits, billed by call duration — this is a heavier operation and costs noticeably more than a typical conversation.

![Call For Me: clarification card (Maps restaurant match)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35640/055dd7c7.png)

![Call For Me: the calling tool requires verifying your phone number first](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35640/518b06b0.png)

## Send emails

### 1. Connect Gmail or Outlook

The first time you send an email, if you haven't connected a mailbox yet, the system will pop up an OAuth authorization prompt ("Authorization Required: Gmail → Authorize Now"). Follow the prompts to complete Gmail or Outlook authorization (which stays valid long-term after a one-time grant).

### 2. Describe the email content

> "Send an email to marketing@company.com to set up a time to discuss the New Year marketing plan"

The AI will draft the email and let you confirm before sending (you can also choose to generate just the draft text without actually sending).

![Send email: Gmail OAuth authorization prompt (blocks when not connected)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35640/0a9c52e0.png)

## Save files to AI Drive

In the conversation, have Super Agent save generated or downloaded files to your AI Drive:

> "Search for and download 10 research papers on solar technology, and save them to my AI Drive"

Once files are saved to AI Drive, they can be reused in other Agents or in the Hub, and you'll also see them under Recent Files in the AI Drive interface.

![AI Drive: saved files appear in Recent Files](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35640/27974364.png)

## FAQ

**How do I get it to make a call for me?**
Just say what call you want to make in the conversation, and it will run through a few rounds of clarification cards to confirm the details. First-time use requires completing call setup (set name / verify phone number / choose AI voice). Calls consume credits based on call duration and are a heavier operation.

**How do I connect my mailbox?**
Say "send an email for me" in the conversation and follow the prompts to complete Gmail/Outlook authorization. Authorization stays valid long-term after a one-time grant.

**Will it ask me to confirm before sending an email?**
Yes. The AI drafts the email, and you confirm before it sends.

**Can files saved to AI Drive be used elsewhere?**
Yes. Files in AI Drive can be referenced in other Agents or in the Hub.

## Next steps

- [Hub workspace](https://page.gensparksite.com/manual/buddy-guides/v1/en/hub-overview.md) — put frequently used files in the Hub for long-term reuse
- [Product overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/super-agent-overview.md)
