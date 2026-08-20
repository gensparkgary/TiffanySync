# Email Brain: What the AI Learned From Your Inbox

> For Buddy Agent internal use.
> type: concept | feature: genmail-email-brain | keywords: Email Brain, inbox profile, SENSITIVE, Fix, Forget, recent updates, daily refresh, Super Agent
> User loop: Understand what Email Brain is → know what facts it has learned → know how to view/fix/forget → understand its relationship with Super Agent → know this is a gradually rolling-out feature

> **Rolling out gradually**: Email Brain is being rolled out gradually and only appears once it's enabled for your account. If **Email Brain** shows up on the left Nav Rail and you can open its contents, your account has it enabled. Go by what actually appears in the app; not seeing it doesn't mean the feature is missing—your account just hasn't been reached yet.

## Why understand Email Brain

- **Know what the AI is basing its help on**: When GenMail drafts a reply for you, curates "On Your Radar," or runs a task, its judgment doesn't come out of nowhere—it's based on facts it read from your inbox. Understanding Email Brain lets you see what that help is grounded in and how much to trust it.
- **You calibrate the results**: If the AI got something wrong (e.g., treating an outdated title or an old address as current), you can correct it directly or make it forget—and the next draft or roundup will use the corrected version. You don't have to re-explain who you are every time.
- **See the boundaries**: What gets flagged as sensitive, what can be deleted, how often information refreshes—knowing this makes clear exactly what the AI has after you hand it your inbox.

## What is Email Brain

Email Brain is an **inbox profile** that GenMail builds for you: the AI reads the correspondence in your connected mailbox, distills **fact cards** about you and the people and matters you deal with regularly, and lists them all in one place.

Think of it as a notebook the AI keeps "about me," with contents such as:

- Your identity and everyday context—your role, frequent collaborators, and the projects and topics you care about
- Key contacts—who reaches out to you often and what you're working on together
- Recurring matters—patterns like regular bills, subscriptions, or fixed itineraries

You don't fill these facts in by hand—the AI **summarizes them automatically** from your email. Their purpose is to give GenMail something to work from when it acts on your behalf—drafting replies, deciding which email is "On Your Radar," running tasks in Super Agent—so it doesn't have to ask again "Who are you, and what's the background here?"

## The SENSITIVE flag

Some facts may be flagged **SENSITIVE**—this kind of information typically involves personal privacy or security (such as identity, finances, or health), and the AI flags it separately when it recognizes it as more private. Whether this flag appears depends on whether your inbox contains facts judged to be sensitive; **go by what actually appears in the interface**.

When you see the SENSITIVE flag, you can decide: keep it (so the AI keeps referencing it when acting for you) or make it forget (see Forget below). This gives you a clear checkpoint—private information you don't want the AI to remember, you can clear out yourself.

## Fix and Forget

You have the final say over the facts Email Brain learns. The interface lets you do two kinds of actions on learned facts (the exact entry points **depend on what actually appears in the interface**, and may only show up when you click into or hover over a fact):

| Action | What it does | When to use it |
|------|---------|-----------|
| **Fix** | Change the fact to the correct content | The AI got it wrong or the info is outdated (e.g., an old title, a former address, a finished project) |
| **Forget** | Make the AI delete this fact and stop referencing it | This shouldn't have been remembered, or it's private information you don't want the AI to use |

After you fix or forget something, GenMail will use the updated profile the next time it drafts, curates, or runs tasks for you—correct it once and it shapes all its later judgments, no need to keep explaining.

> Forget makes the AI stop referencing a fact—it targets the AI's memory and **won't delete any email in your inbox**. Your original emails stay untouched.

## Recent updates and daily refresh

Email Brain isn't built once and then frozen—it **keeps updating as new email arrives**:

- **Recent updates**: The interface lists facts recently added or changed, so you can see at a glance what the AI has just learned or modified, without paging through the whole profile.
- **Daily refresh**: The AI periodically (roughly daily) re-reads your recent email, adding new facts and updating old ones that have changed. So the profile you see today is usually closer to your current situation than it was last week.

The refresh happens automatically—you don't need to trigger it manually. If a refresh brings in an incorrect fact, you can still correct it on the spot with Fix / Forget.

## How Email Brain relates to Super Agent

Email Brain is "what the AI knows about you," and Super Agent is "the AI doing things for you"—the former is the **underlying basis** for the latter.

- When you tell Super Agent "reply to this email for me," it can write like you and grasp the background precisely because Email Brain supplies your identity, relationships, and past matters.
- When "On Your Radar" surfaces the few emails that matter, it too draws on Email Brain's understanding of "what's important to you."

So the two work together: **the more accurate Email Brain is, the more Super Agent's work fits you**. When you use Fix / Forget to correct the profile, you're really tuning everything Super Agent does afterward.

> Both of these features are currently rolling out gradually and need to be enabled for your account. Whether they're available, and their exact form, depends on what actually appears in the app.

## FAQ

**Do I fill in the facts in Email Brain manually?**
No. The AI automatically distills them from the correspondence in your connected mailbox. You don't need to enter anything—just use Fix when it gets something wrong and Forget when it shouldn't be remembering something.

**Will using Forget on a fact delete my email?**
No. Forget only clears that distilled fact so the AI no longer references it; the original emails in your inbox are completely unaffected.

**Why are some facts flagged SENSITIVE?**
Because the AI recognizes them as more private (involving personal, financial, health matters, etc.). The flag simply signals "this is sensitive information it recorded"—you decide whether to keep it, and can Forget it anytime.

**I don't see Email Brain in the Nav Rail—what's going on?**
Email Brain is rolling out gradually and only appears once it's enabled for your account. Not seeing it means your account hasn't been reached yet—go by what actually appears in the app.

**After I fix a fact, will the AI act on the new content right away?**
Yes. Once Fix / Forget takes effect, GenMail will use the updated profile the next time it drafts, curates, or runs tasks for you—you won't have to explain it again.

## Next steps

- [Super Agent: run tasks using email as context →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-super-agent.md)
- [GenMail overview: your inbox now has a brain →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-overview.md)
- [Install and sign in: download, sign in, connect your mailbox →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-get-started.md)
