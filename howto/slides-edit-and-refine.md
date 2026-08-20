# AI Slides — Editing and Refining

> For Buddy Agent internal use.
> type: howto | feature: ai-slides | keywords: Select, Draw, Edit, built-in editor, annotate, Edit queue, Fix Layout, Polish, Verify Content, Enrich, Simplify, Redesign
> User loop: Get the deck → Select an element for precise AI edits → Draw to mark up several spots and send once → Edit in the built-in editor for manual tweaks (free) → one-click AI refinements → Verify content → satisfied final version

## Why you need editing tools

It's rare for AI to generate a perfect deck in one shot. Editing tools help you reach the result you want with the least effort:

- **Edit (built-in editor, free)**: Small changes cost nothing—text, colors, positions, and images can be edited manually right on the canvas
- **Select**: Click the element you want changed before giving the instruction, so AI doesn't accidentally alter other content
- **Draw**: Mark up the whole deck like annotating a printed draft, then hand the entire batch to AI at once
- **One-click AI refinements**: Overall optimization (layout/content/style)—let AI handle in one click what would be tedious to do by hand
- **Verify content**: Data-heavy decks (market reports, fundraising materials) must be verified to avoid the trust issues caused by AI hallucinations

**Key principle for saving credits**: If the Edit mode can fix it manually for free, don't ask AI to regenerate.

## Prerequisites

- A deck has been generated and you're in the Slides workspace (canvas + chat)
- The toolbar above the slide shows the **Select / Draw / Edit** mode switch

## The editing interface (Slides workspace)

The canvas has been upgraded into a full presentation workspace:

- **Outline rail on the left**: every slide's thumbnail at a glance—click any thumbnail to jump to that page
- **Center stage**: the current slide sits center stage, and you can watch AI build the deck page by page
- **Bottom toolbar**: a zoom control (−/+/%, click the percentage to snap back to fit) and the **Notes** (speaker notes) panel entry
- **Toolbar above the slide**: the **Select / Draw / Edit** mode switch on the left, and the active mode's tools on the right

After generation, the Agent automatically reviews the layout (checking each slide's layout, comparing against screenshots, and auto-fixing overlapping elements), so the first draft you receive has no obvious layout issues.

## Select — click an element for precise AI edits

In **Select** mode, click any element on a slide—a title, a paragraph, an image, a chart (the selection frame is labeled by element type)—then describe the change you want. AI changes exactly that spot without touching the rest of the page.

You can also batch across pages: click elements on any pages and leave a note for each, then send all the edits to the Agent at once.

Best for: pinpointing exactly what to change ("replace this image with a bar chart", "translate this text to Chinese").

## Draw — mark up the whole deck, send once

Switch to **Draw** mode and mark up changes the way you'd annotate a printed draft:

- **Pen**: draw freehand around anything
- **Marker**: click to drop a numbered marker
- **Box**: drag to box in an area

Jot a short note next to each mark. All marks collect into the **Edit queue**—annotations stay put as you flip through pages. When you've marked up everything, click **"Send N edits"** once and AI works through the whole batch. Changed your mind about a mark? Remove it individually, or use **Discard** to clear the current page or all pages.

Note: Creative Mode starts in Draw annotation mode by default, so you can mark up the visuals directly.

## Edit — the built-in editor (free manual editing)

Switch to **Edit** mode and the current slide becomes directly editable right on the canvas—no page change, with the chat and AI still by your side. **Free**—no credits consumed. You can:

- **Work with elements like a design tool**: click to select, drag to move, use handles to resize and rotate; marquee-drag several elements to align, distribute, or group them; reorder layers; right-click for cut, copy, paste, and duplicate
- **Format text in place**: double-click into any text and type; the floating toolbar covers font, size, color, bold/italic/underline/strikethrough, alignment, line height, and letter spacing
- **Fine-tune images**: replace an image, crop it freely or to a shape or ratio, round its corners—or open **Change Focus** and drag a dot to choose exactly which part of the original photo stays in frame
- **Manage pages**: drag thumbnails in the left rail to reorder; right-click a page for cut, copy, paste, delete, new slide, or duplicate slide
- **Edit speaker notes**: type directly in the **Notes** panel
- **Undo anything**: every action can be undone/redone; changes save automatically

Currently the **built-in Edit editor is available in Professional Mode only**; Creative Mode does not support it yet (follow the notice shown in the UI).

## One-click AI refinements (by mode)

In Select mode, the right side of the toolbar offers one-click AI refinement buttons; clicking one sends an optimization request for the current slide to the Agent. The options **depend on your mode**:

**Professional Mode:**

| Option | Description |
|---|---|
| Fix Layout | Identify and fix layout issues: overlapping elements, content overflow, misalignment |
| Polish Content | Enhance content logic and layout while matching the current style |

**Creative Mode:**

| Option | Description |
|---|---|
| Enrich Content | Expand details and information density to make slides more self-explanatory |
| Simplify Content | Condense dense information and highlight key takeaways |
| Redesign Layout | Explore alternative visual structures and creative schemes |

## Verify Content

Click **"Verify content"** in the toolbar, then choose **"Verify this page"** or **"Verify entire deck"**. The Agent decides on its own whether to check against the web or your uploaded files, cross-checks facts, figures, sources, and calculations, corrects what's wrong, and leaves a verification mark on each checked slide (Verified OK / Possible issue) with reference links.

Verification records can be reviewed in the **Verify** panel; when you export to PPTX, the verification trail is written into each slide's speaker notes automatically, so whoever receives the file can see the evidence behind every number.

We recommend running a verification on important data slides before the final export.

## Recommended editing workflow

1. Start with **Draw** to mark up everything that needs changing across the deck, then **Send N edits** in one batch
2. Use **Select** for precise changes to individual spots
3. For small text/position tweaks, switch to the **Edit** built-in editor (free)
4. Use one-click AI refinements for overall optimization (Fix Layout for layout → Polish Content for logic)
5. Finally, run **Verify content** on key data slides

## FAQ

### Will editing one piece of text accidentally break other content?

No. For manual changes, use the **Edit** built-in editor (free, and only touches the elements you operate on). When you want AI to change a specific spot, use **Select**—click the element first, then give the instruction, and AI will only modify that one location without affecting the rest of the slide.

### Should I use the Edit built-in editor or an AI edit?

The rule of thumb is simple: for things you can do manually yourself (typos, color changes, repositioning), switch to **Edit** mode and change them directly—free and immediate; for things that need AI judgment (rearranging layout, adding logic, changing chart types), use Select/Draw or the one-click AI refinements. Don't spend credits on changes you can make for free.

### Why doesn't Creative Mode have the Edit built-in editor?

Currently the built-in editor is available in Professional Mode only; Creative Mode does not support it yet (follow the notice shown in the UI). To adjust content in Creative Mode, use Draw annotations (on by default) or the Enrich / Simplify / Redesign one-click refinements.

### Where did the old Advanced Edit and Fact Check go?

After the workspace redesign: the old **Advanced Edit** (a separate-page manual editor) became the toolbar's **Edit** mode—a built-in editor right on the canvas, still free; the old **Fact Check** was upgraded to **Verify content**, which supports whole-deck verification, on-slide verification marks, and a verification trail that travels with PPTX exports.

## Next steps

- To generate or modify charts and images: see [Charts and Media Content](https://page.gensparksite.com/manual/buddy-guides/v1/en/slides-charts-and-media.md)
- To achieve the same result while spending fewer credits: see [Tips and Credit Optimization](https://page.gensparksite.com/manual/buddy-guides/v1/en/slides-tips-and-credits.md)
