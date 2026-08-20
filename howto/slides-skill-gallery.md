# AI Slides — Using the Skill Gallery

> For Buddy Agent internal use.
> type: howto | feature: ai-slides | keywords: Skill Gallery, Skill Library, My Skills, Featured, Team Skills, Categories, ordering
> Note: This doc covers only the Skill Gallery inside AI Slides, and is unrelated to the sidebar Skills product (/skills).
> User loop: Open the creation page → Open the Skill Gallery → Browse multiple categories or My Skills → Add & Use one or more Skills → The Agent generates a PPT based on the Skill(s)

## Prerequisites

- You're on the `/ai_slides` creation page
- Professional Mode (the Skill Gallery is not shown in Creative Mode)

## Why use the Skill Gallery

- **No prompt-writing skills required**: Picking a Skill from one of the many categories (refer to the UI) is far easier than describing "what style of PPT I want" yourself
- **Professional quality from the start**: Each Skill includes structure, style, and content guidance, producing much higher quality than a blank prompt
- **Quick start**: Browse → Select → Add & Use — three steps cover most of what writing a prompt would do
- **Reusable**: Save a great PPT you've made with Save as Skill, and reuse it directly next time

## What is the Skill Gallery

The Skill Gallery is a library of reusable PPT recipes inside the AI Slides creation page. Each Skill includes structure, style, and content guidance to help the Agent generate a specific type of PPT. Think of it as "advanced templates with built-in AI understanding."

> **Don't confuse them**: "Skill" here refers specifically to AI Slides' PPT recipe templates. It's a different feature from the sidebar **Skills** product (`/skills`, a general-purpose skills platform built on SuperAgent Sandbox). They share a name but serve different purposes.

## Steps

### 1. Open the Skill Gallery

In the settings area of the creation page, find the **Skill Gallery** panel. There are two tabs at the top:
- **Skills** — Browse all Skills; below it is a filter bar with **All | My Skills | Featured | + multiple categories (refer to the UI)**; if your organization has published team Skills, a **Team Skills** tab appears too (see below)
- **Recents** — Recently used Skills

![Skill Gallery entry (Skills / Recents + filter bar)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36116/42eaa613.png)

### 2. Browse categories

In the Skills tab's filter bar, besides **All / My Skills / Featured**, there are multiple categories (refer to the UI). Examples include:

| Category | Use cases |
|------|---------|
| Coursework | Classroom reports, academic presentations |
| Corporate Strategy | Business strategy |
| Training | Training materials |
| B2B Sales | Sales proposals |
| Academic | Academic research |
| Marketing | Marketing plans, promotion plans |
| Data & KPI | Data analysis, KPI reporting |
| Fundraising | Fundraising pitches |
| Public Policy | Public policy |
| Product Mgmt | Product management |
| Consulting | Consulting reports |
| Career | Career development |
| AI Literacy | AI literacy |
| Life | Lifestyle |
| Design Craft | Design inspiration |

Skill cards are shown in a masonry layout. Hover over a card to preview the result.

![Browsing category cards](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36116/ebe92ce8.png)

### 3. Select a Skill

There are two ways to add a Skill — both have the exact same effect, adding the Skill to the input box:

**Option A: Add directly from the card**
Click the **"Add & Use"** button on the Skill card.

**Option B: Preview first, then Use this Skill**
Click a Skill card to open the details dialog, where you can view:
- The Skill's description and intended use
- Preview sample pages — the number varies by Skill (a page indicator such as "1 / 5" shows the count)
- Action buttons at the bottom of the dialog: for a Skill you own these are **Delete / Download / Edit / Share / Use this Skill**. The dialog's primary button for applying a Skill is **"Use this Skill"** — the **"Add & Use"** label only appears on the card hover

Once you've confirmed it's the Skill you want, click **"Use this Skill"**.

![Skill details dialog (preview pages + Delete / Download / Edit / Share / Use this Skill)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/51105/c7f555a7.png)

You can select multiple Skills: clicking **"Add & Use"** on a second Skill doesn't replace the first — it **stacks chips**. Selected Skills stack as chips, and the input box prompt is automatically rewritten to "Add these skills... combine them."

![Selecting multiple Skills (two chips stacked)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36116/d9a71874.png)

### 4. Enter a prompt and generate

After selecting a Skill, describe your specific content needs in the input box. The Agent will generate the PPT based on the Skill's structure and style guidance combined with your content.

## My Skills

Click **My Skills** in the Skills tab's filter bar to see the personal Skills you saved via **Save as Skill** or **Create Skill**. The details dialog of a Skill you own offers **Delete / Download / Edit / Share / Use this Skill** at the bottom.

If you don't have any personal Skills yet, an empty state will guide you to create one.

![My Skills view (inline New Skill card with three creation paths + your saved Skills)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/51105/8f6289bd.png)

### Custom ordering

Cards for your own Skills (and your organization's team Skills) support **drag-to-reorder**, so you can put frequently used ones first; each card also has a **move-to-front** shortcut in its top-right corner. The ordering is saved per user and only affects what you see.

## Team Skills (organization-shared Skills)

If your account belongs to an organization with team features enabled (refer to the UI), the Skills library gains a **"Team Skills"** tab: Skills submitted by members and approved by an admin appear here and **activate automatically for every member** — no importing needed. When the publisher updates a Skill, everyone gets the latest version automatically.

To publish your own Skill to the whole organization: see the Team Skills section of [Create and Manage Skills](https://page.gensparksite.com/manual/buddy-guides/v1/en/slides-create-skill.md).

## FAQ

**Q: Is the Skill Gallery the same as the sidebar Skills product?**
A: No. Skills here refer specifically to AI Slides' PPT recipe templates; the sidebar Skills (`/skills`) is a general-purpose skills platform built on SuperAgent Sandbox. They share a name but serve different functions.

**Q: Can I use multiple Skills at once?**
A: Yes. Clicking "Add & Use" on a second Skill doesn't replace it — it stacks a chip, and the prompt is automatically rewritten to combine the multiple Skills.

**Q: Why are the buttons on the cards different?**
A: The card hover shows **`Add & Use`**, while the details dialog applies a Skill via its primary **`Use this Skill`** button; the dialog of a Skill you own additionally offers `Delete` / `Download` / `Edit` / `Share`.

**Q: How many categories are there in total?**
A: Refer to the UI. Besides All / My Skills / Featured, the Skills tab's filter bar has multiple categories (such as Coursework, Marketing, Consulting, etc.).

**Q: Can I change the display order of Skill cards?**
A: Yes. Your own Skills and team Skills can be dragged to reorder, or use the move-to-front button in a card's top-right corner; the order only affects your own view.

**Q: Do I still need to write a prompt after selecting a Skill?**
A: You should add your specific content needs. The Agent will generate the PPT based on the Skill's structure and style combined with your content.

## Next steps

- [Create your own Skill](https://page.gensparksite.com/manual/buddy-guides/v1/en/slides-create-skill.md)
- [AI Slides overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/slides-overview.md)
