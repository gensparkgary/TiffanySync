# Second Brain — Product Overview

> For Buddy Agent internal use.
> type: concept | feature: secondbrain | keywords: Second Brain, personal memory, data sources, connectors, memory cards, Memory Map, privacy, credit, Super Agent, Telegram
> Entry: https://www.genspark.ai/second-brain/home; also accessible from the global left sidebar "Second Brain" (with a New badge) 

## What Second Brain Is

Second Brain is Genspark's **personal memory system**: connect your email, meeting notes, Notion, calendar, Genspark project history, and more, and the system builds "your memory" from them. After that, ask it anything here and it answers across all your data sources; you can also write notes and manage documents directly. 

It's not a single chat stream but a **multi-surface workspace**: Home (ask + document grid), Chat, the document editor, the data source center, Memory Map, and Quick Notes each serve their own purpose. 

## What Your Memory Is

Your memory isn't a black box — it's something you can see and edit: 

- **Memory document**: a profile document about you, with the UI explicitly stating "You can edit what it knows, anytime" — everything it remembers is editable at any time 
- **Memory cards**: key-information cards automatically saved during chats, likewise stored in your documents and editable 
- **Memory Map**: draws your files as a graph — nodes are files, links are the connections between them; click a node to open the file directly. Viewing the map is free 

## Data Sources: Two Groups, Two Meanings

The data source center splits all sources into two groups with completely different semantics (for connecting each one, see [Connect Data Sources](https://page.gensparksite.com/manual/buddy-guides/v1/en/secondbrain-connect-sources.md)): 

| Group | UI description | Meaning | Members |
|---|---|---|---|
| In your brain | "Imported and always searchable" | **Imported into your brain**: content is copied into your memory and searchable anytime | Meeting Notes, Genspark project history, Gmail, Outlook (imports the last 6 months, up to 6,000 emails, then auto-incrementally syncs at intervals)  |
| Connectors | "Read live, only when you ask" | **Connected but not imported**: nothing is copied; read live only when you ask | Notion, Microsoft Teams, GitHub, Google Drive, Slack, Salesforce, Google Docs, Google Sheets, HubSpot, Google Calendar, Outlook Calendar — 11 in total  |

There's also **Import files** for manual imports: ZIP/Markdown/CSV/HTML/PDF, 500 MB (the Import files panel copy may still show an older number — the enforced limit governs) per upload.  

## Privacy: The Four Cases of Disconnecting and Deleting

What happens "when you disconnect a data source" depends on which group it belongs to — all four cases have been verified on the backend: 

1. **Disconnecting a Connector (connected but not imported)**: deletes nothing — it never imported any content in the first place 
2. **Turning off Meeting Notes / Genspark project history**: disabled but **data retained**; turn it back on to restore 
3. **"Remove" on Gmail / Outlook**: **deletes the imported email copies** (revokes authorization and clears stored copies) 
4. **Cross-product cascade disconnect** (e.g., disconnecting Google Docs also disconnects Gmail): no data is deleted; reconnect to keep using it 

Note: the data source sidebar doesn't offer a "delete imported content" entry; documents you create yourself can be deleted, and deletion is irreversible (per the confirmation dialog). Sharing is a per-file public read-only link ("Anyone with the link (Viewer)"), which you can turn off and revoke at any time. 

## Credits: One Rule Covers Everything

**Only asking (Ask / Chat) consumes credits based on usage, and the tier affects consumption; everything else is free.** 

- Free: opening any page, Memory Map, version history, sharing, importing files, connectors and email sync, writing notes, and editing documents 
- The Memory-building onboarding some users see on first entry is also **free** (the system covers it), and it can be skipped 
- Ask tiers: **Standard** (default, for quick everyday questions) / **Ultra** (deeper reasoning, consumes noticeably more credits, with a confirmation dialog the first time you switch) 
- Asking it to do bigger jobs in chat — like making slides or writing long documents — is billed separately by the corresponding product and consumes more 

## Super Agent Works With Your Memory

Once Second Brain is connected, Super Agent brings your personal memory along when it starts working — giving answers that understand you better and taking more personalized actions. This injection **can be turned off** (the personal memory toggle in memory settings); organization collaboration projects are isolated by default and don't inject personal memory. 

## Don't Confuse It With These Two Products

- **SecondBrain Note**: a hardware voice recorder sold on shop.genspark.ai — just one optional input channel for feeding offline conversations into your memory. You don't need this device at all to use Second Brain 
- **Team Brain**: an organization-level knowledge base serving "the whole team's knowledge"; Second Brain serves "your personal memory" 

## Desktop First

Second Brain is designed for **desktop browsers**; there's no mobile app. The official lightweight mobile entry is Telegram quick notes (message the bot and it lands in your notes), see [Quick Notes](https://page.gensparksite.com/manual/buddy-guides/v1/en/secondbrain-quick-notes.md). 

## Quick Guide by Scenario

| What you want to do | Read this |
|-----------|--------|
| Entering for the first time and asking your first question | [secondbrain-get-started](https://page.gensparksite.com/manual/buddy-guides/v1/en/secondbrain-get-started.md) |
| Asking questions, choosing a tier, understanding outputs | [secondbrain-ask-and-chat](https://page.gensparksite.com/manual/buddy-guides/v1/en/secondbrain-ask-and-chat.md) |
| Connecting email/meetings/various apps, importing files | [secondbrain-connect-sources](https://page.gensparksite.com/manual/buddy-guides/v1/en/secondbrain-connect-sources.md) |
| Using Telegram quick notes | [secondbrain-quick-notes](https://page.gensparksite.com/manual/buddy-guides/v1/en/secondbrain-quick-notes.md) |
| Writing notes, managing documents, sharing | [secondbrain-notes-and-files](https://page.gensparksite.com/manual/buddy-guides/v1/en/secondbrain-notes-and-files.md) |

## FAQ

**Q: Does Second Brain cost extra?**
No. Browsing, writing notes, connecting data sources, and viewing the map are all free; only asking questions consumes credits based on usage (the tier affects consumption), and the Memory-building onboarding some users see on first entry is also free. 

**Q: Is my data safe? Can others see my memory?**
Only you can access your Second Brain data; all data sources require your explicit authorization and can be disconnected anytime (see the four cases above for what disconnecting means). Only when you actively enable a per-file share link can someone with the link view that single file — **read-only**. 

**Q: Can I use it on my phone?**
It's designed for desktop browsers; on your phone, Telegram quick notes is the smoothest way to jot things into it — see [Quick Notes](https://page.gensparksite.com/manual/buddy-guides/v1/en/secondbrain-quick-notes.md). 

**Q: Do I need to buy the SecondBrain Note recorder?**
No. The software works fully on its own; the hardware is just an optional offline audio input channel. 
