
# Free AI Model Providers

This repository contains a list of several 3rd-party AI model providers configuration that compatible with AiSudo App.
Explore and test various AI models from different providers, all in one place. Browse through our list to find the perfect model for your project, and start building with ease.

## What is AiSudo? <[https://aisudo.com](https://aisudo.com)>
AiSudo is a multi-platform client software for AI chat and image generation, all in one app. It supports various AI models from third-party providers.
![Screenshot AiSudo](https://raw.githubusercontent.com/aisudoapp/ai-model-providers/main/assets/screenshot-aisudo.jpg)

## Usage
You only need raw JSON file at **providers** folder, which serve as **editable** model configuration.

-> Clone the Repository or download the raw JSON file at <providers> folder.  
-> Visit AiSudo, then [download](https://aisudo.com/) the app or use the [online web app](https://app.aisudo.com).

In App instruction:
1. Click "(+) Models"
2. In Choose Model page, click "⋮" Icon
3. Select "Load from JSON File"

![Screenshot AiSudo](https://raw.githubusercontent.com/aisudoapp/ai-model-providers/main/assets/screenshot-load-json.jpg)


## Folder & File Naming
```
providers
└───provider-name
│   └───model-type
│       │   cc-model-name.json
│       │   tti-model-name.json
│       │   ...
│       │   README.md
```

- cc = Chat Completions
- tti = Text to Image

The README.md also served as model information.

## Limitations
- Currently, AiSudo only support chat completions for the 3rd party models. We are working to expand our capabilities in the future.
- When using the model listed in this repository, you can ignore the request rate limit on your aisudo account, that limit is only for our official models.
- Request rate limits are dependent on the 3rd party provider and may vary. We recommend checking the provider's website for the most up-to-date information on request rates.


## Privacy

We do not collect or store any data sent to third-party providers. Any data exchanged with these providers is not retained or saved in our database, ensuring that your information remains private and secure.

We only monitor login activity into our system to ensure the security and integrity of our platform. This limited monitoring is necessary to prevent unauthorized access and protect your account.


## 🤝 Contribute

We welcome contributions from the community. Whether you're adding new providers or models, or simply fixing typos and making small improvements, your input is valued. Once all changes have been addressed and tested we'll merge the pull request into the main branch and release the updates at a later time.


