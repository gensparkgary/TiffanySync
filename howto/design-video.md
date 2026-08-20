# Genspark Design — Designing Videos

> For Buddy Agent internal use.
> type: howto | feature: genspark-design | keywords: Video, Animation, Frame Movie, Short Film, MP4, Export, Timeline, multi-shot
> User loop: Describe video/animation needs → AI generates animation design → Preview and annotate → Export MP4

## Why Use Design for Video

- **AI generates animations directly**: Instead of stitching together ready-made assets, it generates professional-grade, smooth motion
- **Three video modes**: Use Animated Video for simple animations, Frame Movie for complex multi-shot videos, Short Film for narrative filmmaking
- **Precise annotation**: The video annotation queue lets you batch your edit notes across different points in time
- **HD export**: Supports 1080p / 4K, 24 / 30 / 60 FPS

## Three Video Modes

| | **Animated Video** | **Frame Movie** | **Short Film** |
|---|---|---|---|
| Focus | Single-scene animation | Multi-shot timeline video | Narrative short film (realistic footage) |
| Complexity | Lower, great for getting started | Higher, supports complex storytelling | Highest, made by the AI with a director-style process |
| Typical use cases | Logo motion, product showcase animations, UI motion | Multi-shot ad spots, narrative animations, product demos | Brand story films, concept shorts, creative storytelling |
| Visuals | Smooth motion (transitions / transforms / 3D) | Multiple frames auto-composed into a timeline (with transitions and captions) | AI-generated realistic footage with narration and sound design |
| Export | MP4 | MP4 | MP4 |

## Animated Video

### 1. Create an Animation

Click the **"Video"** button, or just describe what you want:

- "Create a logo animation for our brand"
- "Design a product showcase animation with 3D rotation"
- "Make a loading animation with bouncing dots"

### 2. Preview the Animation

Preview the animation directly in the Canvas. The AI chooses the right animation approach as needed:

- Simple transitions and transforms
- Complex multi-step choreographed animations
- Vector graphics animations (scale without quality loss)
- 3D animations

### 3. Edit the Animation

Describe your edits in chat:

- "Make the animation slower"
- "Add a fade-in effect for the title"
- "Change the easing to spring bounce"

## Frame Movie (Multi-Frame Timeline Video)

### 1. Create a Frame Movie

Describe a multi-shot video in chat:

- "Create a 30-second product demo video with 5 scenes"
- "Design a story animation about a day in the life of a developer"
- "Make a brand introduction video with transitions between scenes"

The AI automatically composes your multiple frames into a timeline video, with transitions between shots and optional captions.

### 2. Timeline Editing

Frame Movie supports:

- Arranging multiple frames along a timeline
- Transition effects between frames
- Captions
- Real-time preview as you work

### 3. The AI Brings the Right Animation Capabilities

For a multi-shot video, the AI automatically picks the right animation capability for each scene — you don't have to specify it. Common ones include:

| Capability | Description |
|--------|------|
| 3D animation | 3D scenes and camera moves |
| Motion graphics | Data visualization animations |
| Text animation | Title and subtitle motion |
| Particle effects | Particle system animations |
| Vector animation | Graphics animations that scale without quality loss |
| Others | Character animation, UI motion, and more |

## Short Film (Narrative Filmmaking)

When you want a short film with realistic footage and a story, just describe it in chat, for example:

- "Make a short film about a lighthouse keeper's last night"
- "Create a 3-minute brand story film for our coffee brand"

### How the AI Makes a Short Film

The AI works through the whole film with a director-style process:

- It designs the narrative first (suspense, pacing, sound design), then generates the film shot by shot
- The visuals are **AI-generated realistic footage** (not motion-graphics collage), with narration, sound effects, and other sound design
- Generation takes longer and costs more — best for work you want to polish seriously

### The Assets Panel

Short film projects get an **Assets** panel in the Canvas:

- Browse the generated assets (frames, clips, audio) as a gallery
- Draw annotations directly on assets you're not happy with, so the AI regenerates them
- Batch regeneration is supported

The finished film is delivered as a timeline video that you can preview section by section in the Canvas and export as MP4.

## Video Annotation Queue

When editing a video, you can use the **annotation queue** to batch your edit notes across different points in time:

### Steps

1. Switch to **Draw** mode
2. Pause the video at the moment you want to annotate
3. Draw annotations or add sticky notes on the frame
4. Keep playing to the next point you want to annotate
5. Repeat the annotation
6. Once you've finished all annotations, send them all to the AI with one click

> This is far more efficient than describing edits frame by frame—you can annotate every edit point across the entire video in a single pass.

## Export MP4

### Steps

1. Once you're happy with the design, say "Export as MP4" or "Download video" in chat
2. Choose your export settings:

| Setting | Options |
|------|------|
| **Resolution** | 1080p / 4K, etc. |
| **Frame rate** | 24 / 30 / 60 FPS |
| **Format** | MP4 |

3. The AI generates the video file automatically
4. It downloads automatically

## FAQ

### How long can an animated video be?

There's no hard limit, but we recommend keeping it under 1-2 minutes. For longer videos, use Frame Movie's multi-shot mode.

### Can I add background music?

Animated Video / Frame Movie animations don't include audio by default; you can export the MP4 and add music in another video editing tool. **Short Film is the exception** — short films come with AI-produced narration, sound effects, and other sound design.

### How do I choose between Animated Video, Frame Movie, and Short Film?

- Motion for a single scene (logo animation, loading animation, UI transition) → **Animated Video**
- Multiple scenes/shots with a narrative, animation style → **Frame Movie**
- A narrative short with realistic footage and sound → **Short Film**
- Not sure → Start with **Animated Video**, then step up if you need a more complex structure
