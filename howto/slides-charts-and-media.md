# AI Slides — Charts & Media Content

> For Buddy Agent internal use.
> type: howto | feature: ai-slides | keywords: charts, Chart, data visualization, image generation, Image, AI image generation, video, audio
> User loop: Describe data/chart needs → AI generates charts in the slide → Modify via chat or Select → Insert AI images to enrich visuals

## Charts & Data Visualization

AI Slides can generate **charts** directly in your presentation — no Excel or third-party tools required.

### Supported Chart Types

AI automatically picks the right chart style based on your data. Common types include:

- **Bar / column charts** — great for comparing data across categories
- **Line / area charts** — great for showing trends over time
- **Pie / donut charts** — great for showing proportional distribution
- **Scatter plots** — great for showing the relationship between two variables
- **Radar charts** — great for multi-dimensional capability comparisons
- **Combo charts** — e.g. a bar chart overlaid with a line chart

### How to Generate Charts

Just describe your data and needs in the chat:

- "Create a bar chart comparing Q1-Q4 revenue for 2024 and 2025"
- "Add a pie chart showing market share: Company A 35%, B 28%, C 22%, Others 15%"
- "Generate a line chart showing user growth from January to December"

AI generates the chart in the slide, with values labeled directly on the chart.

### Modifying Chart Data

After generation, you can request changes in the chat:

- "Update the Q3 revenue to $4.2M"
- "Change the chart colors to blue and green"
- "Add a trend line to the chart"

You can also click the chart directly in **Select** mode (the selection frame is labeled as a chart) and type your instruction — AI changes only that chart without touching the rest of the page.

### Things to Note

- Chart data must come from you or from AI search results — AI will not make up data
- Charts appear as static graphics in the slide and stay consistent when exported to PDF/PPTX
- To edit chart data, go through chat or Select and let AI make the change; the built-in editor (Edit mode) is for text and layout, not for editing a chart's internal data
- Complex data visualizations (such as geographic heat maps or 3D charts) may need more specific descriptions

## AI Image Generation

AI Slides has built-in image generation, so it can create original illustrations, backgrounds, and supporting visuals for your slides.

### Image Models

When creating in Creative Mode, you can switch image models in the Image Model selector at the top — different models excel at different styles, so go by the options shown in the UI (for the current options and selection tips, see [Creative Mode](https://page.gensparksite.com/manual/buddy-guides/v1/en/slides-create-creative.md)). In Professional Mode, AI automatically generates supporting visuals as needed.

### Image Search

Besides generating images with AI, you can also search the web for images:

- "Find a photo of the Golden Gate Bridge for the title slide"
- "Search for a minimalist icon set for the feature comparison slide"

AI searches for and inserts a suitable image into the slide.

## AI's File & Data Processing Capabilities

In certain advanced scenarios, AI can run code in a secure, isolated environment to:

- Process images you've uploaded (crop, resize)
- Run data processing scripts to generate chart data
- Transcode or process media files

These operations are handled by AI automatically — no manual work required on your part.

## FAQ

### Can charts be generated automatically from my data files?

Yes. After uploading a CSV, Excel, or PDF file, AI can read the data and generate charts automatically. In your prompt, say something like "Read the data from the uploaded file and create a chart showing...".

### Can I use Creative Mode's AI images together with Professional Mode's charts?

The two modes have different strengths: Professional Mode is better at generating data charts and structured content, while Creative Mode is better at full-frame AI illustrations. If you need a "data chart + polished visuals" combination, we recommend generating the content in Professional Mode, then fine-tuning the visuals with the one-click AI refinements.

### Can I add video to Slides now?

AI Slides currently does not support generating or embedding video directly. For video-style presentation content, we recommend using the Video feature in [Genspark Design](https://page.gensparksite.com/manual/buddy-guides/v1/en/design-overview.md).

## Next Steps

- Want to further adjust charts or visuals after generation: see [Editing & Refining](https://page.gensparksite.com/manual/buddy-guides/v1/en/slides-edit-and-refine.md)
- Want to spend fewer Credits generating charts and images: see [Tips & Credit Optimization](https://page.gensparksite.com/manual/buddy-guides/v1/en/slides-tips-and-credits.md)
