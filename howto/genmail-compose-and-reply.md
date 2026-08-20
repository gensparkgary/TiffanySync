# GenMail — Compose, Reply & Forward: Editor, Attachments, Signatures, Schedule Send

> For Buddy Agent internal use.
> type: howto | feature: genmail | keywords: compose, writing emails, reply, reply all, forward, drafts, rich text, attachments, inline images, recipients, Cc, Bcc, contact autocomplete, signature, Signature, schedule send, Schedule send
> User loop: Open GenMail → New/Reply/Forward → Fill in recipients, write body, add attachments → Choose signature → Send now or schedule send → Confirm in Sent/Drafts

## Why read this first

- **Write a complete, polished email without ever leaving GenMail**: from filling in recipients and formatting the body to attaching files and adding a signature—it all happens in one interface. And if your connection drops mid-write, nothing is lost: drafts are saved for you, and unsent emails wait in line until you're back online.
- **Replies and forwards keep their context**: the original message and recipients are pulled in with one click. Who to reply to and who to Cc are already filled in—you just add the line that needs adding.
- **Composing, replying, and forwarding themselves cost no credits.** Credits are only consumed when you have AI draft, rewrite, or reply for you—see [AI Compose & AI Reply](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-ai-write.md) for that.

## Prerequisites

- Entry: GenMail is a **desktop client you download and install**. Download and install → launch → sign in with your Genspark account (this opens your system browser to complete) → (first time) connect your Gmail / Outlook mailbox → once you reach the app's main interface, you can compose and send emails. For installation and connection steps, see [Get Started](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-get-started.md).
- At least one connected mailbox account (this determines which address you send from).
- Sending, replying, forwarding, and saving drafts are all **free**.

## Steps

### 1. Open the compose window

From the **Mail** workspace in the left navigation, open the email list, then click the **compose button** (new email icon) in the interface to open a blank compose window.

![GenMail compose window: ① Send / Schedule send (▾ contains schedule send) · ② To / Cc / Bcc recipients · ③ rich text toolbar](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/39193/9f153d98.png)

There are five ways to start composing—pick the one that matches your intent:

| What you want to do | How to get there | What the system pulls in for you |
|------------|----------|------------------|
| **New** email from scratch | Click the compose button | Blank—fill in everything yourself |
| **Reply** to the sender | Click Reply on an email | Recipient = original sender, subject prefixed with Re:, original message quoted below |
| **Reply All** | Click Reply All on an email | Recipients = original sender + everyone originally Cc'd |
| **Forward** to someone else | Click Forward on an email | Original message + original attachments carried over, recipient left blank for you to fill |
| **Continue a draft** | Open it from Drafts | Exactly where you left off, as it was saved |

### 2. Fill in recipients To / Cc / Bcc

Type the person's name or email address in the recipient field. GenMail **autocompletes** from your contacts—as you type, it offers candidates; click one to fill it in, so you don't have to remember the full address.

When you need to Cc or Bcc, expand the **Cc** (carbon copy, visible to everyone) and **Bcc** (blind carbon copy, recipients can't see each other) fields to fill them in separately.

### 3. Write the subject and body (rich text editor)

Fill in the subject, then format the body in the **rich text editor**: bold, italic, lists, links, font size and color, and more can all be set directly—what you write is exactly what the recipient sees.

### 4. Add attachments and inline images

Click the attachment button to select files, and they'll be sent along with the email. You can also place images directly in the body (rather than as attachments)—for example, paste or drag an image into the body, and the recipient will see this **inline image** right in the message.

### 5. Choose a signature

If you've set up a **Signature**, you can use it while composing. Signatures can be set **per account** (different mailboxes use different sign-offs), or you can set one **global** signature for everything. The compose window toolbar has a **Select signature** entry—click it to insert an existing signature into the body.

To have a signature **automatically added** to the end of the body when composing a new email, you first need to **set that signature as the account's default signature** in settings; otherwise, you can manually pick it from **Select signature** in the toolbar while composing.

First time using it and don't want to type out your signature? GenMail lets you **import** the signature you already have in **Gmail / Outlook** directly, saving you from rebuilding it. Creating, importing, and assigning signatures per account is done in settings—see [Settings & Account Management](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-settings-and-accounts.md) for details.

### 6. Drafts save automatically—nothing lost even offline

No need to save manually mid-write—GenMail **auto-saves drafts**. Step away to handle something else, or even close the window, and you can pick right back up in Drafts. Drafts you truly don't want can simply be **discarded**.

If you happen to be **offline** when you send, the email won't be lost or stuck with an error—it's marked as **pending (queued)** and **sent automatically** once your connection is back, no need to resend. (Pending is a send status of that email, not a separate Outbox folder.)

### 7. Send now, or schedule send

When you're done, click **Send** to send immediately.

If you want the email to go out at **some future time** (say you finish it late at night but want it to land in their inbox at 9 AM), use **Schedule send**: choose a send time, and the email will go out automatically when the time comes.

> **Schedule send is rolling out gradually** and only appears once it's enabled for your account. **Go by what your interface actually shows**—if you don't see the schedule send option, just click Send to send immediately.

## FAQ

**Q: What's the difference between Reply and Reply All, and which should I use?**
Reply sends only to the original sender; Reply All sends to the original sender plus everyone who was originally Cc'd. If you just want to respond privately to the sender, use Reply; only use Reply All when you need the whole discussion group to see it.

**Q: Will the original attachments come along when I forward?**
Yes. Forward carries over both the original email's body and its attachments, leaving the recipient field blank for you to fill in who to forward to.

**Q: My computer died and shut down mid-write—is my content still there?**
Yes. GenMail auto-saves drafts, and after reopening you'll find it in Drafts to continue writing.

**Q: I clicked Send while offline—where did my email go?**
It's marked as pending (queued) and won't be lost; it's sent automatically once your connection returns, with nothing for you to do. This is a send status of the email, not a separate Outbox folder, so there's no Outbox to go looking for.

**Q: I have two mailboxes—can each use a different sign-off?**
Yes. Signatures can be set per account, so different mailboxes use different sign-offs; you can also set one global signature for everything. Once you set a signature as an account's default, composing a new email from that mailbox adds it automatically; otherwise, you can manually pick it from "Select signature" in the toolbar while composing. See "Next steps" below for how to set this up.

**Q: Do writing emails, adding attachments, or scheduling send cost credits?**
No. Composing, replying, forwarding, adding attachments, saving drafts, and scheduling send are all free themselves. Credits are only consumed when you have AI draft or rewrite the body for you.

## Next steps

- [Have AI write emails for you (AI Compose & AI Reply) →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-ai-write.md)
- [Reading & managing emails: list, conversations, organizing actions →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-read-and-manage.md)
- [Settings & Account Management: accounts, signatures, AI preferences, shortcuts →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-settings-and-accounts.md)
- [What is GenMail →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-overview.md)
