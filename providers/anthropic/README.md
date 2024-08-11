

# Anthropics Integration - Aisudo 3rd Party API
*Document is last updated at: 11 August 2024*
This readme document also available at: [AiSudo Github - Anthropic](https://github.com/aisudoapp/ai-model-providers/tree/main/providers/anthropic)


## How to use
### Get your API at Anthropic
- Go to [https://console.anthropic.com/settings/keys](https://console.anthropic.com/settings/keys)
- Click "+ Create Key"
- Copy and save this API KEY, you will not be able to view it again.

If haven't use Anthropics api before, you need to activate free plan:
- Go to [https://console.anthropic.com/settings/plans](https://console.anthropic.com/settings/plans)
- Click "Claim"

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
- Paste the API Key from Anthropic

  
## Web App CORS
There are 2 configurations platform for Claude, web and desktop config. 
On Web configuration, your request will be routed to AiSudo server first, this is because Anthropic API is not supporting CORS.
Detail: [https://github.com/anthropics/anthropic-sdk-typescript/issues/219](https://github.com/anthropics/anthropic-sdk-typescript/issues/219)
  
If you are using desktop app, please use desktop config, your request will be sent directly to anthropic and it will be faster.


---

## Limits
This is the limit for Anthropics Free Tier:

| MODEL TIER | REQUESTS PER MINUTE | TOKENS PER MINUTE | TOKENS PER DAY |
| --- | --- | --- | --- |
| Claude 3.5 Sonnet | 5 | 20,000 | 300,000 |
| Claude 3 Opus | 5 | 10,000 | 300,000 |
| Claude 3 Sonnet | 5 | 20,000 | 300,000 |
| Claude 3 Haiku | 5 | 25,000 | 300,000 |
  
---

## Pricing
This is the pricing for each model in the Claude family:

| Model | Claude 3.5 Sonnet | Claude 3 Opus | Claude 3 Sonnet | Claude 3 Haiku |
| --- | --- | --- | --- | --- |
| **Description** | Most intelligent model | Powerful model for highly complex tasks | Balance of intelligence and speed | Fastest and most compact model for near-instant responsiveness |
| **Strengths** | Highest level of intelligence and capability | Top-level performance, intelligence, fluency, and understanding | Strong utility, balanced for scaled deployments | Quick and accurate targeted performance |
| **Multilingual** | Yes | Yes | Yes | Yes |
| **Vision** | Yes | Yes | Yes | Yes |
| **API model name** | claude-3-5-sonnet-20240620 | claude-3-opus-20240229 | claude-3-sonnet-20240229 | claude-3-haiku-20240307 |
| **API format** | Messages API | Messages API | Messages API | Messages API |
| **Comparative latency** | Fast | Moderately fast | Fast | Fastest |
| **Context window** | 200K | 200K | 200K | 200K |
| **Max output** | 4096 tokens | 4096 tokens | 4096 tokens | 4096 tokens |
| **Cost (Input / Output per MTok)** | $3.00 / $15.00 | $15.00 / $75.00 | $3.00 / $15.00 | $0.25 / $1.25 |
| **Training data cut-off** | Apr 2024 | Aug 2023 | Aug 2023 | Aug 2023 |
  
---
  
## Model Comparison
![Claude Model Comparison](https://raw.githubusercontent.com/aisudoapp/ai-model-providers/main/assets/anthropic-3-5-sonnet-curve.png)
  
  
---
  
## Parameters
Check [https://docs.anthropic.com/en/api/messages](https://docs.anthropic.com/en/api/messages) for further information.
  
---
  
## Screenshot
![Screenshot AiSudo](https://raw.githubusercontent.com/aisudoapp/ai-model-providers/main/assets/screenshot-provider-anthropic-2.jpg)