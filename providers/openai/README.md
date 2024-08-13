

# OpenAIs Integration - Aisudo 3rd Party API
*Document is last updated at: 11 August 2024*
This readme document also available at: [AiSudo Github - OpenAI](https://github.com/aisudoapp/ai-model-providers/tree/main/providers/openai)


## How to use
### Get your API at OpenAI
- Go to [https://platform.openai.com/api-keys](https://platform.openai.com/api-keys)
- Click "+ Create new secret key"
- Copy and save this API KEY, you will not be able to view it again.

*Note: There seems some trouble people getting $5 free trial credits, you might need to setup OpenAI billing to start using their API.*

### Setup AiSudo App

1. Open AiSudo App
- Click "+ New Session" 
- Click "3rd Party API"
- Click "Load from JSON File" 
- Select the json file you downloaded.
- Click "Create Session"
After that, the session will be created.
2. After session created: 
- Click "Settings" (if you're on mobile)
- Paste the API Key from OpenAI


---

## AiSudo Limitation
- Free users are limited to 5 sessions (model connections).
- Ignore the request rate limit on your AiSudo account. API request rate limits are dependent on the provider and may vary. We recommend checking the provider's website for the most up-to-date information on request rates.
- AiSudo presets and language selection is not available for 3rd-party-api.


---

## Model Rate Limits
Refer to this page to check OpenAI rate limit: [https://platform.openai.com/docs/guides/rate-limits/usage-tiers](https://platform.openai.com/docs/guides/rate-limits/usage-tiers)
  
---

## Pricing
This is the pricing for each model in the GPT family:

| Model              | Input Price        | Output Price       |
|--------------------|--------------------|--------------------|
| gpt-4o             | $5.00 / 1M tokens  | $15.00 / 1M tokens |
| gpt-4o-mini        | $0.150 / 1M tokens | $0.600 / 1M tokens |
| gpt-4-turbo        | $10.00 / 1M tokens | $30.00 / 1M tokens |
| gpt-4              | $30.00 / 1M tokens | $60.00 / 1M tokens |
| gpt-3.5-turbo-0125 | $0.50 / 1M tokens  | $1.50 / 1M tokens  |

---
  
## Model Comparison

| Model  | Description | Context window | Max output tokens | Training data  |
|--------------|-----------|----------------|-------------------|----------------|
| gpt-4o             | High-intelligence flagship model for complex, multi-step tasks. GPT-4o is cheaper and faster than GPT-4 Turbo. Currently points to gpt-4o-2024-05-13.     | 128,000 tokens | 4,096 tokens      | Up to Oct 2023 |
| gpt-4o-mini        | Affordable and intelligent small model for fast, lightweight tasks. GPT-4o mini is cheaper and more capable than GPT-3.5 Turbo. Currently points to gpt-4o-mini-2024-07-18.                    | 128,000 tokens | 16,384 tokens     | Up to Oct 2023 |
| gpt-4-turbo        | The latest GPT-4 Turbo model with vision capabilities. Vision requests can now use JSON mode and function calling. Currently points to gpt-4-turbo-2024-04-09.                                     | 128,000 tokens | 4,096 tokens      | Up to Dec 2023 |
| gpt-3.5-turbo-0125 | The latest GPT-3.5 Turbo model with higher accuracy at responding in requested formats and a fix for a bug which caused a text encoding issue for non-English language function calls. Learn more. | 16,385 tokens  | 4,096 tokens      | Up to Sep 2021 |
  
---
  
## Parameters
Check [https://platform.openai.com/docs/api-reference/chat/create](https://platform.openai.com/docs/api-reference/chat/create) for further information.
  
---
  
## Screenshot
![Screenshot AiSudo](https://raw.githubusercontent.com/aisudoapp/ai-model-providers/main/assets/screenshot/provider-openai.jpg)