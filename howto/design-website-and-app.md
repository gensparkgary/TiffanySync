# Genspark Design — Design Websites and Apps

> For Buddy Agent internal use.
> type: howto | feature: genspark-design | keywords: website, app, web page, mobile, iOS, Android, prototype, Prototype, Build it, handoff, developer
> User loop: Describe website/app requirements → AI generates designs with device frames → Prototype for interactive preview → Build it to deliver code / Handoff to developer

## Why Use Design for Websites and Apps

- **Rapid prototyping**: Go from description to an interactive website/app prototype in minutes
- **Realistic device previews**: Automatically wrapped in iPhone, Android, Mac, or Chrome browser frames
- **One-click code delivery**: Build it generates ready-to-run website or app code directly

## Design a Website

### 1. Describe Your Website

Describe the website you want in the chat box. You can be specific about the page type:

- "Design a SaaS landing page for a project management tool"
- "Create a dashboard with charts and user statistics"
- "Design a restaurant website with online menu and reservation"

> Mention **Prototype** (interactive prototype) in your description to generate designs with real interactions like button clicks and form inputs.

### 2. View the Design in a Browser Frame

AI can present your website design inside a **browser window frame**, making it look like it's open in a real Chrome browser. The frame includes elements like the address bar and tabs, helping you visualize the final result. Whether the frame is used is decided automatically by the AI based on the design context.

![SaaS landing page rendered live (edge-to-edge rendering, frame chosen by AI as needed)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34398/7a2a9462.png)

### 3. Iterate and Refine

Keep describing the changes you want in the chat:

- "Make the hero section taller and add a background video"
- "Change the color scheme to dark mode"
- "Add a pricing section with three tiers"

You can also use [Tweaks](https://page.gensparksite.com/manual/buddy-guides/v1/en/design-canvas-tools.md) to directly adjust parameters like colors and spacing, or use [Comment](https://page.gensparksite.com/manual/buddy-guides/v1/en/design-canvas-tools.md) to leave feedback at specific spots.

## Design a Mobile App

### 1. Describe Your App

Describe the app you want in the chat box:

- "Design an iOS fitness tracking app with workout logs"
- "Create an Android e-commerce app with product listing and cart"
- "Design a 4-screen mobile onboarding wireframe"

### 2. View the Design in a Device Frame

AI automatically selects the appropriate device frame based on your description:

| Frame | Use Case |
|------|---------|
| **iPhone frame** | iOS app design, including the notch/Dynamic Island and Home Indicator |
| **Android frame** | Android app design, including the status bar and navigation bar |
| **macOS window** | Desktop app design, including the traffic-light buttons and title bar |

The design is presented in a realistic device shell, making it easy for you and your team to review.

### 3. Interactive Prototype

When you choose the **Prototype** type, the generated design is more than a static image — it also includes:

- Clickable buttons and links
- Fillable forms
- Page transitions and navigation
- Modals and drawers

You can click to experience the interactions directly in the Canvas, or use [Present](https://page.gensparksite.com/manual/buddy-guides/v1/en/design-export-and-share.md) for a full-screen demo.

## Export and Handoff

Once you're happy with the design, you can export it as runnable code or hand it off to developers. See [Export, Share, and Version Management](https://page.gensparksite.com/manual/buddy-guides/v1/en/design-export-and-share.md) for detailed steps.

- **Build it**: Canvas top bar → Website / App
- **Download**: standalone button next to Build it, downloads the project ZIP
- **Handoff to developer**: Say "Handoff to developer" in the chat → packaged in a developer-friendly format
- **Standalone HTML**: Say "Save as standalone HTML" in the chat → a single file that works offline

## FAQ

### Can I design responsive websites?

Yes. State in your description that you need mobile support, and AI will generate a responsive layout. You can also design the desktop version first and then ask AI to add mobile adaptations.

### Can I design multiple pages at once?

Yes. Continue the conversation within the same project to gradually add more pages. You can also use multiple conversations to design different pages separately in different chats.
