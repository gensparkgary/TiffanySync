# Genspark Code — Connect to Existing Code

> For Buddy Agent internal use.
> type: howto | feature: ai-developer | keywords: existing code, existing code, GitHub, repository, repository, SSH, server, Shopify, connect
> User loop: Pick an "Existing code" starting point → connect your repo/server/store → let AI work on your existing code

## Why use this

You don't always start from scratch. If you already have a GitHub repository, a server, or a Shopify store, Genspark Code can connect to them directly, letting AI understand, modify, and extend your existing codebase—no rebuilding required, just keep moving forward.

## 1. Connect an existing GitHub repository

On the starting points home page, pick **Existing GitHub Project** (under the "Existing code" category) and follow the prompts to connect your GitHub and specify the repository you want to use. Once connected, AI reads the code in your repo, and then you can describe the changes or new features you want it to make.
![Existing GitHub Project starting point and connection flow](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35762/8e1aeb7e.png)

## 2. Connect your own server (SSH)

Pick the **Bring Your Own SSH Server** starting point and provide your server's connection details, and AI works directly on your server—ideal when you want your code to run on your own machine.
![Bring Your Own SSH Server starting point setup](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35762/c9e690fb.png)

## 3. Shopify development

Pick the **Shopify Development And Manager** starting point (under the "E-commerce" category) to develop Shopify themes or store features. Follow the prompts to connect your Shopify, and AI can then work on your store.
![Shopify Development And Manager starting point and connection](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35762/0e8dde7f.png)

## About credits

Connecting a repo/server/store itself doesn't consume credits; each round where AI understands and modifies the code consumes credits based on usage.

## FAQ

**Can I connect my existing repository?**
Yes. Pick the Existing GitHub Project starting point, connect GitHub and specify the repository, and AI will work on your existing code.

**Are private repositories supported?**
Once you've authorized through GitHub, you can access any repository you have permission for. Just complete the authorization following the starting point's connection prompts.

**I want my code to run on my own server?**
Pick the Bring Your Own SSH Server starting point and provide your server's connection details, and AI works directly on your machine.

**How do I deliver the result when I'm done?**
Push it back to GitHub, deploy it, or download the code—see [Deploy and Export](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-developer-deploy-and-export.md).

## Next steps

- [Preview and Edit](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-developer-preview-and-edit.md) — preview and iterate on the connected code
- [Deploy and Export](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-developer-deploy-and-export.md) — push changes back to GitHub / deploy / download
- Want to build a new app from scratch? See [Get Started](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-developer-get-started.md)
