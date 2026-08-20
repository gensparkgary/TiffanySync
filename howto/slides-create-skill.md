# AI Slides — Create and Manage Skills

> For Buddy Agent internal use.
> type: howto | feature: ai-slides | keywords: Create Skill, Save as Skill, New Skill, Skill package, custom, Share, Team Skills
> User loop: Have a great deck → Save as Skill / create a New Skill in the Skill Gallery (3 paths) → share it with others or publish to your organization → reuse it next time via the Skill Gallery

## Prerequisites

- Logged in
- Entry point: the Skill Gallery on the `/ai_slides` creation page

## Why create your own Skill

- **Brand consistency**: Does your company have a unified PPT style? Upload it once, and from then on everyone generates with the same Skill — no more style drift
- **Double the efficiency**: Producing weekly or monthly reports? A Skill saves the complete blueprint, so you just feed in new data to get a new deck
- **Team sharing**: One person creates it, the whole team reuses it. Even newcomers can produce decks at a "veteran level"
- **More powerful than a prompt**: A Skill contains structure definitions + style guidelines + content guidance, conveying far more than a single prompt ever could

## Two entry points for creating a Skill

### Entry 1: Save as Skill

In the Slides workspace, click the **⋮ menu at the top right → Save as Skill**. The Agent launches a multi-turn interactive flow: it first reflects on the current deck's structure and style, then asks 2-3 confirmation questions (such as the Skill name, applicable scenarios, etc.), and creates the Skill once confirmed.

Best for: you've just finished a great deck and want to keep it as a reusable blueprint.

### Entry 2: New Skill (manual creation)

On the `/ai_slides` creation page, find the **"New Skill"** card in the Skill Gallery — it's visible right on the default **All** tab (and under **My Skills** too).

![The New Skill card on the default All tab](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/51105/ae556edf.png)

## Three creation paths

The three paths are laid out inline on the New Skill card itself — each with its own button (Upload / Upload / Create); there is no intermediate dialog:

### 1. Save my presentation as a template

Save an existing presentation as a Skill template. The card reads **"Upload a PowerPoint or PDF to get started"** — click its **Upload** button and pick your file. The upload dialog accepts `.pptx` / `.pdf` files **up to 100 MB**, and the Agent automatically extracts the layout and styles to generate a Skill.

Best for: you already have a well-designed PowerPoint or PDF file.

![Path 1: Save my presentation as a template (upload a PowerPoint or PDF)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36195/374e8509.png)

### 2. I already have a skill package

Import a Skill package (`.zip` file) that someone has already bundled. This is a full Skill package import, not an analysis of multiple decks.

Best for: you received a Skill package shared by a colleague or the community and want to import it directly.

### 3. I'm starting from scratch

Click its **Create** button to open the **"Custom new skill"** dialog: describe the Skill structure and style you want, and the Agent creates the Skill based on your description. The dialog now also includes a file-attachment area (**"Click or drag files here"**) — you can optionally attach reference files (Word / PDF / PPT / Excel / images) alongside your description.

Best for: you have a clear blueprint in mind but no existing file.

![Path 3: Create a Skill from scratch (Custom new skill dialog, with optional file attachments)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/51105/0f15166d.png)

![The three inline New Skill paths (Upload / Upload / Create)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/51105/41fabb15.png)

## Fill in the Skill details

After choosing a path, upload your file or describe your requirements according to that path. The Agent will guide you through the creation flow.

Once created, the Skill appears in the **"My Skills"** tab of the Skill Gallery, ready to use the next time you create a deck.

## Share a Skill (one link is enough)

Every Skill you own has a **Share** panel — share it like a doc, no more exporting a `.zip` and sending files around:

1. Open one of your Skills and click **Share**
2. Invite specific people by email, or switch General access to **"Anyone with the link"** and copy the link

Recipients can preview the Skill and import their own copy. You stay in control: remove a person or disable the link at any time — copies people already imported remain theirs.

## Team Skills: publish to your whole organization

If your account belongs to an organization with team features enabled (refer to the UI), you can publish a Skill for the whole organization to use:

1. **Members**: open your Skill, click **Share**, and set General access to **"Organization"** — this submits it for admin review
2. **Admins**: approve or reject (with a reason) on the team admin's Skills page; both sides get email and in-app notifications
3. Once approved, the Skill appears under the **"Team Skills"** tab of every member's Skills library and activates automatically; when the publisher updates it, everyone gets the latest version

Best for: the company proposal framework, a department's brand style, a report format refined over years — publish once, and the whole organization benefits.

## FAQ

**Q: What's the difference between Save as Skill and New Skill?**
A: Save as Skill turns the deck you just finished directly into a reusable blueprint (its entry is the ⋮ menu at the top right of the workspace); New Skill is created manually from the Skill Gallery and supports three paths — uploading a file, importing a Skill package, or describing from scratch.

**Q: What files can I upload to create a Skill?**
A: The template path accepts `.pptx` or `.pdf` files up to 100 MB; importing a Skill package uses a `.zip` file.

**Q: Can I create a Skill without an existing file?**
A: Yes. Choose "I'm starting from scratch" and simply describe the structure and style you want — the Agent will create it accordingly.

**Q: Where can I find a Skill I've created?**
A: In the **"My Skills"** tab of the Skill Gallery, ready to use the next time you create a deck.

**Q: Can I take back a Skill after sharing it?**
A: You can remove invited people or disable the share link at any time; however, copies others imported before that remain theirs and are not recalled.

## Next steps

- [Using the Skill Gallery](https://page.gensparksite.com/manual/buddy-guides/v1/en/slides-skill-gallery.md)
- [AI Slides overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/slides-overview.md)
