# GenMail — Search Emails and Contacts

> For Buddy Agent internal use.
> type: howto | feature: genmail-search | keywords: search, Search, keyword, subject, sender, body, contacts, local cache, compose, natural language search, Find it for me, Super Agent
> User loop: Open search → type a keyword to match subject/sender/body in real time → locate the email/contact in the results → write to a contact in one click, or hand a complex question to Super Agent's Find it for me

## Why use search

- **Dig up that email from months ago in seconds**: What you usually remember isn't the exact subject line—it's the sender's name, or a phrase from the body. Search matches across subject, sender, and body all at once, narrowing results as you type, so you never have to scroll page after page.
- **Look up old emails even offline**: Your frequently used emails are cached on your computer. Search checks locally first, then fills in cloud results once you're online—so results appear instantly, and you can still browse old emails on a plane or subway with no connection.
- **Find someone and act right away**: Searching contacts isn't just about "finding this person"—one click in the results takes you straight to composing, with no need to copy the email address, create a new message, then paste.
- **Let the agent find what you can't describe**: When a question can't be summed up in a single keyword (e.g., "which supplier sent the lowest quote last month"), open Super Agent, choose the **Find it for me** skill, and let the AI read your emails and give you the answer.

Search itself is **free**—typing a keyword, browsing results, and writing to a contact all cost no credits. Credits are only used when you hand a question to the agent to read, analyze, and respond.

## Prerequisites

- Entry: Search is used inside the GenMail desktop client. First download, install, and launch GenMail, sign in with your Genspark account (this opens your system browser to complete), and connect at least one mailbox (Gmail or Outlook). For install and connect steps, see [Install and Sign In](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-get-started.md).
- Once you're in the **Mail** workspace, use the search entry at the top.
- To use natural-language "Find it for me," your account needs Super Agent enabled—this capability is rolling out gradually and must be enabled for your account, so go by what actually appears in the UI.

## Steps

### 1. Open search

In the left Nav Rail, select the **Mail** workspace and click the search box above the list.

![GenMail top search box: ① type a keyword to instantly match an email's subject / sender / body, and show contact results](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/39204/82345867.png)

### 2. Type a keyword

Just type whatever clue you remember—a word from the subject, the sender's name or email, or a phrase from the body. The system matches across subject, sender, and body at the same time, narrowing results as you type.

Because your frequently used emails are already cached on your computer, results **come from local first**—so you can find these emails even with no connection right now; once you're online, earlier cloud results are filled in.

### 3. Find a contact, write in one click

Search matches not only emails but also **contacts**. Results are split into "Email matches" and "Contacts"—when a person shows up in the results, you can click straight from the contact result to **compose**, which automatically fills that person into the recipient field so you can just write your message, without first copying the email address and creating a new message.

For the full workflow of composing and replying (rich text, attachments, signatures, Schedule send, etc.), see [Compose, Reply, and Forward](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-compose-and-reply.md).

### 4. Hand what you can't describe to "Find it for me"

If your question can't be summed up in a single keyword—like "which email last week mentioned I need to confirm by Friday" or "add up the amounts across all this month's invoices"—these questions require **reading and understanding multiple emails**, which keyword search can't answer. In that case, open **Super Agent** in the left Nav Rail and choose the **Find it for me** skill: it reads the relevant emails for you, synthesizes them, and tells you the answer, instead of just dumping a list of emails for you to read yourself.

> Find it for me has the agent actually read your emails and respond, so it **uses credits**; ordinary keyword search is always free.

## FAQ

**Q: Does search cost credits?**
Ordinary search—typing keywords, browsing results, and writing to a contact—is all **free**. Credits are only used when you hand a question to Super Agent's Find it for me and let the AI read, synthesize, and respond for you.

**Q: Can I search offline?**
You can search emails already cached on your computer—frequently used emails return local results first, so you can find them even offline. Earlier, not-yet-cached cloud emails are only filled in once you're online.

**Q: My keyword didn't match, but I'm sure this email exists?**
First try loosening it up—drop overly specific words and keep just the sender's name or a word or two from the body. If what you remember is the "gist" rather than the exact wording, just use Find it for me to describe it in a sentence and let the agent figure out which one you're looking for.

**Q: What content does search match?**
Keywords match across an email's subject, sender, and body at the same time, and matched terms are highlighted in the results. Beyond emails, search also lists matching contacts separately, so you can write to them directly.

## Next steps

- [Compose, Reply, and Forward →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-compose-and-reply.md)
- [Read and Manage Emails →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-read-and-manage.md)
- [Super Agent: Run tasks with email as context →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-super-agent.md)
- [GenMail Overview: Your inbox now has a brain →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-overview.md)
