# Genspark App — Asking Questions & Voice

> For Buddy Agent internal use.
> type: howto | feature: mobile-app | keywords: asking questions, input, attachments, photo capture, voice, dictation, realtime voice, Speak, microphone, paste image, voice
> User loop: home input box → submit via text/attachment/voice → get AI results; realtime voice conversations stay fully hands-free start to finish

## Why ask questions on your phone

- **Snap it and ask**: contracts, whiteboards, menus — just shoot a photo with the camera and use it directly as source material, no need to move it to a computer.
- **Talking beats typing**: turn voice input into text, or just start a realtime voice conversation with the AI — hand off tasks while walking or driving.
- **No need to babysit after starting**: submit a task, lock your screen, walk away, and results sync to all your devices.

## Prerequisites

- Genspark App installed and signed in (see [Get Started](https://page.gensparksite.com/manual/buddy-guides/v1/en/mobile-app-get-started.md))
- Asking questions consumes credits (same billing as the web version); balance is visible on the settings page

## Steps

### 1. Ask by text

Enter your content in the home input box and submit. To route it to a specific product: tap the product tag above the input box, or type `@` to pick an agent.

![Enter a question and send](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/buddy-guides/mobile-app/cv-compose.png)

The **model button** next to the input box lets you switch model tiers (available options follow what's shown in the UI). Once a conversation starts, the current session is locked to the selected model; to change models, start a new session.

### 2. Add attachments: photo, album, files

Tap the **"+"** on the left of the input box to open the attachment menu:

| Option | Purpose |
|---|---|
| **Camera** | Take a photo on the spot as source material |
| **Photos** | Pick an image from your album |
| **Files** | Pick a file from your phone |
| **From AI Drive** | Pick an existing file from your cloud drive |
| **Edit Image** | Circle, annotate, or redact on an image before submitting |
| **Connectors** | Connected external service tools |

![Attachment menu](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/buddy-guides/mobile-app/cv-attach.png)

Copied images can also be **pasted directly** into the input box.

### 3. Voice dictation

Tap the **microphone button** on the right of the input box and speak; your words appear in the input box, and you submit after confirming. If Genspark Speakly keyboard is installed, it's used for dictation first; otherwise the App's built-in speech recognition is used. For a stronger dictation experience (personal dictionary, speaking style), install Speakly — see the [Speakly Guide](https://page.gensparksite.com/manual/buddy-guides/v1/en/speakly-get-started.md).

![Voice dictation in progress](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/buddy-guides/mobile-app/cv-dictate.png)

### 4. Realtime voice conversation

Tap the **Speak** button on the right of the input box to enter realtime voice mode: talk directly with the AI, it listens and answers as you go, and the screen shows listening/speaking status. During the conversation you can have it run tasks (which move to the background), and you can also open the camera to let it see what's in front of you. Note the in-app reminder: realtime voice consumes credits faster than text.

![Speak button enters realtime voice](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/buddy-guides/mobile-app/cv-speak-entry.png)

### 5. Controlling the generation process

- You can **stop** anytime during generation
- If sending fails due to poor network, the message is marked as unsent — tap it to **resend in place** without retyping

## FAQ

**What if voice recognition is inaccurate?**
Try again in a quieter environment; for scenarios with many proper nouns, install the Genspark Speakly keyboard and configure a personal dictionary — see the [Speakly Guide](https://page.gensparksite.com/manual/buddy-guides/v1/en/speakly-custom-instructions-and-dictionary.md).

**What's the difference between realtime voice and voice dictation?**
Dictation (microphone button) just converts speech to text, and it's only sent after you confirm; realtime voice (Speak button) is a continuous two-way conversation where the AI responds directly by voice and can run tasks, and it consumes credits faster.

**How many credits does one question cost?**
Same as the web version — it depends on task complexity and the product used; balance is visible on the account card in the settings page, and you'll be prompted to top up when it's low.

**What happens if I exit the App mid-generation?**
The task keeps running in the cloud; come back and open the project to see progress. If push is enabled, you'll get a reminder when it's done (see [Notifications & Sharing](https://page.gensparksite.com/manual/buddy-guides/v1/en/mobile-app-notifications-and-sharing.md)).

## Next steps

- Task-complete push, sharing content into the App → [Notifications & Sharing](https://page.gensparksite.com/manual/buddy-guides/v1/en/mobile-app-notifications-and-sharing.md)
- Usage and subscriptions → [Subscription & Settings](https://page.gensparksite.com/manual/buddy-guides/v1/en/mobile-app-subscribe-and-settings.md)
