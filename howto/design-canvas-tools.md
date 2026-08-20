# Genspark Design — Canvas Editing Tools

> For Buddy Agent internal use.
> type: howto | feature: genspark-design | keywords: Tweaks, Edit, Comment, Draw, fine-tune, edit, annotate, brush, Make Tweakable
> User loop: Open an existing design → Choose a tool → Tweaks to fine-tune parameters / Edit to click and modify / Comment to add text annotations / Draw to mark up with the brush → Changes apply in real time

## Why You Need These Tools

AI-generated designs usually need fine-tuning. The toolbar in the top-right corner of the Canvas offers 4 tools that let you make precise adjustments without re-describing anything, each tool corresponding to a different way of editing.

## Tweaks — Visual Parameter Fine-Tuning

The most intuitive way to fine-tune—AI generates adjustable controls for key parameters in your design, and dragging them gives you a real-time preview.

### Opening Tweaks

Click the **"Tweaks"** toggle button in the Canvas toolbar at the top right, and the Tweaks panel pops out on the right. The Tweaks button only appears when the design contains adjustable controls.

![Tweaks: top-right toggle + right-side panel (color / Dark mode / Density and other controls)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34396/932d8a08.png)

### Control Types

| Control | Use | Action |
|------|------|------|
| **Color picker** | Brand color, background color, text color | Click to pick a color |
| **Number input** | Spacing, font size, corner radius, opacity | Enter a value |
| **Text input** | Title, subtitle, button text | Type directly |

### Tips

- Adjustments give you a **real-time preview**—no waiting for the AI to regenerate
- Changes save automatically, no manual action needed
- If a design has no Tweaks controls, say "Make this tweakable" in the chat and the AI will add them automatically (see Make Tweakable below)

## Edit — Edit Design Elements Directly

Click an element in the design to edit it directly—no need to describe in words "which element to change."

### How It Works

1. Click the **"Edit"** button in the Canvas toolbar at the top right
2. Click the element you want to modify in the Canvas (text, image, button, etc.)
3. The editing panel for that element pops up: numbers → number input, color → picker, text → text input, choices → dropdown
4. Changes apply in real time

When editing text elements, the typography options go further: the **font** field is a searchable dropdown (fonts actually used in the current design are listed first, and you can also type any font name), plus options like weight, letter case, italic style, and underline.

![Edit: element properties panel on the left (number input / color picker / dropdown), changes apply in real time](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34396/cd57245a.png)

> The difference between Edit and Tweaks: Tweaks shows preset global parameters, while Edit lets you click individual elements and modify them one by one.

## Comment — Annotated Canvas Comments

Add comments at specific spots on the design to tell the AI exactly where changes are needed.

### How It Works

1. Click the **"Comment"** button in the Canvas toolbar at the top right
2. Click the spot on the Canvas you want to comment on
3. Enter your feedback (you can attach a screenshot for reference)
4. After submitting, the canvas shows numbered markers (1, 2, 3…)
5. Continue adding comments at other spots
6. Once all annotations are done, click send and the AI makes changes based on all the comments

![Comment: numbered markers ①② + batch Send all button](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34396/8ddde8dc.png)

### Comment Management

- **Batch submit**: Send multiple comments to the AI all at once

## Draw — Brush Annotations

Draw annotations directly on the design to sketch out the changes you want.

### Tools

| Tool | Description |
|------|------|
| **Brush** | Fixed red brush |
| **Sticky note** | A draggable text box to write your feedback |
| **Undo** | Undo the last step |
| **Clear** | Clear all annotations |

### How It Works

1. Select the brush or sticky note
2. Draw the changes you want on the design (arrows to indicate movement direction, circle areas to delete, etc.)
3. Add sticky notes to write text explanations
4. Once you're done drawing, send it to the AI with one click

![Draw: fixed red brush + sticky note + Discard / Undo / Send toolbar](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34396/7bc02399.png)

> Comment is best for descriptive changes ("change this to blue"), while Draw is best for visual changes (drawing arrows, circling areas). The two can be used together.

## Make Tweakable — Make Any Design Tweakable

Say "Make this tweakable" about any design, and the AI will generate Tweaks controls for the key parameters.

### How It Works

1. Click **"More"** → **"Make tweakable"**, or say "Make this design tweakable" in the chat
2. The AI automatically adds Tweaks controls to the design
3. Adjustable controls appear in the Tweaks panel—drag them for a real-time preview

> Great for designs that need repeated fine-tuning—adjust the title and date of the same poster for different events, with each adjustment applying in real time.

![Make Tweakable: after triggering it in chat, the AI adds new Tweaks controls to the design](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34396/0338a3ba.png)

## FAQ

### What if the Tweaks panel is empty?

The current design has no preset controls. Say "Make this tweakable" in the chat and the AI will add them.

### What's the difference between Comment and Draw?

- **Comment**: Write a text comment at a specific spot, best for descriptive changes ("change the color here to blue")
- **Draw**: Sketch the effect you want directly on the design, best for visual changes (drawing arrows, circling areas to delete)
- The two can be used together.

### Can I undo changes after making them?

Yes. Tell the AI in the chat which changes you want to undo, and the AI can help you restore them.
