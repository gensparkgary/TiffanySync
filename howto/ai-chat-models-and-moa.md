# AI Chat — Models & Mixture-of-Agents

> For Buddy Agent internal use.
> type: howto | feature: ai-chat | keywords: AI Chat, choosing a model, switching models, Mixture-of-Agents, MoA, multiple models, model comparison, selection advice, model locking, model retirement, automatic switch
> User loop: At the decision point of "which model should I pick / should I use MoA" → understand single model vs MoA → choose by scenario → know the model locks after sending a message

## Why knowing how to pick a model matters

Different models have different strengths—pick the right one and you get a more fitting answer at a better cost. AI Chat puts the choice in your hands: fast, reliable, or economical—you decide. This guide helps you decide between picking a single model and letting multiple models work together.

## Where to choose

The **model selection dropdown** above the input box. Open it and you'll see a selectable list with **dozens of single models**, plus **Mixture-of-Agents** at the top of the list—the option that lets multiple models collaborate (its subtitle explains it "automatically blends the models best suited to your task"). At the bottom of the dropdown there's also a Search Web toggle.
![Model selection dropdown with single models and the Mixture-of-Agents option](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35958/7ab9ff9a.png)

> Which models are available, and how many, will update over time—go by what's actually shown in the interface.

## Single model vs Mixture-of-Agents

| | Single model | Mixture-of-Agents (MoA) |
|---|-----------|------------------------|
| How it answers | One model answers directly | Multiple models each answer, then results are aggregated into one synthesized answer |
| Best for | Clear, routine questions; when you want speed and savings | Important, complex questions where you want a more thorough, reliable answer |
| Cost | Lower (one model's usage) | Higher (multiple models + one synthesis pass) |

**Selection advice**:
- Not sure → pick a **single model** first—fast, economical, and good enough.
- The question is important and you want a more reliable answer → pick **Mixture-of-Agents**, trading multi-model collaboration for higher quality.

## How Mixture-of-Agents works

You ask a question, and MoA has **multiple models each answer**, then the system runs **a layer of aggregation and reflection, finally synthesizing one answer**. In the interface you can see each model's individual response, as well as the final synthesis process. Multiple models cover for one another, reducing the blind spots of any single model. It's an option inside AI Chat—you don't need to open multiple tools separately.

## The model locks once the conversation starts

Once you've picked a model and sent the first message, **the model for that conversation is fixed**—click the dropdown again and it'll be grayed out with a prompt saying you "need to start a new conversation to change the model." Just click New Chat in the prompt. So confirm you've picked the one you want before sending. (The Search Web toggle isn't affected by this lock—you can still change it anytime.)

## Models are occasionally retired—the system notifies you in advance

The model list updates over time, and individual models are occasionally retired. This is the one exception to the lock rule above, handled by the system with no action needed from you:

- If your ongoing conversation is using a model that's about to be retired, **a notice appears above the input box** showing the retirement date and suggesting a model to switch to.  
- Close to the retirement date, that model is **hidden from the model dropdown for new conversations**; conversations already using it are unaffected and can continue. 
- After the retirement date, conversations still on that model **automatically continue on the replacement model**—the conversation itself is not interrupted. 

## FAQ

**Q: Is MoA much more expensive than a single model?**
It's more expensive than a single model because it runs multiple models and then synthesizes. Free users pay more under usage-based billing; Plus / Pro users get unlimited core conversations with no credit consumption. It's worth it for important questions—use a single model for everyday Q&A.

**Q: Can I switch models partway through after choosing one?**
Not within the same conversation. Confirm before sending; if you need to switch, start a new conversation. (The one exception: when a model is retired, the system automatically switches the conversation to a replacement model—see the section above.) 

**Q: The models in the interface don't match what the docs say?**
Go by **what the interface shows**. The model list updates over time, so the docs don't hard-code specific names.

## Next steps

- Want to walk through the full conversation flow (web/upload/voice) → [Get Started](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-chat-get-started.md)
- Want to understand where AI Chat fits overall → [Product Overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-chat-overview.md)
