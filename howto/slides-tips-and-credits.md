# AI Slides — Tips & Credit Optimization

> For Buddy Agent internal use.
> type: howto | feature: ai-slides | keywords: Credit, save credit, Ultra, Standard, tips, Tips, efficiency, Edit, built-in editor, Skill, Prompt
> User loop: Understand Credit consumption rules → Master Credit-saving tips → Make better PPTs with fewer Credits

## Credit Consumption Rules

In AI Slides, every AI operation (generation, editing, AI refinements, etc.) consumes Credits. The amount depends on the **tier** you choose:

| Tier | Characteristics | Best for |
|------|------|---------|
| **Ultra** (default) | Highest quality, refined layout | Important presentations, complex structures, high-quality requirements |
| **Standard** | Faster, more economical | Everyday PPTs, quick drafts, simple content |

There are only two tiers, Standard / Ultra; Ultra is the default. Standard is the more economical choice and Ultra puts quality first — for the exact credit cost of each tier, go by what the tier selector on the creation page shows.

### Operations That Don't Consume Credits

The following operations are **completely free** and consume no Credits:

- **The Edit built-in editor** — modify text, images, colors, and layout directly on the canvas; manual editing that doesn't go through AI
- **Presenting** — Present fullscreen shows, Presenter view, and Presentation View previews
- **Page navigation** — switching between slides to view them
- **Version rollback** — rolling back to a Save Point in the History panel
- **Make a Copy** — duplicating a project
- **Share** — sharing links

## Credit-Saving Tips

### 1. Use the Edit Built-in Editor for Small Changes

If you just need to change a few words, swap a color, or nudge an element, switch to the toolbar's **Edit** mode and change it directly on the canvas instead of having the AI regenerate. The built-in editor is completely free.

How to: Click **"Edit"** in the toolbar above the slide → modify text and elements directly on the slide.

### 2. Use the Standard Tier for Everyday PPTs

Not every PPT needs Ultra. For internal meeting notes, simple information summaries, and slides for everyday communication, the Standard tier is enough and costs noticeably less (see the tier selector for the live credit cost).

How to switch: In the tier selector at the bottom left of the input box on the creation page, select **Standard**.

### 3. Use Skills to Reduce Iterations

If you frequently make PPTs in a similar style (such as weekly or monthly reports), first create a template you're happy with, then **Save as Skill**. Next time, start directly from the Skill, and the AI can generate a PPT close to the final result in one go, reducing the Credit consumption of repeated revisions.

### 4. Write Specific Prompts

Vague prompts make the AI guess your intent, and the results may require multiple rounds of revisions. Stating the key information clearly up front can significantly reduce the number of iterations:

| Vague (may need 3-4 rounds of revisions) | Specific (usually just 1-2 rounds) |
|---|---|
| "Make a pitch deck" | "Create a 10-slide Series A pitch deck for an AI startup. Include: problem, solution, market size ($50B), business model (SaaS), team (3 founders), and ask ($5M)" |
| "Add a chart" | "Add a bar chart on slide 3 comparing Q1-Q4 revenue: Q1=$2.1M, Q2=$2.8M, Q3=$3.5M, Q4=$4.2M" |

### 5. Make the Most of Select and Draw Batching

To have the AI change just one spot, use **Select** to click that element before giving the instruction — the AI pinpoints the exact edit location and avoids regenerating the whole page. When there's a lot to change, use **Draw** to mark up the whole deck and click **"Send N edits"** once — many changes merge into a single AI call, far cheaper than sending messages one by one.

### 6. Use Guide Mode to Reduce Major Rework

For important presentations (pitch decks, board reports), enable **Guide Mode**. The AI first conducts an in-depth consultation, confirming the structure and content before generating, which reduces "generate then heavily revise" situations. Although Guide Mode itself consumes a few extra rounds of conversation Credits, it avoids the cost of repeated rework later.

### 7. State Complex Changes All at Once

Don't submit revision requests one by one across multiple messages; put all changes into a single message:

| Inefficient (3 AI calls) | Efficient (1 AI call) |
|---|---|
| "Change the title color to blue" | "Change the title color to blue, increase font size to 36px on slide 2, and replace the stock photo on slide 5 with a chart showing our user growth data" |
| "Make the font bigger on slide 2" | |
| "Replace the image on slide 5" | |

### 8. Start a New Chat to Manage Context

Long conversations make the AI's context grow longer and processing slower. If the current PPT is basically finalized, start a new chat for small revisions and the AI will respond faster.

How to: Hover over the **Memory indicator** in the editor and click **"+ New chat"** in the popup (see [Memory & New Chat](https://page.gensparksite.com/manual/buddy-guides/v1/en/slides-new-chat.md) for details).

## FAQ

### Can I still use AI Slides after my Credits run out?

Once Credits run out, you can't perform AI operations (generation, editing, etc.), but you can still use the Edit built-in editor (free manual editing) and the presenting features (Present / Presentation View). Note that **Export is gated by membership, not credits**: it requires a Plus, Pro, or Team membership, and Free-tier accounts cannot export regardless of their credit balance.

### Is there a big difference between Ultra and Standard results?

For simple PPTs (10 pages or fewer, with clear content), the difference is small. For complex scenarios (data-heavy, many charts, requiring creative layouts), Ultra's output quality is noticeably higher. Recommendation: try Standard first, and switch to Ultra if you're not satisfied.

### How do I check my Credit balance?

You can see your current Credit balance in the menu at the bottom left of the page.

## Next Steps

- Want to polish your PPT with the editing tools: see [Editing & Refining](https://page.gensparksite.com/manual/buddy-guides/v1/en/slides-edit-and-refine.md)
- Want to generate charts and AI images: see [Charts & Media Content](https://page.gensparksite.com/manual/buddy-guides/v1/en/slides-charts-and-media.md)
