# AI Model Prices

Daily-updated AI model API prices across OpenAI, Anthropic, Google Gemini, DeepSeek, xAI, Mistral, and many more providers. Browse LLM token pricing or download open JSON and CSV datasets.

**AI model API pricing** for LLMs, reasoning models, and other hosted AI models. Compare input, output, and cached-token costs across providers, with free machine-readable **JSON and CSV** downloads. This catalog is generated automatically from the latest collected pricing data.

**3,496 model offerings** · **153 providers** · **2,360 distinct model names**  
**Prices:** USD per 1 million tokens · **Catalog generated:** 2026-10-27 12:09 UTC

[**Download JSON**](prices.json) · [**Download CSV**](prices.csv) · [**Browse providers**](#providers)

## Get the data

No API key or account is required to use the published data files. Both exports contain the same pricing records; JSON includes dataset metadata and CSV is spreadsheet-friendly.

```bash
curl -L -o prices.json https://raw.githubusercontent.com/jessejones/ai-model-prices/main/prices.json
curl -L -o prices.csv https://raw.githubusercontent.com/jessejones/ai-model-prices/main/prices.csv
```

**JSON shape:** `metadata` (generation time, counts, units) and `models` (individual model offerings). Prices are in USD per 1 million tokens; very small rates retain their precision.

## Providers

Browse the complete pricing tables for **153 providers**. Provider names are normalized for easier discovery; different billing platforms may remain separate.

<details>
<summary>View provider index (153)</summary>

| Provider | Provider | Provider |
| --- | --- | --- |
| [abliteration](#abliteration) (4) | [ai21](#ai21) (12) | [aihubmix](#aihubmix) (72) |
| [aion-labs](#aion-labs) (6) | [amazon](#amazon) (5) | [amazon_nova](#amazon_nova) (4) |
| [anthracite-org](#anthracite-org) (1) | [anthropic](#anthropic) (42) | [anyscale](#anyscale) (12) |
| [azure](#azure) (139) | [azure_ai](#azure_ai) (135) | [azure_text](#azure_text) (3) |
| [baseten](#baseten) (34) | [bedrock](#bedrock) (121) | [bedrock_converse](#bedrock_converse) (233) |
| [bedrock_mantle](#bedrock_mantle) (32) | [bespoke](#bespoke) (3) | [bytedance](#bytedance) (1) |
| [bytedance-seed](#bytedance-seed) (6) | [cerebras](#cerebras) (9) | [cloudflare](#cloudflare) (34) |
| [codestral](#codestral) (2) | [cognition](#cognition) (3) | [cognitivecomputations](#cognitivecomputations) (1) |
| [cohere](#cohere) (25) | [coralbricks](#coralbricks) (6) | [crusoe](#crusoe) (7) |
| [darkbloom](#darkbloom) (2) | [dashscope](#dashscope) (27) | [databricks](#databricks) (60) |
| [deepinfra](#deepinfra) (136) | [deepseek](#deepseek) (23) | [dots-studio](#dots-studio) (1) |
| [elorian](#elorian) (1) | [fal_ai](#fal_ai) (1) | [fireworks_ai](#fireworks_ai) (302) |
| [fireworks_ai-embedding-models](#fireworks_ai-embedding-models) (7) | [friendliai](#friendliai) (7) | [gemini](#gemini) (66) |
| [gigachat](#gigachat) (7) | [github_copilot](#github_copilot) (33) | [gmi](#gmi) (16) |
| [google](#google) (43) | [gradient_ai](#gradient_ai) (10) | [groq](#groq) (7) |
| [gryphe](#gryphe) (1) | [hyperbolic](#hyperbolic) (16) | [ibm-granite](#ibm-granite) (1) |
| [inception](#inception) (3) | [inclusionai](#inclusionai) (3) | [inference-net](#inference-net) (2) |
| [inferenceapis](#inferenceapis) (24) | [jina_ai](#jina_ai) (1) | [lambda_ai](#lambda_ai) (20) |
| [laya](#laya) (3) | [lemonade](#lemonade) (5) | [libertai](#libertai) (12) |
| [liquid](#liquid) (3) | [llamagate](#llamagate) (16) | [mancer](#mancer) (1) |
| [meituan](#meituan) (1) | [meta](#meta) (9) | [meta-llama](#meta-llama) (8) |
| [microsoft](#microsoft) (1) | [microsoft_365_copilot](#microsoft_365_copilot) (1) | [minimax](#minimax) (11) |
| [mistral](#mistral) (75) | [moondream](#moondream) (2) | [moonshotai](#moonshotai) (21) |
| [morph](#morph) (2) | [nace](#nace) (4) | [nebius](#nebius) (61) |
| [nex-agi](#nex-agi) (2) | [nlp_cloud](#nlp_cloud) (2) | [nousresearch](#nousresearch) (3) |
| [novita](#novita) (134) | [nscale](#nscale) (14) | [nvidia](#nvidia) (11) |
| [nvidia_nim](#nvidia_nim) (2) | [oci](#oci) (50) | [ollama](#ollama) (29) |
| [openai](#openai) (220) | [opencode_go](#opencode_go) (30) | [openinfer](#openinfer) (3) |
| [openrouter](#openrouter) (1) | [ovhcloud](#ovhcloud) (15) | [perceptron](#perceptron) (2) |
| [perplexity](#perplexity) (86) | [pinstripes](#pinstripes) (6) | [poolside](#poolside) (4) |
| [prism](#prism) (2) | [prism-ml](#prism-ml) (1) | [publicai](#publicai) (9) |
| [qwen](#qwen) (43) | [qwen_ai_platform](#qwen_ai_platform) (27) | [qwencloud](#qwencloud) (25) |
| [recursive](#recursive) (1) | [reflection](#reflection) (1) | [refuseless](#refuseless) (5) |
| [rekaai](#rekaai) (2) | [relace](#relace) (2) | [replicate](#replicate) (40) |
| [sagemaker](#sagemaker) (6) | [sail](#sail) (12) | [sakana](#sakana) (4) |
| [sambanova](#sambanova) (8) | [sao10k](#sao10k) (2) | [sarvam](#sarvam) (1) |
| [scaledown](#scaledown) (5) | [scaleway](#scaleway) (15) | [scx-ai](#scx-ai) (5) |
| [snowflake](#snowflake) (21) | [stepfun](#stepfun) (3) | [strands_decider](#strands_decider) (1) |
| [tencent](#tencent) (20) | [tensormesh](#tensormesh) (10) | [text-completion-codestral](#text-completion-codestral) (2) |
| [text-completion-inception](#text-completion-inception) (1) | [text-completion-openai](#text-completion-openai) (6) | [thedrummer](#thedrummer) (3) |
| [thinkingmachines](#thinkingmachines) (4) | [together_ai](#together_ai) (93) | [typesafe](#typesafe) (4) |
| [unbiased](#unbiased) (2) | [undi95](#undi95) (1) | [upstage](#upstage) (3) |
| [v0](#v0) (3) | [vercel_ai_gateway](#vercel_ai_gateway) (97) | [vertex_ai](#vertex_ai) (50) |
| [vertex_ai-ai21_models](#vertex_ai-ai21_models) (5) | [vertex_ai-anthropic_models](#vertex_ai-anthropic_models) (38) | [vertex_ai-deepseek_models](#vertex_ai-deepseek_models) (4) |
| [vertex_ai-embedding-models](#vertex_ai-embedding-models) (10) | [vertex_ai-language-models](#vertex_ai-language-models) (32) | [vertex_ai-llama_models](#vertex_ai-llama_models) (12) |
| [vertex_ai-minimax_models](#vertex_ai-minimax_models) (1) | [vertex_ai-mistral_models](#vertex_ai-mistral_models) (15) | [vertex_ai-moonshot_models](#vertex_ai-moonshot_models) (1) |
| [vertex_ai-openai_models](#vertex_ai-openai_models) (3) | [vertex_ai-qwen_models](#vertex_ai-qwen_models) (4) | [vertex_ai-text-models](#vertex_ai-text-models) (2) |
| [vertex_ai-zai_models](#vertex_ai-zai_models) (3) | [volcengine](#volcengine) (12) | [voyage](#voyage) (31) |
| [wandb](#wandb) (33) | [watsonx](#watsonx) (30) | [writer](#writer) (1) |
| [xai](#xai) (52) | [xiaomi](#xiaomi) (5) | [xiaomi_mimo](#xiaomi_mimo) (2) |
| [xingchen-agi](#xingchen-agi) (1) | [zai](#zai) (36) | [~unbiased](#unbiased) (1) |

</details>

## All AI model prices

Sorted alphabetically by provider and model. **Input**, **Output**, and **Cached input** prices are in USD per 1 million tokens. A dash indicates unavailable data, not a free price.

## abliteration

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| abliterated-model | $1.00 | $3.00 | $0.10 | 262.14K |
| abliterated-model-large | $3.00 | $5.00 | $0.30 | 1M |
| abliterated-model-large-flash | $1.00 | $2.00 | $0.10 | 1.05M |
| abliterated-model-large-v2 | $3.00 | $5.00 | $0.30 | 1M |

## ai21

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| j2-light | $3.00 | $3.00 | — | 8.19K |
| j2-mid | $10.00 | $10.00 | — | 8.19K |
| j2-ultra | $15.00 | $15.00 | — | 8.19K |
| jamba-1.5 | $0.20 | $0.40 | — | 256K |
| jamba-1.5-large | $2.00 | $8.00 | — | 256K |
| jamba-1.5-large@001 | $2.00 | $8.00 | — | 256K |
| jamba-1.5-mini | $0.20 | $0.40 | — | 256K |
| jamba-1.5-mini@001 | $0.20 | $0.40 | — | 256K |
| jamba-large-1.6 | $2.00 | $8.00 | — | 256K |
| jamba-large-1.7 | $2.00 | $8.00 | — | 256K |
| jamba-mini-1.6 | $0.20 | $0.40 | — | 256K |
| jamba-mini-1.7 | $0.20 | $0.40 | — | 256K |

## aihubmix

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| agnes-2.5-flash | $0.03 | $0.15 | — | 512K |
| agnes-2.5-pro | $0.45 | $0.90 | $0.00378 | 1M |
| cc-glm-5.1 | $0.06 | $0.22 | — | 200K |
| claude-fable-5 | $11.00 | $55.00 | $1.10 | 1M |
| claude-haiku-4-5 | $1.10 | $5.50 | $0.11 | 200K |
| claude-opus-4-8-think | $5.00 | $25.00 | $0.50 | 1M |
| claude-opus-5 | $5.00 | $25.00 | $0.50 | 1M |
| claude-sonnet-5 | $2.00 | $10.00 | $0.20 | 1M |
| coding-glm-5.3 | $0.06 | $0.22 | $0.02 | 1.05M |
| coding-kimi-k3 | $0.44 | $1.61 | $0.07 | 1.05M |
| coding-xiaomi-mimo-v2-omni | $0.08 | $0.40 | $0.02 | — |
| coding-xiaomi-mimo-v2.5 | $0.08 | $0.16 | $0.0016 | 1.05M |
| coding-xiaomi-mimo-v2.5-pro | $0.20 | $0.40 | $0.0016 | 1.05M |
| command-a-plus-05-2026 | $2.50 | $10.00 | — | 128K |
| deepseek-v4-flash | $0.14 | $0.28 | $0.03 | 1M |
| deepseek-v4-pro | $1.69 | $3.38 | $0.14 | 1M |
| doubao-seed-2-0-code-preview | $0.48 | $2.41 | $0.10 | 256K |
| doubao-seed-2-0-lite-260428 | $0.09 | $0.54 | $0.02 | 256K |
| doubao-seed-2-0-mini | $0.03 | $0.30 | $0.006027 | 256K |
| doubao-seed-2-0-pro | $0.48 | $2.41 | $0.10 | 256K |
| doubao-seed-2-1-turbo | $0.46 | $2.32 | $0.09 | 256K |
| ernie-5.1 | $0.56 | $2.54 | $0.56 | 119K |
| gemini-3-flash-preview | $0.50 | $3.00 | $0.05 | 1.05M |
| gemini-3-flash-preview-search | $0.50 | $3.00 | $0.05 | 1.05M |
| gemini-3.1-pro-preview | $2.00 | $12.00 | $0.20 | 1.05M |
| gemini-3.1-pro-preview-customtools | $2.00 | $12.00 | $0.20 | 1.05M |
| gemini-3.5-flash-lite | $0.30 | $2.50 | $0.03 | 1.05M |
| gemini-3.7-flash | $0.75 | $3.75 | $0.08 | 1.05M |
| gemma-4-26b-a4b-it | $0.14 | $0.40 | — | 262.14K |
| gemma-4-31b-it | $0.14 | $0.40 | — | 262.14K |
| glm-5.2-fast-preview | $2.25 | $7.89 | $0.56 | 1M |
| glm-5.3 | $1.13 | $3.94 | $0.28 | 1.05M |
| glm-5.3-flash | $0.11 | $0.39 | $0.03 | 1.05M |
| glm-5v-turbo | $0.70 | $3.10 | $0.17 | 200K |
| gpt-5.3-codex | $1.75 | $14.00 | $0.18 | 400K |
| gpt-5.4-high | $2.50 | $15.00 | $0.25 | 1.05M |
| gpt-5.4-low | $2.50 | $15.00 | $0.25 | 1.05M |
| gpt-5.4-mini | $0.75 | $4.50 | $0.08 | 400K |
| gpt-5.4-nano | $0.20 | $1.25 | $0.02 | 400K |
| gpt-5.5 | $5.00 | $30.00 | $0.50 | 1.05M |
| gpt-5.5-pro | $30.00 | $180.00 | — | 1.05M |
| gpt-5.6-luna | $0.20 | $1.20 | $0.02 | 1.05M |
| gpt-5.6-sol-disc | $4.00 | $20.00 | $0.40 | 1.05M |
| gpt-5.6-terra | $2.00 | $12.00 | $0.20 | 1.05M |
| gpt-chat-latest | $5.00 | $30.00 | $0.50 | 400K |
| grok-4-20-non-reasoning | $2.00 | $6.00 | $0.20 | 1M |
| grok-4-20-reasoning | $2.00 | $6.00 | $0.20 | 1M |
| grok-4.6 | $2.00 | $6.00 | $0.50 | 500K |
| grok-build-0.1 | $1.00 | $2.00 | $0.20 | 256K |
| hy3 | $0.16 | $0.62 | $0.04 | 256K |
| hy4-preview | $0.84 | $2.54 | $0.04 | 1.05M |
| kimi-k2.6 | $0.95 | $4.00 | $0.16 | 262.14K |
| kimi-k2.7-code-highspeed | $1.90 | $8.00 | $0.32 | 262.14K |
| kimi-k3 | $3.00 | $15.00 | $0.30 | 1.05M |
| longcat-2.0 | $0.77 | $3.10 | $0.02 | 1M |
| mai-thinking-1 | $2.00 | $8.00 | — | 256K |
| mimo-v2-omni | $0.44 | $2.20 | $0.09 | 256K |
| mimo-v2-pro | $1.10 | $3.30 | $0.22 | 1M |
| minimax-m2.7 | $0.30 | $1.18 | $0.06 | 204.8K |
| minimax-m3 | $0.29 | $1.15 | — | 1M |
| muse-spark-1.2 | $1.38 | $4.68 | — | 1.05M |
| qwen3-coder-next | $0.14 | $0.55 | — | 262.14K |
| qwen3.5-122b-a10b | $0.11 | $0.90 | — | 262.14K |
| qwen3.5-397b-a17b | $0.16 | $0.99 | — | 262.14K |
| qwen3.6-27b | $0.42 | $2.53 | — | 262.14K |
| qwen3.6-35b-a3b | $0.25 | $1.52 | — | 262.14K |
| qwen3.6-max-preview | $1.27 | $7.61 | $0.13 | 262.14K |
| qwen3.7-plus | $0.28 | $1.13 | $0.06 | 1M |
| qwen3.8-2.4t-a95b | $2.00 | $6.00 | $0.50 | 1M |
| qwen3.8-flash | $0.11 | $0.38 | $0.01 | 1M |
| qwen3.8-max | $1.69 | $5.07 | $0.17 | 1M |
| step-3.7-flash | $0.22 | $1.32 | $0.04 | 256K |

## aion-labs

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| aionlabs: aion 3.5 | $3.00 | $6.00 | $0.75 | 262.14K |
| aionlabs: aion 3.5 mini | $0.70 | $1.40 | $0.18 | 262.14K |
| aionlabs: aion-2.0 | $0.80 | $1.60 | $0.20 | 131.07K |
| aionlabs: aion-3.0 | $3.00 | $6.00 | $0.75 | 131.07K |
| aionlabs: aion-3.0-mini | $0.70 | $1.40 | $0.18 | 131.07K |
| aionlabs: aion-rp 1.0 (8b) | $0.80 | $1.60 | — | 32.77K |

## amazon

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| nova 2 lite | $0.30 | $2.50 | — | 1M |
| nova lite 1.0 | $0.06 | $0.24 | — | 300K |
| nova micro 1.0 | $0.04 | $0.14 | — | 128K |
| nova premier 1.0 | $2.50 | $12.50 | $0.62 | 1M |
| nova pro 1.0 | $0.80 | $3.20 | — | 300K |

## amazon_nova

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| nova-lite-v1 | $0.06 | $0.24 | — | 300K |
| nova-micro-v1 | $0.04 | $0.14 | — | 128K |
| nova-premier-v1 | $2.50 | $12.50 | — | 1M |
| nova-pro-v1 | $0.80 | $3.20 | — | 300K |

## anthracite-org

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| magnum v4 72b | $2.50 | $5.00 | — | 32.77K |

## anthropic

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| claude fable 5 (batch) | $5.00 | $25.00 | $0.50 | 1M |
| claude fable 5.1 (batch) | $5.00 | $25.00 | $0.12 | 1M |
| claude fable latest | $10.00 | $50.00 | $0.25 | 1M |
| claude haiku 4.5 (batch) | $0.50 | $2.50 | $0.05 | 200K |
| claude haiku 5.5 (batch) | $0.05 | $0.25 | $0.005 | 1M |
| claude haiku latest | $0.10 | $0.50 | $0.01 | 1M |
| claude opus 4.1 | $15.00 | $75.00 | $1.50 | 200K |
| claude opus 4.1 (batch) | $7.50 | $37.50 | $0.75 | 200K |
| claude opus 4.5 (batch) | $2.50 | $12.50 | $0.25 | 200K |
| claude opus 4.6 (batch) | $2.50 | $12.50 | $0.25 | 1M |
| claude opus 4.7 (batch) | $2.50 | $12.50 | $0.25 | 1M |
| claude opus 4.8 (batch) | $2.50 | $12.50 | $0.25 | 1M |
| claude opus 5 (batch) | $2.50 | $12.50 | $0.25 | 1M |
| claude opus 5.5 (batch) | $2.00 | $10.00 | $0.10 | 1M |
| claude opus latest | $4.00 | $20.00 | $0.20 | 1M |
| claude sonnet 4.5 (batch) | $1.50 | $7.50 | $0.15 | 1M |
| claude sonnet 4.6 (batch) | $1.50 | $7.50 | $0.15 | 1M |
| claude sonnet 5 (batch) | $1.00 | $5.00 | $0.10 | 1M |
| claude sonnet 5.5 (batch) | $1.00 | $5.00 | $0.05 | 1M |
| claude sonnet latest | $2.00 | $10.00 | $0.10 | 1M |
| claude-fable-5 | $10.00 | $50.00 | $1.00 | 1M |
| claude-fable-5-1 | $10.00 | $50.00 | $0.25 | 1M |
| claude-haiku-4-5 | $1.00 | $5.00 | $0.10 | 200K |
| claude-haiku-4-5-20251001 | $1.00 | $5.00 | $0.10 | 200K |
| claude-haiku-5-5 | $0.10 | $0.50 | $0.01 | 1M |
| claude-mythos-5 | $10.00 | $50.00 | $1.00 | 1M |
| claude-mythos-5-1 | $10.00 | $50.00 | $0.25 | 1M |
| claude-mythos-preview | $10.00 | $50.00 | $1.00 | 1M |
| claude-opus-4-5 | $5.00 | $25.00 | $0.50 | 200K |
| claude-opus-4-5-20251101 | $5.00 | $25.00 | $0.50 | 200K |
| claude-opus-4-6 | $5.00 | $25.00 | $0.50 | 1M |
| claude-opus-4-6-20260205 | $5.00 | $25.00 | $0.50 | 1M |
| claude-opus-4-7 | $5.00 | $25.00 | $0.50 | 1M |
| claude-opus-4-7-20260416 | $5.00 | $25.00 | $0.50 | 1M |
| claude-opus-4-8 | $5.00 | $25.00 | $0.50 | 1M |
| claude-opus-5 | $5.00 | $25.00 | $0.50 | 1M |
| claude-opus-5-5 | $4.00 | $20.00 | $0.20 | 1M |
| claude-sonnet-4-5 | $3.00 | $15.00 | $0.30 | 200K |
| claude-sonnet-4-5-20250929 | $3.00 | $15.00 | $0.30 | 200K |
| claude-sonnet-4-6 | $3.00 | $15.00 | $0.30 | 1M |
| claude-sonnet-5 | $2.00 | $10.00 | $0.20 | 1M |
| claude-sonnet-5-5 | $2.00 | $10.00 | $0.10 | 1M |

## anyscale

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| codellama-34b-instruct-hf | $1.00 | $1.00 | — | 4.1K |
| codellama-70b-instruct-hf | $1.00 | $1.00 | — | 4.1K |
| gemma-7b-it | $0.15 | $0.15 | — | 8.19K |
| llama-2-7b-chat-hf | $0.15 | $0.15 | — | 4.1K |
| llama-2-13b-chat-hf | $0.25 | $0.25 | — | 4.1K |
| llama-2-70b-chat-hf | $1.00 | $1.00 | — | 4.1K |
| meta-llama-3-8b-instruct | $0.15 | $0.15 | — | 8.19K |
| meta-llama-3-70b-instruct | $1.00 | $1.00 | — | 8.19K |
| mistral-7b-instruct-v0.1 | $0.15 | $0.15 | — | 16.38K |
| mixtral-8x7b-instruct-v0.1 | $0.15 | $0.15 | — | 16.38K |
| mixtral-8x22b-instruct-v0.1 | $0.90 | $0.90 | — | 65.54K |
| zephyr-7b-beta | $0.15 | $0.15 | — | 16.38K |

## azure

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| ada | $0.11 | $0.00 | — | 8.19K |
| chat-latest | $5.00 | $30.00 | $0.50 | 272K |
| codex-mini | $1.50 | $6.00 | $0.38 | 200K |
| command-r-plus | $3.00 | $15.00 | — | 128K |
| computer-use-preview | $3.00 | $12.00 | — | 8.19K |
| dall-e-2 | — | $0.00 | — | — |
| dall-e-3 | — | $0.00 | — | — |
| gpt-3.5-turbo | $0.50 | $1.50 | — | 4.1K |
| gpt-4 | $30.00 | $60.00 | — | 8.19K |
| gpt-4-32k | $60.00 | $120.00 | — | 32.77K |
| gpt-4-32k-0613 | $60.00 | $120.00 | — | 32.77K |
| gpt-4-0125-preview | $10.00 | $30.00 | — | 128K |
| gpt-4-0613 | $30.00 | $60.00 | — | 8.19K |
| gpt-4-1106-preview | $10.00 | $30.00 | — | 128K |
| gpt-4-turbo | $11.00 | $33.00 | — | 128K |
| gpt-4-turbo-2024-04-09 | $11.00 | $33.00 | — | 128K |
| gpt-4-turbo-vision-preview | $11.00 | $33.00 | — | 128K |
| gpt-4.1 | $2.20 | $8.80 | $0.55 | — |
| gpt-4.1-2025-04-14 | $2.00 | $8.00 | $0.50 | 1.05M |
| gpt-4.1-mini | $0.44 | $1.76 | $0.11 | — |
| gpt-4.1-mini-2025-04-14 | $0.40 | $1.60 | $0.10 | 1.05M |
| gpt-4.1-nano | $0.11 | $0.44 | $0.03 | — |
| gpt-4.1-nano-2025-04-14 | $0.10 | $0.40 | $0.02 | 1.05M |
| gpt-4.5-preview | $75.00 | $150.00 | $37.50 | 128K |
| gpt-4o | $2.75 | $11.00 | $1.38 | 128K |
| gpt-4o-2024-05-13 | $5.50 | $16.50 | — | 128K |
| gpt-4o-2024-08-06 | $2.75 | $11.00 | $1.38 | 128K |
| gpt-4o-2024-11-20 | $2.75 | $11.00 | $1.38 | 128K |
| gpt-4o-audio-preview-2024-12-17 | $2.50 | $10.00 | — | 128K |
| gpt-4o-mini | $0.16 | $0.66 | $0.08 | 128K |
| gpt-4o-mini-2024-07-18 | $0.16 | $0.66 | $0.08 | 128K |
| gpt-4o-mini-audio-preview-2024-12-17 | $0.15 | $0.60 | — | 128K |
| gpt-4o-mini-realtime-preview-2024-12-17 | $0.66 | $2.64 | $0.33 | 128K |
| gpt-4o-mini-transcribe | $1.25 | $5.00 | — | 16K |
| gpt-4o-mini-tts | $0.60 | $10.00 | — | — |
| gpt-4o-realtime-preview-2024-10-01 | $5.50 | $22.00 | $2.75 | 128K |
| gpt-4o-realtime-preview-2024-12-17 | $5.50 | $22.00 | $2.75 | 16K |
| gpt-4o-transcribe | $2.50 | $10.00 | — | 16K |
| gpt-4o-transcribe-diarize | $2.50 | $10.00 | — | 16K |
| gpt-5 | $1.38 | $11.00 | $0.14 | — |
| gpt-5-2025-08-07 | $1.38 | $11.00 | $0.14 | 272K |
| gpt-5-chat | $1.25 | $10.00 | $0.12 | 128K |
| gpt-5-codex | $1.38 | $11.00 | $0.14 | — |
| gpt-5-mini | $0.28 | $2.20 | $0.03 | — |
| gpt-5-mini-2025-08-07 | $0.28 | $2.20 | $0.03 | 272K |
| gpt-5-nano | $0.06 | $0.44 | $0.0055 | — |
| gpt-5-nano-2025-08-07 | $0.06 | $0.44 | $0.0055 | 272K |
| gpt-5-pro | $16.50 | $132.00 | — | — |
| gpt-5.1 | $1.38 | $11.00 | $0.14 | 272K |
| gpt-5.1-2025-11-13 | $1.25 | $10.00 | $0.12 | 272K |
| gpt-5.1-chat | $1.38 | $11.00 | $0.14 | 111.62K |
| gpt-5.1-codex | $1.38 | $11.00 | $0.14 | 272K |
| gpt-5.1-codex-2025-11-13 | $1.25 | $10.00 | $0.12 | 272K |
| gpt-5.1-codex-max | $1.38 | $11.00 | $0.14 | — |
| gpt-5.1-codex-mini | $0.28 | $2.20 | $0.03 | 272K |
| gpt-5.1-codex-mini-2025-11-13 | $0.25 | $2.00 | $0.02 | 272K |
| gpt-5.2 | $1.92 | $15.40 | $0.19 | — |
| gpt-5.2-2025-12-11 | $1.75 | $14.00 | $0.18 | 272K |
| gpt-5.2-chat | $1.92 | $15.40 | $0.19 | 111.62K |
| gpt-5.2-codex | $1.92 | $15.40 | $0.19 | — |
| gpt-5.2-pro | $23.10 | $184.80 | — | — |
| gpt-5.2-pro-2025-12-11 | $21.00 | $168.00 | — | 272K |
| gpt-5.3-chat | $1.92 | $15.40 | $0.19 | 111.62K |
| gpt-5.3-codex | $1.92 | $15.40 | $0.19 | — |
| gpt-5.4 | $2.75 | $16.50 | $0.28 | 922K |
| gpt-5.4-2026-03-05 | $2.75 | $16.50 | $0.28 | 922K |
| gpt-5.4-mini | $0.82 | $4.95 | $0.08 | — |
| gpt-5.4-mini-2026-03-17 | $0.75 | $4.50 | $0.08 | 272K |
| gpt-5.4-nano | $0.22 | $1.38 | $0.02 | — |
| gpt-5.4-nano-2026-03-17 | $0.20 | $1.25 | $0.02 | 272K |
| gpt-5.4-pro | $30.00 | $180.00 | $3.00 | 922K |
| gpt-5.4-pro-2026-03-05 | $30.00 | $180.00 | $3.00 | 922K |
| gpt-5.5 | $5.50 | $33.00 | $0.55 | 922K |
| gpt-5.5-2026-04-23 | $5.50 | $33.00 | $0.55 | 922K |
| gpt-5.5-2026-04-24 | $5.50 | $33.00 | $0.55 | 922K |
| gpt-5.5-pro | $30.00 | $180.00 | $3.00 | 1.05M |
| gpt-5.5-pro-2026-04-23 | $30.00 | $180.00 | $3.00 | 1.05M |
| gpt-5.6 | $4.40 | $22.00 | $0.44 | 922K |
| gpt-5.6-luna | $0.22 | $1.32 | $0.02 | 922K |
| gpt-5.6-luna-2026-07-09 | $0.20 | $1.20 | $0.02 | 922K |
| gpt-5.6-sol | $4.40 | $22.00 | $0.44 | 922K |
| gpt-5.6-sol-2026-07-09 | $4.00 | $20.00 | $0.40 | 922K |
| gpt-5.6-terra | $2.20 | $13.20 | $0.22 | 922K |
| gpt-5.6-terra-2026-07-09 | $2.00 | $12.00 | $0.20 | 922K |
| gpt-6-astra | $12.00 | $60.00 | $1.20 | 922K |
| gpt-6-astra-2026-09-03 | $10.00 | $50.00 | $1.00 | 922K |
| gpt-6-luna | $0.12 | $0.60 | $0.01 | 922K |
| gpt-6-luna-2026-09-22 | $0.10 | $0.50 | $0.01 | 922K |
| gpt-6-sol | $2.40 | $12.00 | $0.24 | 922K |
| gpt-6-sol-2026-09-22 | $2.00 | $10.00 | $0.20 | 922K |
| gpt-6.1-sol | $2.40 | $12.00 | $0.12 | 922K |
| gpt-6.1-sol-2026-09-29 | $2.00 | $10.00 | $0.10 | 922K |
| gpt-35-turbo | $0.50 | $1.50 | — | 4.1K |
| gpt-35-turbo-16k | $3.00 | $4.00 | — | 16.39K |
| gpt-35-turbo-16k-0613 | $3.00 | $4.00 | — | 16.39K |
| gpt-audio | $2.50 | $10.00 | — | 128K |
| gpt-audio-1.5 | $2.50 | $10.00 | — | 128K |
| gpt-audio-1.5-2026-02-23 | $2.50 | $10.00 | — | 128K |
| gpt-audio-2025-08-28 | $2.50 | $10.00 | — | 128K |
| gpt-audio-mini | $0.60 | $2.40 | — | 128K |
| gpt-audio-mini-2025-10-06 | $0.60 | $2.40 | — | 128K |
| gpt-chat-latest | $5.00 | $30.00 | $0.50 | 128K |
| gpt-image-1 | $5.00 | — | $1.25 | — |
| gpt-image-1-mini | $2.00 | — | $0.20 | — |
| gpt-image-1.5 | $5.00 | $10.00 | $1.25 | — |
| gpt-image-1.5-2025-12-16 | $5.00 | $10.00 | $1.25 | — |
| gpt-image-2 | $5.00 | — | $1.25 | — |
| gpt-image-2-2026-04-21 | $5.00 | — | $1.25 | — |
| gpt-image-2.5-flare | $5.00 | — | $1.25 | — |
| gpt-image-2.5-sunburst | $5.00 | — | $1.25 | — |
| gpt-realtime | $4.00 | $16.00 | $0.40 | 32K |
| gpt-realtime-1.5 | $4.00 | $16.00 | $0.40 | 32K |
| gpt-realtime-1.5-2026-02-23 | $4.00 | $16.00 | $0.40 | 32K |
| gpt-realtime-2 | $4.00 | $24.00 | $0.40 | 32K |
| gpt-realtime-2.1 | $4.00 | $24.00 | $0.40 | 32K |
| gpt-realtime-2.1-mini | $0.60 | $2.40 | $0.06 | 32K |
| gpt-realtime-2025-08-28 | $4.00 | $16.00 | $0.40 | 32K |
| gpt-realtime-mini | $0.60 | $2.40 | $0.06 | 32K |
| gpt-realtime-mini-2025-10-06 | $0.60 | $2.40 | $0.06 | 32K |
| mistral-large-2402 | $8.00 | $24.00 | — | 32K |
| mistral-large-latest | $8.00 | $24.00 | — | 32K |
| model-router | $0.14 | $0.00 | — | 200K |
| o1 | $16.50 | $66.00 | $8.25 | 200K |
| o1-2024-12-17 | $16.50 | $66.00 | $8.25 | 200K |
| o1-mini | $1.21 | $4.84 | $0.60 | — |
| o1-mini-2024-09-12 | $1.21 | $4.84 | $0.60 | 128K |
| o1-preview | $16.50 | $66.00 | $8.25 | 128K |
| o3 | $2.20 | $8.80 | $0.55 | 200K |
| o3-2025-04-16 | $2.20 | $8.80 | $0.55 | 200K |
| o3-deep-research | $11.00 | $44.00 | $2.75 | — |
| o3-mini | $1.21 | $4.84 | $0.60 | 200K |
| o3-mini-2025-01-31 | $1.21 | $4.84 | $0.60 | 200K |
| o3-pro | $20.00 | $80.00 | — | 200K |
| o3-pro-2025-06-10 | $20.00 | $80.00 | — | 200K |
| o4-mini | $1.21 | $4.84 | $0.30 | 200K |
| o4-mini-2025-04-16 | $1.21 | $4.84 | $0.30 | 200K |
| text-embedding-3-large | $0.14 | $0.00 | — | 8.19K |
| text-embedding-3-small | $0.02 | $0.00 | — | 8.19K |
| text-embedding-ada-002 | $0.11 | $0.00 | — | 8.19K |

## azure_ai

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| claude-fable-5 | $10.00 | $50.00 | $1.00 | 1M |
| claude-fable-5-1 | $10.00 | $50.00 | $0.25 | 1M |
| claude-haiku-4-5 | $1.00 | $5.00 | $0.10 | 200K |
| claude-haiku-5-5 | $0.10 | $0.50 | $0.01 | 1M |
| claude-opus-4-5 | $5.00 | $25.00 | $0.50 | 200K |
| claude-opus-4-6 | $5.00 | $25.00 | $0.50 | 1M |
| claude-opus-4-7 | $5.00 | $25.00 | $0.50 | 1M |
| claude-opus-4-8 | $5.00 | $25.00 | $0.50 | 1M |
| claude-opus-5 | $5.00 | $25.00 | $0.50 | 1M |
| claude-opus-5-5 | $4.00 | $20.00 | $0.20 | 1M |
| claude-opus-5-5-fast | $8.00 | $40.00 | $0.40 | 1M |
| claude-sonnet-4-5 | $3.00 | $15.00 | $0.30 | 200K |
| claude-sonnet-4-6 | $3.00 | $15.00 | $0.30 | 1M |
| claude-sonnet-5 | $2.00 | $10.00 | $0.20 | 1M |
| claude-sonnet-5-5 | $2.00 | $10.00 | $0.20 | 1M |
| codestral-2501 | $0.30 | $0.90 | — | 256K |
| codex-mini | $1.50 | $6.00 | $0.38 | 200K |
| cohere-command-a | $2.50 | $10.00 | — | 131.07K |
| cohere-command-a-plus-05-2026 | $0.80 | $3.20 | — | 128K |
| cohere-embed-v3-english | $0.10 | $0.00 | — | 512 |
| cohere-embed-v3-multilingual | $0.10 | $0.00 | — | 512 |
| cohere-embed-v5-fast | $0.08 | $0.00 | — | 128K |
| cohere-embed-v5-pro | $0.12 | $0.00 | — | 128K |
| cohere-rerank-v3-english | $0.00 | $0.00 | — | 4.1K |
| cohere-rerank-v3-multilingual | $0.00 | $0.00 | — | 4.1K |
| cohere-rerank-v4.0-fast | $0.00 | $0.00 | — | 32.77K |
| cohere-rerank-v4.0-pro | $0.00 | $0.00 | — | 32.77K |
| deepseek-r1 | $1.35 | $5.40 | — | — |
| deepseek-v3 | $1.14 | $4.56 | — | 128K |
| deepseek-v3-0324 | $1.14 | $4.56 | — | — |
| deepseek-v3.1 | $1.23 | $4.94 | — | — |
| deepseek-v3.2 | $0.58 | $1.68 | — | 128K |
| deepseek-v3.2-speciale | $0.58 | $1.68 | — | 128K |
| deepseek-v4-flash | $0.19 | $0.51 | $0.03 | 1M |
| deepseek-v4-flash-0731 | $0.44 | $1.32 | $0.01 | 1M |
| deepseek-v4-pro | $1.74 | $3.48 | $0.14 | 1M |
| deepseek-v4.1-flash | $0.30 | $1.20 | $0.006 | 1M |
| embed-v-4-0 | $0.12 | $0.00 | — | 128K |
| fw-deepseek-v3.2 | $0.62 | $1.85 | $0.31 | 163.84K |
| fw-deepseek-v4-flash | $0.15 | $0.31 | $0.03 | 1M |
| fw-deepseek-v4-pro | $1.92 | $3.83 | $0.16 | 1M |
| fw-deepseek-v4.1-flash | $0.38 | $1.50 | $0.008 | 1M |
| fw-glm-5 | $1.10 | $3.52 | $0.22 | 200K |
| fw-glm-5.1 | $1.54 | $4.84 | $0.29 | 202.8K |
| fw-glm-5.2 | $1.54 | $4.84 | $0.15 | 1.05M |
| fw-glm-5.2-fast | $2.31 | $7.26 | $0.23 | 1.05M |
| fw-glm-5.3 | $1.75 | $5.50 | $0.32 | 1.05M |
| fw-glm-5.3-flash | $0.19 | $0.62 | $0.04 | 1.05M |
| fw-gpt-oss-120b | $0.16 | $0.66 | $0.08 | 131.07K |
| fw-inkling | $1.10 | $4.46 | $0.19 | 1.05M |
| fw-kimi-k2.5 | $0.66 | $3.30 | $0.11 | 262.14K |
| fw-kimi-k2.6 | $1.04 | $4.40 | $0.18 | 262.14K |
| fw-kimi-k2.7-code | $1.05 | $4.40 | $0.21 | 262.14K |
| fw-kimi-k3 | $3.00 | $15.00 | $0.30 | 1.05M |
| fw-minimax-m2.5 | $0.33 | $1.32 | $0.03 | 1M |
| fw-minimax-m3 | $0.33 | $1.32 | $0.07 | 512K |
| fw-nemotron-3-ultra-nvfp4 | $0.66 | $2.64 | $0.13 | 262.14K |
| fw-nemotron-lightning-3.5-30b-a3b | $0.06 | $0.22 | $0.01 | 262.14K |
| gpt-5.4 | $2.50 | $15.00 | $0.25 | 922K |
| gpt-5.4-2026-03-05 | $2.50 | $15.00 | $0.25 | 922K |
| gpt-5.4-mini | $0.75 | $4.50 | $0.08 | 272K |
| gpt-5.4-mini-2026-03-17 | $0.75 | $4.50 | $0.08 | 272K |
| gpt-5.4-nano | $0.20 | $1.25 | $0.02 | 272K |
| gpt-5.4-nano-2026-03-17 | $0.20 | $1.25 | $0.02 | 272K |
| gpt-5.4-pro | $30.00 | $180.00 | $3.00 | 922K |
| gpt-5.4-pro-2026-03-05 | $30.00 | $180.00 | $3.00 | 922K |
| gpt-5.5 | $5.00 | $30.00 | $0.50 | 922K |
| gpt-5.5-2026-04-23 | $5.00 | $30.00 | $0.50 | 922K |
| gpt-5.5-2026-04-24 | $5.00 | $30.00 | $0.50 | 922K |
| gpt-6-astra | $10.00 | $50.00 | $1.00 | 922K |
| gpt-6-luna | $0.10 | $0.50 | $0.01 | 922K |
| gpt-6-sol | $2.00 | $10.00 | $0.20 | 922K |
| gpt-6.1-sol | $2.00 | $10.00 | $0.10 | 922K |
| gpt-chat-latest | $5.00 | $30.00 | $0.50 | 128K |
| gpt-image-2 | $5.00 | — | $1.25 | — |
| gpt-oss-120b | $0.15 | $0.60 | — | 131.07K |
| grok-3 | $3.00 | $15.00 | — | — |
| grok-3-mini | $0.25 | $1.27 | — | — |
| grok-4 | $3.00 | $15.00 | — | 262K |
| grok-4-1-fast-non-reasoning | $0.20 | $0.50 | — | 128K |
| grok-4-1-fast-reasoning | $0.20 | $0.50 | — | 128K |
| grok-4-20-non-reasoning | $1.25 | $2.50 | $1.25 | 262K |
| grok-4-20-reasoning | $1.25 | $2.50 | $1.25 | 262K |
| grok-4-fast-non-reasoning | $0.20 | $0.50 | — | — |
| grok-4-fast-reasoning | $0.20 | $0.50 | — | — |
| grok-4.3 | $1.25 | $2.50 | $0.20 | 200K |
| grok-4.6 | $2.00 | $6.00 | $0.50 | 200K |
| grok-4.7 | $2.00 | $6.00 | $0.50 | 500K |
| grok-code-fast-1 | $0.20 | $1.50 | — | 256K |
| jais-30b-chat | $3,200.00 | $9,710.00 | — | 8.19K |
| jamba-instruct | $0.50 | $0.70 | — | 70K |
| kimi-k2-thinking | $0.60 | $2.50 | — | 262.14K |
| kimi-k2.5 | $0.60 | $3.00 | $0.10 | 262.14K |
| kimi-k2.6 | $0.95 | $4.00 | $0.16 | 262.14K |
| kimi-k2.7-code | $0.95 | $4.00 | $0.19 | 262.14K |
| llama-3.3-70b-instruct | $0.71 | $0.71 | — | 128K |
| llama-4-maverick-17b-128e-instruct-fp8 | $0.25 | $1.00 | — | 1M |
| llama-4-scout-17b-16e-instruct | $0.20 | $0.78 | — | 10M |
| mai-code-1.1-flash | $0.20 | $1.20 | $0.02 | 256K |
| mai-cyber-1-flash | $0.60 | $3.50 | $0.06 | 256K |
| mai-ds-r1 | $1.35 | $5.40 | — | 128K |
| mai-image-2.5 | $5.00 | — | — | 32K |
| mai-image-2.5-flash | $1.75 | — | — | 32K |
| mai-image-2.5-pro | $5.00 | — | — | 32K |
| mai-image-2.6 | $5.00 | — | — | 32K |
| mai-image-2.6-flash | $1.75 | — | — | 32K |
| mai-thinking-1 | $2.00 | $8.00 | $0.20 | 256K |
| meta-llama-3-70b-instruct | $1.10 | $0.37 | — | 8.19K |
| meta-llama-3.1-70b-instruct | $2.68 | $3.54 | — | 128K |
| microsoft-decision-1 | $0.04 | $0.00 | — | 32.77K |
| ministral-3b | $0.04 | $0.04 | — | 128K |
| mistral-large | $4.00 | $12.00 | — | 32K |
| mistral-large-3 | $0.50 | $1.50 | — | 256K |
| mistral-large-2407 | $2.00 | $6.00 | — | 128K |
| mistral-large-latest | $2.00 | $6.00 | — | 128K |
| mistral-medium-3-5 | $1.50 | $7.50 | — | 128K |
| mistral-medium-2505 | $0.40 | $2.00 | — | 131.07K |
| mistral-nemo | $0.15 | $0.15 | — | 131.07K |
| mistral-small | $1.00 | $3.00 | — | 32K |
| mistral-small-2503 | $0.10 | $0.30 | — | 128K |
| model-router | $0.14 | $0.00 | — | 200K |
| phi-3-medium-4k-instruct | $0.17 | $0.68 | — | 4.1K |
| phi-3-medium-128k-instruct | $0.17 | $0.68 | — | 128K |
| phi-3-mini-4k-instruct | $0.13 | $0.52 | — | 4.1K |
| phi-3-mini-128k-instruct | $0.13 | $0.52 | — | 128K |
| phi-3-small-8k-instruct | $0.15 | $0.60 | — | 8.19K |
| phi-3-small-128k-instruct | $0.15 | $0.60 | — | 128K |
| phi-3.5-mini-instruct | $0.13 | $0.52 | — | 128K |
| phi-3.5-moe-instruct | $0.16 | $0.64 | — | 128K |
| phi-3.5-vision-instruct | $0.13 | $0.52 | — | 128K |
| phi-4 | $0.12 | $0.50 | — | 16.38K |
| phi-4-mini-instruct | $0.08 | $0.30 | — | 131.07K |
| phi-4-mini-reasoning | $0.08 | $0.30 | — | 131.07K |
| phi-4-multimodal-instruct | $0.08 | $0.32 | — | 131.07K |
| phi-4-reasoning | $0.12 | $0.50 | — | 32.77K |

## azure_text

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| gpt-3.5-turbo-instruct-0914 | $1.65 | $2.20 | — | 4.1K |
| gpt-35-turbo-instruct | $1.65 | $2.20 | — | 4.1K |
| gpt-35-turbo-instruct-0914 | $1.65 | $2.20 | — | 4.1K |

## baseten

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| baseten-elephant-9b-latest | $0.00 | $0.00 | — | 16.38K |
| baseten-mammoth-27b-latest | $0.00 | $0.00 | — | 16.38K |
| beam-1.0 | $0.40 | $1.20 | $0.04 | 1.05M |
| deepseek-v3-0324 | $0.77 | $0.77 | — | — |
| deepseek-v3.1 | $0.50 | $1.50 | — | — |
| deepseek-v4-flash-0731 | $0.13 | $0.26 | $0.03 | 1.05M |
| deepseek-v4-pro | $1.74 | $3.48 | $0.14 | 1.05M |
| deepseek-v4-pro-0813 | $1.32 | $3.96 | $0.13 | 1.05M |
| deepseek-v4.1-flash | $0.30 | $1.20 | $0.007 | 1.05M |
| deepseek-v4.1-flash-1017 | $0.30 | $1.20 | $0.007 | 1.05M |
| deepseek-v4.1-flash-1017-fast | $0.60 | $2.40 | $0.01 | 1.05M |
| deepseek-v4.1-flash-fast | $0.60 | $2.40 | $0.01 | 1.05M |
| glm-4.6 | $0.60 | $2.20 | — | — |
| glm-4.7 | $0.60 | $2.20 | $0.12 | 200K |
| glm-5 | $0.95 | $3.15 | — | — |
| glm-5.2 | $1.40 | $4.40 | $0.14 | 1.05M |
| glm-5.2-fast | $2.10 | $6.60 | $0.21 | 1.05M |
| glm-5.3 | $1.40 | $4.40 | $0.14 | 1.05M |
| glm-5.3-fast | $2.10 | $6.60 | $0.21 | 1.05M |
| glm-5.3-flash | $0.15 | $0.50 | $0.03 | 1.05M |
| gpt-oss-120b | $0.10 | $0.50 | $0.10 | 128.07K |
| inkling | $1.00 | $4.05 | $0.17 | 1.05M |
| inkling-small | $0.50 | $1.20 | $0.10 | 1.05M |
| kimi-k2-instruct-0905 | $0.60 | $2.50 | — | — |
| kimi-k2-thinking | $0.60 | $2.50 | — | — |
| kimi-k2.5 | $0.60 | $3.00 | — | — |
| kimi-k2.6 | $0.95 | $4.00 | $0.16 | 262K |
| kimi-k2.7-code | $0.95 | $4.00 | $0.16 | 262K |
| kimi-k3 | $3.00 | $15.00 | $0.30 | 1.05M |
| minimax-m2.5 | $0.30 | $1.20 | — | — |
| muse-spark-open | $1.25 | $4.25 | $0.15 | 1.05M |
| nemotron-120b-a12b | $0.30 | $0.75 | — | — |
| nvidia-nemotron-3-ultra-550b-a55b | $0.60 | $2.40 | $0.12 | 202.8K |
| nvidia-nemotron-3.5-super-vl-120b-a12b | $0.20 | $0.50 | $0.04 | 1.05M |

## bedrock

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| ai21.j2-mid-v1 | $12.50 | $12.50 | — | 8.19K |
| ai21.j2-ultra-v1 | $18.80 | $18.80 | — | 8.19K |
| ai21.jamba-1-5-large-v1:0 | $2.00 | $8.00 | — | 256K |
| ai21.jamba-1-5-mini-v1:0 | $0.20 | $0.40 | — | 256K |
| ai21.jamba-instruct-v1:0 | $0.50 | $0.70 | — | 70K |
| amazon.nova-2-5-sonic | $0.33 | $2.75 | — | 256K |
| amazon.nova-2-multimodal-embeddings-v1:0 | $0.14 | $0.00 | — | 8.17K |
| amazon.nova-2-sonic-v1:0 | $0.33 | $2.75 | — | 1M |
| amazon.nova-lite-v1:0 | $0.07 | $0.29 | $0.02 | 300K |
| amazon.nova-micro-v1:0 | $0.04 | $0.17 | $0.01 | 128K |
| amazon.nova-pro-v1:0 | $0.96 | $3.84 | $0.24 | 300K |
| amazon.rerank-v1:0 | $0.00 | $0.00 | — | 32K |
| amazon.titan-embed-g1-text-02 | $0.10 | $0.00 | — | 8.19K |
| amazon.titan-embed-image-v1 | $0.80 | $0.00 | — | 128 |
| amazon.titan-embed-text-v1 | $0.10 | $0.00 | — | 8.19K |
| amazon.titan-embed-text-v2:0 | $0.02 | $0.00 | — | 8.19K |
| amazon.titan-text-express-v1 | $0.20 | $0.60 | — | 42K |
| amazon.titan-text-lite-v1 | $0.15 | $0.20 | — | 42K |
| amazon.titan-text-premier-v1:0 | $0.50 | $1.50 | — | 42K |
| anthropic.claude-3-5-haiku-20241022-v1:0 | $0.80 | $4.00 | $0.08 | 200K |
| anthropic.claude-3-5-sonnet-20240620-v1:0 | $3.00 | $15.00 | $0.30 | 200K |
| anthropic.claude-3-5-sonnet-20241022-v2:0 | $3.00 | $15.00 | $0.30 | 200K |
| anthropic.claude-3-7-sonnet-20240620-v1:0 | $3.60 | $18.00 | $0.36 | 200K |
| anthropic.claude-3-opus-20240229-v1:0 | $15.00 | $75.00 | $1.50 | 200K |
| anthropic.claude-fable-5-1 | $12.00 | $60.00 | $0.30 | 1M |
| anthropic.claude-haiku-4-5-20251001-v1:0 | $1.20 | $6.00 | $0.12 | 200K |
| anthropic.claude-haiku-5-5 | $0.12 | $0.60 | $0.01 | 1M |
| anthropic.claude-instant-v1 | $0.80 | $2.40 | — | 100K |
| anthropic.claude-mythos-preview | $27.50 | $137.50 | $2.75 | 1M |
| anthropic.claude-opus-4-8 | $6.00 | $30.00 | $0.60 | 1M |
| anthropic.claude-opus-5 | $6.00 | $30.00 | $0.60 | 1M |
| anthropic.claude-opus-5-5 | $4.80 | $24.00 | $0.24 | 1M |
| anthropic.claude-sonnet-4-5-20250929-v1:0 | $3.60 | $18.00 | $0.36 | 200K |
| anthropic.claude-sonnet-5 | $2.40 | $12.00 | $0.24 | 1M |
| anthropic.claude-sonnet-5-5 | $2.40 | $12.00 | $0.12 | 1M |
| anthropic.claude-v1 | $8.00 | $24.00 | — | 100K |
| anthropic.claude-v2:1 | $8.00 | $24.00 | — | 100K |
| claude-fable-5 | $10.00 | $50.00 | $1.00 | 1M |
| claude-fable-5-1 | $10.00 | $50.00 | $0.25 | 1M |
| claude-haiku-4-5 | $1.00 | $5.00 | $0.10 | 200K |
| claude-haiku-5-5 | $0.10 | $0.50 | $0.01 | 1M |
| claude-opus-4-5 | $5.00 | $25.00 | $0.50 | 200K |
| claude-opus-4-6 | $5.00 | $25.00 | $0.50 | 1M |
| claude-opus-4-7 | $5.00 | $25.00 | $0.50 | 1M |
| claude-opus-4-8 | $5.00 | $25.00 | $0.50 | 1M |
| claude-opus-5 | $5.00 | $25.00 | $0.50 | 1M |
| claude-opus-5-5 | $4.00 | $20.00 | $0.20 | 1M |
| claude-sonnet-4-5 | $3.00 | $15.00 | $0.30 | 200K |
| claude-sonnet-4-5-20250929-v1:0 | $3.60 | $18.00 | $0.36 | 200K |
| claude-sonnet-4-6 | $3.00 | $15.00 | $0.30 | 1M |
| claude-sonnet-5 | $2.00 | $10.00 | $0.20 | 1M |
| claude-sonnet-5-5 | $2.00 | $10.00 | $0.10 | 1M |
| cohere.command-light-text-v14 | $0.30 | $0.60 | — | 4.1K |
| cohere.command-text-v14 | $1.00 | $2.00 | — | 4.1K |
| cohere.embed-english-v3 | $0.10 | $0.00 | — | 512 |
| cohere.embed-multilingual-v3 | $0.10 | $0.00 | — | 512 |
| cohere.embed-v4:0 | $0.12 | $0.00 | — | 128K |
| cohere.rerank-v3-5:0 | $0.00 | $0.00 | — | 4.1K |
| deepseek.v3.2 | $0.74 | $2.22 | — | 163.84K |
| eu.anthropic.claude-3-5-haiku-20241022-v1:0 | $0.80 | $4.00 | $0.08 | 200K |
| eu.anthropic.claude-3-5-sonnet-20240620-v1:0 | $3.00 | $15.00 | $0.30 | 200K |
| eu.anthropic.claude-3-5-sonnet-20241022-v2:0 | $3.00 | $15.00 | $0.30 | 200K |
| eu.anthropic.claude-3-7-sonnet-20250219-v1:0 | $3.00 | $15.00 | $0.30 | 200K |
| eu.anthropic.claude-3-opus-20240229-v1:0 | $15.00 | $75.00 | $1.50 | 200K |
| eu.meta.llama3-2-1b-instruct-v1:0 | $0.13 | $0.13 | — | 128K |
| eu.meta.llama3-2-3b-instruct-v1:0 | $0.19 | $0.19 | — | 128K |
| eu.twelvelabs.marengo-embed-2-7-v1:0 | — | $0.00 | — | 77 |
| eu.twelvelabs.marengo-embed-3-0-v1:0 | — | $0.00 | — | 500 |
| eu.twelvelabs.pegasus-1-2-v1:0 | — | $7.50 | — | — |
| global.cohere.embed-v4:0 | $0.12 | $0.00 | — | 128K |
| global.twelvelabs.pegasus-1-2-v1:0 | — | $7.50 | — | — |
| global.twelvelabs.pegasus-1-5-v1:0 | — | $7.50 | — | 261.12K |
| meta.llama2-13b-chat-v1 | $0.75 | $1.00 | — | 4.1K |
| meta.llama2-70b-chat-v1 | $1.95 | $2.56 | — | 4.1K |
| meta.llama3-1-8b-instruct-v1:0 | $0.22 | $0.22 | — | 128K |
| meta.llama3-1-70b-instruct-v1:0 | $0.72 | $0.72 | — | 128K |
| meta.llama3-1-405b-instruct-v1:0 | $2.40 | $2.40 | — | 128K |
| meta.llama3-2-1b-instruct-v1:0 | $0.10 | $0.10 | — | 128K |
| meta.llama3-2-3b-instruct-v1:0 | $0.15 | $0.15 | — | 128K |
| meta.llama3-2-11b-instruct-v1:0 | $0.16 | $0.16 | — | 128K |
| meta.llama3-2-90b-instruct-v1:0 | $0.72 | $0.72 | — | 128K |
| meta.llama3-8b-instruct-v1:0 | $0.36 | $0.72 | — | 8.19K |
| meta.llama3-70b-instruct-v1:0 | $3.18 | $4.20 | — | 8.19K |
| minimax.minimax-m2.1 | $0.36 | $1.44 | — | 196K |
| minimax.minimax-m2.5 | $0.36 | $1.44 | — | 196K |
| mistral.mistral-7b-instruct-v0:2 | $0.20 | $0.26 | — | 32K |
| mistral.mistral-large-2402-v1:0 | $5.20 | $15.60 | — | 32K |
| mistral.mistral-large-2407-v1:0 | $2.00 | $6.00 | — | 128K |
| mistral.mistral-small-2402-v1:0 | $1.00 | $3.00 | — | 32K |
| mistral.mixtral-8x7b-instruct-v0:1 | $0.59 | $0.91 | — | 32K |
| moonshotai.kimi-k2-thinking | $0.73 | $3.03 | — | 262.14K |
| moonshotai.kimi-k2.5 | $0.72 | $3.60 | — | 262.14K |
| nvidia.nemotron-nano-3-30b | $0.07 | $0.29 | — | 262.14K |
| nvidia.nemotron-nano-9b-v2 | $0.07 | $0.28 | — | 128K |
| nvidia.nemotron-nano-12b-v2 | $0.24 | $0.72 | — | 128K |
| nvidia.nemotron-super-3-120b | $0.23 | $1.01 | — | 256K |
| openai.gpt-oss-20b-1:0 | $0.08 | $0.36 | — | 128K |
| openai.gpt-oss-120b-1:0 | $0.18 | $0.72 | — | 128K |
| qwen.qwen3-coder-next | $0.60 | $1.44 | — | 262.14K |
| qwen.qwen3-next-80b-a3b | $0.18 | $1.45 | — | 262.14K |
| twelvelabs.marengo-embed-2-7-v1:0 | — | $0.00 | — | 77 |
| twelvelabs.marengo-embed-3-0-v1:0 | — | $0.00 | — | 500 |
| twelvelabs.pegasus-1-2-v1:0 | — | $7.50 | — | — |
| twelvelabs.pegasus-1-5-v1:0 | — | $7.50 | — | 261.12K |
| us.anthropic.claude-3-5-haiku-20241022-v1:0 | $0.80 | $4.00 | $0.08 | 200K |
| us.anthropic.claude-3-5-sonnet-20240620-v1:0 | $3.00 | $15.00 | $0.30 | 200K |
| us.anthropic.claude-3-5-sonnet-20241022-v2:0 | $3.00 | $15.00 | $0.30 | 200K |
| us.anthropic.claude-3-opus-20240229-v1:0 | $15.00 | $75.00 | $1.50 | 200K |
| us.cohere.embed-v4:0 | $0.12 | $0.00 | — | 128K |
| us.meta.llama3-1-8b-instruct-v1:0 | $0.22 | $0.22 | — | 128K |
| us.meta.llama3-1-70b-instruct-v1:0 | $0.72 | $0.72 | — | 128K |
| us.meta.llama3-1-405b-instruct-v1:0 | $2.40 | $2.40 | — | 128K |
| us.meta.llama3-2-1b-instruct-v1:0 | $0.10 | $0.10 | — | 128K |
| us.meta.llama3-2-3b-instruct-v1:0 | $0.15 | $0.15 | — | 128K |
| us.meta.llama3-2-11b-instruct-v1:0 | $0.16 | $0.16 | — | 128K |
| us.meta.llama3-2-90b-instruct-v1:0 | $0.72 | $0.72 | — | 128K |
| us.twelvelabs.marengo-embed-2-7-v1:0 | — | $0.00 | — | 77 |
| us.twelvelabs.marengo-embed-3-0-v1:0 | — | $0.00 | — | 500 |
| us.twelvelabs.pegasus-1-2-v1:0 | — | $7.50 | — | — |
| us.twelvelabs.pegasus-1-5-v1:0 | — | $7.50 | — | 261.12K |
| zai.glm-5 | $1.00 | $3.20 | — | 200K |

## bedrock_converse

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| amazon.nova-2-lite-v1:0 | $0.30 | $2.50 | $0.08 | 1M |
| amazon.nova-2-pro-preview-20251202-v1:0 | $1.25 | $10.00 | $0.31 | 1M |
| amazon.nova-lite-v1:0 | $0.06 | $0.24 | $0.02 | 300K |
| amazon.nova-micro-v1:0 | $0.04 | $0.14 | $0.00875 | 128K |
| amazon.nova-premier-v1:0 | $2.50 | $12.50 | $0.62 | 1M |
| amazon.nova-pro-v1:0 | $0.80 | $3.20 | $0.20 | 300K |
| anthropic.claude-3-7-sonnet-20250219-v1:0 | $3.00 | $15.00 | $0.30 | 200K |
| anthropic.claude-fable-5 | $10.00 | $50.00 | $1.00 | 1M |
| anthropic.claude-fable-5-1 | $10.00 | $50.00 | $0.25 | 1M |
| anthropic.claude-haiku-4-5-20251001-v1:0 | $1.00 | $5.00 | $0.10 | 200K |
| anthropic.claude-haiku-4-5@20251001 | $1.00 | $5.00 | $0.10 | 200K |
| anthropic.claude-haiku-5-5 | $0.10 | $0.50 | $0.01 | 1M |
| anthropic.claude-mythos-5-1 | $10.00 | $50.00 | $0.25 | 1M |
| anthropic.claude-opus-4-1-20250805-v1:0 | $15.00 | $75.00 | $1.50 | 200K |
| anthropic.claude-opus-4-5-20251101-v1:0 | $5.00 | $25.00 | $0.50 | 200K |
| anthropic.claude-opus-4-6-v1 | $5.00 | $25.00 | $0.50 | 1M |
| anthropic.claude-opus-4-7 | $5.00 | $25.00 | $0.50 | 1M |
| anthropic.claude-opus-4-8 | $5.00 | $25.00 | $0.50 | 1M |
| anthropic.claude-opus-4-20250514-v1:0 | $15.00 | $75.00 | $1.50 | 200K |
| anthropic.claude-opus-5 | $5.00 | $25.00 | $0.50 | 1M |
| anthropic.claude-opus-5-5 | $4.00 | $20.00 | $0.20 | 1M |
| anthropic.claude-sonnet-4-5-20250929-v1:0 | $3.00 | $15.00 | $0.30 | 200K |
| anthropic.claude-sonnet-4-6 | $3.00 | $15.00 | $0.30 | 1M |
| anthropic.claude-sonnet-4-20250514-v1:0 | $3.00 | $15.00 | $0.30 | 200K |
| anthropic.claude-sonnet-5 | $2.00 | $10.00 | $0.20 | 1M |
| anthropic.claude-sonnet-5-5 | $2.00 | $10.00 | $0.10 | 1M |
| apac.amazon.nova-2-lite-v1:0 | $0.40 | $3.31 | $0.10 | 1M |
| apac.amazon.nova-2-pro-preview-20251202-v1:0 | $1.38 | $11.00 | $0.34 | 1M |
| apac.amazon.nova-lite-v1:0 | $0.06 | $0.25 | $0.02 | 300K |
| apac.amazon.nova-micro-v1:0 | $0.04 | $0.15 | $0.00925 | 128K |
| apac.amazon.nova-pro-v1:0 | $0.84 | $3.36 | $0.21 | 300K |
| apac.anthropic.claude-fable-5 | $11.00 | $55.00 | $1.10 | 1M |
| apac.anthropic.claude-haiku-4-5-20251001-v1:0 | $1.10 | $5.50 | $0.11 | 200K |
| apac.anthropic.claude-haiku-5-5 | $0.11 | $0.55 | $0.01 | 1M |
| apac.anthropic.claude-mythos-preview | $27.50 | $137.50 | $2.75 | 1M |
| apac.anthropic.claude-opus-4-7 | $5.50 | $27.50 | $0.55 | 1M |
| apac.anthropic.claude-opus-4-8 | $5.50 | $27.50 | $0.55 | 1M |
| apac.anthropic.claude-opus-5 | $5.50 | $27.50 | $0.55 | 1M |
| apac.anthropic.claude-opus-5-5 | $4.40 | $22.00 | $0.22 | 1M |
| apac.anthropic.claude-sonnet-4-6 | $3.30 | $16.50 | $0.33 | 1M |
| apac.anthropic.claude-sonnet-4-20250514-v1:0 | $3.00 | $15.00 | $0.30 | 200K |
| apac.anthropic.claude-sonnet-5 | $2.20 | $11.00 | $0.22 | 1M |
| apac.anthropic.claude-sonnet-5-5 | $2.20 | $11.00 | $0.11 | 1M |
| au.anthropic.claude-fable-5 | $11.00 | $55.00 | $1.10 | 1M |
| au.anthropic.claude-haiku-4-5-20251001-v1:0 | $1.10 | $5.50 | $0.11 | 200K |
| au.anthropic.claude-haiku-5-5 | $0.11 | $0.55 | $0.01 | 1M |
| au.anthropic.claude-mythos-preview | $27.50 | $137.50 | $2.75 | 1M |
| au.anthropic.claude-opus-4-6-v1 | $5.50 | $27.50 | $0.55 | 1M |
| au.anthropic.claude-opus-4-7 | $5.50 | $27.50 | $0.55 | 1M |
| au.anthropic.claude-opus-4-8 | $5.50 | $27.50 | $0.55 | 1M |
| au.anthropic.claude-opus-5 | $5.50 | $27.50 | $0.55 | 1M |
| au.anthropic.claude-opus-5-5 | $4.40 | $22.00 | $0.22 | 1M |
| au.anthropic.claude-sonnet-4-5-20250929-v1:0 | $3.30 | $16.50 | $0.33 | 200K |
| au.anthropic.claude-sonnet-4-6 | $3.30 | $16.50 | $0.33 | 1M |
| au.anthropic.claude-sonnet-5 | $2.20 | $11.00 | $0.22 | 1M |
| au.anthropic.claude-sonnet-5-5 | $2.20 | $11.00 | $0.11 | 1M |
| deepseek.r1-v1:0 | $1.35 | $5.40 | — | 128K |
| deepseek.v3-v1:0 | $0.58 | $1.68 | — | 128K |
| deepseek.v3.2 | $0.62 | $1.85 | — | 164K |
| eu.amazon.nova-2-lite-v1:0 | $0.43 | $3.60 | $0.11 | 1M |
| eu.amazon.nova-2-pro-preview-20251202-v1:0 | $1.38 | $11.00 | $0.34 | 1M |
| eu.amazon.nova-lite-v1:0 | $0.08 | $0.31 | $0.02 | 300K |
| eu.amazon.nova-micro-v1:0 | $0.05 | $0.18 | $0.01 | 128K |
| eu.amazon.nova-pro-v1:0 | $1.05 | $4.20 | $0.26 | 300K |
| eu.anthropic.claude-fable-5 | $11.00 | $55.00 | $1.10 | 1M |
| eu.anthropic.claude-fable-5-1 | $11.00 | $55.00 | $0.28 | 1M |
| eu.anthropic.claude-haiku-4-5-20251001-v1:0 | $1.10 | $5.50 | $0.11 | 200K |
| eu.anthropic.claude-haiku-5-5 | $0.11 | $0.55 | $0.01 | 1M |
| eu.anthropic.claude-opus-4-1-20250805-v1:0 | $15.00 | $75.00 | $1.50 | 200K |
| eu.anthropic.claude-opus-4-5-20251101-v1:0 | $5.50 | $27.50 | $0.55 | 200K |
| eu.anthropic.claude-opus-4-6-v1 | $5.50 | $27.50 | $0.55 | 1M |
| eu.anthropic.claude-opus-4-7 | $5.50 | $27.50 | $0.55 | 1M |
| eu.anthropic.claude-opus-4-8 | $5.50 | $27.50 | $0.55 | 1M |
| eu.anthropic.claude-opus-4-20250514-v1:0 | $15.00 | $75.00 | $1.50 | 200K |
| eu.anthropic.claude-opus-5 | $5.50 | $27.50 | $0.55 | 1M |
| eu.anthropic.claude-opus-5-5 | $4.40 | $22.00 | $0.22 | 1M |
| eu.anthropic.claude-sonnet-4-5-20250929-v1:0 | $3.30 | $16.50 | $0.33 | 200K |
| eu.anthropic.claude-sonnet-4-6 | $3.30 | $16.50 | $0.33 | 1M |
| eu.anthropic.claude-sonnet-4-20250514-v1:0 | $3.00 | $15.00 | $0.30 | 200K |
| eu.anthropic.claude-sonnet-5 | $2.20 | $11.00 | $0.22 | 1M |
| eu.anthropic.claude-sonnet-5-5 | $2.20 | $11.00 | $0.11 | 1M |
| eu.deepseek.v3.2 | $0.74 | $2.22 | — | 163.84K |
| eu.mistral.pixtral-large-2502-v1:0 | $2.00 | $6.00 | — | 128K |
| global.amazon.nova-2-lite-v1:0 | $0.30 | $2.50 | $0.08 | 1M |
| global.anthropic.claude-fable-5 | $10.00 | $50.00 | $1.00 | 1M |
| global.anthropic.claude-fable-5-1 | $10.00 | $50.00 | $0.25 | 1M |
| global.anthropic.claude-haiku-4-5-20251001-v1:0 | $1.00 | $5.00 | $0.10 | 200K |
| global.anthropic.claude-haiku-5-5 | $0.10 | $0.50 | $0.01 | 1M |
| global.anthropic.claude-mythos-5-1 | $10.00 | $50.00 | $0.25 | 1M |
| global.anthropic.claude-opus-4-5-20251101-v1:0 | $5.00 | $25.00 | $0.50 | 200K |
| global.anthropic.claude-opus-4-6-v1 | $5.00 | $25.00 | $0.50 | 1M |
| global.anthropic.claude-opus-4-7 | $5.00 | $25.00 | $0.50 | 1M |
| global.anthropic.claude-opus-4-8 | $5.00 | $25.00 | $0.50 | 1M |
| global.anthropic.claude-opus-5 | $5.00 | $25.00 | $0.50 | 1M |
| global.anthropic.claude-opus-5-5 | $4.00 | $20.00 | $0.20 | 1M |
| global.anthropic.claude-sonnet-4-5-20250929-v1:0 | $3.00 | $15.00 | $0.30 | 200K |
| global.anthropic.claude-sonnet-4-6 | $3.00 | $15.00 | $0.30 | 1M |
| global.anthropic.claude-sonnet-4-20250514-v1:0 | $3.00 | $15.00 | $0.30 | 200K |
| global.anthropic.claude-sonnet-5 | $2.00 | $10.00 | $0.20 | 1M |
| global.anthropic.claude-sonnet-5-5 | $2.00 | $10.00 | $0.10 | 1M |
| global.moonshotai.kimi-k3 | $3.00 | $15.00 | $0.30 | 1M |
| global.openai.gpt-5.4 | $2.50 | $15.00 | $0.25 | 1.05M |
| global.openai.gpt-5.5 | $5.00 | $30.00 | $0.50 | 1.05M |
| global.openai.gpt-5.6-luna | $0.20 | $1.20 | $0.02 | 1.05M |
| global.openai.gpt-5.6-sol | $4.00 | $20.00 | $0.40 | 1.05M |
| global.openai.gpt-5.6-terra | $2.00 | $12.00 | $0.20 | 1.05M |
| global.openai.gpt-6-astra | $10.00 | $50.00 | $1.00 | 1.05M |
| global.openai.gpt-6-luna | $0.10 | $0.50 | $0.01 | 1.05M |
| global.openai.gpt-6-sol | $2.00 | $10.00 | $0.20 | 1.05M |
| global.openai.gpt-6.1-sol | $2.00 | $10.00 | $0.10 | 1M |
| global.openai.gpt-6.1-terra | $1.00 | $5.00 | $0.05 | 922K |
| global.xai.grok-4.6 | $2.00 | $6.00 | $0.50 | 500K |
| global.xai.grok-4.7 | $2.00 | $6.00 | $0.50 | 524.29K |
| global.zai.glm-5.3 | $1.68 | $5.28 | $0.31 | 1M |
| google.gemma-3-4b-it | $0.04 | $0.08 | — | 128K |
| google.gemma-3-12b-it | $0.09 | $0.29 | — | 128K |
| google.gemma-3-27b-it | $0.23 | $0.38 | — | 128K |
| in.moonshotai.kimi-k3 | $3.30 | $16.50 | $0.33 | 1M |
| jp.amazon.nova-2-lite-v1:0 | $0.40 | $3.31 | $0.10 | 1M |
| jp.anthropic.claude-haiku-4-5-20251001-v1:0 | $1.10 | $5.50 | $0.11 | 200K |
| jp.anthropic.claude-haiku-5-5 | $0.11 | $0.55 | $0.01 | 1M |
| jp.anthropic.claude-opus-4-7 | $5.50 | $27.50 | $0.55 | 1M |
| jp.anthropic.claude-opus-4-8 | $5.50 | $27.50 | $0.55 | 1M |
| jp.anthropic.claude-opus-5 | $5.50 | $27.50 | $0.55 | 1M |
| jp.anthropic.claude-opus-5-5 | $4.40 | $22.00 | $0.22 | 1M |
| jp.anthropic.claude-sonnet-4-5-20250929-v1:0 | $3.30 | $16.50 | $0.33 | 200K |
| jp.anthropic.claude-sonnet-4-6 | $3.30 | $16.50 | $0.33 | 1M |
| jp.anthropic.claude-sonnet-5 | $2.20 | $11.00 | $0.22 | 1M |
| jp.anthropic.claude-sonnet-5-5 | $2.20 | $11.00 | $0.11 | 1M |
| meta.llama3-3-70b-instruct-v1:0 | $0.72 | $0.72 | — | 128K |
| meta.llama4-maverick-17b-instruct-v1:0 | $0.24 | $0.97 | — | 1M |
| meta.llama4-scout-17b-instruct-v1:0 | $0.17 | $0.66 | — | 10M |
| minimax.minimax-m2 | $0.30 | $1.20 | — | 1M |
| minimax.minimax-m2.1 | $0.30 | $1.20 | — | 196K |
| minimax.minimax-m2.5 | $0.30 | $1.20 | — | 196K |
| mistral.devstral-2-123b | $0.40 | $2.00 | — | 256K |
| mistral.magistral-small-2509 | $0.50 | $1.50 | — | 128K |
| mistral.ministral-3-3b-instruct | $0.10 | $0.10 | — | 128K |
| mistral.ministral-3-8b-instruct | $0.15 | $0.15 | — | 128K |
| mistral.ministral-3-14b-instruct | $0.20 | $0.20 | — | 128K |
| mistral.mistral-large-3-675b-instruct | $0.50 | $1.50 | — | 256K |
| mistral.pixtral-large-2502-v1:0 | $2.00 | $6.00 | — | 128K |
| mistral.voxtral-mini-3b-2507 | $0.04 | $0.04 | — | 32.77K |
| mistral.voxtral-small-24b-2507 | $0.10 | $0.30 | — | 32.77K |
| moonshot.kimi-k2-thinking | $0.60 | $2.50 | — | 256K |
| moonshotai.kimi-k2.5 | $0.60 | $3.00 | — | 256K |
| moonshotai.kimi-k3 | $3.30 | $16.50 | $0.33 | 1M |
| nvidia.nemotron-nano-3-30b | $0.06 | $0.24 | — | 256K |
| nvidia.nemotron-nano-9b-v2 | $0.06 | $0.23 | — | 128K |
| nvidia.nemotron-nano-12b-v2 | $0.20 | $0.60 | — | 128K |
| nvidia.nemotron-super-3-120b | $0.15 | $0.65 | — | 256K |
| openai.gpt-6-luna | $0.10 | $0.50 | $0.01 | 1.05M |
| openai.gpt-6-sol | $2.00 | $10.00 | $0.20 | 1.05M |
| openai.gpt-oss-20b-1:0 | $0.07 | $0.30 | — | 128K |
| openai.gpt-oss-120b-1:0 | $0.15 | $0.60 | — | 128K |
| openai.gpt-oss-safeguard-20b | $0.07 | $0.20 | — | 128K |
| openai.gpt-oss-safeguard-120b | $0.15 | $0.60 | — | 128K |
| qwen.qwen3-32b-v1:0 | $0.15 | $0.60 | — | 32.77K |
| qwen.qwen3-235b-a22b-2507-v1:0 | $0.22 | $0.88 | — | 262.14K |
| qwen.qwen3-coder-30b-a3b-v1:0 | $0.15 | $0.60 | — | 262.14K |
| qwen.qwen3-coder-480b-a35b-v1:0 | $0.45 | $1.80 | — | 262.14K |
| qwen.qwen3-coder-next | $0.50 | $1.20 | — | 256K |
| qwen.qwen3-next-80b-a3b | $0.15 | $1.20 | — | 256K |
| qwen.qwen3-vl-235b-a22b | $0.53 | $2.66 | — | 256K |
| us-gov.anthropic.claude-fable-5-1 | $12.00 | $60.00 | $0.30 | 1M |
| us-gov.anthropic.claude-haiku-5-5 | $0.12 | $0.60 | $0.01 | 1M |
| us-gov.anthropic.claude-opus-4-8 | $6.00 | $30.00 | $0.60 | 1M |
| us-gov.anthropic.claude-opus-5 | $6.00 | $30.00 | $0.60 | 1M |
| us-gov.anthropic.claude-opus-5-5 | $4.80 | $24.00 | $0.24 | 1M |
| us-gov.anthropic.claude-sonnet-4-5-20250929-v1:0 | $3.60 | $18.00 | $0.36 | 200K |
| us-gov.anthropic.claude-sonnet-5 | $2.40 | $12.00 | $0.24 | 1M |
| us-gov.anthropic.claude-sonnet-5-5 | $2.40 | $12.00 | $0.12 | 1M |
| us-gov.nvidia.nemotron-nano-3-30b | $0.07 | $0.29 | — | 262.14K |
| us-gov.nvidia.nemotron-nano-9b-v2 | $0.07 | $0.28 | — | 128K |
| us-gov.nvidia.nemotron-nano-12b-v2 | $0.24 | $0.72 | — | 128K |
| us-gov.nvidia.nemotron-super-3-120b | $0.18 | $0.78 | — | 256K |
| us-gov.openai.gpt-oss-20b-1:0 | $0.08 | $0.36 | — | 128K |
| us-gov.openai.gpt-oss-120b-1:0 | $0.18 | $0.72 | — | 128K |
| us-gov.xai.grok-4.6 | $2.64 | $7.92 | $0.66 | 500K |
| us.amazon.nova-2-lite-v1:0 | $0.33 | $2.75 | $0.08 | 1M |
| us.amazon.nova-2-pro-preview-20251202-v1:0 | $1.38 | $11.00 | $0.34 | 1M |
| us.amazon.nova-lite-v1:0 | $0.06 | $0.24 | $0.02 | 300K |
| us.amazon.nova-micro-v1:0 | $0.04 | $0.14 | $0.00875 | 128K |
| us.amazon.nova-pro-v1:0 | $0.80 | $3.20 | $0.20 | 300K |
| us.anthropic.claude-3-7-sonnet-20250219-v1:0 | $3.00 | $15.00 | $0.30 | 200K |
| us.anthropic.claude-fable-5 | $11.00 | $55.00 | $1.10 | 1M |
| us.anthropic.claude-fable-5-1 | $11.00 | $55.00 | $0.28 | 1M |
| us.anthropic.claude-haiku-4-5-20251001-v1:0 | $1.10 | $5.50 | $0.11 | 200K |
| us.anthropic.claude-haiku-5-5 | $0.11 | $0.55 | $0.01 | 1M |
| us.anthropic.claude-mythos-5 | $11.00 | $55.00 | $1.10 | 1M |
| us.anthropic.claude-mythos-5-1 | $11.00 | $55.00 | $0.28 | 1M |
| us.anthropic.claude-mythos-preview | $27.50 | $137.50 | $2.75 | 1M |
| us.anthropic.claude-opus-4-1-20250805-v1:0 | $15.00 | $75.00 | $1.50 | 200K |
| us.anthropic.claude-opus-4-5-20251101-v1:0 | $5.50 | $27.50 | $0.55 | 200K |
| us.anthropic.claude-opus-4-6-v1 | $5.50 | $27.50 | $0.55 | 1M |
| us.anthropic.claude-opus-4-7 | $5.50 | $27.50 | $0.55 | 1M |
| us.anthropic.claude-opus-4-8 | $5.50 | $27.50 | $0.55 | 1M |
| us.anthropic.claude-opus-4-20250514-v1:0 | $15.00 | $75.00 | $1.50 | 200K |
| us.anthropic.claude-opus-5 | $5.50 | $27.50 | $0.55 | 1M |
| us.anthropic.claude-opus-5-5 | $4.40 | $22.00 | $0.22 | 1M |
| us.anthropic.claude-sonnet-4-5-20250929-v1:0 | $3.30 | $16.50 | $0.33 | 200K |
| us.anthropic.claude-sonnet-4-6 | $3.30 | $16.50 | $0.33 | 1M |
| us.anthropic.claude-sonnet-4-20250514-v1:0 | $3.00 | $15.00 | $0.30 | 200K |
| us.anthropic.claude-sonnet-5 | $2.20 | $11.00 | $0.22 | 1M |
| us.anthropic.claude-sonnet-5-5 | $2.20 | $11.00 | $0.11 | 1M |
| us.deepseek.r1-v1:0 | $1.35 | $5.40 | — | 128K |
| us.deepseek.v3.2 | $0.62 | $1.85 | — | 163.84K |
| us.meta.llama3-3-70b-instruct-v1:0 | $0.72 | $0.72 | — | 128K |
| us.meta.llama4-maverick-17b-instruct-v1:0 | $0.24 | $0.97 | — | 1M |
| us.meta.llama4-scout-17b-instruct-v1:0 | $0.17 | $0.66 | — | 10M |
| us.mistral.pixtral-large-2502-v1:0 | $2.00 | $6.00 | — | 128K |
| us.moonshotai.kimi-k3 | $3.30 | $16.50 | $0.33 | 1M |
| us.openai.gpt-5.4 | $2.75 | $16.50 | $0.28 | 1.05M |
| us.openai.gpt-5.5 | $5.50 | $33.00 | $0.55 | 1.05M |
| us.openai.gpt-5.6-luna | $0.22 | $1.32 | $0.02 | 1.05M |
| us.openai.gpt-5.6-sol | $4.40 | $22.00 | $0.44 | 1.05M |
| us.openai.gpt-5.6-terra | $2.20 | $13.20 | $0.22 | 1.05M |
| us.openai.gpt-6-astra | $11.00 | $55.00 | $1.10 | 1.05M |
| us.openai.gpt-6-luna | $0.11 | $0.55 | $0.01 | 1.05M |
| us.openai.gpt-6-sol | $2.20 | $11.00 | $0.22 | 1.05M |
| us.openai.gpt-6.1-sol | $2.20 | $11.00 | $0.11 | 1M |
| us.openai.gpt-6.1-terra | $1.10 | $5.50 | $0.06 | 922K |
| us.writer.palmyra-x4-v1:0 | $2.50 | $10.00 | — | 128K |
| us.writer.palmyra-x5-v1:0 | $0.60 | $6.00 | — | 128K |
| us.xai.grok-4.6 | $2.20 | $6.60 | $0.55 | 500K |
| us.xai.grok-4.7 | $2.20 | $6.60 | $0.55 | 524.29K |
| us.zai.glm-5.3 | $1.85 | $5.81 | $0.34 | 1M |
| writer.palmyra-vision-7b | $0.15 | $0.60 | — | 4.1K |
| writer.palmyra-x4-v1:0 | $2.50 | $10.00 | — | 128K |
| writer.palmyra-x5-v1:0 | $0.60 | $6.00 | — | 128K |
| zai.glm-4.7 | $0.60 | $2.20 | — | 203K |
| zai.glm-4.7-flash | $0.07 | $0.40 | — | 203K |
| zai.glm-5 | $1.00 | $3.20 | — | 200K |

## bedrock_mantle

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| anthropic.claude-haiku-4-5 | $1.00 | $5.00 | $0.10 | 200K |
| anthropic.claude-haiku-5-5 | $0.11 | $0.55 | $0.01 | 1M |
| anthropic.claude-opus-5-5 | $4.40 | $22.00 | $0.22 | 1M |
| anthropic.claude-sonnet-5-5 | $2.20 | $11.00 | $0.11 | 1M |
| deepseek.v3.1 | $0.58 | $1.68 | — | 128K |
| google.gemma-4-26b-a4b | $0.13 | $0.40 | — | 256K |
| google.gemma-4-31b | $0.14 | $0.40 | — | 256K |
| google.gemma-4-e2b | $0.04 | $0.08 | — | 128K |
| moonshotai.kimi-k2-thinking | $0.60 | $2.50 | — | 256K |
| openai.gpt-5.4 | $2.75 | $16.50 | $0.28 | 1.05M |
| openai.gpt-5.5 | $5.50 | $33.00 | $0.55 | 1.05M |
| openai.gpt-5.6-cyber | $13.75 | $82.50 | $1.38 | 1.05M |
| openai.gpt-5.6-luna | $0.22 | $1.32 | $0.02 | 1.05M |
| openai.gpt-5.6-sol | $4.40 | $22.00 | $0.44 | 1.05M |
| openai.gpt-5.6-terra | $2.20 | $13.20 | $0.22 | 1.05M |
| openai.gpt-6-astra | $11.00 | $55.00 | $1.10 | 1.05M |
| openai.gpt-6-luna | $0.11 | $0.55 | $0.01 | 1.05M |
| openai.gpt-6-sol | $2.20 | $11.00 | $0.22 | 1.05M |
| openai.gpt-6.1-sol | $2.20 | $11.00 | $0.11 | 1M |
| openai.gpt-daybreak-blue-5.6-sol | $4.40 | $22.00 | $0.44 | 1.05M |
| openai.gpt-oss-20b | $0.07 | $0.30 | — | 131.07K |
| openai.gpt-oss-120b | $0.15 | $0.60 | — | 131.07K |
| openai.gpt-oss-safeguard-20b | $0.07 | $0.20 | — | 131.07K |
| openai.gpt-oss-safeguard-120b | $0.15 | $0.60 | — | 131.07K |
| qwen.qwen3-32b | $0.15 | $0.60 | — | 32K |
| qwen.qwen3-235b-a22b-2507 | $0.22 | $0.88 | — | 256K |
| qwen.qwen3-coder-30b-a3b-instruct | $0.15 | $0.60 | — | 256K |
| qwen.qwen3-coder-480b-a35b-instruct | $0.45 | $1.80 | — | 262.14K |
| qwen.qwen3-next-80b-a3b-instruct | $0.14 | $1.20 | — | 256K |
| qwen.qwen3-vl-235b-a22b-instruct | $0.53 | $2.66 | — | 256K |
| xai.grok-4.3 | $1.50 | $3.00 | $0.24 | 1.05M |
| xai.grok-4.6 | $2.64 | $7.92 | $0.66 | 500K |

## bespoke

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| bespoke-nimble-9b | $0.00 | $0.00 | — | 8.19K |
| nimble | $0.00 | $0.00 | — | 8.19K |
| nimble-latest | $0.00 | $0.00 | — | 8.19K |

## bytedance

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| ui-tars 7b | $0.10 | $0.20 | $0.10 | 128K |

## bytedance-seed

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| bytedance seed: seed 1.6 | $0.25 | $2.00 | — | 262.14K |
| bytedance seed: seed 1.6 flash | $0.08 | $0.30 | — | 262.14K |
| bytedance seed: seed 2.1 turbo | $0.50 | $2.50 | — | 262.14K |
| bytedance seed: seed-2.0-code | $0.50 | $3.00 | — | 262.14K |
| bytedance seed: seed-2.0-lite | $0.25 | $2.00 | — | 262.14K |
| bytedance seed: seed-2.0-mini | $0.10 | $0.40 | — | 262.14K |

## cerebras

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| gemma-4-31b | $0.99 | $1.49 | — | 131.07K |
| gpt-oss-120b | $0.35 | $0.75 | — | 131.07K |
| llama3.1-8b | $0.10 | $0.10 | — | 128K |
| llama3.1-70b | $0.60 | $0.60 | — | 128K |
| llama-3.1-8b | $0.10 | $0.10 | — | 128K |
| llama-3.1-70b | $0.60 | $0.60 | — | 128K |
| llama-3.3-70b | $0.85 | $1.20 | — | 128K |
| qwen-3-32b | $0.40 | $0.80 | — | 128K |
| qwen-3.8-27b | $0.99 | $1.49 | — | 65.54K |

## cloudflare

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| clairic | $0.10 | $0.00 | — | 65.54K |
| clef | $0.24 | $0.00 | — | 65.54K |
| clef-flash | $0.09 | $0.00 | — | 65.54K |
| clef-omni | $0.15 | $0.00 | — | 64K |
| codellama-7b-instruct-awq | $1.92 | $1.92 | — | 4.1K |
| deepseek-r1-distill-qwen-32b | $0.50 | $4.88 | — | 80K |
| gemma-2b-it-lora | $0.00 | $0.00 | — | 8.19K |
| gemma-4-26b-a4b-it | $0.10 | $0.30 | — | 256K |
| gemma-7b-it-lora | $0.00 | $0.00 | — | 3.5K |
| gemma-sea-lion-v4-27b-it | $0.35 | $0.56 | — | 128K |
| glm-4.7-flash | $0.06 | $0.40 | — | 131.07K |
| glm-5.2 | $1.40 | $4.40 | $0.26 | 262.14K |
| gpt-oss-20b | $0.20 | $0.30 | — | 128K |
| gpt-oss-120b | $0.35 | $0.75 | — | 128K |
| granite-4.0-h-micro | $0.02 | $0.11 | — | 131K |
| kimi-k2.6 | $0.95 | $4.00 | $0.16 | 262.14K |
| kimi-k2.7-code | $0.95 | $4.00 | $0.19 | 262.14K |
| llama-2-7b-chat-fp16 | $1.92 | $1.92 | — | 3.07K |
| llama-2-7b-chat-hf-lora | $0.00 | $0.00 | — | 8.19K |
| llama-2-7b-chat-int8 | $1.92 | $1.92 | — | 2.05K |
| llama-3.1-8b-instruct-fp8 | $0.15 | $0.29 | — | 32K |
| llama-3.2-1b-instruct | $0.03 | $0.20 | — | 60K |
| llama-3.2-3b-instruct | $0.05 | $0.34 | — | 80K |
| llama-3.2-11b-vision-instruct | $0.05 | $0.68 | — | 128K |
| llama-3.3-70b-instruct-fp8-fast | $0.29 | $2.25 | — | 24K |
| llama-4-scout-17b-16e-instruct | $0.27 | $0.85 | — | 131K |
| llama-guard-3-8b | $0.48 | $0.03 | — | 131.07K |
| mistral-7b-instruct-v0.1 | $1.92 | $1.92 | — | 8.19K |
| mistral-7b-instruct-v0.2-lora | $0.00 | $0.00 | — | 15K |
| mistral-small-3.1-24b-instruct | $0.35 | $0.56 | — | 128K |
| nemotron-3-120b-a12b | $0.50 | $1.50 | — | 256K |
| qwen2.5-coder-32b-instruct | $0.66 | $1.00 | — | 32.77K |
| qwen3-30b-a3b-fp8 | $0.05 | $0.34 | — | 32.77K |
| qwq-32b | $0.66 | $1.00 | — | 24K |

## codestral

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| codestral-2405 | $0.00 | $0.00 | — | 32K |
| codestral-latest | $0.00 | $0.00 | — | 32K |

## cognition

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| swe-1.6 | $0.50 | $2.50 | $0.20 | — |
| swe-1.7 | $0.50 | $2.50 | $0.20 | — |
| swe-1.7-lightning | $2.50 | $12.50 | $1.00 | — |

## cognitivecomputations

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| venice: uncensored | $0.20 | $0.90 | — | 128K |

## cohere

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| c4ai-aya-expanse-32b | $0.50 | $1.50 | — | 128K |
| command a | $2.50 | $10.00 | — | 256K |
| command a+ | $0.30 | $1.50 | $0.15 | 192K |
| command r7b (12-2024) | $0.04 | $0.15 | — | 128K |
| command r (08-2024) | $0.15 | $0.60 | — | 128K |
| command r+ (08-2024) | $2.50 | $10.00 | — | 128K |
| command-a-03-2025 | $2.50 | $10.00 | — | 256K |
| command-a-plus-05-2026 | $0.00 | $0.00 | — | 128K |
| command-nightly | $1.00 | $2.00 | — | 4.1K |
| command-r7b-12-2024 | $0.04 | $0.15 | — | 128K |
| command-r-08-2024 | $0.15 | $0.60 | — | 128K |
| command-r-plus-08-2024 | $2.50 | $10.00 | — | 128K |
| embed-english-light-v3.0 | $0.10 | $0.00 | — | 512 |
| embed-english-v3.0 | $0.10 | $0.00 | — | 512 |
| embed-multilingual-light-v3.0 | $100.00 | $0.00 | — | 512 |
| embed-multilingual-v3.0 | $0.10 | $0.00 | — | 512 |
| embed-v4.0 | $0.12 | $0.00 | — | 128K |
| embed-v5.0-fast | $0.08 | $0.00 | — | 128K |
| embed-v5.0-pro | $0.12 | $0.00 | — | 128K |
| north mini code (free) | $0.00 | $0.00 | — | 256K |
| rerank-english-v3.0 | $0.00 | $0.00 | — | 4.1K |
| rerank-multilingual-v3.0 | $0.00 | $0.00 | — | 4.1K |
| rerank-v3.5 | $0.00 | $0.00 | — | 4.1K |
| rerank-v4.0-fast | $0.00 | $0.00 | — | 32.77K |
| rerank-v4.0-pro | $0.00 | $0.00 | — | 32.77K |

## coralbricks

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| deepseek-v4.1-flash | $0.01 | $1.20 | $0.00 | 1.05M |
| deepseek-v4.1-flash-fast | $0.01 | $1.20 | $0.00 | 1.05M |
| deepseek-v4.1-flash-fast-fp4 | $0.01 | $1.20 | $0.00 | 1.05M |
| glm-5.3 | $1.12 | $4.40 | $0.00 | 1.05M |
| glm-5.3-fast | $1.12 | $4.40 | $0.00 | 1.05M |
| glm-5.3-fp4 | $1.12 | $4.40 | $0.00 | 1.05M |

## crusoe

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| deepseek-r1-0528 | $3.00 | $7.00 | — | 163.84K |
| deepseek-v3-0324 | $1.50 | $1.50 | — | 163.84K |
| gemma-3-12b-it | $0.10 | $0.10 | — | 131.07K |
| gpt-oss-120b | $0.80 | $0.80 | — | 131.07K |
| kimi-k2-thinking | $2.50 | $2.50 | — | 262.14K |
| llama-3.3-70b-instruct | $0.20 | $0.20 | — | 131.07K |
| qwen3-235b-a22b-instruct-2507 | $3.00 | $3.00 | — | 262.14K |

## darkbloom

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| gemma-4-26b | $0.03 | $0.16 | — | 131.07K |
| gpt-oss-20b | $0.01 | $0.07 | — | 131.07K |

## dashscope

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| deepseek-v4-flash | $0.20 | $0.40 | $0.04 | 1M |
| deepseek-v4-flash-0731 | $0.20 | $0.40 | $0.04 | 1M |
| deepseek-v4-pro | $2.40 | $4.80 | $0.20 | 1M |
| glm-5.1 | $1.40 | $4.40 | $0.26 | 202.75K |
| glm-5.2 | $1.40 | $4.40 | $0.28 | 1.05M |
| kimi-k2.7-code | $0.95 | $4.00 | $0.19 | 229.38K |
| qwen3-next-80b-a3b-instruct | $0.15 | $1.20 | — | 262.14K |
| qwen3-next-80b-a3b-thinking | $0.15 | $1.20 | — | 262.14K |
| qwen3-vl-32b-instruct | $0.16 | $0.64 | — | 131.07K |
| qwen3-vl-32b-thinking | $0.16 | $2.87 | — | 131.07K |
| qwen3-vl-235b-a22b-instruct | $0.40 | $1.60 | — | 131.07K |
| qwen3-vl-235b-a22b-thinking | $0.40 | $4.00 | — | 131.07K |
| qwen3.7-max | $2.50 | $7.50 | $0.50 | 991.81K |
| qwen3.8-flash | $0.15 | $0.47 | $0.02 | 991.81K |
| qwen3.8-max | $2.00 | $6.00 | $0.25 | 991.81K |
| qwen3.8-omni-flash | $0.15 | $0.47 | $0.02 | 991.81K |
| qwen-coder | $0.30 | $1.50 | — | 1M |
| qwen-max | $1.60 | $6.40 | — | 30.72K |
| qwen-plus | $0.40 | $1.20 | — | 129.02K |
| qwen-plus-2025-01-25 | $0.40 | $1.20 | — | 129.02K |
| qwen-plus-2025-04-28 | $0.40 | $1.20 | — | 129.02K |
| qwen-plus-2025-07-14 | $0.40 | $1.20 | — | 129.02K |
| qwen-turbo | $0.05 | $0.20 | — | 129.02K |
| qwen-turbo-2024-11-01 | $0.05 | $0.20 | — | 1M |
| qwen-turbo-2025-04-28 | $0.05 | $0.20 | — | 1M |
| qwen-turbo-latest | $0.05 | $0.20 | — | 1M |
| qwq-plus | $0.80 | $2.40 | — | 98.3K |

## databricks

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| ai_decide | $0.00 | $0.00 | $0.00 | — |
| databricks-bge-large-en | $0.10 | $0.00 | $0.10 | 512 |
| databricks-claude-fable-5 | $10.00 | $50.00 | $1.00 | 1M |
| databricks-claude-fable-5-1 | $10.00 | $50.00 | $0.25 | 1M |
| databricks-claude-haiku-4-5 | $1.00 | $5.00 | $0.10 | 200K |
| databricks-claude-opus-4 | $15.00 | $75.00 | $1.50 | 200K |
| databricks-claude-opus-4-1 | $15.00 | $75.00 | $1.50 | 200K |
| databricks-claude-opus-4-5 | $5.00 | $25.00 | $0.50 | 200K |
| databricks-claude-opus-4-6 | $5.00 | $25.00 | $0.50 | 1M |
| databricks-claude-opus-4-7 | $5.00 | $25.00 | $0.50 | 1M |
| databricks-claude-opus-4-8 | $5.00 | $25.00 | $0.50 | 1M |
| databricks-claude-opus-5 | $5.00 | $25.00 | $0.50 | 1M |
| databricks-claude-opus-5-5 | $4.00 | $20.00 | $0.20 | 1M |
| databricks-claude-sonnet-4 | $3.00 | $15.00 | $0.30 | 200K |
| databricks-claude-sonnet-4-1 | $3.00 | $15.00 | $0.30 | 200K |
| databricks-claude-sonnet-4-5 | $3.00 | $15.00 | $0.30 | 200K |
| databricks-claude-sonnet-4-6 | $3.00 | $15.00 | $0.30 | 1M |
| databricks-claude-sonnet-5 | $3.00 | $15.00 | $0.30 | 1M |
| databricks-deepseek-v4-flash-0731 | $0.14 | $0.28 | $0.03 | 1M |
| databricks-deepseek-v4-pro-0813 | $1.32 | $3.96 | $0.13 | 1M |
| databricks-gemini-2-5-flash | $0.30 | $2.50 | $0.03 | 1.05M |
| databricks-gemini-2-5-pro | $1.25 | $10.00 | $0.12 | 1.05M |
| databricks-gemini-3-1-flash-lite | $0.31 | $1.88 | $0.03 | 1.05M |
| databricks-gemini-3-1-pro | $2.50 | $15.00 | $0.25 | 1.05M |
| databricks-gemini-3-5-flash | $1.88 | $11.25 | $0.19 | 1.05M |
| databricks-gemini-3-5-flash-lite | $0.37 | $3.13 | $0.04 | 1.05M |
| databricks-gemini-3-6-flash | $1.88 | $9.38 | $0.19 | 1.05M |
| databricks-gemini-3-flash | $0.63 | $3.75 | $0.06 | 1.05M |
| databricks-gemini-3-pro | $2.50 | $15.00 | $0.25 | 1.05M |
| databricks-gemma-3-12b | $0.15 | $0.50 | $0.15 | 128K |
| databricks-glm-5-2 | $1.40 | $4.40 | $0.26 | 1M |
| databricks-glm-5-3 | $1.40 | $4.40 | $0.26 | 1.05M |
| databricks-glm-5-3-flash | $0.15 | $0.50 | $0.03 | 1.05M |
| databricks-gpt-5 | $1.25 | $10.00 | $0.13 | 272K |
| databricks-gpt-5-1 | $1.25 | $10.00 | $0.13 | 272K |
| databricks-gpt-5-2 | $1.75 | $14.00 | $0.18 | 272K |
| databricks-gpt-5-3-codex | $1.75 | $14.00 | $0.18 | 272K |
| databricks-gpt-5-4 | $2.50 | $15.00 | $0.25 | 922K |
| databricks-gpt-5-4-mini | $0.75 | $4.50 | $0.07 | 272K |
| databricks-gpt-5-4-nano | $0.20 | $1.25 | $0.02 | 272K |
| databricks-gpt-5-5 | $5.00 | $30.00 | $0.50 | 922K |
| databricks-gpt-5-5-pro | $30.00 | $180.00 | $30.00 | 922K |
| databricks-gpt-5-6-luna | $1.00 | $6.00 | $0.10 | 922K |
| databricks-gpt-5-6-sol | $4.00 | $20.00 | $0.40 | 922K |
| databricks-gpt-5-6-terra | $2.50 | $15.00 | $0.25 | 922K |
| databricks-gpt-5-mini | $0.25 | $2.00 | $0.02 | 272K |
| databricks-gpt-5-nano | $0.05 | $0.40 | $0.00497 | 272K |
| databricks-gpt-oss-20b | $0.07 | $0.30 | $0.07 | 131.07K |
| databricks-gpt-oss-120b | $0.15 | $0.60 | $0.15 | 131.07K |
| databricks-grok-4-6 | $2.50 | $7.50 | $0.63 | 500K |
| databricks-gte-large-en | $0.13 | $0.00 | $0.13 | 8.19K |
| databricks-inkling | $1.00 | $4.05 | $0.17 | 1M |
| databricks-kimi-k3 | $3.00 | $15.00 | $0.30 | 1M |
| databricks-llama-4-maverick | $0.50 | $1.50 | $0.50 | 128K |
| databricks-meta-llama-3-1-8b-instruct | $0.15 | $0.45 | $0.15 | 200K |
| databricks-meta-llama-3-3-70b-instruct | $0.50 | $1.50 | $0.50 | 128K |
| databricks-openjev-qwen35-4b | $0.00 | $0.00 | $0.00 | — |
| databricks-qwen3-embedding-0-6b | $0.02 | $0.00 | $0.02 | 32.77K |
| databricks-qwen3-next-80b-a3b-instruct | $0.15 | $1.20 | $0.15 | — |
| databricks-qwen35-122b-a10b | $0.22 | $2.20 | $0.22 | 262.14K |

## deepinfra

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| claude-3-7-sonnet-latest | $3.30 | $16.50 | $0.33 | 200K |
| claude-4-opus | $16.50 | $82.50 | — | 200K |
| claude-4-sonnet | $3.30 | $16.50 | — | 200K |
| claude-fable-5 | $10.00 | $50.00 | — | 1M |
| claude-haiku-4-5 | $1.00 | $5.00 | — | 200K |
| claude-opus-4-7 | $5.00 | $25.00 | — | 1M |
| claude-opus-4-8 | $5.00 | $25.00 | — | 1M |
| claude-opus-5 | $5.00 | $25.00 | — | 1M |
| claude-sonnet-4-6 | $3.00 | $15.00 | — | 1M |
| claude-sonnet-5 | $2.00 | $10.00 | — | 1M |
| deepseek-r1 | $0.70 | $2.40 | — | 163.84K |
| deepseek-r1-0528 | $0.50 | $2.15 | $0.40 | 163.84K |
| deepseek-r1-0528-turbo | $1.00 | $3.00 | — | 32.77K |
| deepseek-r1-distill-llama-70b | $0.20 | $0.60 | — | 131.07K |
| deepseek-r1-distill-qwen-32b | $0.27 | $0.27 | — | 131.07K |
| deepseek-r1-turbo | $1.00 | $3.00 | — | 40.96K |
| deepseek-v3 | $0.32 | $0.89 | — | 163.84K |
| deepseek-v3-0324 | $0.24 | $0.90 | $0.14 | 163.84K |
| deepseek-v3.1 | $0.25 | $0.95 | $0.22 | 163.84K |
| deepseek-v3.1-terminus | $0.27 | $1.00 | $0.22 | 163.84K |
| deepseek-v3.2 | $0.26 | $0.38 | $0.13 | 163.84K |
| deepseek-v4-flash | $0.09 | $0.18 | $0.02 | 1.05M |
| deepseek-v4-flash-0731 | $0.08 | $0.18 | $0.02 | 1.05M |
| deepseek-v4-pro | $1.30 | $2.60 | $0.10 | 1.05M |
| deepseek-v4-pro-0813 | $1.30 | $2.60 | $0.10 | 1.05M |
| deepseek-v4.1-flash | $0.14 | $0.42 | $0.0042 | 1.05M |
| deepseek-v4.1-flash-1017 | $0.14 | $0.42 | $0.0042 | 1.05M |
| gemini-2.5-flash | $0.30 | $2.50 | — | 1M |
| gemini-2.5-pro | $1.25 | $10.00 | — | 1M |
| gemini-3.1-flash-lite | $0.25 | $1.50 | — | 1M |
| gemini-3.1-pro | $2.00 | $12.00 | — | 1M |
| gemini-3.5-flash | $1.50 | $9.00 | — | 1M |
| gemini-3.7-flash | $0.75 | $3.75 | — | 1M |
| gemma-3-4b-it | $0.05 | $0.10 | — | 131.07K |
| gemma-3-12b-it | $0.05 | $0.15 | — | 131.07K |
| gemma-3-27b-it | $0.08 | $0.16 | — | 131.07K |
| gemma-4-26b-a4b-it | $0.07 | $0.34 | — | 262.14K |
| gemma-4-31b-it | $0.13 | $0.38 | — | 262.14K |
| gemma-4-31b-it-turbo | $0.09 | $0.34 | $0.05 | 262.14K |
| gemma-4-31b-it-ultra | $0.27 | $0.76 | — | 131.07K |
| gemma-4-e4b-it | $0.02 | $0.10 | — | 131.07K |
| glm-4.5 | $0.40 | $1.60 | — | 131.07K |
| glm-4.6 | $0.50 | $2.00 | $0.10 | 202.75K |
| glm-4.7 | $0.40 | $1.75 | $0.08 | 202.75K |
| glm-4.7-flash | $0.06 | $0.40 | $0.01 | 202.75K |
| glm-5 | $0.60 | $2.08 | $0.12 | 202.75K |
| glm-5.1 | $1.05 | $3.50 | $0.20 | 202.75K |
| glm-5.2 | $0.75 | $2.40 | $0.14 | 1.05M |
| gpt-oss-20b | $0.03 | $0.14 | — | 131.07K |
| gpt-oss-120b | $0.04 | $0.17 | — | 131.07K |
| gpt-oss-120b-turbo | $0.15 | $0.60 | — | 131.07K |
| gpt-oss-120b-ultra | $0.20 | $0.95 | — | 131.07K |
| hermes-3-llama-3.1-70b | $0.70 | $0.70 | — | 131.07K |
| hermes-3-llama-3.1-405b | $1.00 | $1.00 | — | 131.07K |
| hy3 | $0.14 | $0.58 | $0.04 | 262.14K |
| inkling | $0.95 | $4.05 | $0.16 | 524.29K |
| inkling-small | $0.45 | $1.20 | $0.10 | 524.29K |
| kimi-k2-instruct | $0.50 | $2.00 | — | 131.07K |
| kimi-k2-instruct-0905 | $0.50 | $2.00 | $0.40 | 262.14K |
| kimi-k2.5 | $0.45 | $2.25 | $0.07 | 262.14K |
| kimi-k2.6 | $0.75 | $3.50 | $0.15 | 262.14K |
| kimi-k2.7-code | $0.68 | $3.40 | $0.14 | 262.14K |
| kimi-k3 | $2.85 | $14.25 | $0.28 | 1.05M |
| l3-8b-lunaris-v1-turbo | $0.04 | $0.05 | — | 8.19K |
| l3.1-70b-euryale-v2.2 | $0.85 | $0.85 | — | 131.07K |
| l3.3-70b-euryale-v2.3 | $0.65 | $0.75 | — | 131.07K |
| ling-3.0-flash | $0.06 | $0.18 | $0.01 | 131.07K |
| llama-3.1-nemotron-70b-instruct | $0.60 | $0.60 | — | 131.07K |
| llama-3.2-3b-instruct | $0.02 | $0.02 | — | 131.07K |
| llama-3.2-11b-vision-instruct | $0.05 | $0.05 | — | 131.07K |
| llama-3.3-70b-instruct | $0.23 | $0.40 | — | 131.07K |
| llama-3.3-70b-instruct-turbo | $0.10 | $0.32 | — | 131.07K |
| llama-3.3-nemotron-super-49b-v1.5 | $0.10 | $0.40 | — | 131.07K |
| llama-4-maverick-17b-128e-instruct-fp8 | $0.20 | $0.80 | — | 1.05M |
| llama-4-scout-17b-16e-instruct | $0.10 | $0.30 | — | 327.68K |
| llama-guard-3-8b | $0.06 | $0.06 | — | 131.07K |
| llama-guard-4-12b | $0.18 | $0.18 | — | 163.84K |
| meta-llama-3-8b-instruct | $0.03 | $0.06 | — | 8.19K |
| meta-llama-3.1-8b-instruct | $0.03 | $0.05 | — | 131.07K |
| meta-llama-3.1-8b-instruct-turbo | $0.02 | $0.04 | — | 131.07K |
| meta-llama-3.1-70b-instruct | $0.40 | $0.40 | — | 131.07K |
| meta-llama-3.1-70b-instruct-turbo | $0.40 | $0.40 | — | 131.07K |
| mimo-v2.5 | $0.40 | $2.00 | $0.08 | 262.14K |
| mimo-v2.5-pro | $1.00 | $3.00 | $0.20 | 1.05M |
| minimax-m2.7 | $0.25 | $1.00 | $0.05 | 196.61K |
| minimax-m2.7-turbo | $0.38 | $1.70 | $0.07 | 196.61K |
| minimax-m3 | $0.28 | $1.10 | $0.06 | 524.29K |
| mistral-nemo-instruct-2407 | $0.02 | $0.03 | — | 131.07K |
| mistral-small-3.2-24b-instruct-2506 | $0.08 | $0.20 | — | 128K |
| mistral-small-24b-instruct-2501 | $0.05 | $0.08 | — | 32.77K |
| mixtral-8x7b-instruct-v0.1 | $0.40 | $0.40 | — | 32.77K |
| muse-glimmer-30b | $0.30 | $1.20 | $0.04 | 131.07K |
| mythomax-l2-13b | $0.40 | $0.40 | — | 4.1K |
| nemotron-3-nano-30b-a3b | $0.05 | $0.20 | $0.02 | 262.14K |
| nemotron-content-safety-3.5 | $0.20 | $0.20 | — | 131.07K |
| nvidia-nemotron-3-super-120b-a12b | $0.08 | $0.40 | — | 262.14K |
| nvidia-nemotron-3-ultra-550b-a55b | $0.50 | $2.20 | $0.10 | 262.14K |
| nvidia-nemotron-3.5-lightning | $0.08 | $0.20 | $0.04 | 262.14K |
| nvidia-nemotron-nano-9b-v2 | $0.04 | $0.16 | — | 131.07K |
| olmocr-7b-0725-fp8 | $0.27 | $1.50 | — | 16.38K |
| phi-4 | $0.07 | $0.14 | — | 16.38K |
| qwen2.5-7b-instruct | $0.04 | $0.10 | — | 32.77K |
| qwen2.5-72b-instruct | $0.36 | $0.40 | — | 32.77K |
| qwen2.5-vl-32b-instruct | $0.20 | $0.60 | — | 128K |
| qwen3-14b | $0.12 | $0.24 | — | 40.96K |
| qwen3-30b-a3b | $0.12 | $0.50 | — | 40.96K |
| qwen3-32b | $0.08 | $0.28 | — | 40.96K |
| qwen3-235b-a22b | $0.18 | $0.54 | — | 40.96K |
| qwen3-235b-a22b-instruct-2507 | $0.09 | $0.55 | — | 262.14K |
| qwen3-235b-a22b-thinking-2507 | $0.30 | $2.90 | — | 262.14K |
| qwen3-coder-480b-a35b-instruct | $0.40 | $1.60 | — | 262.14K |
| qwen3-coder-480b-a35b-instruct-turbo | $0.30 | $1.00 | $0.10 | 262.14K |
| qwen3-max | $1.20 | $6.00 | $0.24 | 256K |
| qwen3-max-thinking | $1.20 | $6.00 | $0.24 | 256K |
| qwen3-next-80b-a3b-instruct | $0.09 | $1.10 | — | 262.14K |
| qwen3-next-80b-a3b-thinking | $0.14 | $1.40 | — | 262.14K |
| qwen3-vl-30b-a3b-instruct | $0.15 | $0.60 | — | 262.14K |
| qwen3-vl-235b-a22b-instruct | $0.20 | $0.88 | $0.11 | 262.14K |
| qwen3.5-9b | $0.10 | $0.15 | — | 262.14K |
| qwen3.5-27b | $0.26 | $2.60 | — | 262.14K |
| qwen3.5-35b-a3b | $0.14 | $1.00 | $0.05 | 262.14K |
| qwen3.5-122b-a10b | $0.29 | $2.40 | — | 262.14K |
| qwen3.5-397b-a17b | $0.45 | $3.00 | $0.22 | 262.14K |
| qwen3.6-27b | $0.32 | $3.20 | — | 262.14K |
| qwen3.6-35b-a3b | $0.10 | $0.95 | — | 262.14K |
| qwen3.7-max | $2.50 | $7.50 | $0.50 | 256K |
| qwen3.8-2.4t-a95b | $2.00 | $6.00 | $0.20 | 262.14K |
| qwen3.8-27b | $0.40 | $3.00 | $0.04 | 262.14K |
| qwen3.8-max | $1.65 | $4.95 | $0.21 | 256K |
| qwq-32b | $0.15 | $0.40 | — | 131.07K |
| seed-1.8 | $0.25 | $2.00 | $0.05 | 256K |
| seed-2.0-code | $0.50 | $3.00 | $0.10 | 256K |
| seed-2.0-mini | $0.10 | $0.40 | $0.02 | 256K |
| seed-2.0-pro | $0.50 | $3.00 | $0.10 | 256K |
| step-3.7-flash | $0.20 | $1.15 | $0.04 | 262.14K |
| wizardlm-2-8x22b | $0.48 | $0.48 | — | 65.54K |

## deepseek

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| deepseek flash latest | $0.02 | $1.00 | $0.02 | 1.05M |
| deepseek pro latest | $0.22 | $8.00 | $0.22 | 1.05M |
| deepseek v3 0324 | $0.29 | $1.14 | $0.11 | 163.84K |
| deepseek v3.1 | $0.25 | $0.95 | $0.13 | 163.84K |
| deepseek v3.1 terminus | $0.27 | $1.00 | — | 163.84K |
| deepseek v3.2 exp | $0.27 | $0.41 | — | 163.84K |
| deepseek v4 flash 0731 | $0.12 | $0.24 | $0.02 | 1.05M |
| deepseek v4 flash latest | $0.05 | $0.16 | $0.03 | 1.05M |
| deepseek v4 pro 0813 | $0.66 | $1.98 | $0.02 | 1.05M |
| deepseek v4.1 flash | $0.14 | $0.42 | $0.0042 | 1.05M |
| deepseek v4.1 flash 1017 | $0.15 | $0.60 | $0.003 | 1.05M |
| deepseek v4.1 flash (batch) | $0.05 | $0.15 | $0.004 | 1.05M |
| deepseek-chat | $0.28 | $0.42 | $0.03 | 131.07K |
| deepseek-coder | $0.14 | $0.28 | $0.01 | 128K |
| deepseek-flash | $0.30 | $1.20 | $0.006 | 1M |
| deepseek-r1 | $0.55 | $2.19 | $0.14 | 65.54K |
| deepseek-reasoner | $0.28 | $0.42 | $0.03 | 131.07K |
| deepseek-v3 | $0.27 | $1.10 | $0.07 | 65.54K |
| deepseek-v3.2 | $0.28 | $0.40 | $0.03 | 163.84K |
| deepseek-v4-flash | $0.30 | $1.20 | $0.006 | 1M |
| deepseek-v4-flash-vision-exp | $0.30 | $1.20 | $0.006 | 1M |
| deepseek-v4-pro | $1.32 | $3.96 | $0.04 | 1M |
| r1 0528 | $0.50 | $2.15 | $0.35 | 163.84K |

## dots-studio

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| dots studio: dots3-note preview (free) | $0.00 | $0.00 | — | 512K |

## elorian

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| glimpse | $0.60 | $3.00 | $0.06 | 262.14K |

## fal_ai

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| query | $0.40 | $3.50 | — | — |

## fireworks_ai

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| chronos-hermes-13b-v2 | $0.20 | $0.20 | — | 4.1K |
| code-llama-7b | $0.20 | $0.20 | — | 16.38K |
| code-llama-7b-instruct | $0.20 | $0.20 | — | 16.38K |
| code-llama-7b-python | $0.20 | $0.20 | — | 16.38K |
| code-llama-13b | $0.20 | $0.20 | — | 16.38K |
| code-llama-13b-instruct | $0.20 | $0.20 | — | 16.38K |
| code-llama-13b-python | $0.20 | $0.20 | — | 16.38K |
| code-llama-34b | $0.90 | $0.90 | — | 16.38K |
| code-llama-34b-instruct | $0.90 | $0.90 | — | 16.38K |
| code-llama-34b-python | $0.90 | $0.90 | — | 16.38K |
| code-llama-70b | $0.90 | $0.90 | — | 4.1K |
| code-llama-70b-instruct | $0.90 | $0.90 | — | 4.1K |
| code-llama-70b-python | $0.90 | $0.90 | — | 4.1K |
| code-qwen-1p5-7b | $0.20 | $0.20 | — | 65.54K |
| codegemma-2b | $0.10 | $0.10 | — | 8.19K |
| codegemma-7b | $0.20 | $0.20 | — | 8.19K |
| cogito-671b-v2-p1 | $1.20 | $1.20 | — | 163.84K |
| cogito-v1-preview-llama-3b | $0.10 | $0.10 | — | 131.07K |
| cogito-v1-preview-llama-8b | $0.20 | $0.20 | — | 131.07K |
| cogito-v1-preview-llama-70b | $0.90 | $0.90 | — | 131.07K |
| cogito-v1-preview-qwen-14b | $0.20 | $0.20 | — | 131.07K |
| cogito-v1-preview-qwen-32b | $0.90 | $0.90 | — | 131.07K |
| dbrx-instruct | $1.20 | $1.20 | — | 32.77K |
| deepseek-coder-1b-base | $0.10 | $0.10 | — | 16.38K |
| deepseek-coder-7b-base | $0.20 | $0.20 | — | 4.1K |
| deepseek-coder-7b-base-v1p5 | $0.20 | $0.20 | — | 4.1K |
| deepseek-coder-7b-instruct-v1p5 | $0.20 | $0.20 | — | 4.1K |
| deepseek-coder-33b-instruct | $0.90 | $0.90 | — | 16.38K |
| deepseek-coder-v2-instruct | $1.20 | $1.20 | — | 65.54K |
| deepseek-coder-v2-lite-base | $0.50 | $0.50 | — | 163.84K |
| deepseek-coder-v2-lite-instruct | $0.50 | $0.50 | — | 163.84K |
| deepseek-prover-v2 | $1.20 | $1.20 | — | 163.84K |
| deepseek-r1 | $3.00 | $8.00 | — | 163.84K |
| deepseek-r1-0528 | $3.00 | $8.00 | — | 163.84K |
| deepseek-r1-0528-distill-qwen3-8b | $0.20 | $0.20 | — | 131.07K |
| deepseek-r1-basic | $0.55 | $2.19 | — | 163.84K |
| deepseek-r1-distill-llama-8b | $0.20 | $0.20 | — | 131.07K |
| deepseek-r1-distill-llama-70b | $0.90 | $0.90 | — | 131.07K |
| deepseek-r1-distill-qwen-1p5b | $0.10 | $0.10 | — | 131.07K |
| deepseek-r1-distill-qwen-7b | $0.20 | $0.20 | — | 131.07K |
| deepseek-r1-distill-qwen-14b | $0.20 | $0.20 | — | 131.07K |
| deepseek-r1-distill-qwen-32b | $0.90 | $0.90 | — | 131.07K |
| deepseek-v2-lite-chat | $0.50 | $0.50 | — | 163.84K |
| deepseek-v2p5 | $1.20 | $1.20 | — | 32.77K |
| deepseek-v3 | $0.90 | $0.90 | — | 131.07K |
| deepseek-v3-0324 | $0.90 | $0.90 | — | 163.84K |
| deepseek-v3p1 | $0.56 | $1.68 | — | 128K |
| deepseek-v3p1-terminus | $0.56 | $1.68 | — | 128K |
| deepseek-v3p2 | $0.56 | $1.68 | — | 163.84K |
| deepseek-v4-flash | $0.14 | $0.28 | $0.03 | 1.05M |
| deepseek-v4-flash-0731 | $0.22 | $0.66 | $0.007 | 1.05M |
| deepseek-v4-flash-vision-exp | $0.22 | $0.66 | $0.007 | 1.05M |
| deepseek-v4-pro | $1.20 | $1.20 | $0.60 | 1.05M |
| deepseek-v4-pro-0813 | $1.32 | $3.96 | $0.04 | 1.05M |
| deepseek-v4p1-flash | $0.30 | $1.20 | $0.006 | 1.05M |
| deepseek-v4p1-flash-1017 | $0.30 | $1.20 | $0.006 | 1.05M |
| deepseek-v4p1-flash-1017-us | $0.45 | $1.80 | $0.009 | 1.05M |
| deepseek-v4p1-flash-us | $0.45 | $1.80 | $0.009 | 1.05M |
| devstral-small-2505 | $0.90 | $0.90 | — | 131.07K |
| dobby-mini-unhinged-plus-llama-3-1-8b | $0.20 | $0.20 | — | 131.07K |
| dobby-unhinged-llama-3-3-70b-new | $0.90 | $0.90 | — | 131.07K |
| dolphin-2-9-2-qwen2-72b | $0.90 | $0.90 | — | 131.07K |
| dolphin-2p6-mixtral-8x7b | $0.50 | $0.50 | — | 32.77K |
| ember-1 | $3.00 | $15.00 | $0.30 | 1.05M |
| ember-1 | $3.00 | $15.00 | $0.30 | 1.05M |
| ernie-4p5-21b-a3b-pt | $0.10 | $0.10 | — | 131.07K |
| ernie-4p5-300b-a47b-pt | $0.10 | $0.10 | — | 131.07K |
| fare-20b | $0.90 | $0.90 | — | 131.07K |
| firefunction-v1 | $0.50 | $0.50 | — | 32.77K |
| firefunction-v2 | $0.90 | $0.90 | — | 8.19K |
| firellava-13b | $0.20 | $0.20 | — | 4.1K |
| firesearch-ocr-v6 | $0.20 | $0.20 | — | 8.19K |
| fireworks-ai-4.1b-to-16b | $0.20 | $0.20 | — | — |
| fireworks-ai-56b-to-176b | $1.20 | $1.20 | — | — |
| fireworks-ai-above-16b | $0.90 | $0.90 | — | — |
| fireworks-ai-default | $0.00 | $0.00 | — | — |
| fireworks-ai-moe-up-to-56b | $0.50 | $0.50 | — | — |
| fireworks-ai-up-to-4b | $0.10 | $0.10 | — | — |
| fireworks-asr-large | $0.00 | $0.00 | — | 4.1K |
| fireworks-asr-v2 | $0.00 | $0.00 | — | 4.1K |
| flux-1-dev | $0.10 | $0.10 | — | 4.1K |
| flux-1-dev-controlnet-union | $0.001 | $0.001 | — | 4.1K |
| flux-1-dev-fp8 | $0.0005 | $0.0005 | — | 4.1K |
| flux-1-schnell | $0.10 | $0.10 | — | 4.1K |
| flux-1-schnell-fp8 | $0.00035 | $0.00035 | — | 4.1K |
| flux-kontext-max | $0.08 | $0.08 | — | 4.1K |
| flux-kontext-pro | $0.04 | $0.04 | — | 4.1K |
| gemma2-9b-it | $0.20 | $0.20 | — | 8.19K |
| gemma-2b-it | $0.10 | $0.10 | — | 8.19K |
| gemma-3-27b-it | $0.90 | $0.90 | — | 131.07K |
| gemma-7b | $0.20 | $0.20 | — | 8.19K |
| gemma-7b-it | $0.20 | $0.20 | — | 8.19K |
| glm-4p5 | $0.55 | $2.19 | — | 131.07K |
| glm-4p5-air | $0.22 | $0.88 | — | 131.07K |
| glm-4p5v | $1.20 | $1.20 | — | 131.07K |
| glm-4p6 | $0.55 | $2.19 | — | 202.75K |
| glm-4p7 | $0.60 | $2.20 | $0.30 | 202.75K |
| glm-5p1 | $1.40 | $4.40 | $0.26 | 202.75K |
| glm-5p1-fast | $2.80 | $8.80 | $0.52 | 202.8K |
| glm-5p2 | $1.40 | $4.40 | $0.14 | 1.05M |
| glm-5p2-fast | $2.10 | $6.60 | $0.21 | 1.05M |
| glm-5p2-fast-us | $2.10 | $6.60 | $0.21 | 1.05M |
| glm-5p3 | $1.40 | $4.40 | $0.26 | 1.05M |
| glm-5p3-fast | $2.10 | $6.60 | $0.39 | 1.05M |
| glm-5p3-flash | $0.15 | $0.50 | $0.03 | 1.05M |
| glm-5p3-flash-us | $0.22 | $0.75 | $0.04 | 1.05M |
| glm-5p3-us | $2.10 | $6.60 | $0.39 | 1.05M |
| gpt-oss-20b | $0.07 | $0.30 | $0.04 | 131.07K |
| gpt-oss-120b | $0.15 | $0.60 | $0.02 | 131.07K |
| gpt-oss-safeguard-20b | $0.50 | $0.50 | — | 131.07K |
| gpt-oss-safeguard-120b | $1.20 | $1.20 | — | 131.07K |
| hermes-2-pro-mistral-7b | $0.20 | $0.20 | — | 32.77K |
| inkling | $1.00 | $4.05 | $0.17 | 1.05M |
| internvl3-8b | $0.20 | $0.20 | — | 16.38K |
| internvl3-38b | $0.90 | $0.90 | — | 16.38K |
| internvl3-78b | $0.90 | $0.90 | — | 16.38K |
| japanese-stable-diffusion-xl | $0.00013 | $0.00013 | — | 4.1K |
| kat-coder | $0.90 | $0.90 | — | 262.14K |
| kat-dev-32b | $0.90 | $0.90 | — | 131.07K |
| kat-dev-72b-exp | $0.90 | $0.90 | — | 131.07K |
| kimi-k2-instruct | $0.60 | $2.50 | — | 131.07K |
| kimi-k2-instruct-0905 | $0.60 | $2.50 | — | 262.14K |
| kimi-k2-thinking | $0.60 | $2.50 | — | 262.14K |
| kimi-k2p5 | $0.60 | $3.00 | $0.10 | 262.14K |
| kimi-k2p6 | $0.95 | $4.00 | $0.16 | 262.14K |
| kimi-k2p6-fast | $2.00 | $8.00 | $0.30 | 262.14K |
| kimi-k2p7-code | $0.95 | $4.00 | $0.19 | 262.14K |
| kimi-k2p7-code-fast | $1.90 | $8.00 | $0.38 | 262.14K |
| kimi-k3 | $3.00 | $15.00 | $0.30 | 1.05M |
| kimi-k3-fast | $4.50 | $22.50 | $0.45 | 1.05M |
| kimi-k3-us | $4.50 | $22.50 | $0.45 | 1.05M |
| llama4-maverick-instruct-basic | $0.22 | $0.88 | — | 131.07K |
| llama4-scout-instruct-basic | $0.15 | $0.60 | — | 131.07K |
| llama-guard-2-8b | $0.20 | $0.20 | — | 8.19K |
| llama-guard-3-1b | $0.10 | $0.10 | — | 131.07K |
| llama-guard-3-8b | $0.20 | $0.20 | — | 131.07K |
| llama-v2-7b | $0.20 | $0.20 | — | 4.1K |
| llama-v2-7b-chat | $0.20 | $0.20 | — | 4.1K |
| llama-v2-13b | $0.20 | $0.20 | — | 4.1K |
| llama-v2-13b-chat | $0.20 | $0.20 | — | 4.1K |
| llama-v2-70b | $0.10 | $0.10 | — | 4.1K |
| llama-v2-70b-chat | $0.90 | $0.90 | — | 2.05K |
| llama-v3-8b | $0.20 | $0.20 | — | 8.19K |
| llama-v3-8b-instruct-hf | $0.20 | $0.20 | — | 8.19K |
| llama-v3-70b-instruct | $0.90 | $0.90 | — | 8.19K |
| llama-v3-70b-instruct-hf | $0.90 | $0.90 | — | 8.19K |
| llama-v3p1-8b-instruct | $0.10 | $0.10 | — | 131.07K |
| llama-v3p1-70b-instruct | $0.90 | $0.90 | — | 131.07K |
| llama-v3p1-70b-instruct-1b | $0.10 | $0.10 | — | 4.1K |
| llama-v3p1-405b-instruct | $3.00 | $3.00 | — | 131.07K |
| llama-v3p1-405b-instruct-long | $0.10 | $0.10 | — | 4.1K |
| llama-v3p1-nemotron-70b-instruct | $0.90 | $0.90 | — | 131.07K |
| llama-v3p2-1b | $0.10 | $0.10 | — | 131.07K |
| llama-v3p2-1b-instruct | $0.10 | $0.10 | — | 131.07K |
| llama-v3p2-3b | $0.10 | $0.10 | — | 131.07K |
| llama-v3p2-3b-instruct | $0.10 | $0.10 | — | 131.07K |
| llama-v3p2-11b-vision-instruct | $0.20 | $0.20 | — | 131.07K |
| llama-v3p2-90b-vision-instruct | $0.90 | $0.90 | — | 131.07K |
| llama-v3p3-70b-instruct | $0.90 | $0.90 | — | 131.07K |
| llamaguard-7b | $0.20 | $0.20 | — | 4.1K |
| llava-yi-34b | $0.90 | $0.90 | — | 4.1K |
| minimax-m1-80k | $0.10 | $0.10 | — | 4.1K |
| minimax-m2 | $0.30 | $1.20 | — | 196.61K |
| minimax-m2p1 | $0.30 | $1.20 | $0.03 | 196.61K |
| minimax-m3 | $0.30 | $1.20 | $0.06 | 512K |
| minimax-m3p1-flash | $0.15 | $0.60 | $0.02 | 1.05M |
| ministral-3-3b-instruct-2512 | $0.10 | $0.10 | — | 256K |
| ministral-3-8b-instruct-2512 | $0.20 | $0.20 | — | 256K |
| ministral-3-14b-instruct-2512 | $0.20 | $0.20 | — | 256K |
| mistral-7b | $0.20 | $0.20 | — | 32.77K |
| mistral-7b-instruct-4k | $0.20 | $0.20 | — | 32.77K |
| mistral-7b-instruct-v0p2 | $0.20 | $0.20 | — | 32.77K |
| mistral-7b-instruct-v3 | $0.20 | $0.20 | — | 32.77K |
| mistral-7b-v0p2 | $0.20 | $0.20 | — | 32.77K |
| mistral-large-3-fp8 | $1.20 | $1.20 | — | 256K |
| mistral-nemo-base-2407 | $0.20 | $0.20 | — | 128K |
| mistral-nemo-instruct-2407 | $0.20 | $0.20 | — | 128K |
| mistral-small-24b-instruct-2501 | $0.90 | $0.90 | — | 32.77K |
| mixtral-8x7b | $0.50 | $0.50 | — | 32.77K |
| mixtral-8x7b-instruct | $0.50 | $0.50 | — | 32.77K |
| mixtral-8x7b-instruct-hf | $0.50 | $0.50 | — | 32.77K |
| mixtral-8x22b | $1.20 | $1.20 | — | 65.54K |
| mixtral-8x22b-instruct | $1.20 | $1.20 | — | 65.54K |
| mixtral-8x22b-instruct-hf | $1.20 | $1.20 | — | 65.54K |
| muse-glimmer-30b | $0.35 | $1.50 | $0.04 | 131.07K |
| muse-spark-open | $1.25 | $4.25 | $0.15 | 1.05M |
| mythomax-l2-13b | $0.20 | $0.20 | — | 4.1K |
| nemotron-3-ultra-nvfp4 | $0.60 | $2.40 | $0.12 | 262.14K |
| nemotron-lightning-3p5-30b-a3b | $0.05 | $0.20 | $0.01 | 262.14K |
| nemotron-nano-v2-12b-vl | $0.10 | $0.10 | — | 131.07K |
| nous-capybara-7b-v1p9 | $0.20 | $0.20 | — | 32.77K |
| nous-hermes-2-mixtral-8x7b-dpo | $0.50 | $0.50 | — | 32.77K |
| nous-hermes-2-yi-34b | $0.90 | $0.90 | — | 4.1K |
| nous-hermes-llama2-7b | $0.20 | $0.20 | — | 4.1K |
| nous-hermes-llama2-13b | $0.20 | $0.20 | — | 4.1K |
| nous-hermes-llama2-70b | $0.90 | $0.90 | — | 4.1K |
| nvidia-nemotron-nano-9b-v2 | $0.20 | $0.20 | — | 128K |
| nvidia-nemotron-nano-12b-v2 | $0.20 | $0.20 | — | 128K |
| openchat-3p5-0106-7b | $0.20 | $0.20 | — | 8.19K |
| openhermes-2-mistral-7b | $0.20 | $0.20 | — | 32.77K |
| openhermes-2p5-mistral-7b | $0.20 | $0.20 | — | 32.77K |
| openorca-7b | $0.20 | $0.20 | — | 32.77K |
| phi-2-3b | $0.10 | $0.10 | — | 2.05K |
| phi-3-mini-128k-instruct | $0.10 | $0.10 | — | 131.07K |
| phi-3-vision-128k-instruct | $0.20 | $0.20 | — | 32.06K |
| phind-code-llama-34b-python-v1 | $0.90 | $0.90 | — | 16.38K |
| phind-code-llama-34b-v1 | $0.90 | $0.90 | — | 16.38K |
| phind-code-llama-34b-v2 | $0.90 | $0.90 | — | 16.38K |
| playground-v2-5-1024px-aesthetic | $0.00013 | $0.00013 | — | 4.1K |
| playground-v2-1024px-aesthetic | $0.00013 | $0.00013 | — | 4.1K |
| pythia-12b | $0.20 | $0.20 | — | 2.05K |
| qwen1p5-72b-chat | $0.90 | $0.90 | — | 32.77K |
| qwen2-7b-instruct | $0.20 | $0.20 | — | 32.77K |
| qwen2-72b-instruct | $0.90 | $0.90 | — | 32.77K |
| qwen2-vl-2b-instruct | $0.10 | $0.10 | — | 32.77K |
| qwen2-vl-7b-instruct | $0.20 | $0.20 | — | 32.77K |
| qwen2-vl-72b-instruct | $0.90 | $0.90 | — | 32.77K |
| qwen2p5-0p5b-instruct | $0.10 | $0.10 | — | 32.77K |
| qwen2p5-1p5b-instruct | $0.10 | $0.10 | — | 32.77K |
| qwen2p5-7b-instruct | $0.20 | $0.20 | — | 32.77K |
| qwen2p5-14b | $0.20 | $0.20 | — | 131.07K |
| qwen2p5-32b | $0.90 | $0.90 | — | 131.07K |
| qwen2p5-32b-instruct | $0.90 | $0.90 | — | 32.77K |
| qwen2p5-72b | $0.90 | $0.90 | — | 131.07K |
| qwen2p5-72b-instruct | $0.90 | $0.90 | — | 32.77K |
| qwen2p5-coder-0p5b | $0.10 | $0.10 | — | 32.77K |
| qwen2p5-coder-0p5b-instruct | $0.10 | $0.10 | — | 32.77K |
| qwen2p5-coder-1p5b | $0.10 | $0.10 | — | 32.77K |
| qwen2p5-coder-1p5b-instruct | $0.10 | $0.10 | — | 32.77K |
| qwen2p5-coder-3b | $0.10 | $0.10 | — | 32.77K |
| qwen2p5-coder-3b-instruct | $0.10 | $0.10 | — | 32.77K |
| qwen2p5-coder-7b | $0.20 | $0.20 | — | 32.77K |
| qwen2p5-coder-7b-instruct | $0.20 | $0.20 | — | 32.77K |
| qwen2p5-coder-14b | $0.20 | $0.20 | — | 32.77K |
| qwen2p5-coder-14b-instruct | $0.20 | $0.20 | — | 32.77K |
| qwen2p5-coder-32b | $0.90 | $0.90 | — | 32.77K |
| qwen2p5-coder-32b-instruct | $0.90 | $0.90 | — | 4.1K |
| qwen2p5-coder-32b-instruct-32k-rope | $0.90 | $0.90 | — | 32.77K |
| qwen2p5-coder-32b-instruct-64k | $0.90 | $0.90 | — | 65.54K |
| qwen2p5-coder-32b-instruct-128k | $0.90 | $0.90 | — | 131.07K |
| qwen2p5-math-72b-instruct | $0.90 | $0.90 | — | 4.1K |
| qwen2p5-vl-3b-instruct | $0.20 | $0.20 | — | 128K |
| qwen2p5-vl-7b-instruct | $0.20 | $0.20 | — | 128K |
| qwen2p5-vl-32b-instruct | $0.90 | $0.90 | — | 128K |
| qwen2p5-vl-72b-instruct | $0.90 | $0.90 | — | 128K |
| qwen3-0p6b | $0.10 | $0.10 | — | 40.96K |
| qwen3-1p7b | $0.10 | $0.10 | — | 131.07K |
| qwen3-1p7b-fp8-draft | $0.10 | $0.10 | — | 262.14K |
| qwen3-1p7b-fp8-draft-40960 | $0.10 | $0.10 | — | 40.96K |
| qwen3-1p7b-fp8-draft-131072 | $0.10 | $0.10 | — | 131.07K |
| qwen3-4b | $0.20 | $0.20 | — | 40.96K |
| qwen3-4b-instruct-2507 | $0.20 | $0.20 | — | 262.14K |
| qwen3-8b | $0.20 | $0.20 | — | 40.96K |
| qwen3-14b | $0.20 | $0.20 | — | 40.96K |
| qwen3-30b-a3b | $0.15 | $0.60 | — | 131.07K |
| qwen3-30b-a3b-instruct-2507 | $0.50 | $0.50 | — | 262.14K |
| qwen3-30b-a3b-thinking-2507 | $0.90 | $0.90 | — | 262.14K |
| qwen3-32b | $0.90 | $0.90 | — | 131.07K |
| qwen3-235b-a22b | $0.22 | $0.88 | — | 131.07K |
| qwen3-235b-a22b-instruct-2507 | $0.22 | $0.88 | — | 262.14K |
| qwen3-235b-a22b-thinking-2507 | $0.22 | $0.88 | — | 262.14K |
| qwen3-coder-30b-a3b-instruct | $0.15 | $0.60 | — | 262.14K |
| qwen3-coder-480b-a35b-instruct | $0.45 | $1.80 | — | 262.14K |
| qwen3-coder-480b-instruct-bf16 | $0.90 | $0.90 | — | 262.14K |
| qwen3-embedding-0p6b | $0.00 | $0.00 | — | 32.77K |
| qwen3-embedding-4b | $0.00 | $0.00 | — | 40.96K |
| qwen3-embedding-8b | $0.10 | $0.00 | — | 40.96K |
| qwen3-next-80b-a3b-instruct | $0.90 | $0.90 | — | 4.1K |
| qwen3-next-80b-a3b-thinking | $0.90 | $0.90 | — | 4.1K |
| qwen3-reranker-0p6b | $0.00 | $0.00 | — | 40.96K |
| qwen3-reranker-4b | $0.00 | $0.00 | — | 40.96K |
| qwen3-reranker-8b | $0.20 | $0.00 | — | 40.96K |
| qwen3-vl-8b-instruct | $0.20 | $0.20 | — | 262.14K |
| qwen3-vl-30b-a3b-instruct | $0.15 | $0.60 | — | 262.14K |
| qwen3-vl-30b-a3b-thinking | $0.15 | $0.60 | — | 262.14K |
| qwen3-vl-32b-instruct | $0.90 | $0.90 | — | 4.1K |
| qwen3-vl-235b-a22b-instruct | $0.22 | $0.88 | — | 262.14K |
| qwen3-vl-235b-a22b-thinking | $0.22 | $0.88 | — | 262.14K |
| qwen3p7-plus | $0.40 | $1.60 | $0.08 | 262.14K |
| qwen3p8-max | $2.00 | $6.00 | $0.25 | 262.14K |
| qwen-qwq-32b-preview | $0.90 | $0.90 | — | 32.77K |
| qwen-v2p5-7b | $0.20 | $0.20 | — | 131.07K |
| qwen-v2p5-14b-instruct | $0.20 | $0.20 | — | 32.77K |
| qwq-32b | $0.90 | $0.90 | — | 131.07K |
| rolm-ocr | $0.20 | $0.20 | — | 128K |
| rune | $0.04 | $0.00 | $0.0084 | 262.14K |
| snorkel-mistral-7b-pairrm-dpo | $0.20 | $0.20 | — | 32.77K |
| ssd-1b | $0.00013 | $0.00013 | — | 4.1K |
| stable-diffusion-xl-1024-v1-0 | $0.00013 | $0.00013 | — | 4.1K |
| stablecode-3b | $0.10 | $0.10 | — | 4.1K |
| starcoder2-3b | $0.10 | $0.10 | — | 16.38K |
| starcoder2-7b | $0.20 | $0.20 | — | 16.38K |
| starcoder2-15b | $0.20 | $0.20 | — | 16.38K |
| starcoder-7b | $0.20 | $0.20 | — | 8.19K |
| starcoder-16b | $0.20 | $0.20 | — | 8.19K |
| toppy-m-7b | $0.20 | $0.20 | — | 32.77K |
| yi-6b | $0.20 | $0.20 | — | 4.1K |
| yi-34b | $0.90 | $0.90 | — | 4.1K |
| yi-34b-200k-capybara | $0.90 | $0.90 | — | 200K |
| yi-34b-chat | $0.90 | $0.90 | — | 4.1K |
| yi-large | $3.00 | $3.00 | — | 32.77K |
| zephyr-7b-beta | $0.20 | $0.20 | — | 32.77K |

## fireworks_ai-embedding-models

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| fireworks-ai-embedding-150m-to-350m | $0.02 | $0.00 | — | — |
| fireworks-ai-embedding-up-to-150m | $0.008 | $0.00 | — | — |
| gte-base | $0.008 | $0.00 | — | 512 |
| gte-large | $0.02 | $0.00 | — | 512 |
| nomic-embed-text-v1 | $0.008 | $0.00 | — | 8.19K |
| nomic-embed-text-v1.5 | $0.008 | $0.00 | — | 8.19K |
| uae-large-v1 | $0.02 | $0.00 | — | 512 |

## friendliai

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| deepseek-v3.2 | $0.50 | $1.50 | $0.25 | 163.84K |
| gemma-4-31b-it | $0.14 | $0.40 | — | 262.14K |
| glm-5.1 | $1.40 | $4.40 | $0.26 | 202.75K |
| glm-5.2 | $1.40 | $4.40 | $0.26 | 1.05M |
| glm-5.3 | $1.26 | $3.96 | $0.23 | 1.05M |
| glm-5.3-flash | $0.15 | $0.50 | $0.03 | 1.05M |
| minimax-m2.5 | $0.30 | $1.20 | $0.06 | 196.61K |

## gemini

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| deep-research-max-preview-04-2026 | $2.00 | $12.00 | — | 1.05M |
| deep-research-preview-04-2026 | $2.00 | $12.00 | — | 1.05M |
| deep-research-pro-preview-12-2025 | $2.00 | $12.00 | — | 1.05M |
| gemini-2.0-flash-exp-image-generation | $0.00 | $0.00 | — | 32.77K |
| gemini-2.5-computer-use-preview-10-2025 | $1.25 | $10.00 | — | 128K |
| gemini-2.5-flash | $0.30 | $2.50 | $0.03 | 1.05M |
| gemini-2.5-flash-image | $0.30 | $2.50 | $0.03 | 65.54K |
| gemini-2.5-flash-lite | $0.10 | $0.40 | $0.01 | 1.05M |
| gemini-2.5-flash-native-audio-latest | $0.50 | $2.00 | — | 131.07K |
| gemini-2.5-flash-native-audio-preview-09-2025 | $0.50 | $2.00 | — | 1.05M |
| gemini-2.5-flash-native-audio-preview-12-2025 | $0.50 | $2.00 | — | 131.07K |
| gemini-2.5-flash-preview-tts | $0.50 | $10.00 | — | 8.19K |
| gemini-2.5-pro | $1.25 | $10.00 | $0.12 | 1.05M |
| gemini-2.5-pro-preview-tts | $1.00 | $20.00 | $0.12 | 8.19K |
| gemini-3-flash-preview | $0.50 | $3.00 | $0.05 | 1.05M |
| gemini-3-pro-image | $2.00 | $12.00 | — | 65.54K |
| gemini-3-pro-image-preview | $2.00 | $12.00 | — | 131.07K |
| gemini-3.1-flash-image | $0.50 | $3.00 | — | 131.07K |
| gemini-3.1-flash-image-preview | $0.50 | $3.00 | — | 65.54K |
| gemini-3.1-flash-lite | $0.25 | $1.50 | $0.02 | 1.05M |
| gemini-3.1-flash-lite-image | $0.25 | $1.50 | — | 65.54K |
| gemini-3.1-flash-lite-preview | $0.25 | $1.50 | $0.02 | 1.05M |
| gemini-3.1-flash-live-preview | $0.75 | $4.50 | — | 131.07K |
| gemini-3.1-flash-tts-preview | $1.00 | $20.00 | — | 8.19K |
| gemini-3.1-pro-preview | $2.00 | $12.00 | $0.20 | 1.05M |
| gemini-3.1-pro-preview-customtools | $2.00 | $12.00 | $0.20 | 1.05M |
| gemini-3.5-flash | $1.50 | $9.00 | $0.15 | 1.05M |
| gemini-3.5-flash-lite | $0.30 | $2.50 | $0.03 | 1.05M |
| gemini-3.5-live-translate-preview | $3.50 | $21.00 | — | 131.07K |
| gemini-3.5-transcribe | $2.00 | $12.00 | — | 98.3K |
| gemini-3.5-transcribe-live | $3.50 | $21.00 | — | 131.07K |
| gemini-3.6-flash | $0.75 | $3.75 | $0.08 | 1.05M |
| gemini-3.7-flash | $0.75 | $3.75 | $0.08 | 1.05M |
| gemini-3.8-flash | $0.75 | $3.75 | $0.08 | 1.05M |
| gemini-3.8-flash-lite-tts | $0.50 | $6.00 | $0.12 | 8.19K |
| gemini-3.8-flash-tts | $0.50 | $9.00 | $0.12 | 8.19K |
| gemini-3.8-live | $0.75 | $4.50 | — | 131.07K |
| gemini-3.8-live-extended-thinking | $0.75 | $4.50 | — | 131.07K |
| gemini-4-argon | $2.00 | $10.00 | $0.10 | 1.05M |
| gemini-embedding-001 | $0.15 | $0.00 | — | 2.05K |
| gemini-embedding-2 | $0.20 | $0.00 | — | 8.19K |
| gemini-embedding-2-preview | $0.20 | $0.00 | — | 8.19K |
| gemini-exp-1114 | $0.00 | $0.00 | — | 1.05M |
| gemini-exp-1206 | $0.30 | $2.50 | $0.03 | 1.05M |
| gemini-flash-latest | $0.75 | $3.75 | $0.08 | 1.05M |
| gemini-flash-lite-latest | $0.30 | $2.50 | $0.03 | 1.05M |
| gemini-gemma-2-9b-it | $0.35 | $1.05 | — | 8.19K |
| gemini-gemma-2-27b-it | $0.35 | $1.05 | — | 8.19K |
| gemini-live-2.5-flash-preview-native-audio-09-2025 | $0.50 | $2.00 | — | 1.05M |
| gemini-nano-banana-2.1 | $1.50 | $7.50 | — | 131.07K |
| gemini-omni-1.1-flash | $1.50 | $9.00 | — | 1.05M |
| gemini-omni-flash-preview | $1.50 | $9.00 | — | 131.07K |
| gemini-pro-latest | $2.00 | $12.00 | $0.20 | 1.05M |
| gemini-robotics-er-2-preview | $1.00 | $5.00 | $0.10 | 131.07K |
| gemini-robotics-er-2-streaming-preview | $1.00 | $5.00 | — | 131.07K |
| gemma-3-27b-it | $0.00 | $0.00 | — | 131.07K |
| gemma-4-26b-a4b-it | $0.00 | $0.00 | — | 262.14K |
| gemma-4-31b-it | $0.00 | $0.00 | — | 262.14K |
| learnlm-1.5-pro-experimental | $0.00 | $0.00 | — | 32.77K |
| lyria-3-clip-preview | $0.00 | $0.00 | — | 131.07K |
| lyria-3-pro-preview | $0.00 | $0.00 | — | 131.07K |
| lyria-3.5 | $0.00 | $0.00 | — | 131.07K |
| lyria-3.5-clip-preview | $0.00 | $0.00 | — | 131.07K |
| lyria-3.5-pro-preview | $0.00 | $0.00 | — | 131.07K |
| lyria-realtime-exp | $0.00 | $0.00 | — | 1.05M |
| nano-banana-pro-preview | $2.00 | $12.00 | — | 131.07K |

## gigachat

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| embeddings | $0.00 | $0.00 | — | 512 |
| embeddings-2 | $0.00 | $0.00 | — | 512 |
| embeddingsgigar | $0.00 | $0.00 | — | 4.1K |
| gigachat-2 | $0.00 | $0.00 | — | 128K |
| gigachat-2-max | $0.00 | $0.00 | — | 128K |
| gigachat-2-pro | $0.00 | $0.00 | — | 128K |
| gigaembeddings-3b-2025-09 | $0.00 | $0.00 | — | 4.1K |

## github_copilot

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| claude-fable-5 | $10.00 | $50.00 | $1.00 | 200K |
| claude-fable-5.1 | $10.00 | $50.00 | $0.25 | 200K |
| claude-haiku-4.5 | $1.00 | $5.00 | $0.10 | 128K |
| claude-haiku-5.5 | $0.10 | $0.50 | $0.01 | 128K |
| claude-opus-4.8 | $5.00 | $25.00 | $0.50 | 200K |
| claude-opus-4.8-fast | $10.00 | $50.00 | $1.00 | 200K |
| claude-opus-5 | $5.00 | $25.00 | $0.50 | 200K |
| claude-opus-5.5 | $4.00 | $20.00 | $0.20 | 200K |
| claude-sonnet-4.6 | $3.00 | $15.00 | $0.30 | 200K |
| claude-sonnet-5 | $2.00 | $10.00 | $0.20 | 200K |
| claude-sonnet-5.5 | $2.00 | $10.00 | $0.10 | 200K |
| gemini-3.7-flash | $0.75 | $3.75 | $0.08 | 200K |
| gemini-3.8-flash | $0.75 | $3.75 | $0.08 | 200K |
| gemini-4-argon | $2.00 | $10.00 | $0.10 | 200K |
| gpt-5-mini | $0.25 | $2.00 | $0.02 | 128K |
| gpt-5.3-codex | $1.75 | $14.00 | $0.18 | 128K |
| gpt-5.4 | $2.50 | $15.00 | $0.25 | 272K |
| gpt-5.4-mini | $0.75 | $4.50 | $0.08 | 272K |
| gpt-5.4-nano | $0.20 | $1.25 | $0.02 | 272K |
| gpt-5.5 | $5.00 | $30.00 | $0.50 | 272K |
| gpt-5.6-luna | $0.20 | $1.20 | $0.02 | 200K |
| gpt-5.6-sol | $4.00 | $20.00 | $0.40 | 272K |
| gpt-5.6-terra | $2.00 | $12.00 | $0.20 | 272K |
| gpt-6-astra | $10.00 | $50.00 | $1.00 | 922K |
| gpt-6-luna | $0.10 | $0.50 | $0.01 | 922K |
| gpt-6-sol | $2.00 | $10.00 | $0.20 | 922K |
| gpt-6.1-sol | $2.00 | $10.00 | $0.10 | 922K |
| gpt-6.1-terra | $1.00 | $5.00 | $0.05 | 922K |
| grok-4.5 | $2.00 | $6.00 | $0.50 | 500K |
| grok-4.6 | $2.00 | $6.00 | $0.50 | 500K |
| grok-4.7 | $2.00 | $6.00 | $0.50 | 500K |
| kimi-k3 | $3.00 | $15.00 | $0.30 | 917.5K |
| mai-code-1.1-flash | $0.20 | $1.20 | $0.02 | 128K |

## gmi

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| claude-opus-4 | $15.00 | $75.00 | — | 409.6K |
| claude-opus-4.5 | $5.00 | $25.00 | — | 409.6K |
| claude-sonnet-4 | $3.00 | $15.00 | — | 409.6K |
| claude-sonnet-4.5 | $3.00 | $15.00 | — | 409.6K |
| deepseek-v3-0324 | $0.28 | $0.88 | — | 163.84K |
| deepseek-v3.2 | $0.28 | $0.40 | — | 163.84K |
| gemini-3-flash-preview | $0.50 | $3.00 | — | 1.05M |
| glm-4.7-fp8 | $0.40 | $2.00 | — | 202.75K |
| gpt-4o | $2.50 | $10.00 | — | 131.07K |
| gpt-4o-mini | $0.15 | $0.60 | — | 131.07K |
| gpt-5 | $1.25 | $10.00 | — | 409.6K |
| gpt-5.1 | $1.25 | $10.00 | — | 409.6K |
| gpt-5.2 | $1.75 | $14.00 | — | 409.6K |
| kimi-k2-thinking | $0.80 | $1.20 | — | 262.14K |
| minimax-m2.1 | $0.30 | $1.20 | — | 196.61K |
| qwen3-vl-235b-a22b-instruct-fp8 | $0.30 | $1.40 | — | 262.14K |

## google

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| gemini 2.5 flash | $0.30 | $2.50 | $0.03 | 1.05M |
| gemini 2.5 flash lite | $0.10 | $0.40 | $0.01 | 1.05M |
| gemini 2.5 pro | $1.25 | $10.00 | $0.12 | 1.05M |
| gemini 2.5 pro preview 06-05 | $1.25 | $10.00 | $0.12 | 1.05M |
| gemini 3 flash preview | $0.50 | $3.00 | $0.05 | 1.05M |
| gemini 3 flash preview (batch) | $0.25 | $1.50 | — | 1.05M |
| gemini 3.1 flash lite | $0.25 | $1.50 | $0.02 | 1.05M |
| gemini 3.1 flash lite (batch) | $0.12 | $0.75 | $0.01 | 1.05M |
| gemini 3.1 flash lite preview | $0.25 | $1.50 | $0.02 | 1.05M |
| gemini 3.1 pro preview | $2.00 | $12.00 | $0.20 | 1.05M |
| gemini 3.1 pro preview (batch) | $1.00 | $6.00 | — | 1.05M |
| gemini 3.1 pro preview custom tools | $2.00 | $12.00 | $0.20 | 1.05M |
| gemini 3.5 flash | $1.50 | $9.00 | $0.15 | 1.05M |
| gemini 3.5 flash (batch) | $0.75 | $4.50 | $0.08 | 1.05M |
| gemini 3.5 flash lite | $0.30 | $2.50 | $0.03 | 1.05M |
| gemini 3.5 flash lite (batch) | $0.15 | $1.25 | $0.02 | 1.05M |
| gemini 3.6 flash | $0.75 | $3.75 | $0.08 | 1.05M |
| gemini 3.6 flash (batch) | $0.38 | $1.88 | $0.04 | 1.05M |
| gemini 3.7 flash | $0.75 | $3.75 | $0.08 | 1.05M |
| gemini 3.7 flash (batch) | $0.38 | $1.88 | $0.04 | 1.05M |
| gemini 3.8 flash | $0.82 | $4.12 | $0.08 | 1.05M |
| gemini 3.8 flash (batch) | $0.38 | $1.88 | $0.04 | 1.05M |
| gemini 4 argon | $2.00 | $10.00 | $0.10 | 1.05M |
| gemini 4 argon (batch) | $1.00 | $5.00 | $0.05 | 1.05M |
| gemini flash latest | $0.75 | $3.75 | $0.08 | 1.05M |
| gemini pro latest | $2.00 | $10.00 | $0.10 | 1.05M |
| gemma 2 27b | $0.65 | $0.65 | — | 8.19K |
| gemma 3 4b | $0.05 | $0.10 | — | 131.07K |
| gemma 3 12b | $0.05 | $0.15 | — | 131.07K |
| gemma 3 27b | $0.08 | $0.35 | $0.04 | 131.07K |
| gemma 4 26b a4b | $0.09 | $0.30 | $0.05 | 262.14K |
| gemma 4 26b a4b  (free) | $0.00 | $0.00 | — | 262.14K |
| gemma 4 31b | $0.20 | $0.40 | — | 262.14K |
| gemma 4 31b (free) | $0.00 | $0.00 | — | 262.14K |
| lyria 3 clip preview | $0.00 | $0.00 | — | 1.05M |
| lyria 3 pro preview | $0.00 | $0.00 | — | 1.05M |
| nano banana 2 (gemini 3.1 flash image preview) | $0.50 | $3.00 | — | 65.54K |
| nano banana 2 (gemini 3.1 flash image) | $0.50 | $3.00 | — | 131.07K |
| nano banana 2 lite (gemini 3.1 flash lite image) | $0.25 | $1.50 | — | 65.54K |
| nano banana 2.1 | $1.50 | $7.50 | — | 65.54K |
| nano banana (gemini 2.5 flash image) | $0.30 | $2.50 | $0.03 | 32.77K |
| nano banana pro (gemini 3 pro image preview) | $2.00 | $12.00 | $0.20 | 65.54K |
| nano banana pro (gemini 3 pro image) | $2.00 | $12.00 | $0.20 | 131.07K |

## gradient_ai

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| anthropic-claude-3-opus | $15.00 | $75.00 | — | 200K |
| anthropic-claude-3.5-haiku | $0.80 | $4.00 | — | 200K |
| anthropic-claude-3.5-sonnet | $3.00 | $15.00 | — | 200K |
| anthropic-claude-3.7-sonnet | $3.00 | $15.00 | — | 200K |
| deepseek-r1-distill-llama-70b | $0.99 | $0.99 | — | 32.77K |
| llama3-8b-instruct | $0.20 | $0.20 | — | 8.19K |
| llama3.3-70b-instruct | $0.65 | $0.65 | — | 128K |
| mistral-nemo-instruct-2407 | $0.30 | $0.30 | — | 128K |
| openai-o3 | $2.00 | $8.00 | — | 200K |
| openai-o3-mini | $1.10 | $4.40 | — | 200K |

## groq

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| gpt-oss-20b | $0.08 | $0.30 | $0.04 | 131.07K |
| gpt-oss-120b | $0.15 | $0.60 | $0.08 | 131.07K |
| gpt-oss-safeguard-20b | $0.08 | $0.30 | $0.04 | 131.07K |
| llama-guard-3-8b | $0.20 | $0.20 | — | 8.19K |
| llama-prompt-guard-2-22m | $0.03 | $0.03 | — | 512 |
| llama-prompt-guard-2-86m | $0.04 | $0.04 | — | 512 |
| qwen3.8-27b | $0.80 | $4.00 | — | 131.07K |

## gryphe

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| mythomax 13b | $0.08 | $0.11 | — | 8.19K |

## hyperbolic

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| deepseek-r1 | $0.40 | $0.40 | — | 32.77K |
| deepseek-r1-0528 | $0.25 | $0.25 | — | 131.07K |
| deepseek-v3 | $0.20 | $0.20 | — | 32.77K |
| deepseek-v3-0324 | $0.40 | $0.40 | — | 32.77K |
| hermes-3-llama-3.1-70b | $0.12 | $0.30 | — | 32.77K |
| kimi-k2-instruct | $2.00 | $2.00 | — | 131.07K |
| llama-3.2-3b-instruct | $0.12 | $0.30 | — | 32.77K |
| llama-3.3-70b-instruct | $0.12 | $0.30 | — | 131.07K |
| meta-llama-3-70b-instruct | $0.12 | $0.30 | — | 131.07K |
| meta-llama-3.1-8b-instruct | $0.12 | $0.30 | — | 32.77K |
| meta-llama-3.1-70b-instruct | $0.12 | $0.30 | — | 32.77K |
| meta-llama-3.1-405b-instruct | $0.12 | $0.30 | — | 32.77K |
| qwen2.5-72b-instruct | $0.12 | $0.30 | — | 131.07K |
| qwen2.5-coder-32b-instruct | $0.12 | $0.30 | — | 32.77K |
| qwen3-235b-a22b | $2.00 | $2.00 | — | 131.07K |
| qwq-32b | $0.20 | $0.20 | — | 131.07K |

## ibm-granite

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| ibm: granite 4.2 8b | $0.06 | $0.25 | $0.02 | 131.07K |

## inception

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| mercury 3 | $0.10 | $0.35 | $0.01 | 1M |
| mercury-2 | $0.25 | $0.75 | $0.02 | 128K |
| mercury-2.5 | $0.20 | $0.75 | $0.02 | 260K |

## inclusionai

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| ling 3.0 flash | $0.02 | $0.06 | $0.0042 | 262.14K |
| ling 3.0 flash vl | $0.06 | $0.18 | $0.01 | 131.07K |
| ling 3.1 flash | $0.08 | $0.22 | $0.02 | 262.14K |

## inference-net

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| inference.net: schematron v2 small | $0.05 | $0.23 | $0.05 | 128K |
| inference.net: schematron v2 turbo | $0.03 | $0.15 | $0.03 | 128K |

## inferenceapis

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| deepseek-chat | $0.19 | $0.38 | $0.04 | 1.05M |
| deepseek-flash | $0.40 | $1.60 | $0.01 | 1.05M |
| deepseek-reasoner | $0.19 | $0.38 | $0.04 | 1.05M |
| deepseek-v3 | $0.19 | $0.38 | $0.04 | 1.05M |
| deepseek-v4-flash | $0.19 | $0.38 | $0.04 | 1.05M |
| deepseek-v4-flash-0731 | $0.19 | $0.38 | $0.04 | 1.05M |
| deepseek-v4-pro | $1.72 | $5.15 | $0.17 | 1.05M |
| deepseek-v4-pro-0813 | $1.72 | $5.15 | $0.17 | 1.05M |
| deepseek-v4.1-flash | $0.40 | $1.60 | $0.01 | 1.05M |
| glm-5.3 | $1.82 | $5.72 | $0.34 | 1.05M |
| glm-5.3-flash | $0.20 | $0.66 | $0.04 | 1.05M |
| gpt-oss-20b | $0.04 | $0.19 | — | 131.07K |
| gpt-oss-120b | $0.20 | $0.80 | — | 131.07K |
| kimi-k2.7-code | $0.89 | $4.42 | $0.18 | 262.14K |
| llama-3.1-8b-instant | $0.20 | $0.50 | — | 131.07K |
| llama-3.3-70b | $0.20 | $0.50 | — | 131.07K |
| llama-3.3-70b-instruct | $0.20 | $0.50 | — | 131.07K |
| llama-3.3-70b-instruct-turbo | $0.20 | $0.50 | — | 131.07K |
| llama-3.3-70b-versatile | $0.20 | $0.50 | — | 131.07K |
| minimax-m3 | $0.39 | $1.56 | $0.08 | 524.29K |
| qwen3-vl | $0.26 | $1.15 | — | 262.14K |
| qwen3-vl-235b | $0.26 | $1.15 | — | 262.14K |
| qwen3-vl-235b-a22b-instruct | $0.26 | $1.15 | — | 262.14K |
| qwen3.8-flash | $0.15 | $0.50 | $0.02 | 1M |

## jina_ai

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| jina-reranker-v2-base-multilingual | $0.05 | $0.00 | — | 1.02K |

## lambda_ai

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| deepseek-llama3.3-70b | $0.20 | $0.60 | — | 131.07K |
| deepseek-r1-0528 | $0.20 | $0.60 | — | 131.07K |
| deepseek-r1-671b | $0.80 | $0.80 | — | 131.07K |
| deepseek-v3-0324 | $0.20 | $0.60 | — | 131.07K |
| hermes3-8b | $0.02 | $0.04 | — | 131.07K |
| hermes3-70b | $0.12 | $0.30 | — | 131.07K |
| hermes3-405b | $0.80 | $0.80 | — | 131.07K |
| lfm-7b | $0.02 | $0.04 | — | 131.07K |
| lfm-40b | $0.10 | $0.20 | — | 131.07K |
| llama3.1-8b-instruct | $0.02 | $0.04 | — | 131.07K |
| llama3.1-70b-instruct-fp8 | $0.12 | $0.30 | — | 131.07K |
| llama3.1-405b-instruct-fp8 | $0.80 | $0.80 | — | 131.07K |
| llama3.1-nemotron-70b-instruct-fp8 | $0.12 | $0.30 | — | 131.07K |
| llama3.2-3b-instruct | $0.02 | $0.02 | — | 131.07K |
| llama3.2-11b-vision-instruct | $0.02 | $0.02 | — | 131.07K |
| llama3.3-70b-instruct-fp8 | $0.12 | $0.30 | — | 131.07K |
| llama-4-maverick-17b-128e-instruct-fp8 | $0.05 | $0.10 | — | 131.07K |
| llama-4-scout-17b-16e-instruct | $0.05 | $0.10 | — | 16.38K |
| qwen3-32b-fp8 | $0.05 | $0.10 | — | 131.07K |
| qwen25-coder-32b-instruct | $0.05 | $0.10 | — | 131.07K |

## laya

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| english | $0.00 | $0.00 | — | — |
| multilingual | $0.00 | $0.00 | — | — |
| typed-decisions | $0.00 | $0.00 | — | — |

## lemonade

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| gemma-3-4b-it-gguf | $0.00 | $0.00 | — | 128K |
| gpt-oss-20b-mxfp4-gguf | $0.00 | $0.00 | — | 131.07K |
| gpt-oss-120b-mxfp-gguf | $0.00 | $0.00 | — | 131.07K |
| qwen3-4b-instruct-2507-gguf | $0.00 | $0.00 | — | 262.14K |
| qwen3-coder-30b-a3b-instruct-gguf | $0.00 | $0.00 | — | 262.14K |

## libertai

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| bge-m3 | $0.01 | $0.00 | — | 8.19K |
| deepseek-v4-flash | $0.25 | $1.75 | — | 200K |
| deepseek-v4-flash-thinking | $0.25 | $1.75 | — | 200K |
| gemma-4-31b-it | $0.15 | $0.40 | — | 262.14K |
| gemma-4-31b-it-thinking | $0.15 | $0.40 | — | 262.14K |
| hermes-3-8b-tee | $0.15 | $0.60 | — | 16K |
| qwen3.5-122b-a10b | $0.25 | $1.75 | — | 262.14K |
| qwen3.5-122b-a10b-thinking | $0.25 | $1.75 | — | 262.14K |
| qwen3.6-27b | $0.15 | $0.50 | — | 262.14K |
| qwen3.6-27b-thinking | $0.15 | $0.50 | — | 262.14K |
| qwen3.6-35b-a3b | $0.15 | $0.50 | — | 262.14K |
| qwen3.6-35b-a3b-thinking | $0.15 | $0.50 | — | 262.14K |

## liquid

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| liquidai: lfm2.5-2.6b | $0.35 | $0.50 | $0.04 | 128K |
| liquidai: lfm2.5-2.6b (free) | $0.00 | $0.00 | — | 65.54K |
| liquidai: lfm2.5-24b-a2b | $0.05 | $0.70 | $0.02 | 128K |

## llamagate

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| codellama-7b | $0.06 | $0.12 | — | 16.38K |
| deepseek-coder-6.7b | $0.06 | $0.12 | — | 16.38K |
| deepseek-r1-7b-qwen | $0.08 | $0.15 | — | 131.07K |
| deepseek-r1-8b | $0.10 | $0.20 | — | 65.54K |
| dolphin3-8b | $0.08 | $0.15 | — | 128K |
| gemma3-4b | $0.03 | $0.08 | — | 128K |
| llama-3.1-8b | $0.03 | $0.05 | — | 131.07K |
| llama-3.2-3b | $0.04 | $0.08 | — | 131.07K |
| llava-7b | $0.10 | $0.20 | — | 4.1K |
| mistral-7b-v0.3 | $0.10 | $0.15 | — | 32.77K |
| nomic-embed-text | $0.02 | $0.00 | — | 8.19K |
| openthinker-7b | $0.08 | $0.15 | — | 32.77K |
| qwen2.5-coder-7b | $0.06 | $0.12 | — | 32.77K |
| qwen3-8b | $0.04 | $0.14 | — | 32.77K |
| qwen3-embedding-8b | $0.02 | $0.00 | — | 40.96K |
| qwen3-vl-8b | $0.15 | $0.55 | — | 32.77K |

## mancer

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| weaver (alpha) | $0.40 | $0.75 | — | 8K |

## meituan

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| longcat 2.0 | $0.30 | $1.20 | $0.006 | 1.05M |

## meta

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| muse glimmer 30b | $0.30 | $1.20 | $0.04 | 131.07K |
| muse spark open | $1.25 | $4.25 | $0.15 | 1.05M |
| muse wonder | $4.00 | $20.00 | $0.20 | 1.05M |
| muse-spark-1.1 | $1.25 | $4.25 | $0.15 | 1.05M |
| muse-spark-1.2 | $1.25 | $4.25 | $0.15 | 1.05M |
| muse-spark-1.2-contributor | $0.10 | $0.20 | $0.002 | 1.05M |
| muse-spark-1.3 | $1.25 | $4.25 | $0.15 | 1.05M |
| muse-spark-1.3-contributor | $0.10 | $0.20 | $0.002 | 1.05M |
| muse-wonder-1.0 | $4.00 | $20.00 | $0.20 | 1.05M |

## meta-llama

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| meta: llama 3.1 8b instruct | $0.05 | $0.08 | $0.02 | 131.07K |
| meta: llama 3.1 70b instruct | $0.40 | $0.40 | — | 131.07K |
| meta: llama 3.2 1b instruct | $0.03 | $0.20 | — | 60K |
| meta: llama 3.2 3b instruct | $0.05 | $0.33 | — | 131.07K |
| meta: llama 3.3 70b instruct | $0.10 | $0.32 | — | 131.07K |
| meta: llama 4 maverick | $0.19 | $0.65 | $0.05 | 524.29K |
| meta: llama 4 scout | $0.10 | $0.30 | — | 1.31M |
| meta: llama guard 4 12b | $0.18 | $0.18 | — | 163.84K |

## microsoft

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| phi 4 | $0.07 | $0.14 | — | 16.38K |

## microsoft_365_copilot

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| chat | $0.00 | $0.00 | — | — |

## minimax

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| minimax m1 | $0.55 | $2.20 | — | 1M |
| minimax m2-her | $0.30 | $1.20 | $0.03 | 65.54K |
| minimax m2.7 | $0.30 | $1.20 | $0.06 | 204.8K |
| minimax m3.1 flash | $0.15 | $0.60 | $0.02 | 1.05M |
| minimax-01 | $0.20 | $1.10 | — | 1M |
| minimax-m2 | $0.30 | $1.20 | $0.03 | 200K |
| minimax-m2.1 | $0.30 | $1.20 | $0.03 | 1M |
| minimax-m2.1-lightning | $0.30 | $2.40 | $0.03 | 1M |
| minimax-m2.5 | $0.30 | $1.20 | $0.03 | 1M |
| minimax-m2.5-lightning | $0.30 | $2.40 | $0.03 | 1M |
| minimax-m3 | $0.30 | $1.20 | $0.06 | 1M |

## mistral

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| codestral 2508 | $0.30 | $0.90 | $0.03 | 256K |
| codestral-2508 | $0.30 | $0.90 | $0.03 | 128K |
| codestral-embed | $0.15 | — | $0.02 | 8.19K |
| codestral-embed-2505 | $0.15 | — | $0.02 | 8.19K |
| codestral-latest | $0.30 | $0.90 | $0.03 | 128K |
| codestral-mamba-latest | $0.25 | $0.25 | $0.02 | 256K |
| devstral 2 2512 | $0.40 | $2.00 | $0.04 | 262.14K |
| devstral-latest | $0.40 | $2.00 | $0.04 | 256K |
| devstral-medium-latest | $0.40 | $2.00 | $0.04 | 256K |
| devstral-small-latest | $0.10 | $0.30 | $0.01 | 256K |
| glm-5-2 | $1.40 | $4.40 | $0.14 | 1.05M |
| labs-leanstral-1-5 | $0.00 | $0.00 | — | 262.14K |
| labs-leanstral-1-5-1 | $0.00 | $0.00 | — | 262.14K |
| magistral-medium-latest | $1.50 | $7.50 | $0.15 | 262.14K |
| magistral-small-latest | $0.15 | $0.60 | $0.02 | 262.14K |
| ministral 3 3b 2512 | $0.10 | $0.10 | $0.01 | 131.07K |
| ministral 3 8b 2512 | $0.15 | $0.15 | $0.02 | 262.14K |
| ministral 3 14b 2512 | $0.20 | $0.20 | $0.02 | 262.14K |
| ministral-3-3b-2512 | $0.10 | $0.10 | $0.01 | 131.07K |
| ministral-3-8b-2512 | $0.15 | $0.15 | $0.02 | 262.14K |
| ministral-3-14b-2512 | $0.20 | $0.20 | $0.02 | 262.14K |
| ministral-3b-2512 | $0.10 | $0.10 | $0.01 | 131.07K |
| ministral-3b-latest | $0.10 | $0.10 | $0.01 | 131.07K |
| ministral-8b-2512 | $0.15 | $0.15 | $0.02 | 262.14K |
| ministral-8b-latest | $0.15 | $0.15 | $0.02 | 262.14K |
| ministral-14b-2512 | $0.20 | $0.20 | $0.02 | 262.14K |
| ministral-14b-latest | $0.20 | $0.20 | $0.02 | 262.14K |
| mistral large | $2.00 | $6.00 | $0.20 | 128K |
| mistral large 3 2512 | $0.50 | $1.50 | $0.05 | 262.14K |
| mistral large 4 | $1.36 | $4.18 | $0.14 | 1.05M |
| mistral large 2407 | $2.00 | $6.00 | $0.20 | 131.07K |
| mistral medium 3 | $0.40 | $2.00 | $0.04 | 131.07K |
| mistral medium 3.1 | $0.40 | $2.00 | $0.04 | 131.07K |
| mistral medium 3.5 | $1.50 | $7.50 | — | 262.14K |
| mistral medium 3.5 (batch) | $0.75 | $3.75 | — | 262.14K |
| mistral nemo | $0.03 | $0.03 | — | 131.07K |
| mistral small 3 | $0.05 | $0.08 | — | 32.77K |
| mistral small 3.1 24b | $0.35 | $0.56 | — | 128K |
| mistral small 3.2 24b | $0.08 | $0.20 | — | 256K |
| mistral small 4 | $0.15 | $0.60 | $0.02 | 262.14K |
| mistral-code-agent-latest | $0.40 | $2.00 | $0.04 | 256K |
| mistral-code-fim-latest | $0.30 | $0.90 | $0.03 | 128K |
| mistral-code-latest | $0.30 | $0.90 | $0.03 | 128K |
| mistral-embed | $0.10 | — | — | 8.19K |
| mistral-embed-2312 | $0.10 | — | — | 8.19K |
| mistral-large-3 | $0.50 | $1.50 | $0.05 | 262.14K |
| mistral-large-4 | $0.68 | $2.09 | $0.07 | 1.05M |
| mistral-large-4-0 | $0.68 | $2.09 | $0.07 | 1.05M |
| mistral-large-2512 | $0.50 | $1.50 | $0.05 | 262.14K |
| mistral-large-latest | $0.50 | $1.50 | $0.05 | 262.14K |
| mistral-medium | $1.50 | $7.50 | $0.15 | 262.14K |
| mistral-medium-3 | $1.50 | $7.50 | $0.15 | 262.14K |
| mistral-medium-3-5 | $1.50 | $7.50 | $0.15 | 262.14K |
| mistral-medium-2604 | $1.50 | $7.50 | $0.15 | 262.14K |
| mistral-medium-latest | $1.50 | $7.50 | $0.15 | 262.14K |
| mistral-moderation-2603 | $0.00 | $0.00 | — | 131.07K |
| mistral-small | $0.10 | $0.30 | $0.01 | 32K |
| mistral-small-2603 | $0.15 | $0.60 | $0.02 | 262.14K |
| mistral-small-latest | $0.15 | $0.60 | $0.02 | 262.14K |
| mistral-tiny | $0.25 | $0.25 | $0.02 | 32K |
| mistral-vibe-cli-fast | $0.15 | $0.60 | $0.02 | 262.14K |
| mistral-vibe-cli-latest | $1.50 | $7.50 | $0.15 | 262.14K |
| mistral-vibe-cli-with-tools | $1.50 | $7.50 | $0.15 | 262.14K |
| mixtral 8x22b instruct | $2.00 | $6.00 | $0.20 | 65.54K |
| open-mistral-nemo | $0.30 | $0.30 | $0.03 | 128K |
| pixtral-large-latest | $2.00 | $6.00 | $0.20 | 128K |
| saba | $0.20 | $0.60 | $0.02 | 32.77K |
| voxtral small 24b 2507 | $0.10 | $0.30 | $0.01 | 32.77K |
| voxtral-small-2507 | $0.10 | $0.40 | $0.01 | 32.77K |
| voxtral-small-latest | $0.10 | $0.40 | $0.01 | 32.77K |
| zai-glm-5 | $1.40 | $4.40 | $0.14 | 1.05M |
| zai-glm-5-2 | $1.40 | $4.40 | $0.14 | 1.05M |
| zai-glm-5-3 | $1.40 | $4.40 | $0.14 | 1.05M |
| zai-glm-5-3-flash | $0.15 | $0.50 | $0.03 | 1.05M |
| zai-glm-latest | $1.40 | $4.40 | $0.14 | 1.05M |

## moondream

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| moondream 3 preview | $0.30 | $2.50 | — | 32K |
| moondream 3.1 | $0.30 | $2.50 | — | 32K |

## moonshotai

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| kimi k2 0711 | $0.57 | $2.30 | — | 131.07K |
| kimi k2 0905 | $0.60 | $2.50 | — | 262.14K |
| kimi k2 thinking | $0.60 | $2.50 | $0.15 | 262.14K |
| kimi k2.5 | $0.50 | $2.50 | $0.15 | 262.14K |
| kimi k2.6 | $0.65 | $3.41 | $0.15 | 262.14K |
| kimi k2.7 code | $0.67 | $3.10 | $0.15 | 262.14K |
| kimi k3 | $0.18 | $20.00 | $0.17 | 1.05M |
| kimi k3 (batch) | $2.28 | $11.40 | $0.23 | 1.05M |
| kimi k3.1 pro | $2.00 | $10.00 | $0.20 | 1.05M |
| kimi latest | $0.18 | $20.00 | $0.17 | 1.05M |
| kimi-k2.5 | $0.60 | $3.00 | $0.10 | 262.14K |
| kimi-k2.6 | $0.95 | $4.00 | $0.16 | 262.14K |
| kimi-k2.7-code | $0.95 | $4.00 | $0.19 | 262.14K |
| kimi-k3 | $3.00 | $15.00 | $0.30 | 1.05M |
| moonshot-v1-8k | $0.20 | $2.00 | — | 8.19K |
| moonshot-v1-8k-vision-preview | $0.20 | $2.00 | — | 8.19K |
| moonshot-v1-32k | $1.00 | $3.00 | — | 32.77K |
| moonshot-v1-32k-vision-preview | $1.00 | $3.00 | — | 32.77K |
| moonshot-v1-128k | $2.00 | $5.00 | — | 131.07K |
| moonshot-v1-128k-vision-preview | $2.00 | $5.00 | — | 131.07K |
| moonshot-v1-auto | $2.00 | $5.00 | — | 131.07K |

## morph

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| morph-v3-fast | $0.80 | $1.20 | — | 16K |
| morph-v3-large | $0.90 | $1.90 | — | 16K |

## nace

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| drex-latest | $0.06 | $0.00 | — | 131.07K |
| drex-v1.0 | $0.04 | $0.00 | — | 32.77K |
| drex-v1.5 | $0.05 | $0.00 | — | 131.07K |
| drex-v2.0 | $0.06 | $0.00 | — | 131.07K |

## nebius

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| beam | $0.25 | $1.00 | — | 1.05M |
| bge-en-icl | $0.01 | $0.00 | — | 32.77K |
| bge-multilingual-gemma2 | $0.01 | $0.00 | — | 8.19K |
| cosmos3-super-reasoner | $0.10 | $0.30 | — | 262.14K |
| deepseek-r1 | $0.80 | $2.40 | — | 128K |
| deepseek-r1-0528 | $0.80 | $2.40 | — | 164K |
| deepseek-r1-distill-llama-70b | $0.25 | $0.75 | — | 128K |
| deepseek-v3 | $0.50 | $1.50 | — | 128K |
| deepseek-v3-0324 | $0.50 | $1.50 | — | 128K |
| deepseek-v4-flash | $0.14 | $0.28 | — | 1.05M |
| deepseek-v4-flash-0731 | $0.14 | $0.28 | — | 1.02M |
| deepseek-v4-pro | $1.75 | $3.50 | — | 1.05M |
| deepseek-v4-pro-0813 | $1.32 | $3.96 | — | 979K |
| deepseek-v4.1-flash | $0.30 | $1.20 | — | 1.05M |
| e5-mistral-7b-instruct | $0.01 | $0.00 | — | 32.77K |
| gemma-3-27b-it | $0.10 | $0.30 | — | 110K |
| glm-5.1 | $1.40 | $4.40 | — | 202.75K |
| glm-5.2 | $1.40 | $4.40 | — | 1.05M |
| glm-5.3 | $1.40 | $4.40 | — | 1.02M |
| glm-5.3-flash | $0.15 | $0.50 | — | 1.02M |
| gpt-oss-120b | $0.15 | $0.60 | — | 131.07K |
| hermes-3-llama-3.1-405b | $1.00 | $3.00 | — | 128K |
| hermes-4-70b | $0.13 | $0.40 | — | 131.07K |
| hermes-4-405b | $1.00 | $3.00 | — | 131.07K |
| kimi-k2.6 | $0.95 | $4.00 | — | 262.14K |
| kimi-k2.7-code | $0.95 | $4.00 | — | 262.14K |
| kimi-k3 | $3.00 | $15.00 | — | 1.02M |
| llama-3.1-nemotron-ultra-253b-v1 | $0.60 | $1.80 | — | 128K |
| llama-3.3-70b-instruct | $0.13 | $0.40 | — | 131.07K |
| llama-3.3-nemotron-super-49b-v1 | $0.10 | $0.40 | — | 131.07K |
| llama-guard-3-8b | $0.02 | $0.06 | — | 128K |
| meta-llama-3.1-8b-instruct | $0.02 | $0.06 | — | 128K |
| meta-llama-3.1-70b-instruct | $0.13 | $0.40 | — | 128K |
| meta-llama-3.1-405b-instruct | $1.00 | $3.00 | — | 128K |
| minicpm-v-4_5 | $0.66 | $1.11 | — | 32K |
| minimax-m2.5 | $0.30 | $1.20 | — | 196.61K |
| minimax-m3 | $0.30 | $1.20 | — | 1.05M |
| mistral-nemo-instruct-2407 | $0.04 | $0.12 | — | 128K |
| nemotron-3-nano-omni | $0.06 | $0.24 | — | 262.14K |
| nemotron-3-super-120b-a12b | $0.30 | $0.90 | — | 262.14K |
| nemotron-3-ultra-550b-a55b | $1.00 | $3.00 | — | 1.05M |
| nemotron-3_5-lightning | $0.06 | $0.24 | — | 1.05M |
| nvidia-nemotron-3-nano-30b-a3b | $0.06 | $0.24 | — | 262.14K |
| qwen2-vl-7b-instruct | $0.02 | $0.06 | — | 131.07K |
| qwen2-vl-72b-instruct | $0.13 | $0.40 | — | 131.07K |
| qwen2.5-32b-instruct | $0.06 | $0.20 | — | 128K |
| qwen2.5-72b-instruct | $0.13 | $0.40 | — | 128K |
| qwen2.5-coder-7b | $0.01 | $0.03 | — | 32.77K |
| qwen2.5-vl-72b-instruct | $0.25 | $0.75 | — | 32K |
| qwen3-4b | $0.08 | $0.24 | — | 32.77K |
| qwen3-14b | $0.08 | $0.24 | — | 32.77K |
| qwen3-30b-a3b | $0.10 | $0.30 | — | 32.77K |
| qwen3-30b-a3b-instruct-2507 | $0.10 | $0.30 | — | 262.14K |
| qwen3-32b | $0.10 | $0.30 | — | 40.96K |
| qwen3-235b-a22b | $0.20 | $0.60 | — | 262.14K |
| qwen3-235b-a22b-instruct-2507 | $0.20 | $0.60 | — | 262.14K |
| qwen3-embedding-8b | $0.01 | $0.00 | — | 40.96K |
| qwen3-next-80b-a3b-thinking | $0.15 | $1.20 | — | 128K |
| qwen3.5-397b-a17b | $0.60 | $3.60 | — | 262.14K |
| qwen3.8-27b | $0.45 | $3.00 | — | 262.14K |
| qwq-32b | $0.15 | $0.45 | — | 32.77K |

## nex-agi

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| nex agi: nex-n2.5-mini | $0.02 | $0.10 | $0.0025 | 262.14K |
| nex agi: nex-n2.5-pro | $0.08 | $0.25 | $0.02 | 262.14K |

## nlp_cloud

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| chatdolphin | $0.50 | $0.50 | — | 16.38K |
| dolphin | $0.50 | $0.50 | — | 16.38K |

## nousresearch

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| nous: hermes 3 70b instruct | $0.70 | $0.70 | — | 131.07K |
| nous: hermes 3 405b instruct | $1.00 | $1.00 | — | 131.07K |
| nous: hermes 4 405b | $1.00 | $3.00 | — | 131.07K |

## novita

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| autoglm-phone-9b-multilingual | $0.04 | $0.14 | — | 65.54K |
| baichuan-m2-32b | $0.07 | $0.07 | — | 131.07K |
| bge-m3 | $0.01 | $0.01 | — | 8.19K |
| bge-reranker-v2-m3 | $0.01 | $0.01 | — | 8K |
| cobuddy | $0.28 | $1.13 | $0.07 | 131.07K |
| community | $4.00 | $4.00 | — | 64K |
| deepseek-ocr | $0.03 | $0.03 | — | 8.19K |
| deepseek-ocr-2 | $0.03 | $0.03 | — | 8.19K |
| deepseek-prover-v2-671b | $0.70 | $2.50 | — | 160K |
| deepseek-r1 | $4.00 | $4.00 | — | 64K |
| deepseek-r1-0528 | $0.70 | $2.50 | $0.35 | 163.84K |
| deepseek-r1-0528-qwen3-8b | $0.06 | $0.09 | — | 128K |
| deepseek-r1-distill-llama-70b | $0.80 | $0.80 | — | 8.19K |
| deepseek-r1-distill-qwen-14b | $0.15 | $0.15 | — | 32.77K |
| deepseek-r1-distill-qwen-32b | $0.30 | $0.30 | — | 64K |
| deepseek-r1-turbo | $0.70 | $2.50 | — | 64K |
| deepseek-v3-0324 | $0.27 | $1.12 | $0.14 | 163.84K |
| deepseek-v3-turbo | $0.40 | $1.30 | — | 64K |
| deepseek-v3.1 | $0.27 | $1.00 | $0.14 | 131.07K |
| deepseek-v3.1-terminus | $0.27 | $1.00 | $0.14 | 131.07K |
| deepseek-v3.2 | $0.27 | $0.40 | $0.13 | 163.84K |
| deepseek-v3.2-exp | $0.27 | $0.41 | — | 163.84K |
| deepseek-v4-flash | $0.14 | $0.28 | $0.03 | 1.05M |
| deepseek-v4-flash-0731 | $0.44 | $1.32 | $0.03 | 1.05M |
| deepseek-v4-flash-vision-exp | $0.44 | $1.32 | $0.03 | 1.05M |
| deepseek-v4-pro | $1.60 | $3.20 | $0.14 | 1.05M |
| deepseek-v4-pro-0813 | $1.32 | $3.96 | $0.13 | 1.05M |
| deepseek_v3 | $0.89 | $0.89 | — | 64K |
| ernie-4.5-21b-a3b | $0.07 | $0.28 | — | 120K |
| ernie-4.5-21b-a3b-thinking | $0.07 | $0.28 | — | 131.07K |
| ernie-4.5-300b-a47b-paddle | $0.28 | $1.10 | — | 123K |
| ernie-4.5-vl-28b-a3b | $0.14 | $0.56 | — | 30K |
| ernie-4.5-vl-28b-a3b-thinking | $0.39 | $0.39 | — | 131.07K |
| ernie-4.5-vl-424b-a47b | $0.42 | $1.25 | — | 123K |
| gemma-3-12b-it | $0.05 | $0.10 | — | 131.07K |
| gemma-3-27b-it | $0.12 | $0.20 | — | 98.3K |
| gemma-4-26b-a4b-it | $0.13 | $0.40 | — | 262.14K |
| gemma-4-31b-it | $0.14 | $0.40 | — | 262.14K |
| glm-4-32b-0414 | $0.55 | $1.66 | — | 32K |
| glm-4.5 | $0.60 | $2.20 | $0.11 | 131.07K |
| glm-4.5-air | $0.13 | $0.85 | $0.02 | 131.07K |
| glm-4.5v | $0.60 | $1.80 | $0.11 | 65.54K |
| glm-4.6 | $0.55 | $2.20 | $0.11 | 204.8K |
| glm-4.6v | $0.30 | $0.90 | $0.06 | 131.07K |
| glm-4.7 | $0.60 | $2.20 | $0.11 | 204.8K |
| glm-4.7-flash | $0.07 | $0.40 | $0.01 | 200K |
| glm-4.7-h | $0.60 | $2.20 | $0.11 | 204.8K |
| glm-5 | $1.00 | $3.20 | $0.20 | 202.8K |
| glm-5-turbo | $1.20 | $4.00 | $0.24 | 202.8K |
| glm-5.1 | $1.38 | $4.40 | $0.26 | 204.8K |
| glm-5.2 | $1.40 | $4.40 | $0.26 | 1.05M |
| glm-5.3 | $1.40 | $4.40 | $0.26 | 1.05M |
| glm-5v-turbo | $1.20 | $4.00 | $0.24 | 204.8K |
| gpt-oss-20b | $0.04 | $0.15 | — | 131.07K |
| gpt-oss-120b | $0.05 | $0.25 | — | 131.07K |
| hermes-2-pro-llama-3-8b | $0.14 | $0.14 | — | 8.19K |
| hy3 | $0.14 | $0.58 | $0.04 | 262.14K |
| kat-coder-pro | $0.30 | $1.20 | $0.06 | 256K |
| kimi-k2-0905 | $0.60 | $2.50 | — | 262.14K |
| kimi-k2-instruct | $0.57 | $2.30 | — | 131.07K |
| kimi-k2-thinking | $0.60 | $2.50 | $0.15 | 262.14K |
| kimi-k2.5 | $0.60 | $3.00 | $0.10 | 262.14K |
| kimi-k2.6 | $0.80 | $3.40 | $0.16 | 262.14K |
| kimi-k2.7-code | $0.95 | $4.00 | $0.19 | 262.14K |
| kimi-k3 | $3.00 | $15.00 | $0.30 | 1.05M |
| l3-8b-lunaris | $0.05 | $0.05 | — | 8.19K |
| l3-8b-stheno-v3.2 | $0.05 | $0.05 | — | 8.19K |
| l3-70b-euryale-v2.1 | $1.48 | $1.48 | — | 8.19K |
| l31-70b-euryale-v2.2 | $1.48 | $1.48 | — | 8.19K |
| ling-3.0-flash | $0.06 | $0.18 | $0.01 | 262.14K |
| ling-3.0-flash-fast | $0.06 | $0.18 | $0.01 | 262.14K |
| llama-3-8b-instruct | $0.04 | $0.04 | — | 8.19K |
| llama-3-70b-instruct | $0.51 | $0.74 | — | 8.19K |
| llama-3.1-8b-instruct | $0.02 | $0.05 | — | 16.38K |
| llama-3.2-1b-instruct | $0.02 | $0.02 | — | 131K |
| llama-3.2-3b-instruct | $0.03 | $0.05 | — | 32.77K |
| llama-3.3-70b-instruct | $0.14 | $0.40 | — | 12.29K |
| llama-4-maverick-17b-128e-instruct-fp8 | $0.27 | $0.85 | — | 1.05M |
| llama-4-scout-17b-16e-instruct | $0.18 | $0.59 | — | 131.07K |
| macaron-v1-tall | $0.45 | $2.60 | $0.08 | 262.14K |
| macaron-v1-venti | $1.50 | $4.50 | $0.30 | 1.05M |
| mimo-v2-flash | $0.11 | $0.33 | $0.02 | 262.14K |
| mimo-v2.5 | $0.17 | $0.34 | $0.0034 | 1.05M |
| mimo-v2.5-pro | $0.52 | $1.04 | $0.0043 | 1.05M |
| minimax-m1-80k | $0.55 | $2.20 | — | 1M |
| minimax-m2 | $0.30 | $1.20 | $0.03 | 204.8K |
| minimax-m2.1 | $0.30 | $1.20 | $0.03 | 204.8K |
| minimax-m2.5 | $0.30 | $1.20 | $0.03 | 204.8K |
| minimax-m2.5-highspeed | $0.60 | $2.40 | $0.03 | 204.8K |
| minimax-m2.7 | $0.30 | $1.20 | $0.06 | 204.8K |
| minimax-m2.7-highspeed | $0.60 | $2.40 | $0.06 | 204.8K |
| minimax-m3 | $0.30 | $1.20 | $0.06 | 1M |
| mistral-nemo | $0.04 | $0.17 | — | 60.29K |
| mythomax-l2-13b | $0.09 | $0.09 | — | 4.1K |
| nemotron-3-nano-30b-a3b | $0.05 | $0.20 | — | 262.14K |
| paddleocr-vl | $0.02 | $0.02 | — | 16.38K |
| qwen2.5-7b-instruct | $0.07 | $0.07 | — | 32K |
| qwen2.5-vl-72b-instruct | $0.80 | $0.80 | — | 32.77K |
| qwen3-4b-fp8 | $0.03 | $0.03 | — | 128K |
| qwen3-8b-fp8 | $0.04 | $0.14 | — | 128K |
| qwen3-30b-a3b-fp8 | $0.09 | $0.45 | — | 40.96K |
| qwen3-32b-fp8 | $0.10 | $0.45 | — | 40.96K |
| qwen3-235b-a22b-fp8 | $0.20 | $0.80 | — | 40.96K |
| qwen3-235b-a22b-instruct-2507 | $0.09 | $0.58 | — | 131.07K |
| qwen3-235b-a22b-thinking-2507 | $0.30 | $3.00 | — | 131.07K |
| qwen3-coder-30b-a3b-instruct | $0.07 | $0.27 | — | 160K |
| qwen3-coder-480b-a35b-instruct | $0.38 | $1.55 | — | 262.14K |
| qwen3-coder-next | $0.20 | $1.50 | — | 262.14K |
| qwen3-embedding-0.6b | $0.07 | $0.00 | — | 32.77K |
| qwen3-embedding-8b | $0.07 | $0.00 | — | 32.77K |
| qwen3-max | $2.11 | $8.45 | — | 262.14K |
| qwen3-next-80b-a3b-instruct | $0.15 | $1.50 | — | 131.07K |
| qwen3-next-80b-a3b-thinking | $0.15 | $1.50 | — | 131.07K |
| qwen3-omni-30b-a3b-instruct | $0.25 | $0.97 | — | 65.54K |
| qwen3-omni-30b-a3b-thinking | $0.25 | $0.97 | — | 65.54K |
| qwen3-reranker-8b | $0.05 | $0.05 | — | 32.77K |
| qwen3-vl-8b-instruct | $0.08 | $0.50 | — | 131.07K |
| qwen3-vl-30b-a3b-instruct | $0.20 | $0.70 | — | 131.07K |
| qwen3-vl-30b-a3b-thinking | $0.20 | $1.00 | — | 131.07K |
| qwen3-vl-235b-a22b-instruct | $0.30 | $1.50 | — | 131.07K |
| qwen3-vl-235b-a22b-thinking | $0.98 | $3.95 | — | 131.07K |
| qwen3.5-27b | $0.30 | $2.40 | — | 262.14K |
| qwen3.5-35b-a3b | $0.25 | $2.00 | — | 262.14K |
| qwen3.5-122b-a10b | $0.40 | $3.20 | — | 262.14K |
| qwen3.5-397b-a17b | $0.60 | $3.60 | — | 262.14K |
| qwen3.6-27b | $0.60 | $3.60 | — | 262.14K |
| qwen3.6-35b-a3b | $0.25 | $1.49 | — | 262.14K |
| qwen3.7-max | $1.25 | $3.75 | $0.25 | 1M |
| qwen3.8-max | $2.00 | $6.00 | $0.25 | 1M |
| qwen-2.5-72b-instruct | $0.38 | $0.40 | — | 32K |
| qwen-mt-plus | $0.25 | $0.75 | — | 16.38K |
| r1v4-lite | $0.20 | $0.60 | — | 262.14K |
| step-3.7-flash | $0.20 | $1.15 | $0.04 | 262.14K |
| wizardlm-2-8x22b | $0.62 | $0.62 | — | 65.53K |

## nscale

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| deepseek-r1-distill-llama-8b | $0.02 | $0.02 | — | — |
| deepseek-r1-distill-llama-70b | $0.38 | $0.38 | — | — |
| deepseek-r1-distill-qwen-1.5b | $0.09 | $0.09 | — | — |
| deepseek-r1-distill-qwen-7b | $0.20 | $0.20 | — | — |
| deepseek-r1-distill-qwen-14b | $0.07 | $0.07 | — | — |
| deepseek-r1-distill-qwen-32b | $0.15 | $0.15 | — | — |
| llama-3.1-8b-instruct | $0.03 | $0.03 | — | — |
| llama-3.3-70b-instruct | $0.20 | $0.20 | — | — |
| llama-4-scout-17b-16e-instruct | $0.09 | $0.29 | — | — |
| mixtral-8x22b-instruct-v0.1 | $0.60 | $0.60 | — | — |
| qwen2.5-coder-3b-instruct | $0.01 | $0.03 | — | — |
| qwen2.5-coder-7b-instruct | $0.01 | $0.03 | — | — |
| qwen2.5-coder-32b-instruct | $0.06 | $0.20 | — | — |
| qwq-32b | $0.18 | $0.20 | — | — |

## nvidia

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| nemotron 3 nano 30b a3b | $0.06 | $0.24 | — | 262.14K |
| nemotron 3 nano omni (free) | $0.00 | $0.00 | — | 256K |
| nemotron 3 super | $0.30 | $2.40 | $0.15 | 262.14K |
| nemotron 3 ultra | $0.60 | $2.40 | $0.12 | 262.14K |
| nemotron 3 ultra (free) | $0.00 | $0.00 | — | 1M |
| nemotron 3.5 content safety | $0.20 | $0.20 | — | 131.07K |
| nemotron 3.5 content safety (free) | $0.00 | $0.00 | — | 128K |
| nemotron 3.5 lightning | $0.07 | $0.20 | $0.04 | 262.14K |
| nemotron 3.5 lightning (free) | $0.00 | $0.00 | — | 1M |
| nemotron 3.5 super vl | $0.15 | $0.50 | $0.02 | 1.05M |
| nemotron 3.5 super vl (free) | $0.00 | $0.00 | — | 1M |

## nvidia_nim

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| llama-3_2-nv-rerankqa-1b-v2 | $0.00 | $0.00 | — | — |
| nv-rerankqa-mistral-4b-v3 | $0.00 | $0.00 | — | — |

## oci

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| cohere.command-a-03-2025 | $1.56 | $1.56 | — | 256K |
| cohere.command-a-reasoning | $1.56 | $1.56 | — | 256K |
| cohere.command-a-reasoning-08-2025 | $1.56 | $1.56 | — | 256K |
| cohere.command-a-translate-08-2025 | $0.09 | $0.09 | — | 256K |
| cohere.command-a-vision | $1.56 | $1.56 | — | 256K |
| cohere.command-a-vision-07-2025 | $1.56 | $1.56 | — | 128K |
| cohere.command-latest | $1.56 | $1.56 | — | 128K |
| cohere.command-plus-latest | $1.56 | $1.56 | — | 128K |
| cohere.command-r-08-2024 | $0.15 | $0.15 | — | 128K |
| cohere.command-r-plus-08-2024 | $1.56 | $1.56 | — | 128K |
| cohere.embed-english-image-v3.0 | $0.10 | $0.00 | — | 512 |
| cohere.embed-english-light-image-v3.0 | $0.10 | $0.00 | — | 512 |
| cohere.embed-english-light-v3.0 | $0.10 | $0.00 | — | 512 |
| cohere.embed-english-v3.0 | $0.10 | $0.00 | — | 512 |
| cohere.embed-multilingual-image-v3.0 | $0.10 | — | — | 512 |
| cohere.embed-multilingual-light-image-v3.0 | $0.10 | $0.00 | — | 512 |
| cohere.embed-multilingual-light-v3.0 | $0.10 | $0.00 | — | 512 |
| cohere.embed-multilingual-v3.0 | $0.10 | $0.00 | — | 512 |
| cohere.embed-v4.0 | $0.12 | $0.00 | — | 128K |
| google.gemini-2.5-flash | $0.15 | $0.60 | — | 1.05M |
| google.gemini-2.5-flash-lite | $0.08 | $0.30 | — | 1.05M |
| google.gemini-2.5-pro | $1.25 | $10.00 | — | 1.05M |
| meta.llama-3.1-8b-instruct | $0.72 | $0.72 | — | 128K |
| meta.llama-3.1-70b-instruct | $0.72 | $0.72 | — | 128K |
| meta.llama-3.1-405b-instruct | $10.68 | $10.68 | — | 128K |
| meta.llama-3.2-11b-vision-instruct | $2.00 | $2.00 | — | 128K |
| meta.llama-3.2-90b-vision-instruct | $2.00 | $2.00 | — | 128K |
| meta.llama-3.3-70b-instruct | $0.72 | $0.72 | — | 128K |
| meta.llama-3.3-70b-instruct-fp8-dynamic | $0.72 | $0.72 | — | 128K |
| meta.llama-4-maverick-17b-128e-instruct-fp8 | $0.72 | $0.72 | — | 1.05M |
| meta.llama-4-scout-17b-16e-instruct | $0.72 | $0.72 | — | 10.49M |
| openai.gpt-5 | $1.25 | $10.00 | — | 272K |
| openai.gpt-5-mini | $0.25 | $2.00 | — | 272K |
| openai.gpt-5-nano | $0.05 | $0.40 | — | 272K |
| openai.gpt-oss-20b | $0.07 | $0.30 | — | 128K |
| openai.gpt-oss-120b | $0.15 | $0.60 | — | 128K |
| xai.grok-3 | $3.00 | $15.00 | — | 131.07K |
| xai.grok-3-fast | $5.00 | $25.00 | — | 131.07K |
| xai.grok-3-mini | $0.30 | $0.50 | — | 131.07K |
| xai.grok-3-mini-fast | $0.60 | $4.00 | — | 131.07K |
| xai.grok-4 | $3.00 | $15.00 | — | 128K |
| xai.grok-4-fast | $5.00 | $25.00 | — | 131.07K |
| xai.grok-4.1-fast | $5.00 | $25.00 | — | 131.07K |
| xai.grok-4.20 | $3.00 | $15.00 | — | 131.07K |
| xai.grok-4.20-0309-non-reasoning | $1.25 | $2.50 | $0.20 | 1M |
| xai.grok-4.20-0309-reasoning | $1.25 | $2.50 | $0.20 | 1M |
| xai.grok-4.20-multi-agent | $3.00 | $15.00 | — | 131.07K |
| xai.grok-4.20-non-reasoning | $1.25 | $2.50 | $0.20 | 1M |
| xai.grok-4.20-reasoning | $1.25 | $2.50 | $0.20 | 1M |
| xai.grok-code-fast-1 | $5.00 | $25.00 | — | 131.07K |

## ollama

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| codegeex4 | $0.00 | $0.00 | — | 32.77K |
| codegemma | $0.00 | $0.00 | — | 8.19K |
| codellama | $0.00 | $0.00 | — | 4.1K |
| deepseek-coder-v2-base | $0.00 | $0.00 | — | 8.19K |
| deepseek-coder-v2-instruct | $0.00 | $0.00 | — | 32.77K |
| deepseek-coder-v2-lite-base | $0.00 | $0.00 | — | 8.19K |
| deepseek-coder-v2-lite-instruct | $0.00 | $0.00 | — | 32.77K |
| deepseek-v3.1:671b-cloud | $0.00 | $0.00 | — | 163.84K |
| gpt-oss:20b-cloud | $0.00 | $0.00 | — | 131.07K |
| gpt-oss:120b-cloud | $0.00 | $0.00 | — | 131.07K |
| internlm2_5-20b-chat | $0.00 | $0.00 | — | 32.77K |
| llama2 | $0.00 | $0.00 | — | 4.1K |
| llama2-uncensored | $0.00 | $0.00 | — | 4.1K |
| llama2:7b | $0.00 | $0.00 | — | 4.1K |
| llama2:13b | $0.00 | $0.00 | — | 4.1K |
| llama2:70b | $0.00 | $0.00 | — | 4.1K |
| llama3 | $0.00 | $0.00 | — | 8.19K |
| llama3.1 | $0.00 | $0.00 | — | 8.19K |
| llama3:8b | $0.00 | $0.00 | — | 8.19K |
| llama3:70b | $0.00 | $0.00 | — | 8.19K |
| mistral | $0.00 | $0.00 | — | 8.19K |
| mistral-7b-instruct-v0.1 | $0.00 | $0.00 | — | 8.19K |
| mistral-7b-instruct-v0.2 | $0.00 | $0.00 | — | 32.77K |
| mistral-large-instruct-2407 | $0.00 | $0.00 | — | 65.54K |
| mixtral-8x7b-instruct-v0.1 | $0.00 | $0.00 | — | 32.77K |
| mixtral-8x22b-instruct-v0.1 | $0.00 | $0.00 | — | 65.54K |
| orca-mini | $0.00 | $0.00 | — | 4.1K |
| qwen3-coder:480b-cloud | $0.00 | $0.00 | — | 262.14K |
| vicuna | $0.00 | $0.00 | — | 2.05K |

## openai

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| chat-latest | $5.00 | $30.00 | $0.50 | 400K |
| chatgpt-image-latest | $5.00 | $10.00 | $1.25 | — |
| computer-use-preview | $3.00 | $12.00 | — | 8.19K |
| computer-use-preview-2025-03-11 | $3.00 | $12.00 | — | 8.19K |
| daybreak-blue-latest | $4.00 | $20.00 | $0.40 | 922K |
| daybreak-red-latest | $12.50 | $75.00 | $1.25 | 400K |
| ft:gpt-3.5-turbo | $3.00 | $6.00 | — | 16.39K |
| ft:gpt-3.5-turbo-0125 | $3.00 | $6.00 | — | 16.39K |
| ft:gpt-3.5-turbo-0613 | $3.00 | $6.00 | — | 4.1K |
| ft:gpt-3.5-turbo-1106 | $3.00 | $6.00 | — | 16.39K |
| ft:gpt-4-0613 | $30.00 | $60.00 | — | 8.19K |
| ft:gpt-4.1-2025-04-14 | $3.00 | $12.00 | $0.75 | 1.05M |
| ft:gpt-4.1-mini-2025-04-14 | $0.80 | $3.20 | $0.20 | 1.05M |
| ft:gpt-4.1-nano-2025-04-14 | $0.20 | $0.80 | $0.05 | 1.05M |
| ft:gpt-4o-2024-08-06 | $3.75 | $15.00 | $1.88 | 128K |
| ft:gpt-4o-2024-11-20 | $3.75 | $15.00 | — | 128K |
| ft:gpt-4o-mini-2024-07-18 | $0.30 | $1.20 | $0.15 | 128K |
| ft:o4-mini-2025-04-16 | $4.00 | $16.00 | $1.00 | 200K |
| gpt astra latest | $10.00 | $50.00 | $1.00 | 1.05M |
| gpt chat latest | $5.00 | $30.00 | $0.50 | 400K |
| gpt luna latest | $0.10 | $0.50 | $0.01 | 1.05M |
| gpt mini latest | $0.75 | $4.50 | $0.08 | 400K |
| gpt sol latest | $2.00 | $10.00 | $0.10 | 1.05M |
| gpt terra latest | $1.00 | $5.00 | $0.05 | 1.05M |
| gpt-3.5 turbo (older v0613) | $1.00 | $2.00 | — | 4.09K |
| gpt-3.5-turbo | $0.50 | $1.50 | — | 16.39K |
| gpt-3.5-turbo-16k | $3.00 | $4.00 | — | 16.39K |
| gpt-3.5-turbo-0125 | $0.50 | $1.50 | — | 16.39K |
| gpt-3.5-turbo-1106 | $1.00 | $2.00 | — | 16.39K |
| gpt-4 | $30.00 | $60.00 | — | 8.19K |
| gpt-4 turbo (batch) | $5.00 | $15.00 | — | 128K |
| gpt-4-0613 | $30.00 | $60.00 | — | 8.19K |
| gpt-4-1106-preview | $10.00 | $30.00 | — | 128K |
| gpt-4-turbo | $10.00 | $30.00 | — | 128K |
| gpt-4-turbo-2024-04-09 | $10.00 | $30.00 | — | 128K |
| gpt-4.1 | $2.00 | $8.00 | $0.50 | 1.05M |
| gpt-4.1 (batch) | $1.00 | $4.00 | $0.25 | 1.05M |
| gpt-4.1 mini (batch) | $0.20 | $0.80 | $0.05 | 1.05M |
| gpt-4.1 nano (batch) | $0.05 | $0.20 | $0.01 | 1.05M |
| gpt-4.1-2025-04-14 | $2.00 | $8.00 | $0.50 | 1.05M |
| gpt-4.1-mini | $0.40 | $1.60 | $0.10 | 1.05M |
| gpt-4.1-mini-2025-04-14 | $0.40 | $1.60 | $0.10 | 1.05M |
| gpt-4.1-nano | $0.10 | $0.40 | $0.02 | 1.05M |
| gpt-4.1-nano-2025-04-14 | $0.10 | $0.40 | $0.02 | 1.05M |
| gpt-4o | $2.50 | $10.00 | $1.25 | 128K |
| gpt-4o (batch) | $1.25 | $5.00 | $0.62 | 128K |
| gpt-4o-2024-05-13 | $5.00 | $15.00 | — | 128K |
| gpt-4o-2024-08-06 | $2.50 | $10.00 | $1.25 | 128K |
| gpt-4o-2024-11-20 | $2.50 | $10.00 | $1.25 | 128K |
| gpt-4o-audio-preview-2024-12-17 | $2.50 | $10.00 | — | 128K |
| gpt-4o-audio-preview-2025-06-03 | $2.50 | $10.00 | — | 128K |
| gpt-4o-mini | $0.15 | $0.60 | $0.08 | 128K |
| gpt-4o-mini (batch) | $0.08 | $0.30 | $0.04 | 128K |
| gpt-4o-mini-2024-07-18 | $0.15 | $0.60 | $0.08 | 128K |
| gpt-4o-mini-audio-preview-2024-12-17 | $0.15 | $0.60 | — | 128K |
| gpt-4o-mini-realtime-preview-2024-12-17 | $0.60 | $2.40 | $0.30 | 128K |
| gpt-4o-mini-search-preview | $0.15 | $0.60 | $0.08 | 128K |
| gpt-4o-mini-search-preview-2025-03-11 | $0.15 | $0.60 | $0.08 | 128K |
| gpt-4o-mini-transcribe | $1.25 | $5.00 | — | 16K |
| gpt-4o-mini-transcribe-2025-03-20 | $1.25 | $5.00 | — | 16K |
| gpt-4o-mini-transcribe-2025-12-15 | $1.25 | $5.00 | — | 16K |
| gpt-4o-mini-tts | $0.60 | $10.00 | — | — |
| gpt-4o-mini-tts-2025-03-20 | $0.60 | $10.00 | — | — |
| gpt-4o-mini-tts-2025-12-15 | $0.60 | $10.00 | — | — |
| gpt-4o-search-preview | $2.50 | $10.00 | $1.25 | 128K |
| gpt-4o-search-preview-2025-03-11 | $2.50 | $10.00 | $1.25 | 128K |
| gpt-4o-transcribe | $2.50 | $10.00 | — | 16K |
| gpt-4o-transcribe-diarize | $2.50 | $10.00 | — | 16K |
| gpt-5 | $1.25 | $10.00 | $0.12 | 272K |
| gpt-5 (batch) | $0.62 | $5.00 | $0.06 | 400K |
| gpt-5 image | $10.00 | $10.00 | $1.25 | 400K |
| gpt-5 image mini | $2.50 | $2.00 | $0.25 | 400K |
| gpt-5 mini (batch) | $0.12 | $1.00 | $0.01 | 400K |
| gpt-5 nano (batch) | $0.02 | $0.20 | $0.0025 | 400K |
| gpt-5 pro (batch) | $7.50 | $60.00 | — | 400K |
| gpt-5-2025-08-07 | $1.25 | $10.00 | $0.12 | 272K |
| gpt-5-chat | $1.25 | $10.00 | $0.12 | 128K |
| gpt-5-chat-latest | $1.25 | $10.00 | $0.12 | 128K |
| gpt-5-codex | $1.25 | $10.00 | $0.12 | 272K |
| gpt-5-mini | $0.25 | $2.00 | $0.02 | 272K |
| gpt-5-mini-2025-08-07 | $0.25 | $2.00 | $0.02 | 272K |
| gpt-5-nano | $0.05 | $0.40 | $0.005 | 272K |
| gpt-5-nano-2025-08-07 | $0.05 | $0.40 | $0.005 | 272K |
| gpt-5-pro | $15.00 | $120.00 | — | 400K |
| gpt-5-pro-2025-10-06 | $15.00 | $120.00 | — | 400K |
| gpt-5-search-api | $1.25 | $10.00 | $0.12 | 272K |
| gpt-5-search-api-2025-10-14 | $1.25 | $10.00 | $0.12 | 272K |
| gpt-5.1 | $1.25 | $10.00 | $0.12 | 272K |
| gpt-5.1 (batch) | $0.62 | $5.00 | $0.06 | 400K |
| gpt-5.1-2025-11-13 | $1.25 | $10.00 | $0.12 | 272K |
| gpt-5.1-chat-latest | $1.25 | $10.00 | $0.12 | 128K |
| gpt-5.1-codex | $1.25 | $10.00 | $0.12 | 400K |
| gpt-5.1-codex-max | $1.25 | $10.00 | $0.12 | 400K |
| gpt-5.1-codex-mini | $0.25 | $2.00 | $0.02 | 400K |
| gpt-5.2 | $1.75 | $14.00 | $0.18 | 272K |
| gpt-5.2 (batch) | $0.88 | $7.00 | $0.09 | 400K |
| gpt-5.2 chat | $1.75 | $14.00 | $0.18 | 128K |
| gpt-5.2 pro (batch) | $10.50 | $84.00 | — | 400K |
| gpt-5.2-2025-12-11 | $1.75 | $14.00 | $0.18 | 272K |
| gpt-5.2-chat-latest | $1.75 | $14.00 | $0.18 | 128K |
| gpt-5.2-codex | $1.75 | $14.00 | $0.18 | 272K |
| gpt-5.2-pro | $21.00 | $168.00 | — | 272K |
| gpt-5.2-pro-2025-12-11 | $21.00 | $168.00 | — | 272K |
| gpt-5.3-chat-latest | $1.75 | $14.00 | $0.18 | 128K |
| gpt-5.3-codex | $1.75 | $14.00 | $0.18 | 272K |
| gpt-5.4 | $2.50 | $15.00 | $0.25 | 1.05M |
| gpt-5.4 (batch) | $1.25 | $7.50 | $0.12 | 1.05M |
| gpt-5.4 image 2 | $8.00 | $15.00 | $2.00 | 272K |
| gpt-5.4 mini (batch) | $0.38 | $2.25 | $0.04 | 400K |
| gpt-5.4 nano (batch) | $0.10 | $0.62 | $0.01 | 400K |
| gpt-5.4 pro (batch) | $15.00 | $90.00 | — | 1.05M |
| gpt-5.4-2026-03-05 | $2.50 | $15.00 | $0.25 | 1.05M |
| gpt-5.4-mini | $0.75 | $4.50 | $0.08 | 272K |
| gpt-5.4-mini-2026-03-17 | $0.75 | $4.50 | $0.08 | 272K |
| gpt-5.4-nano | $0.20 | $1.25 | $0.02 | 272K |
| gpt-5.4-nano-2026-03-17 | $0.20 | $1.25 | $0.02 | 272K |
| gpt-5.4-pro | $30.00 | $180.00 | — | 1.05M |
| gpt-5.4-pro-2026-03-05 | $30.00 | $180.00 | — | 1.05M |
| gpt-5.5 | $5.00 | $30.00 | $0.50 | 1.05M |
| gpt-5.5 (batch) | $2.50 | $15.00 | $0.25 | 1.05M |
| gpt-5.5 pro (batch) | $15.00 | $90.00 | — | 1.05M |
| gpt-5.5-2026-04-23 | $5.00 | $30.00 | $0.50 | 1.05M |
| gpt-5.5-cyber | $12.50 | $75.00 | $1.25 | — |
| gpt-5.5-cyber-preview | $12.50 | $75.00 | $1.25 | — |
| gpt-5.5-pro | $30.00 | $180.00 | — | 1.05M |
| gpt-5.5-pro-2026-04-23 | $30.00 | $180.00 | — | 1.05M |
| gpt-5.6 | $4.00 | $20.00 | $0.40 | 922K |
| gpt-5.6 luna (batch) | $0.10 | $0.60 | $0.01 | 1.05M |
| gpt-5.6 luna pro | $0.20 | $1.20 | $0.02 | 1.05M |
| gpt-5.6 luna pro (batch) | $0.10 | $0.60 | $0.01 | 1.05M |
| gpt-5.6 sol (batch) | $2.00 | $10.00 | $0.20 | 1.05M |
| gpt-5.6 sol pro | $4.00 | $20.00 | $0.40 | 1.05M |
| gpt-5.6 sol pro (batch) | $2.00 | $10.00 | $0.20 | 1.05M |
| gpt-5.6 terra (batch) | $1.00 | $6.00 | $0.10 | 1.05M |
| gpt-5.6 terra pro | $2.00 | $12.00 | $0.20 | 1.05M |
| gpt-5.6 terra pro (batch) | $1.00 | $6.00 | $0.10 | 1.05M |
| gpt-5.6-cyber | $12.50 | $75.00 | $1.25 | 400K |
| gpt-5.6-luna | $0.20 | $1.20 | $0.02 | 922K |
| gpt-5.6-sol | $4.00 | $20.00 | $0.40 | 922K |
| gpt-5.6-terra | $2.00 | $12.00 | $0.20 | 922K |
| gpt-6 astra (batch) | $5.00 | $25.00 | $0.50 | 1.05M |
| gpt-6 astra pro | $10.00 | $50.00 | $1.00 | 1.05M |
| gpt-6 astra pro (batch) | $5.00 | $25.00 | $0.50 | 1.05M |
| gpt-6 luna (batch) | $0.05 | $0.25 | $0.005 | 1.05M |
| gpt-6 luna pro | $0.10 | $0.50 | $0.01 | 1.05M |
| gpt-6 luna pro (batch) | $0.05 | $0.25 | $0.005 | 1.05M |
| gpt-6 sol (batch) | $1.00 | $5.00 | $0.10 | 1.05M |
| gpt-6 sol pro | $2.00 | $10.00 | $0.20 | 1.05M |
| gpt-6 sol pro (batch) | $1.00 | $5.00 | $0.10 | 1.05M |
| gpt-6-astra | $10.00 | $50.00 | $1.00 | 922K |
| gpt-6-luna | $0.10 | $0.50 | $0.01 | 922K |
| gpt-6-sol | $2.00 | $10.00 | $0.20 | 922K |
| gpt-6.1 sol (batch) | $1.00 | $5.00 | $0.05 | 1.05M |
| gpt-6.1 sol pro | $2.00 | $10.00 | $0.10 | 1.05M |
| gpt-6.1 sol pro (batch) | $1.00 | $5.00 | $0.05 | 1.05M |
| gpt-6.1 terra (batch) | $0.50 | $2.50 | $0.02 | 1.05M |
| gpt-6.1 terra pro | $1.00 | $5.00 | $0.05 | 1.05M |
| gpt-6.1 terra pro (batch) | $0.50 | $2.50 | $0.02 | 1.05M |
| gpt-6.1-sol | $2.00 | $10.00 | $0.10 | 922K |
| gpt-6.1-terra | $1.00 | $5.00 | $0.05 | 922K |
| gpt-audio | $2.50 | $10.00 | — | 128K |
| gpt-audio-1.5 | $2.50 | $10.00 | — | 128K |
| gpt-audio-2025-08-28 | $2.50 | $10.00 | — | 128K |
| gpt-audio-mini | $0.60 | $2.40 | — | 128K |
| gpt-audio-mini-2025-10-06 | $0.60 | $2.40 | — | 128K |
| gpt-audio-mini-2025-12-15 | $0.60 | $2.40 | — | 128K |
| gpt-daybreak-blue-latest | $4.00 | $20.00 | $0.40 | 922K |
| gpt-daybreak-red-latest | $12.50 | $75.00 | $1.25 | 400K |
| gpt-image-1 | $5.00 | — | $1.25 | — |
| gpt-image-1-mini | $2.00 | — | $0.20 | — |
| gpt-image-1.5 | $5.00 | $10.00 | $1.25 | — |
| gpt-image-1.5-2025-12-16 | $5.00 | $10.00 | $1.25 | — |
| gpt-image-2 | $5.00 | — | $1.25 | — |
| gpt-image-2-2026-04-21 | $5.00 | — | $1.25 | — |
| gpt-image-2.5-flare | $5.00 | — | $1.25 | — |
| gpt-image-2.5-flare-2026-09-08 | $5.00 | — | $1.25 | — |
| gpt-image-2.5-sunburst | $5.00 | — | $1.25 | — |
| gpt-image-2.5-sunburst-2026-09-08 | $5.00 | — | $1.25 | — |
| gpt-oss-20b | $0.02 | $0.09 | $0.009 | 131.07K |
| gpt-oss-20b (batch) | $0.02 | $0.11 | — | 131.07K |
| gpt-oss-120b | $0.15 | $0.60 | $0.08 | 131.07K |
| gpt-oss-120b (batch) | $0.03 | $0.14 | — | 131.07K |
| gpt-oss-safeguard-20b | $0.08 | $0.30 | $0.04 | 131.07K |
| gpt-realtime | $4.00 | $16.00 | $0.40 | 32K |
| gpt-realtime-1.5 | $4.00 | $16.00 | $0.40 | 32K |
| gpt-realtime-2 | $4.00 | $24.00 | $0.40 | 128K |
| gpt-realtime-2.1 | $4.00 | $24.00 | $0.40 | 128K |
| gpt-realtime-2.1-mini | $0.60 | $2.40 | $0.06 | 128K |
| gpt-realtime-2025-08-28 | $4.00 | $16.00 | $0.40 | 32K |
| gpt-realtime-mini | $0.60 | $2.40 | $0.06 | 32K |
| gpt-realtime-mini-2025-12-15 | $0.60 | $2.40 | $0.06 | 128K |
| gpt-rosalind-discovery | $5.00 | $25.00 | $0.50 | — |
| gpt-rosalind-research | $5.00 | $25.00 | $0.50 | — |
| o1 | $15.00 | $60.00 | $7.50 | 200K |
| o1-2024-12-17 | $15.00 | $60.00 | $7.50 | 200K |
| o1-pro | $150.00 | $600.00 | — | 200K |
| o1-pro-2025-03-19 | $150.00 | $600.00 | — | 200K |
| o3 | $2.00 | $8.00 | $0.50 | 200K |
| o3 (batch) | $1.00 | $4.00 | $0.25 | 200K |
| o3 mini (batch) | $0.55 | $2.20 | $0.28 | 200K |
| o3 mini high | $1.10 | $4.40 | $0.55 | 200K |
| o3-2025-04-16 | $2.00 | $8.00 | $0.50 | 200K |
| o3-deep-research | $10.00 | $40.00 | $2.50 | 200K |
| o3-deep-research-2025-06-26 | $10.00 | $40.00 | $2.50 | 200K |
| o3-mini | $1.10 | $4.40 | $0.55 | 200K |
| o3-mini-2025-01-31 | $1.10 | $4.40 | $0.55 | 200K |
| o3-pro | $20.00 | $80.00 | — | 200K |
| o3-pro-2025-06-10 | $20.00 | $80.00 | — | 200K |
| o4 mini (batch) | $0.55 | $2.20 | $0.14 | 200K |
| o4 mini high | $1.10 | $4.40 | $0.28 | 200K |
| o4-mini | $1.10 | $4.40 | $0.28 | 200K |
| o4-mini-2025-04-16 | $1.10 | $4.40 | $0.28 | 200K |
| o4-mini-deep-research | $2.00 | $8.00 | $0.50 | 200K |
| o4-mini-deep-research-2025-06-26 | $2.00 | $8.00 | $0.50 | 200K |
| omni-moderation-2024-09-26 | $0.00 | $0.00 | — | 32.77K |
| omni-moderation-latest | $0.00 | $0.00 | — | 32.77K |
| text-embedding-3-large | $0.13 | $0.00 | — | 8.19K |
| text-embedding-3-small | $0.02 | $0.00 | — | 8.19K |
| text-embedding-ada-002 | $0.10 | $0.00 | — | 8.19K |
| text-embedding-ada-002-v2 | $0.10 | $0.00 | — | 8.19K |

## opencode_go

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| beam-free | $0.00 | $0.00 | $0.00 | 1.05M |
| claude-haiku-5-5 | $0.10 | $0.50 | $0.01 | 1M |
| deepseek-v4-pro | $1.32 | $3.96 | $0.04 | 1M |
| deepseek-v4.1-flash | $0.30 | $1.20 | $0.006 | 1M |
| gemini-4-argon | $2.00 | $10.00 | $0.10 | 1.05M |
| glm-5.2 | $1.40 | $4.40 | $0.26 | 1M |
| glm-5.3 | $1.40 | $4.40 | $0.26 | 1M |
| glm-5.3-flash | $0.15 | $0.50 | $0.03 | 1M |
| gpt-5.6-luna | $0.20 | $1.20 | $0.02 | 922K |
| gpt-6-luna | $0.10 | $0.50 | $0.01 | 922K |
| grok-4.7 | $2.00 | $6.00 | $0.50 | 500K |
| hy3 | $0.14 | $0.58 | $0.04 | 192K |
| hy4-preview | $0.83 | $2.50 | $0.04 | 1.02M |
| kimi-k2.7-code | $0.95 | $4.00 | $0.19 | 262.14K |
| kimi-k3 | $3.00 | $15.00 | $0.30 | 1.05M |
| kimi-k3.1-pro | $2.00 | $10.00 | $0.20 | 1.05M |
| longcat-2.0 | $0.30 | $1.20 | $0.006 | 1M |
| longcat-2.5-preview-free | $0.00 | $0.00 | $0.00 | 1M |
| mimo-v2.5 | $0.14 | $0.28 | $0.0028 | 1M |
| mimo-v2.5-pro | $0.44 | $0.87 | $0.003625 | 1.05M |
| mimo-v2.6-flash | $0.14 | $0.28 | $0.0028 | 1.05M |
| mimo-v2.6-pro | $0.44 | $0.87 | $0.003625 | 1.05M |
| minimax-m3 | $0.30 | $1.20 | $0.06 | 1M |
| minimax-m3.1-flash | $0.15 | $0.60 | $0.02 | 1M |
| muse-spark-1.2-contributor | $0.10 | $0.20 | $0.002 | 1.05M |
| muse-spark-1.3-contributor | $0.10 | $0.20 | $0.002 | 1.05M |
| qwen3.7-plus | $0.40 | $1.60 | $0.04 | 1M |
| qwen3.8-flash | $0.15 | $0.47 | $0.02 | 1M |
| qwen3.8-max | $2.00 | $6.00 | $0.25 | 1M |
| step-5-preview | $1.00 | $2.70 | $0.10 | 1M |

## openinfer

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| glm-5.3-flash | $0.20 | $1.56 | — | 393.22K |
| qwen3.5-9b | $5.00 | $0.15 | — | 100K |
| qwen3.5-27b | $0.20 | $1.56 | — | 32.77K |

## openrouter

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| free models router | $0.00 | $0.00 | — | 200K |

## ovhcloud

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| deepseek-r1-distill-llama-70b | $0.67 | $0.67 | — | 131K |
| gpt-oss-20b | $0.04 | $0.15 | — | 131K |
| gpt-oss-120b | $0.08 | $0.40 | — | 131K |
| llama-3.1-8b-instruct | $0.10 | $0.10 | — | 131K |
| llava-v1.6-mistral-7b-hf | $0.29 | $0.29 | — | 32K |
| mamba-codestral-7b-v0.1 | $0.19 | $0.19 | — | 256K |
| meta-llama-3_1-70b-instruct | $0.67 | $0.67 | — | 131K |
| meta-llama-3_3-70b-instruct | $0.67 | $0.67 | — | 131K |
| mistral-7b-instruct-v0.3 | $0.10 | $0.10 | — | 127K |
| mistral-nemo-instruct-2407 | $0.13 | $0.13 | — | 118K |
| mistral-small-3.2-24b-instruct-2506 | $0.09 | $0.28 | — | 128K |
| mixtral-8x7b-instruct-v0.1 | $0.63 | $0.63 | — | 32K |
| qwen2.5-coder-32b-instruct | $0.87 | $0.87 | — | 32K |
| qwen2.5-vl-72b-instruct | $0.91 | $0.91 | — | 32K |
| qwen3-32b | $0.08 | $0.23 | — | 32K |

## perceptron

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| perceptron mk1 | $0.15 | $1.50 | — | 32.77K |
| perceptron mk1.5 | $0.15 | $1.50 | — | 36.86K |

## perplexity

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| claude-fable-5 | $10.00 | $50.00 | $1.00 | — |
| claude-fable-5-1 | $10.00 | $50.00 | $0.25 | — |
| claude-haiku-4-5 | $1.00 | $5.00 | $0.10 | — |
| claude-haiku-5-5 | $0.10 | $0.50 | $0.01 | — |
| claude-opus-4-5 | $5.00 | $25.00 | $0.50 | — |
| claude-opus-4-6 | $5.00 | $25.00 | $0.50 | — |
| claude-opus-4-7 | $5.00 | $25.00 | $0.50 | — |
| claude-opus-4-8 | $5.00 | $25.00 | $0.50 | — |
| claude-opus-5 | $5.00 | $25.00 | $0.50 | — |
| claude-opus-5-5 | $4.00 | $20.00 | $0.20 | — |
| claude-sonnet-4-5 | $3.00 | $15.00 | $0.30 | — |
| claude-sonnet-4-6 | $3.00 | $15.00 | $0.30 | — |
| claude-sonnet-5 | $2.00 | $10.00 | $0.20 | — |
| claude-sonnet-5-5 | $2.00 | $10.00 | $0.20 | — |
| codellama-34b-instruct | $0.35 | $1.40 | — | 16.38K |
| codellama-70b-instruct | $0.70 | $2.80 | — | 16.38K |
| deepseek-v4-flash-0731 | $0.13 | $0.26 | $0.03 | — |
| deepseek-v4-pro-0813 | $1.32 | $3.96 | $0.04 | — |
| gemini-3-flash-preview | $0.50 | $3.00 | $0.05 | — |
| gemini-3.1-flash-lite | $0.25 | $1.50 | $0.02 | — |
| gemini-3.1-pro-preview | $2.00 | $12.00 | $0.20 | — |
| gemini-3.5-flash | $1.50 | $9.00 | $0.15 | — |
| gemini-3.5-flash-lite | $0.30 | $2.50 | $0.03 | — |
| gemini-3.6-flash | $1.50 | $7.50 | $0.15 | — |
| gemini-3.7-flash | $0.75 | $3.75 | $0.08 | — |
| gemini-3.8-flash | $0.75 | $3.75 | $0.08 | — |
| glm-5.2 | $1.40 | $4.40 | $0.14 | — |
| glm-5.3 | $1.40 | $4.40 | $0.26 | — |
| glm-5.3-flash | $0.15 | $0.50 | $0.03 | — |
| gpt-5 | $1.25 | $10.00 | $0.12 | — |
| gpt-5-mini | $0.25 | $2.00 | $0.02 | — |
| gpt-5-nano | $0.05 | $0.40 | $0.005 | — |
| gpt-5.1 | $1.25 | $10.00 | $0.12 | — |
| gpt-5.2 | $1.75 | $14.00 | $0.18 | — |
| gpt-5.3-codex | $3.50 | $28.00 | $0.35 | — |
| gpt-5.4 | $2.50 | $15.00 | $0.25 | — |
| gpt-5.4-mini | $0.75 | $4.50 | $0.08 | — |
| gpt-5.4-nano | $0.20 | $1.25 | $0.02 | — |
| gpt-5.5 | $5.00 | $30.00 | $0.50 | — |
| gpt-5.6-luna | $0.20 | $1.20 | $0.02 | — |
| gpt-5.6-sol | $4.00 | $20.00 | $0.40 | — |
| gpt-5.6-terra | $2.00 | $12.00 | $0.20 | — |
| gpt-6-astra | $10.00 | $50.00 | $1.00 | — |
| gpt-6-luna | $0.10 | $0.50 | $0.01 | — |
| gpt-6-sol | $2.00 | $10.00 | $0.20 | — |
| gpt-6.1-sol | $2.00 | $10.00 | $0.10 | — |
| grok-4.3 | $1.25 | $2.50 | $0.20 | — |
| grok-4.5 | $2.00 | $6.00 | $0.30 | — |
| grok-4.6 | $2.00 | $6.00 | $0.50 | — |
| grok-4.7 | $2.00 | $6.00 | $0.50 | — |
| grok-4.20-multi-agent | $1.25 | $2.50 | $0.20 | — |
| grok-4.20-non-reasoning | $1.25 | $2.50 | $0.20 | — |
| grok-4.20-reasoning | $1.25 | $2.50 | $0.20 | — |
| kimi-k2.7-code | $0.95 | $4.00 | $0.19 | — |
| kimi-k3 | $3.00 | $15.00 | $0.30 | — |
| llama-2-70b-chat | $0.70 | $2.80 | — | 4.1K |
| llama-3.1-8b-instruct | $0.20 | $0.20 | — | 131.07K |
| llama-3.1-70b-instruct | $1.00 | $1.00 | — | 131.07K |
| mistral-7b-instruct | $0.07 | $0.28 | — | 4.1K |
| mixtral-8x7b-instruct | $0.07 | $0.28 | — | 4.1K |
| nemotron-3-ultra-550b-a55b | $0.25 | $2.50 | $0.25 | — |
| nemotron-3.5-lightning-30b-a3b | $0.01 | $0.17 | $0.00115 | — |
| pplx-7b-chat | $0.07 | $0.28 | — | 8.19K |
| pplx-7b-online | $0.00 | $0.28 | — | 4.1K |
| pplx-70b-chat | $0.70 | $2.80 | — | 4.1K |
| pplx-70b-online | $0.00 | $2.80 | — | 4.1K |
| pplx-decider-flash-latest | $0.01 | $0.00 | — | 262.14K |
| pplx-decider-flash-v1.2 | $0.01 | $0.00 | — | 262.14K |
| pplx-decider-latest | $0.02 | $0.00 | — | 262.14K |
| pplx-decider-v1-27b | $0.02 | $0.00 | — | 262.14K |
| pplx-decider-v1.1-27b | $0.02 | $0.00 | — | 262.14K |
| pplx-decider-v1.2 | $0.02 | $0.00 | — | 262.14K |
| pplx-embed-context-v1-0.6b | $0.008 | $0.00 | — | 32.77K |
| pplx-embed-context-v1-4b | $0.05 | $0.00 | — | 32.77K |
| pplx-embed-v1-0.6b | $0.004 | $0.00 | — | 32.77K |
| pplx-embed-v1-4b | $0.03 | $0.00 | — | 32.77K |
| sonar | $0.25 | $2.50 | $0.06 | — |
| sonar pro search | $3.00 | $15.00 | — | 200K |
| sonar-deep-research | $2.00 | $8.00 | — | 128K |
| sonar-medium-chat | $0.60 | $1.80 | — | 16.38K |
| sonar-medium-online | $0.00 | $1.80 | — | 12K |
| sonar-pro | $3.00 | $15.00 | — | 200K |
| sonar-reasoning | $1.00 | $5.00 | — | 128K |
| sonar-reasoning-pro | $2.00 | $8.00 | — | 128K |
| sonar-small-chat | $0.07 | $0.28 | — | 16.38K |
| sonar-small-online | $0.00 | $0.28 | — | 12K |

## pinstripes

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| deepseek-v4-flash | $0.10 | $0.20 | — | 163.84K |
| glm-4.5-air | $0.12 | $0.45 | — | 128K |
| minimax-m2.7 | $0.26 | $0.55 | — | 1M |
| qwen3-30b-a3b | $0.09 | $0.20 | — | 131.07K |
| qwen3-coder-30b-a3b | $0.30 | $0.60 | — | 131.07K |
| qwen3.6-35b-a3b | $0.14 | $0.45 | — | 131.07K |

## poolside

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| laguna s 2.1 | $0.09 | $0.18 | $0.009 | 1.05M |
| laguna s 2.1 (free) | $0.00 | $0.00 | — | 262.14K |
| laguna xs 2.1 | $0.06 | $0.12 | $0.03 | 262.14K |
| laguna xs 2.1 (free) | $0.00 | $0.00 | — | 262.14K |

## prism

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| deepseek-v4-flash | $0.17 | $0.21 | $0.07 | 1M |
| deepseek-v4.1-flash | $0.17 | $0.63 | $0.07 | 1M |

## prism-ml

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| prismml: ternary bonsai 2 27b | $0.08 | $0.50 | $0.04 | 262.14K |

## publicai

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| alia-40b-instruct_q8_0 | $0.00 | $0.00 | — | 8.19K |
| apertus-8b-instruct | $0.00 | $0.00 | — | 8.19K |
| apertus-70b-instruct | $0.00 | $0.00 | — | 8.19K |
| gemma-sea-lion-v4-27b-it | $0.00 | $0.00 | — | 8.19K |
| olmo-3-7b-instruct | $0.00 | $0.00 | — | 32.77K |
| olmo-3-7b-think | $0.00 | $0.00 | — | 32.77K |
| olmo-3-32b-think | $0.00 | $0.00 | — | 32.77K |
| qwen-sea-lion-v4-32b-it | $0.00 | $0.00 | — | 32.77K |
| salamandra-7b-instruct-tools-16k | $0.00 | $0.00 | — | 16.38K |

## qwen

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| qwen2.5 7b instruct | $0.10 | $0.20 | — | 32.77K |
| qwen2.5 72b instruct | $0.36 | $0.40 | — | 32.77K |
| qwen2.5 coder 32b instruct | $0.66 | $1.00 | — | 32.77K |
| qwen2.5 vl 72b instruct | $0.80 | $1.00 | $0.40 | 128K |
| qwen3 14b | $0.12 | $0.24 | — | 40.96K |
| qwen3 30b a3b | $0.12 | $0.50 | — | 40.96K |
| qwen3 30b a3b instruct 2507 | $0.10 | $0.30 | — | 262.14K |
| qwen3 32b | $0.08 | $0.28 | — | 131.07K |
| qwen3 235b a22b instruct 2507 | $0.09 | $0.55 | — | 262.14K |
| qwen3 235b a22b thinking 2507 | $0.45 | $3.50 | — | 128K |
| qwen3 coder 30b a3b instruct | $0.07 | $0.28 | — | 262.14K |
| qwen3 coder 480b a35b | $0.30 | $1.00 | $0.10 | 262.14K |
| qwen3 coder flash | $0.20 | $0.98 | $0.04 | 1M |
| qwen3 coder next | $0.12 | $0.80 | $0.07 | 262.14K |
| qwen3 next 80b a3b instruct | $0.09 | $1.10 | — | 262.14K |
| qwen3 next 80b a3b thinking | $0.15 | $1.20 | — | 262.14K |
| qwen3 vl 8b instruct | $0.25 | $0.75 | $0.12 | 262.14K |
| qwen3 vl 30b a3b instruct | $0.15 | $0.60 | — | 262.14K |
| qwen3 vl 30b a3b thinking | $0.29 | $1.00 | — | 262.14K |
| qwen3 vl 235b a22b instruct | $0.21 | $1.90 | $0.10 | 262.14K |
| qwen3.5 397b a17b | $0.50 | $3.60 | $0.30 | 262.14K |
| qwen3.5 plus 2026-02-15 | $0.26 | $1.56 | — | 1M |
| qwen3.5 plus 2026-04-20 | $0.30 | $1.80 | — | 1M |
| qwen3.5-9b | $0.17 | $0.25 | — | 262.14K |
| qwen3.5-27b | $0.26 | $2.60 | — | 262.14K |
| qwen3.5-35b-a3b | $0.14 | $1.00 | $0.05 | 262.14K |
| qwen3.5-122b-a10b | $0.26 | $2.08 | — | 262.14K |
| qwen3.5-flash | $0.06 | $0.26 | — | 1M |
| qwen3.6 27b | $0.32 | $3.20 | — | 262.14K |
| qwen3.6 35b a3b | $0.10 | $0.95 | $0.05 | 262.14K |
| qwen3.6 flash | $0.19 | $1.12 | — | 1M |
| qwen3.6 plus | $0.32 | $1.95 | — | 1M |
| qwen3.7 flash | $0.03 | $0.13 | $0.006 | 1M |
| qwen3.7 max | $1.48 | $4.42 | $0.30 | 1M |
| qwen3.7 plus | $0.32 | $1.28 | $0.06 | 1M |
| qwen3.7 plus (batch) | $0.23 | $0.92 | — | 262.14K |
| qwen3.8 2.4t a95b | $2.00 | $6.00 | $0.25 | 1.05M |
| qwen3.8 27b | $0.20 | $2.50 | $0.09 | 1M |
| qwen3.8 flash | $0.15 | $0.47 | $0.02 | 1M |
| qwen3.8 max (0902) | $2.00 | $6.00 | $0.25 | 1M |
| qwen3.8 max prime | $4.00 | $12.00 | $0.50 | 1M |
| qwen3.8 omni flash | $0.15 | $0.47 | $0.02 | 1M |
| qwen-plus | $0.26 | $0.78 | $0.05 | 1M |

## qwen_ai_platform

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| deepseek-v4-flash | $0.20 | $0.40 | $0.04 | 1M |
| deepseek-v4-flash-0731 | $0.20 | $0.40 | $0.04 | 1M |
| deepseek-v4-pro | $2.40 | $4.80 | $0.20 | 1M |
| glm-5.1 | $1.40 | $4.40 | $0.26 | 202.75K |
| glm-5.2 | $1.40 | $4.40 | $0.28 | 1.05M |
| kimi-k2.7-code | $0.95 | $4.00 | $0.19 | 229.38K |
| qwen3-next-80b-a3b-instruct | $0.15 | $1.20 | — | 262.14K |
| qwen3-next-80b-a3b-thinking | $0.15 | $1.20 | — | 262.14K |
| qwen3-vl-32b-instruct | $0.16 | $0.64 | — | 131.07K |
| qwen3-vl-32b-thinking | $0.16 | $2.87 | — | 131.07K |
| qwen3-vl-235b-a22b-instruct | $0.40 | $1.60 | — | 131.07K |
| qwen3-vl-235b-a22b-thinking | $0.40 | $4.00 | — | 131.07K |
| qwen3.7-max | $2.50 | $7.50 | $0.50 | 991.81K |
| qwen3.8-flash | $0.15 | $0.47 | $0.02 | 991.81K |
| qwen3.8-max | $2.00 | $6.00 | $0.25 | 991.81K |
| qwen3.8-omni-flash | $0.15 | $0.47 | $0.02 | 991.81K |
| qwen-coder | $0.30 | $1.50 | — | 1M |
| qwen-max | $1.60 | $6.40 | — | 30.72K |
| qwen-plus | $0.40 | $1.20 | — | 129.02K |
| qwen-plus-2025-01-25 | $0.40 | $1.20 | — | 129.02K |
| qwen-plus-2025-04-28 | $0.40 | $1.20 | — | 129.02K |
| qwen-plus-2025-07-14 | $0.40 | $1.20 | — | 129.02K |
| qwen-turbo | $0.05 | $0.20 | — | 129.02K |
| qwen-turbo-2024-11-01 | $0.05 | $0.20 | — | 1M |
| qwen-turbo-2025-04-28 | $0.05 | $0.20 | — | 1M |
| qwen-turbo-latest | $0.05 | $0.20 | — | 1M |
| qwq-plus | $0.80 | $2.40 | — | 98.3K |

## qwencloud

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| deepseek-v4-flash | $0.20 | $0.40 | $0.04 | 1M |
| deepseek-v4-flash-0731 | $0.20 | $0.40 | $0.04 | 1M |
| deepseek-v4-pro | $2.40 | $4.80 | $0.20 | 1M |
| glm-5.1 | $1.40 | $4.40 | $0.26 | 202.75K |
| glm-5.2 | $1.40 | $4.40 | $0.28 | 1.05M |
| kimi-k2.7-code | $0.95 | $4.00 | $0.19 | 229.38K |
| qwen3-next-80b-a3b-instruct | $0.15 | $1.20 | — | 262.14K |
| qwen3-next-80b-a3b-thinking | $0.15 | $1.20 | — | 262.14K |
| qwen3-vl-32b-instruct | $0.16 | $0.64 | — | 131.07K |
| qwen3-vl-32b-thinking | $0.16 | $2.87 | — | 131.07K |
| qwen3-vl-235b-a22b-instruct | $0.40 | $1.60 | — | 131.07K |
| qwen3-vl-235b-a22b-thinking | $0.40 | $4.00 | — | 131.07K |
| qwen3.7-max | $2.50 | $7.50 | $0.50 | 991.81K |
| qwen3.8-max | $2.00 | $6.00 | $0.25 | 991.81K |
| qwen-coder | $0.30 | $1.50 | — | 1M |
| qwen-max | $1.60 | $6.40 | — | 30.72K |
| qwen-plus | $0.40 | $1.20 | — | 129.02K |
| qwen-plus-2025-01-25 | $0.40 | $1.20 | — | 129.02K |
| qwen-plus-2025-04-28 | $0.40 | $1.20 | — | 129.02K |
| qwen-plus-2025-07-14 | $0.40 | $1.20 | — | 129.02K |
| qwen-turbo | $0.05 | $0.20 | — | 129.02K |
| qwen-turbo-2024-11-01 | $0.05 | $0.20 | — | 1M |
| qwen-turbo-2025-04-28 | $0.05 | $0.20 | — | 1M |
| qwen-turbo-latest | $0.05 | $0.20 | — | 1M |
| qwq-plus | $0.80 | $2.40 | — | 98.3K |

## recursive

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| flint (free) | $0.00 | $0.00 | — | 262.14K |

## reflection

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| beam 1.0 501b a23b | $0.25 | $1.00 | $0.05 | 1.05M |

## refuseless

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| deepseek-v4.1-flash-abliterated | $0.22 | $0.75 | $0.04 | 1.05M |
| deepseek-v4.1-flash-fast | $0.05 | $0.15 | $0.003 | 1.05M |
| glm-5.3-abliterated | $1.25 | $2.25 | $0.25 | 1.05M |
| glm-5.3-flash-abliterated | $0.25 | $0.80 | $0.15 | 1.05M |
| minimax-m3.1-flash | $0.05 | $0.25 | $0.002 | 1.05M |

## rekaai

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| reka edge | $0.10 | $0.10 | — | 16.38K |
| reka flash 3 | $0.10 | $0.20 | — | 65.54K |

## relace

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| relace apply 3 | $0.85 | $1.25 | — | 256K |
| relace search | $1.00 | $3.00 | — | 256K |

## replicate

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| claude-3.5-haiku | $1.00 | $5.00 | — | — |
| claude-3.5-sonnet | $3.75 | $18.75 | — | — |
| claude-3.7-sonnet | $3.00 | $15.00 | — | — |
| claude-4-sonnet | $3.00 | $15.00 | — | — |
| claude-4.5-haiku | $1.00 | $5.00 | — | — |
| claude-4.5-sonnet | $3.00 | $15.00 | — | — |
| deepseek-r1 | $3.75 | $10.00 | — | 65.54K |
| deepseek-v3 | $1.45 | $1.45 | — | 65.54K |
| deepseek-v3.1 | $0.67 | $2.02 | — | 163.84K |
| gemini-2.5-flash | $0.30 | $2.50 | — | — |
| gemini-3-pro | $2.00 | $12.00 | — | — |
| gpt-4.1 | $2.00 | $8.00 | — | — |
| gpt-4.1-mini | $0.40 | $1.60 | — | — |
| gpt-4.1-nano | $0.10 | $0.40 | — | — |
| gpt-4o | $2.50 | $10.00 | — | — |
| gpt-4o-mini | $0.15 | $0.60 | — | — |
| gpt-5 | $1.25 | $10.00 | — | — |
| gpt-5-mini | $0.25 | $2.00 | — | — |
| gpt-5-nano | $0.05 | $0.40 | — | — |
| gpt-oss-20b | $0.09 | $0.36 | — | — |
| gpt-oss-120b | $0.18 | $0.72 | — | — |
| granite-3.3-8b-instruct | $0.03 | $0.25 | — | — |
| grok-4 | $7.20 | $36.00 | — | — |
| llama-2-7b | $0.05 | $0.25 | — | 4.1K |
| llama-2-7b-chat | $0.05 | $0.25 | — | 4.1K |
| llama-2-13b | $0.10 | $0.50 | — | 4.1K |
| llama-2-13b-chat | $0.10 | $0.50 | — | 4.1K |
| llama-2-70b | $0.65 | $2.75 | — | 4.1K |
| llama-2-70b-chat | $0.65 | $2.75 | — | 4.1K |
| llama-3-8b | $0.05 | $0.25 | — | 8.09K |
| llama-3-8b-instruct | $0.05 | $0.25 | — | 8.09K |
| llama-3-70b | $0.65 | $2.75 | — | 8.19K |
| llama-3-70b-instruct | $0.65 | $2.75 | — | 8.19K |
| mistral-7b-instruct-v0.2 | $0.05 | $0.25 | — | 4.1K |
| mistral-7b-v0.1 | $0.05 | $0.25 | — | 4.1K |
| mixtral-8x7b-instruct-v0.1 | $0.30 | $1.00 | — | 4.1K |
| o1 | $15.00 | $60.00 | — | — |
| o1-mini | $1.10 | $4.40 | — | — |
| o4-mini | $1.00 | $4.00 | — | — |
| qwen3-235b-a22b-instruct-2507 | $0.26 | $1.06 | — | — |

## sagemaker

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| meta-textgeneration-llama-2-7b | $0.00 | $0.00 | — | 4.1K |
| meta-textgeneration-llama-2-7b-f | $0.00 | $0.00 | — | 4.1K |
| meta-textgeneration-llama-2-13b | $0.00 | $0.00 | — | 4.1K |
| meta-textgeneration-llama-2-13b-f | $0.00 | $0.00 | — | 4.1K |
| meta-textgeneration-llama-2-70b | $0.00 | $0.00 | — | 4.1K |
| meta-textgeneration-llama-2-70b-b-f | $0.00 | $0.00 | — | 4.1K |

## sail

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| deepseek-v4-flash-0731 | $0.09 | $0.18 | $0.02 | 1.05M |
| deepseek-v4-pro-0813 | $0.92 | $2.77 | $0.04 | 1.05M |
| deepseek-v4.1-flash | $0.09 | $0.30 | $0.006 | 1.05M |
| gemma-4-12b-it | $0.30 | $2.00 | $0.15 | 16.38K |
| gemma-4-31b-it | $0.40 | $0.60 | $0.20 | 256K |
| gemma-4-31b-it-nvfp4 | $0.14 | $0.40 | $0.07 | 262.14K |
| glm-5.3 | $0.98 | $3.08 | $0.18 | 1.05M |
| glm-5.3-flash | $0.11 | $0.35 | $0.02 | 1.05M |
| gpt-oss-120b | $0.06 | $0.40 | $0.03 | 131.07K |
| kimi-k2.6 | $1.00 | $4.00 | $0.20 | 262.14K |
| kimi-k3 | $2.50 | $12.50 | $0.25 | 1.05M |
| qwen3.6-35b-a3b | $0.05 | $0.40 | $0.02 | 262.14K |

## sakana

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| fugu max | $2.00 | $6.00 | $0.25 | 1M |
| fugu ultra | $5.00 | $30.00 | $0.50 | 1M |
| fugu ultra v2 | $5.00 | $30.00 | $0.50 | 1M |
| sakana namazu | $0.95 | $4.00 | $0.15 | 262.14K |

## sambanova

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| deepseek-r1 | $5.00 | $7.00 | — | 32.77K |
| deepseek-v3.1 | $3.00 | $4.50 | — | 131.07K |
| deepseek-v3.2 | $3.00 | $4.50 | — | 32.77K |
| gemma-4-31b-it | $0.38 | $1.15 | — | 131.07K |
| gpt-oss-120b | $0.22 | $0.59 | — | 131.07K |
| llama-4-maverick-17b-128e-instruct | $0.63 | $1.80 | — | 131.07K |
| meta-llama-3.3-70b-instruct | $0.60 | $1.20 | — | 131.07K |
| minimax-m2.7 | $0.60 | $2.40 | — | 196.61K |

## sao10k

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| llama 3 8b lunaris | $0.04 | $0.05 | — | 8.19K |
| llama 3.1 euryale 70b v2.2 | $0.85 | $0.85 | — | 131.07K |

## sarvam

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| sarvam-m | $0.00 | $0.00 | $0.00 | 8.19K |

## scaledown

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| classify | $0.05 | $0.00 | — | — |
| compress | $0.05 | $0.00 | — | — |
| decisions | $0.05 | $0.00 | — | — |
| extract | $0.05 | $0.00 | — | — |
| summarize | $0.05 | $0.00 | — | — |

## scaleway

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| bge-multilingual-gemma2 | $0.10 | $0.00 | — | — |
| deepseek-v4-flash-0731 | $0.40 | $0.80 | $0.08 | 256K |
| gemma-4-26b-a4b-it | $0.25 | $0.50 | — | 256K |
| glm-5.2 | $1.80 | $5.50 | — | 256K |
| gpt-oss-120b | $0.15 | $0.60 | — | 128K |
| llama-3.3-70b-instruct | $0.90 | $0.90 | — | 128K |
| mistral-medium-3.5-128b | $1.50 | $7.50 | — | 256K |
| mistral-small-3.2-24b-instruct-2506 | $0.15 | $0.35 | — | 128K |
| pixtral-12b-2409 | $0.20 | $0.20 | — | 128K |
| qwen3-235b-a22b-instruct-2507 | $0.75 | $2.25 | — | 256K |
| qwen3-coder-30b-a3b-instruct | $0.20 | $0.80 | — | 128K |
| qwen3-embedding-8b | $0.10 | $0.00 | — | — |
| qwen3.5-397b-a17b | $0.60 | $3.60 | — | 256K |
| qwen3.6-35b-a3b | $0.25 | $1.50 | — | 256K |
| whisper-large-v3 | — | $0.00 | — | — |

## scx-ai

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| deepseek-v4.1-flash | $0.15 | $0.60 | $0.01 | 1M |
| glm-5.2 | $0.61 | $1.98 | $0.22 | 1.05M |
| glm-5.3 | $0.98 | $3.08 | $0.18 | 1M |
| kimi-k3 | $2.83 | $14.13 | $0.28 | 1M |
| qwen3.8-max | $1.65 | $4.99 | $0.21 | 1M |

## snowflake

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| claude-3-5-sonnet | $3.00 | $15.00 | $0.30 | 200K |
| claude-3-7-sonnet | $3.00 | $15.00 | $0.30 | 200K |
| claude-4-opus | $5.00 | $25.00 | $0.50 | 200K |
| claude-4-sonnet | $3.00 | $15.00 | $0.30 | 200K |
| claude-haiku-4-5 | $1.00 | $5.00 | $0.10 | 200K |
| claude-sonnet-4-5 | $3.00 | $15.00 | $0.30 | 200K |
| claude-sonnet-4-6 | $3.00 | $15.00 | $0.30 | 200K |
| deepseek-r1 | $1.35 | $5.40 | — | 128K |
| llama3.1-8b | $0.24 | $0.24 | — | 128K |
| llama3.1-70b | $0.72 | $0.72 | — | 128K |
| llama3.1-405b | $1.20 | $1.20 | — | 128K |
| llama3.3-70b | $0.72 | $0.72 | — | 128K |
| llama4-maverick | $0.24 | $0.97 | — | 128K |
| mistral-large2 | $2.00 | $6.00 | — | 128K |
| openai-gpt-4.1 | $2.00 | $8.00 | $0.50 | 300K |
| openai-gpt-5 | $1.25 | $10.00 | $0.12 | 300K |
| openai-gpt-5-mini | $0.30 | $1.20 | — | 1M |
| openai-gpt-5-nano | $0.15 | $0.60 | — | 5M |
| snowflake-arctic-embed-l-v2.0 | $0.07 | $0.00 | — | 8.19K |
| snowflake-arctic-embed-m-v2.0 | $0.07 | $0.00 | — | 8.19K |
| snowflake-llama-3.3-70b | $0.72 | $0.72 | — | 128K |

## stepfun

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| step 3.5 flash | $0.10 | $0.30 | — | 262.14K |
| step 3.7 flash | $0.20 | $1.15 | $0.04 | 262.14K |
| step 5 preview | $1.00 | $2.70 | $0.10 | 1.05M |

## strands_decider

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| strands-decider-2b-hobson-v19 | $0.00 | $0.00 | — | — |

## tencent

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| deepseek-v4-flash | $0.14 | $0.28 | $0.0028 | 1M |
| deepseek-v4-pro | $1.74 | $3.48 | $0.14 | 1M |
| deepseek-v4-pro-0813 | $1.32 | $3.96 | $0.04 | 1M |
| deepseek-v4.1-flash | $0.30 | $1.20 | $0.006 | 1M |
| glm-5.2 | $1.40 | $4.40 | $0.26 | 1M |
| glm-5.3 | $1.40 | $4.40 | $0.26 | 1M |
| glm-5.3-flash | $0.15 | $0.50 | $0.03 | 1M |
| glm-5.3-flashx | $0.37 | $1.25 | $0.08 | 1M |
| hunyuan a13b instruct | $0.14 | $0.57 | — | 131.07K |
| hy3 | $0.13 | $0.53 | $0.03 | 262.14K |
| hy3 preview | $0.18 | $0.60 | $0.06 | 262.14K |
| hy4 preview | $0.83 | $2.50 | $0.04 | 1.05M |
| hy-mt2-1.8b | $0.04 | $0.18 | — | 8.19K |
| hy-mt2-7b | $0.07 | $0.30 | — | 8.19K |
| hy-mt2-30b-a3b | $0.07 | $0.30 | — | 8.19K |
| kimi-k2.7-code | $0.95 | $4.00 | $0.19 | 256K |
| kimi-k2.7-code-highspeed | $1.90 | $8.00 | $0.38 | 256K |
| kimi-k2.8-preview | $1.00 | $4.00 | $0.25 | 1M |
| kimi-k3 | $3.00 | $15.00 | $0.30 | 1M |
| minimax-m3 | $0.30 | $1.20 | $0.06 | 1M |

## tensormesh

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| deepseek-v4-flash | $0.14 | $0.28 | $0.00 | 32.77K |
| gemma-4-31b-it | $0.14 | $0.56 | $0.00 | 32.77K |
| glm-5.1-nvfp4-mtp | $1.40 | $4.40 | $0.00 | 202.75K |
| gpt-oss-20b | $0.07 | $0.28 | $0.00 | 131.07K |
| gpt-oss-120b | $0.15 | $0.60 | $0.00 | 131.07K |
| kimi-k2.6 | $0.96 | $4.00 | $0.00 | 32.77K |
| minimax-m2.5 | $0.30 | $1.20 | $0.00 | 196.61K |
| qwen3-coder-480b-a35b-instruct-fp8 | $0.45 | $1.80 | $0.00 | 262.14K |
| qwen3.5-397b-a17b-fp8 | $0.60 | $3.60 | $0.00 | 262.14K |
| qwen3.6-27b-fp8 | $0.32 | $3.20 | $0.00 | 262.14K |

## text-completion-codestral

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| codestral-2405 | $0.00 | $0.00 | — | 32K |
| codestral-latest | $0.00 | $0.00 | — | 32K |

## text-completion-inception

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| mercury-edit-2 | $0.25 | $0.75 | $0.02 | 32K |

## text-completion-openai

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| babbage-002 | $0.40 | $0.40 | — | 16.38K |
| davinci-002 | $2.00 | $2.00 | — | 16.38K |
| ft:babbage-002 | $1.60 | $1.60 | — | 16.38K |
| ft:davinci-002 | $12.00 | $12.00 | — | 16.38K |
| gpt-3.5-turbo-instruct | $1.50 | $2.00 | — | 8.19K |
| gpt-3.5-turbo-instruct-0914 | $1.50 | $2.00 | — | 8.19K |

## thedrummer

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| cydonia 24b v4.1 | $0.30 | $0.50 | $0.15 | 131.07K |
| skyfall 36b v2 | $0.55 | $0.80 | $0.25 | 32.77K |
| unslopnemo 12b | $0.40 | $0.40 | — | 1.02M |

## thinkingmachines

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| thinking machines: inkling | $1.00 | $4.05 | $0.17 | 524.29K |
| thinking machines: inkling (free) | $0.00 | $0.00 | — | 1.05M |
| thinking machines: inkling small | $0.45 | $1.20 | $0.10 | 524.29K |
| thinking machines: inkling small (free) | $0.00 | $0.00 | — | 1.05M |

## together_ai

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| beam-1.0-501b-a23b | $0.40 | $1.20 | $0.04 | 1.05M |
| bge-base-en-v1.5 | $0.008 | $0.00 | — | 512 |
| deepseek-coder-33b-instruct | $0.80 | $0.80 | — | 16.38K |
| deepseek-r1-0528 | $3.00 | $7.00 | — | 163.84K |
| deepseek-r1-distill-llama-70b | $2.00 | $2.00 | — | 131.07K |
| deepseek-r1-distill-qwen-1.5b | $0.18 | $0.18 | — | 131.07K |
| deepseek-r1-distill-qwen-14b | $1.60 | $1.60 | — | 131.07K |
| deepseek-v3 | $1.25 | $1.25 | — | 65.54K |
| deepseek-v3.1 | $0.60 | $1.70 | — | 131.07K |
| deepseek-v4-flash-0731 | $0.14 | $0.28 | $0.03 | 1.05M |
| deepseek-v4-pro-0813 | $1.32 | $3.96 | $0.13 | 1.05M |
| deepseek-v4.1-flash | $0.30 | $1.20 | $0.006 | 1.05M |
| deepseek-v4.1-flash-1017 | $0.30 | $1.20 | $0.006 | 1.05M |
| gemma-2-27b-it | $0.80 | $0.80 | — | 8.19K |
| gemma-4-31b-it | $0.39 | $0.97 | — | 262.14K |
| glm-4.5-air-fp8 | $0.20 | $1.10 | — | 131.07K |
| glm-4.6 | $0.60 | $2.20 | — | 202.75K |
| glm-4.7 | $0.45 | $2.00 | — | 202.75K |
| glm-5 | $1.00 | $3.20 | — | 202.75K |
| glm-5.1 | $1.40 | $4.40 | $0.26 | 202.75K |
| glm-5.2 | $1.40 | $4.40 | $0.26 | 1.05M |
| glm-5.3 | $1.40 | $4.40 | $0.26 | 1.05M |
| glm-5.3-flash | $0.15 | $0.50 | $0.03 | 1.05M |
| gpt-oss-20b | $0.05 | $0.20 | — | 131.07K |
| gpt-oss-120b | $0.15 | $0.60 | — | 131.07K |
| inkling | $1.00 | $4.05 | $0.17 | 524.29K |
| kimi-k2-instruct | $1.00 | $3.00 | — | — |
| kimi-k2.5-fp4 | $0.50 | $2.80 | — | 262.14K |
| kimi-k2.6 | $1.20 | $4.50 | $0.20 | 262.14K |
| kimi-k2.7-code | $0.95 | $4.00 | $0.19 | 262.14K |
| kimi-k3 | $3.00 | $15.00 | $0.30 | 1.05M |
| llama-3-8b-chat-hf | $0.20 | $0.20 | — | 8.19K |
| llama-3.1-405b-instruct | $3.50 | $3.50 | — | 4.1K |
| llama-3.1-nemotron-70b-instruct-hf | $0.88 | $0.88 | — | 32.77K |
| llama-3.2-1b-instruct | $0.06 | $0.06 | — | 131.07K |
| llama-3.2-3b-instruct | $0.06 | $0.06 | — | 131.07K |
| llama-3.3-70b-instruct-turbo | $1.04 | $1.04 | — | 131.07K |
| llama-4-scout-17b-16e-instruct | $0.18 | $0.59 | — | 1.05M |
| llama-rank-v1 | $0.10 | $0.00 | — | 8.19K |
| meta-llama-3-8b-instruct | $0.20 | $0.20 | — | 8.19K |
| meta-llama-3-70b-instruct-turbo | $0.88 | $0.88 | — | 8.19K |
| meta-llama-3.1-8b | $0.20 | $0.20 | — | 16.38K |
| meta-llama-3.1-8b-instruct-turbo | $0.18 | $0.18 | — | 131.07K |
| meta-llama-3.1-70b-instruct-turbo | $0.88 | $0.88 | — | 131.07K |
| minimax-m2.7 | $0.30 | $1.20 | $0.06 | 196.61K |
| minimax-m3 | $0.30 | $1.20 | $0.06 | 524.29K |
| minimax-m3.1-flash | $0.15 | $0.60 | $0.02 | 1.05M |
| ministral-3-14b-instruct-2512 | $0.20 | $0.20 | — | 262.14K |
| mistral-7b-instruct-v0.1 | $0.20 | $0.20 | — | 32.77K |
| mistral-7b-instruct-v0.3 | $0.20 | $0.20 | — | 32.77K |
| mistral-small-24b-instruct-2501 | $0.10 | $0.30 | — | 32.77K |
| mixtral-8x7b-instruct-v0.1 | $0.60 | $0.60 | — | 32.77K |
| muse-glimmer-30b | $0.35 | $1.50 | $0.04 | 131.07K |
| muse-spark-open-816b-a42b | $1.25 | $4.25 | $0.15 | 1.05M |
| nemotron-3-ultra-550b-a55b | $0.60 | $3.60 | $0.20 | 512.29K |
| nous-hermes-2-mixtral-8x7b-dpo | $0.60 | $0.60 | — | 32.77K |
| nvidia-nemotron-3.5-super-vl | $0.15 | $0.50 | $0.02 | 262.14K |
| nvidia-nemotron-nano-9b-v2 | $0.06 | $0.25 | — | 131.07K |
| qwen2-1.5b-instruct | $0.02 | $0.02 | — | 32.77K |
| qwen2-72b-instruct | $0.90 | $0.90 | — | 32.77K |
| qwen2-vl-72b-instruct | $1.20 | $1.20 | — | 32.77K |
| qwen2.5-7b-instruct-turbo | $0.30 | $0.30 | — | 32.77K |
| qwen2.5-14b-instruct | $0.80 | $0.80 | — | 32.77K |
| qwen2.5-72b-instruct | $1.20 | $1.20 | — | 32.77K |
| qwen2.5-72b-instruct-turbo | $1.20 | $1.20 | — | 131.07K |
| qwen2.5-coder-32b-instruct | $0.80 | $0.80 | — | 16.38K |
| qwen2.5-vl-72b-instruct | $1.95 | $8.00 | — | 32.77K |
| qwen3-coder-480b-a35b-instruct-fp8 | $2.00 | $2.00 | — | 262.14K |
| qwen3-coder-next-fp8 | $0.50 | $1.20 | — | 262.14K |
| qwen3-next-80b-a3b-instruct | $0.15 | $1.50 | — | 262.14K |
| qwen3-next-80b-a3b-thinking | $0.15 | $1.50 | — | 262.14K |
| qwen3-vl-8b-instruct | $0.18 | $0.68 | — | 262.14K |
| qwen3-vl-32b-instruct | $0.50 | $1.50 | — | 262.14K |
| qwen3.5-9b | $0.17 | $0.25 | — | 262.14K |
| qwen3.5-397b-a17b | $0.60 | $3.60 | $0.35 | 262.14K |
| qwen3.6-plus | $0.50 | $3.00 | — | 1M |
| qwen3.7-max | $1.50 | $4.50 | $0.30 | 1M |
| qwen3.7-plus | $0.32 | $1.28 | — | 1M |
| qwen3.8-2.4t-a95b | $2.00 | $6.00 | $0.25 | 1.01M |
| qwen3.8-flash | $0.15 | $0.47 | — | 1M |
| qwen-2-1.5b-instruct | $0.10 | $0.10 | — | 32.77K |
| qwq-32b | $1.20 | $1.20 | — | 131.07K |
| ternary-bonsai-27b | $0.00 | $0.00 | — | 262.14K |
| tev1-4b-experimental | $0.04 | $0.00 | — | 32.77K |
| together-ai-4.1b-8b | $0.20 | $0.20 | — | — |
| together-ai-8.1b-21b | $0.30 | $0.30 | — | 1K |
| together-ai-21.1b-41b | $0.80 | $0.80 | — | — |
| together-ai-41.1b-80b | $0.90 | $0.90 | — | — |
| together-ai-81.1b-110b | $1.80 | $1.80 | — | — |
| together-ai-embedding-151m-to-350m | $0.02 | $0.00 | — | — |
| together-ai-embedding-up-to-150m | $0.008 | $0.00 | — | — |
| together-ai-up-to-4b | $0.10 | $0.10 | — | — |
| trinity-mini | $0.04 | $0.15 | — | 128K |

## typesafe

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| jev-1.13.0 | $0.04 | $0.00 | — | 65.54K |
| jev-1.14.0 | $0.04 | $0.00 | — | 65.54K |
| jev-latest | $0.04 | $0.00 | — | 65.54K |
| jev-preview | $0.04 | $0.00 | — | 65.54K |

## unbiased

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| pareto 26.9 | $2.50 | $7.50 | $0.25 | 262.14K |
| pareto 26.10 | $0.80 | $3.20 | $0.03 | 1.05M |

## undi95

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| remm slerp 13b | $0.35 | $0.65 | — | 6.14K |

## upstage

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| solar mini 4 | $0.05 | $0.20 | $0.005 | 524.29K |
| solar pro 3 | $0.15 | $0.60 | $0.02 | 131.07K |
| solar pro 4 | $0.15 | $0.60 | $0.03 | 524.29K |

## v0

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| v0-1.0-md | $3.00 | $15.00 | — | 128K |
| v0-1.5-lg | $15.00 | $75.00 | — | 512K |
| v0-1.5-md | $3.00 | $15.00 | — | 128K |

## vercel_ai_gateway

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| claude-3-5-sonnet | $3.00 | $15.00 | $0.30 | 200K |
| claude-3-5-sonnet-20241022 | $3.00 | $15.00 | $0.30 | 200K |
| claude-3-7-sonnet | $3.00 | $15.00 | $0.30 | 200K |
| claude-3-haiku | $0.25 | $1.25 | $0.03 | 200K |
| claude-3-opus | $15.00 | $75.00 | $1.50 | 200K |
| claude-3.5-haiku | $0.80 | $4.00 | $0.08 | 200K |
| claude-4-opus | $15.00 | $75.00 | $1.50 | 200K |
| claude-4-sonnet | $3.00 | $15.00 | $0.30 | 200K |
| claude-haiku-4.5 | $1.00 | $5.00 | $0.10 | 200K |
| claude-opus-4 | $15.00 | $75.00 | $1.50 | 200K |
| claude-opus-4.1 | $15.00 | $75.00 | $1.50 | 200K |
| claude-opus-4.5 | $5.00 | $25.00 | $0.50 | 200K |
| claude-opus-4.6 | $5.00 | $25.00 | $0.50 | 200K |
| claude-sonnet-4 | $3.00 | $15.00 | $0.30 | 200K |
| claude-sonnet-4.5 | $3.00 | $15.00 | $0.30 | 1M |
| codestral | $0.30 | $0.90 | — | 256K |
| codestral-embed | $0.15 | $0.00 | — | — |
| command-a | $2.50 | $10.00 | — | 256K |
| command-r | $0.15 | $0.60 | — | 128K |
| command-r-plus | $2.50 | $10.00 | — | 128K |
| deepseek-r1 | $0.55 | $2.19 | — | 128K |
| deepseek-r1-distill-llama-70b | $0.75 | $0.99 | — | 131.07K |
| deepseek-v3 | $0.90 | $0.90 | — | 128K |
| devstral-small | $0.07 | $0.28 | — | 128K |
| embed-v4.0 | $0.12 | $0.00 | — | — |
| gemini-2.5-flash | $0.30 | $2.50 | $0.03 | 1M |
| gemini-2.5-pro | $1.25 | $10.00 | $0.12 | 1.05M |
| gemini-embedding-001 | $0.15 | $0.00 | — | — |
| gemma-2-9b | $0.20 | $0.20 | — | 8.19K |
| glm-4.5 | $0.60 | $2.20 | — | 131.07K |
| glm-4.5-air | $0.20 | $1.10 | — | 128K |
| glm-4.6 | $0.45 | $1.80 | $0.11 | 200K |
| gpt-3.5-turbo | $0.50 | $1.50 | — | 16.39K |
| gpt-3.5-turbo-instruct | $1.50 | $2.00 | — | 8.19K |
| gpt-4-turbo | $10.00 | $30.00 | — | 128K |
| gpt-4.1 | $2.00 | $8.00 | $0.50 | 1.05M |
| gpt-4.1-mini | $0.40 | $1.60 | $0.10 | 1.05M |
| gpt-4.1-nano | $0.10 | $0.40 | $0.02 | 1.05M |
| gpt-4o | $2.50 | $10.00 | $1.25 | 128K |
| gpt-4o-mini | $0.15 | $0.60 | $0.08 | 128K |
| grok-2 | $2.00 | $10.00 | — | 131.07K |
| grok-2-vision | $2.00 | $10.00 | — | 32.77K |
| grok-3 | $3.00 | $15.00 | — | 131.07K |
| grok-3-fast | $5.00 | $25.00 | — | 131.07K |
| grok-3-mini | $0.30 | $0.50 | — | 131.07K |
| grok-3-mini-fast | $0.60 | $4.00 | — | 131.07K |
| grok-4 | $3.00 | $15.00 | — | 256K |
| kimi-k2 | $0.55 | $2.20 | — | 131.07K |
| llama-3-8b | $0.05 | $0.08 | — | 8.19K |
| llama-3-70b | $0.59 | $0.79 | — | 8.19K |
| llama-3.1-8b | $0.05 | $0.08 | — | 131K |
| llama-3.1-70b | $0.72 | $0.72 | — | 128K |
| llama-3.2-1b | $0.10 | $0.10 | — | 128K |
| llama-3.2-3b | $0.15 | $0.15 | — | 128K |
| llama-3.2-11b | $0.16 | $0.16 | — | 128K |
| llama-3.2-90b | $0.72 | $0.72 | — | 128K |
| llama-3.3-70b | $0.72 | $0.72 | — | 128K |
| llama-4-maverick | $0.20 | $0.60 | — | 131.07K |
| llama-4-scout | $0.10 | $0.30 | — | 131.07K |
| magistral-medium | $2.00 | $5.00 | — | 128K |
| magistral-small | $0.50 | $1.50 | — | 128K |
| mercury-coder-small | $0.25 | $1.00 | — | 32K |
| ministral-3b | $0.04 | $0.04 | — | 128K |
| ministral-8b | $0.10 | $0.10 | — | 128K |
| mistral-embed | $0.10 | $0.00 | — | — |
| mistral-large | $2.00 | $6.00 | — | 32K |
| mistral-saba-24b | $0.79 | $0.79 | — | 32.77K |
| mistral-small | $0.10 | $0.30 | — | 32K |
| mixtral-8x22b-instruct | $1.20 | $1.20 | — | 65.54K |
| morph-v3-fast | $0.80 | $1.20 | — | 32.77K |
| morph-v3-large | $0.90 | $1.90 | — | 32.77K |
| nova-lite | $0.06 | $0.24 | — | 300K |
| nova-micro | $0.04 | $0.14 | — | 128K |
| nova-pro | $0.80 | $3.20 | — | 300K |
| o1 | $15.00 | $60.00 | $7.50 | 200K |
| o3 | $2.00 | $8.00 | $0.50 | 200K |
| o3-mini | $1.10 | $4.40 | $0.55 | 200K |
| o4-mini | $1.10 | $4.40 | $0.28 | 200K |
| pixtral-12b | $0.15 | $0.15 | — | 128K |
| pixtral-large | $2.00 | $6.00 | — | 128K |
| qwen3-coder | $0.40 | $1.60 | — | 262.14K |
| qwen-3-14b | $0.08 | $0.24 | — | 40.96K |
| qwen-3-30b | $0.10 | $0.30 | — | 40.96K |
| qwen-3-32b | $0.10 | $0.30 | — | 40.96K |
| qwen-3-235b | $0.20 | $0.60 | — | 40.96K |
| sonar | $1.00 | $1.00 | — | 127K |
| sonar-pro | $3.00 | $15.00 | — | 200K |
| sonar-reasoning | $1.00 | $5.00 | — | 127K |
| sonar-reasoning-pro | $2.00 | $8.00 | — | 127K |
| text-embedding-3-large | $0.13 | $0.00 | — | — |
| text-embedding-3-small | $0.02 | $0.00 | — | — |
| text-embedding-005 | $0.02 | $0.00 | — | — |
| text-embedding-ada-002 | $0.10 | $0.00 | — | — |
| text-multilingual-embedding-002 | $0.02 | $0.00 | — | — |
| titan-embed-text-v2 | $0.02 | $0.00 | — | — |
| v0-1.0-md | $3.00 | $15.00 | — | 128K |
| v0-1.5-md | $3.00 | $15.00 | — | 128K |

## vertex_ai

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| deepseek-ocr-maas | $0.30 | $1.20 | — | — |
| gemini-2.0-flash | $0.15 | $0.60 | — | — |
| gemini-2.0-flash-lite | $0.08 | $0.30 | — | — |
| gemini-2.5-flash-native-audio | $0.50 | $2.00 | — | — |
| gemini-2.5-flash-preview-tts | $0.50 | $10.00 | — | — |
| gemini-2.5-flash-tts | $0.50 | $10.00 | — | — |
| gemini-2.5-pro-tts | $1.00 | $20.00 | — | — |
| gemini-3-flash-preview | $0.50 | $3.00 | $0.05 | 1.05M |
| gemini-3-pro-preview | $2.00 | $12.00 | $0.20 | 1.05M |
| gemini-3.1-flash-tts-preview | $1.00 | $20.00 | — | — |
| gemini-3.1-pro-preview | $2.00 | $12.00 | $0.20 | 1.05M |
| gemini-3.1-pro-preview-customtools | $2.00 | $12.00 | $0.20 | 1.05M |
| gemini-3.5-flash | $1.50 | $9.00 | $0.15 | 1.05M |
| gemini-3.5-live-translate-preview | $3.50 | $21.00 | — | — |
| gemini-3.5-transcribe | — | $12.00 | — | — |
| gemini-3.5-transcribe-live | — | $21.00 | — | — |
| gemini-3.5-transcribe-live-preview | $3.50 | $21.00 | — | — |
| gemini-3.5-transcribe-preview | $2.00 | $12.00 | — | — |
| gemini-3.6-flash | $0.75 | $3.75 | $0.08 | 1.05M |
| gemini-3.7-flash | $0.75 | $3.75 | $0.08 | 1.05M |
| gemini-3.8-flash | $0.75 | $3.75 | $0.08 | 1.05M |
| gemini-3.8-flash-cyber | $1.50 | $7.50 | $0.15 | 1.05M |
| gemini-3.8-flash-lite-tts | $0.50 | $6.00 | — | 8.19K |
| gemini-3.8-flash-tts | $0.50 | $9.00 | — | 8.19K |
| gemini-3.8-live | $0.75 | $4.50 | — | 131.07K |
| gemini-4-argon | $2.00 | $10.00 | $0.10 | 1.05M |
| gemini-4-argon-cyber-permissive | $4.00 | $20.00 | $0.20 | 1.05M |
| gemini-embedding-2 | $0.20 | $0.00 | — | 8.19K |
| gemini-embedding-2-preview | $0.20 | $0.00 | — | 8.19K |
| gemini-omni-1.1-flash | $1.50 | $9.00 | — | — |
| gemini-omni-1.1-flash-preview | $1.50 | $9.00 | — | 57.92K |
| gemini-robotics-er-2-preview | $1.00 | $5.00 | $0.10 | 131.07K |
| gemma-4-26b-a4b-it | $0.15 | $0.60 | $0.02 | — |
| grok-4.1-fast-non-reasoning | $0.20 | $0.50 | $0.05 | 128K |
| grok-4.1-fast-reasoning | $0.20 | $0.50 | $0.05 | 128K |
| grok-4.3 | $1.25 | $2.50 | $0.20 | 200K |
| grok-4.6 | $2.00 | $6.00 | $0.50 | 524.29K |
| grok-4.7 | $2.00 | $6.00 | $0.50 | 524.29K |
| grok-4.20-non-reasoning | $1.25 | $2.50 | $0.20 | 2M |
| grok-4.20-reasoning | $1.25 | $2.50 | $0.20 | 2M |
| lyria-3-clip-preview | $0.00 | $0.00 | — | 131.07K |
| lyria-3-pro-preview | $0.00 | $0.00 | — | 131.07K |
| semantic-ranker-default | $0.00 | $0.00 | — | — |
| semantic-ranker-default-002 | $0.00 | $0.00 | — | — |
| semantic-ranker-default-003 | $0.00 | $0.00 | — | — |
| semantic-ranker-default-004 | $0.00 | $0.00 | — | — |
| semantic-ranker-default@latest | $0.00 | $0.00 | — | — |
| semantic-ranker-fast | $0.00 | $0.00 | — | — |
| semantic-ranker-fast-004 | $0.00 | $0.00 | — | — |
| semantic-ranker-fast@latest | $0.00 | $0.00 | — | — |

## vertex_ai-ai21_models

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| jamba-1.5 | $0.20 | $0.40 | — | 256K |
| jamba-1.5-large | $2.00 | $8.00 | — | 256K |
| jamba-1.5-large@001 | $2.00 | $8.00 | — | 256K |
| jamba-1.5-mini | $0.20 | $0.40 | — | 256K |
| jamba-1.5-mini@001 | $0.20 | $0.40 | — | 256K |

## vertex_ai-anthropic_models

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| claude-3-5-haiku | $1.00 | $5.00 | — | 200K |
| claude-3-5-haiku@20241022 | $1.00 | $5.00 | — | 200K |
| claude-3-5-sonnet | $3.00 | $15.00 | — | 200K |
| claude-3-5-sonnet@20240620 | $3.00 | $15.00 | — | 200K |
| claude-3-haiku | $0.25 | $1.25 | — | 200K |
| claude-3-haiku@20240307 | $0.25 | $1.25 | — | 200K |
| claude-3-opus | $15.00 | $75.00 | — | 200K |
| claude-3-opus@20240229 | $15.00 | $75.00 | — | 200K |
| claude-3-sonnet | $3.00 | $15.00 | — | 200K |
| claude-3-sonnet@20240229 | $3.00 | $15.00 | — | 200K |
| claude-fable-5 | $10.00 | $50.00 | $1.00 | 1M |
| claude-fable-5-1 | $10.00 | $50.00 | $0.25 | 1M |
| claude-fable-5-1@default | $10.00 | $50.00 | $0.25 | 1M |
| claude-fable-5@default | $10.00 | $50.00 | $1.00 | 1M |
| claude-haiku-4-5 | $1.00 | $5.00 | $0.10 | 200K |
| claude-haiku-4-5@20251001 | $1.00 | $5.00 | $0.10 | 200K |
| claude-haiku-5-5 | $0.10 | $0.50 | $0.01 | 1M |
| claude-haiku-5-5@default | $0.10 | $0.50 | $0.01 | 1M |
| claude-opus-4-5 | $5.00 | $25.00 | $0.50 | 200K |
| claude-opus-4-5@20251101 | $5.00 | $25.00 | $0.50 | 200K |
| claude-opus-4-6 | $5.00 | $25.00 | $0.50 | 1M |
| claude-opus-4-6@default | $5.00 | $25.00 | $0.50 | 1M |
| claude-opus-4-7 | $5.00 | $25.00 | $0.50 | 1M |
| claude-opus-4-7@default | $5.00 | $25.00 | $0.50 | 1M |
| claude-opus-4-8 | $5.00 | $25.00 | $0.50 | 1M |
| claude-opus-4-8@default | $5.00 | $25.00 | $0.50 | 1M |
| claude-opus-5 | $5.00 | $25.00 | $0.50 | 1M |
| claude-opus-5-5 | $4.00 | $20.00 | $0.20 | 1M |
| claude-opus-5-5@default | $4.00 | $20.00 | $0.20 | 1M |
| claude-opus-5@default | $5.00 | $25.00 | $0.50 | 1M |
| claude-sonnet-4-5 | $3.00 | $15.00 | $0.30 | 200K |
| claude-sonnet-4-5@20250929 | $3.00 | $15.00 | $0.30 | 200K |
| claude-sonnet-4-6 | $3.00 | $15.00 | $0.30 | 1M |
| claude-sonnet-4-6@default | $3.00 | $15.00 | $0.30 | 1M |
| claude-sonnet-5 | $2.00 | $10.00 | $0.20 | 1M |
| claude-sonnet-5-5 | $2.00 | $10.00 | $0.10 | 1M |
| claude-sonnet-5-5@default | $2.00 | $10.00 | $0.10 | 1M |
| claude-sonnet-5@default | $2.00 | $10.00 | $0.20 | 1M |

## vertex_ai-deepseek_models

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| deepseek-r1-0528-maas | $1.35 | $5.40 | — | 65.34K |
| deepseek-v3.1-maas | $0.60 | $1.70 | $0.06 | 163.84K |
| deepseek-v3.2-maas | $0.56 | $1.68 | $0.06 | 163.84K |
| deepseek-v4.1-flash-maas | $0.30 | $1.20 | $0.03 | 1.05M |

## vertex_ai-embedding-models

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| gemini-embedding-001 | $0.15 | $0.00 | — | 2.05K |
| gemini-embedding-2 | $0.20 | $0.00 | — | 8.19K |
| gemini-embedding-2-preview | $0.20 | $0.00 | — | 8.19K |
| multimodalembedding | $0.80 | $0.00 | — | 2.05K |
| multimodalembedding@001 | $0.80 | $0.00 | — | 2.05K |
| text-embedding-004 | $0.10 | $0.00 | — | 2.05K |
| text-embedding-005 | $0.10 | $0.00 | — | 2.05K |
| text-embedding-large-exp-03-07 | $0.10 | $0.00 | — | 8.19K |
| text-embedding-preview-0409 | $0.00625 | $0.00 | — | 3.07K |
| text-multilingual-embedding-002 | $0.10 | $0.00 | — | 2.05K |

## vertex_ai-language-models

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| deep-research-pro-preview-12-2025 | $2.00 | $12.00 | $0.20 | 65.54K |
| gemini-2.5-computer-use-preview-10-2025 | $1.25 | $10.00 | — | 128K |
| gemini-2.5-flash | $0.30 | $2.50 | $0.03 | 1.05M |
| gemini-2.5-flash-image | $0.30 | $2.50 | — | 32.77K |
| gemini-2.5-flash-lite | $0.10 | $0.40 | $0.01 | 1.05M |
| gemini-2.5-flash-lite-preview-09-2025 | $0.10 | $0.40 | $0.01 | 1.05M |
| gemini-2.5-flash-preview-09-2025 | $0.30 | $2.50 | $0.03 | 1.05M |
| gemini-2.5-pro | $1.25 | $10.00 | $0.12 | 1.05M |
| gemini-2.5-pro-preview-tts | $1.00 | $20.00 | $0.12 | 1.05M |
| gemini-3-flash-preview | $0.50 | $3.00 | $0.05 | 1.05M |
| gemini-3-pro-image | $2.00 | $12.00 | $0.20 | 65.54K |
| gemini-3-pro-image-preview | $2.00 | $12.00 | $0.20 | 65.54K |
| gemini-3.1-flash-image | $0.50 | $3.00 | $0.05 | 65.54K |
| gemini-3.1-flash-image-preview | $0.50 | $3.00 | $0.05 | 65.54K |
| gemini-3.1-flash-lite | $0.25 | $1.50 | $0.02 | 1.05M |
| gemini-3.1-flash-lite-image | $0.25 | $1.50 | $0.02 | 65.54K |
| gemini-3.1-flash-lite-preview | $0.25 | $1.50 | $0.02 | 1.05M |
| gemini-3.1-pro-preview | $2.00 | $12.00 | $0.20 | 1.05M |
| gemini-3.1-pro-preview-customtools | $2.00 | $12.00 | $0.20 | 1.05M |
| gemini-3.5-flash | $1.50 | $9.00 | $0.15 | 1.05M |
| gemini-3.5-flash-lite | $0.30 | $2.50 | $0.03 | 1.05M |
| gemini-3.6-flash | $0.75 | $3.75 | $0.08 | 1.05M |
| gemini-3.7-flash | $0.75 | $3.75 | $0.08 | 1.05M |
| gemini-3.8-flash | $0.75 | $3.75 | $0.08 | 1.05M |
| gemini-3.8-flash-cyber | $1.50 | $7.50 | $0.15 | 1.05M |
| gemini-flash-experimental | $0.00 | $0.00 | — | 1M |
| gemini-live-2.5-flash-native-audio | $0.50 | $2.00 | — | 131.07K |
| gemini-live-2.5-flash-preview-native-audio-09-2025 | $0.50 | $2.00 | — | 1.05M |
| gemini-nano-banana-2.1 | $1.50 | $7.50 | $0.15 | 131.07K |
| gemini-omni-flash-preview | $1.50 | $9.00 | — | 1.05M |
| gemini-robotics-er-1.5-preview | $0.30 | $2.50 | $0.00 | 1.05M |
| gemini-robotics-er-2-preview | $1.00 | $5.00 | $0.10 | 131.07K |

## vertex_ai-llama_models

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| llama3-8b-instruct-maas | $0.00 | $0.00 | — | 32K |
| llama3-70b-instruct-maas | $0.00 | $0.00 | — | 32K |
| llama3-405b-instruct-maas | $0.00 | $0.00 | — | 32K |
| llama-3.1-8b-instruct-maas | $0.00 | $0.00 | — | 128K |
| llama-3.1-70b-instruct-maas | $0.00 | $0.00 | — | 128K |
| llama-3.1-405b-instruct-maas | $5.00 | $16.00 | — | 128K |
| llama-3.2-90b-vision-instruct-maas | $0.00 | $0.00 | — | 128K |
| llama-3.3-70b-instruct-maas | $0.72 | $0.72 | — | 128K |
| llama-4-maverick-17b-16e-instruct-maas | $0.35 | $1.15 | — | 1M |
| llama-4-maverick-17b-128e-instruct-maas | $0.35 | $1.15 | — | 1M |
| llama-4-scout-17b-16e-instruct-maas | $0.25 | $0.70 | — | 10M |
| llama-4-scout-17b-128e-instruct-maas | $0.25 | $0.70 | — | 10M |

## vertex_ai-minimax_models

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| minimax-m2-maas | $0.30 | $1.20 | $0.03 | 196.61K |

## vertex_ai-mistral_models

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| codestral-2 | $0.30 | $0.90 | — | 128K |
| codestral-2@001 | $0.30 | $0.90 | — | 128K |
| codestral-2501 | $0.20 | $0.60 | — | 128K |
| codestral@2405 | $0.20 | $0.60 | — | 128K |
| codestral@latest | $0.20 | $0.60 | — | 128K |
| mistral-large-2411 | $2.00 | $6.00 | — | 128K |
| mistral-large@2407 | $2.00 | $6.00 | — | 128K |
| mistral-large@2411-001 | $2.00 | $6.00 | — | 128K |
| mistral-large@latest | $2.00 | $6.00 | — | 128K |
| mistral-medium-3 | $0.40 | $2.00 | — | 128K |
| mistral-medium-3@001 | $0.40 | $2.00 | — | 128K |
| mistral-nemo@2407 | $3.00 | $3.00 | — | 128K |
| mistral-nemo@latest | $0.15 | $0.15 | — | 128K |
| mistral-small-2503 | $0.10 | $0.30 | — | 128K |
| mistral-small-2503@001 | $0.10 | $0.30 | — | 32K |

## vertex_ai-moonshot_models

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| kimi-k2-thinking-maas | $0.60 | $2.50 | $0.06 | 256K |

## vertex_ai-openai_models

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| gemma-4-26b-a4b-it-maas | $0.15 | $0.60 | $0.02 | 262.14K |
| gpt-oss-20b-maas | $0.07 | $0.25 | $0.007 | 131.07K |
| gpt-oss-120b-maas | $0.09 | $0.36 | — | 131.07K |

## vertex_ai-qwen_models

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| qwen3-235b-a22b-instruct-2507-maas | $0.22 | $0.88 | — | 262.14K |
| qwen3-coder-480b-a35b-instruct-maas | $0.22 | $1.80 | $0.02 | 262.14K |
| qwen3-next-80b-a3b-instruct-maas | $0.15 | $1.20 | — | 262.14K |
| qwen3-next-80b-a3b-thinking-maas | $0.15 | $1.20 | — | 262.14K |

## vertex_ai-text-models

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| text-unicorn | $10.00 | $28.00 | — | 8.19K |
| text-unicorn@001 | $10.00 | $28.00 | — | 8.19K |

## vertex_ai-zai_models

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| glm-4.7-maas | $0.60 | $2.20 | $0.06 | 200K |
| glm-5-maas | $1.00 | $3.20 | $0.10 | 200K |
| glm-5.2-maas | $1.40 | $4.40 | $0.14 | 1M |

## volcengine

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| deepseek-v3-2-251201 | $0.00 | $0.00 | — | 98.3K |
| doubao-embedding | $0.00 | $0.00 | — | 4.1K |
| doubao-embedding-large | $0.00 | $0.00 | — | 4.1K |
| doubao-embedding-large-text-240915 | $0.00 | $0.00 | — | 4.1K |
| doubao-embedding-large-text-250515 | $0.00 | $0.00 | — | 4.1K |
| doubao-embedding-text-240715 | $0.00 | $0.00 | — | 4.1K |
| doubao-seed-2-1-lite-260915 | $0.12 | $0.39 | $0.02 | 1.02M |
| doubao-seed-2-1-pro-260628 | $0.86 | $4.31 | $0.17 | 256K |
| doubao-seed-2-1-pro-260915 | $0.86 | $4.31 | $0.17 | 1.02M |
| doubao-seed-2-1-turbo-260628 | $0.43 | $2.16 | $0.09 | 256K |
| glm-4-7-251222 | $0.00 | $0.00 | — | 204.8K |
| kimi-k2-thinking-251104 | $0.00 | $0.00 | — | 229.38K |

## voyage

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| rerank-1 | $0.05 | $0.00 | — | 8K |
| rerank-2 | $0.05 | $0.00 | — | 16K |
| rerank-2-lite | $0.02 | $0.00 | — | 8K |
| rerank-2.5 | $0.05 | $0.00 | — | 32K |
| rerank-2.5-lite | $0.02 | $0.00 | — | 32K |
| rerank-3 | $0.05 | $0.00 | — | 32K |
| rerank-3-lite | $0.02 | $0.00 | — | 32K |
| rerank-lite-1 | $0.02 | $0.00 | — | 4K |
| voyage-2 | $0.10 | $0.00 | — | 4K |
| voyage-3 | $0.06 | $0.00 | — | 32K |
| voyage-3-large | $0.18 | $0.00 | — | 32K |
| voyage-3-lite | $0.02 | $0.00 | — | 32K |
| voyage-3.5 | $0.06 | $0.00 | — | 32K |
| voyage-3.5-lite | $0.02 | $0.00 | — | 32K |
| voyage-4 | $0.06 | $0.00 | — | 32K |
| voyage-4-large | $0.12 | $0.00 | — | 32K |
| voyage-4-lite | $0.02 | $0.00 | — | 32K |
| voyage-code-2 | $0.12 | $0.00 | — | 16K |
| voyage-code-3 | $0.18 | $0.00 | — | 32K |
| voyage-code-4 | $0.12 | $0.00 | — | 32K |
| voyage-context-3 | $0.18 | $0.00 | — | 120K |
| voyage-context-4 | $0.12 | $0.00 | — | 120K |
| voyage-finance-2 | $0.12 | $0.00 | — | 32K |
| voyage-large-2 | $0.12 | $0.00 | — | 16K |
| voyage-large-2-instruct | $0.12 | $0.00 | — | 16K |
| voyage-law-2 | $0.12 | $0.00 | — | 16K |
| voyage-lite-01 | $0.10 | $0.00 | — | 4.1K |
| voyage-lite-02-instruct | $0.10 | $0.00 | — | 4K |
| voyage-multilingual-2 | $0.12 | $0.00 | — | 32K |
| voyage-multimodal-3 | $0.12 | $0.00 | — | 32K |
| voyage-multimodal-3.5 | $0.12 | $0.00 | — | 32K |

## wandb

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| beam-1.0-501b-a23b | $1.00 | $3.00 | $0.10 | 1.05M |
| deepseek-v3.1 | $0.55 | $1.65 | — | 161K |
| deepseek-v4-flash | $0.14 | $0.28 | $0.07 | 1.05M |
| deepseek-v4-flash-0731 | $0.13 | $0.28 | $0.07 | 262K |
| deepseek-v4-pro | $1.15 | $2.55 | $0.20 | 1.05M |
| deepseek-v4-pro-0813 | $1.31 | $3.96 | $0.04 | 1.05M |
| deepseek-v4.1-flash | $0.20 | $0.65 | $0.03 | 1.05M |
| gemma-4-26b-a4b-it | $0.10 | $0.30 | $0.05 | 262K |
| gemma-4-31b-it | $0.10 | $0.34 | — | 262K |
| glm-5.2 | $0.76 | $2.42 | $0.14 | 1.05M |
| glm-5.3 | $1.20 | $4.00 | $0.19 | 1.05M |
| glm-5.3-flash | $0.15 | $0.50 | $0.05 | 1.05M |
| gpt-oss-20b | $0.03 | $0.13 | — | 131K |
| gpt-oss-120b | $0.03 | $0.17 | — | 131K |
| granite-4.1-8b | $0.05 | $0.10 | — | 131K |
| granite-4.2-8b | $0.10 | $0.15 | $0.05 | 131K |
| kimi-k2.5 | $0.60 | $3.00 | $0.10 | 262.14K |
| kimi-k2.6 | $0.65 | $3.41 | $0.15 | 262K |
| kimi-k2.7-code | $0.71 | $3.50 | $0.15 | 262K |
| llama-3.1-8b-instruct | $0.22 | $0.22 | — | 131K |
| llama-3.1-70b-instruct | $0.80 | $0.80 | — | 131K |
| llama-3.3-70b-instruct | $0.71 | $0.71 | — | 128K |
| mellum2-12b-a2.5b-instruct | $0.05 | $0.10 | — | 131K |
| minimax-m3 | $0.23 | $0.96 | $0.05 | 262K |
| nvidia-nemotron-3-ultra-550b-a55b | $0.50 | $2.15 | $0.10 | 262K |
| nvidia-nemotron-3.5-lightning-30b-a3b | $0.07 | $0.20 | $0.04 | 262K |
| nvidia-nemotron-3.5-super-vl-120b-a12b | $0.15 | $0.75 | $0.02 | 1.05M |
| qwen3-14b-instruct | $0.05 | $0.22 | — | 32.8K |
| qwen3-30b-a3b-instruct-2507 | $0.10 | $0.30 | — | 262K |
| qwen3.5-35b-a3b | $0.25 | $1.25 | — | 262K |
| qwen3.6-27b | $0.60 | $3.60 | $0.12 | 262K |
| qwen3.6-35b-a3b | $0.25 | $1.25 | — | 262K |
| qwen3.8-27b | $0.40 | $3.00 | $0.15 | 262K |

## watsonx

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| allam-1-13b-instruct | $1.80 | $1.80 | — | 8.19K |
| flan-t5-xl-3b | $0.60 | $0.60 | — | 8.19K |
| gpt-oss-120b | $0.16 | $0.64 | — | 131.07K |
| granite-3-3-8b-instruct | $0.20 | $0.20 | — | 8.19K |
| granite-3-8b-instruct | $0.20 | $0.20 | — | 8.19K |
| granite-4-h-small | $0.06 | $0.26 | — | 131.07K |
| granite-13b-chat-v2 | $0.60 | $0.60 | — | 8.19K |
| granite-13b-instruct-v2 | $0.60 | $0.60 | — | 8.19K |
| granite-guardian-3-2-2b | $0.10 | $0.10 | — | 8.19K |
| granite-guardian-3-3-8b | $0.20 | $0.20 | — | 8.19K |
| granite-ttm-512-96-r2 | $0.38 | $0.38 | — | 512 |
| granite-ttm-1024-96-r2 | $0.38 | $0.38 | — | 512 |
| granite-ttm-1536-96-r2 | $0.38 | $0.38 | — | 512 |
| granite-vision-3-2-2b | $0.10 | $0.10 | — | 8.19K |
| jais-13b-chat | $500.00 | $2,000.00 | — | 8.19K |
| llama-3-2-1b-instruct | $0.10 | $0.10 | — | 128K |
| llama-3-2-3b-instruct | $0.15 | $0.15 | — | 128K |
| llama-3-2-11b-vision-instruct | $0.35 | $0.35 | — | 128K |
| llama-3-2-90b-vision-instruct | $2.00 | $2.00 | — | 128K |
| llama-3-3-70b-instruct | $0.75 | $0.75 | — | 131.07K |
| llama-4-maverick-17b | $0.37 | $1.48 | — | 131.07K |
| llama-4-maverick-17b-128e-instruct-fp8 | $0.37 | $1.48 | — | 131.07K |
| llama-guard-3-11b-vision | $0.35 | $0.35 | — | 128K |
| mistral-large | $3.00 | $10.00 | — | 131.07K |
| mistral-medium-2505 | $3.00 | $10.00 | — | 128K |
| mistral-small-3-1-24b-instruct-2503 | $0.11 | $0.32 | — | 131.07K |
| mistral-small-2503 | $0.10 | $0.30 | — | 32K |
| mt0-xxl | $1.91 | $1.91 | — | 4.1K |
| mt0-xxl-13b | $1.91 | $1.91 | — | 4.1K |
| pixtral-12b-2409 | $0.35 | $0.35 | — | 128K |

## writer

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| palmyra x5 | $0.60 | $6.00 | — | 1.04M |

## xai

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| grok latest | $2.00 | $6.00 | $0.50 | 500K |
| grok-4.3 | $1.25 | $2.50 | $0.20 | 1M |
| grok-4.3-latest | $1.25 | $2.50 | $0.20 | 1M |
| grok-4.5 | $2.00 | $6.00 | $0.30 | 500K |
| grok-4.5-latest | $2.00 | $6.00 | $0.30 | 500K |
| grok-4.6 | $2.00 | $6.00 | $0.50 | 500K |
| grok-4.7 | $2.00 | $6.00 | $0.50 | 500K |
| grok-4.20 | $1.25 | $2.50 | $0.20 | 1M |
| grok-4.20-0309 | $1.25 | $2.50 | $0.20 | 1M |
| grok-4.20-0309-non-reasoning | $1.25 | $2.50 | $0.20 | 1M |
| grok-4.20-0309-reasoning | $1.25 | $2.50 | $0.20 | 1M |
| grok-4.20-beta | $1.25 | $2.50 | $0.20 | 1M |
| grok-4.20-beta-0309 | $1.25 | $2.50 | $0.20 | 1M |
| grok-4.20-beta-0309-non-reasoning | $1.25 | $2.50 | $0.20 | 1M |
| grok-4.20-beta-0309-reasoning | $1.25 | $2.50 | $0.20 | 1M |
| grok-4.20-beta-latest | $1.25 | $2.50 | $0.20 | 1M |
| grok-4.20-beta-latest-non-reasoning | $1.25 | $2.50 | $0.20 | 1M |
| grok-4.20-beta-latest-reasoning | $1.25 | $2.50 | $0.20 | 1M |
| grok-4.20-beta-non-reasoning | $1.25 | $2.50 | $0.20 | 1M |
| grok-4.20-beta-reasoning | $1.25 | $2.50 | $0.20 | 1M |
| grok-4.20-experimental-beta-0304 | $1.25 | $2.50 | $0.20 | 1M |
| grok-4.20-experimental-beta-0304-non-reasoning | $1.25 | $2.50 | $0.20 | 1M |
| grok-4.20-experimental-beta-0304-reasoning | $1.25 | $2.50 | $0.20 | 1M |
| grok-4.20-experimental-beta-latest | $1.25 | $2.50 | $0.20 | 1M |
| grok-4.20-experimental-beta-non-reasoning-latest | $1.25 | $2.50 | $0.20 | 1M |
| grok-4.20-experimental-beta-reasoning-latest | $1.25 | $2.50 | $0.20 | 1M |
| grok-4.20-multi-agent | $1.25 | $2.50 | $0.20 | 1M |
| grok-4.20-multi-agent-0309 | $1.25 | $2.50 | $0.20 | 1M |
| grok-4.20-multi-agent-beta-0309 | $1.25 | $2.50 | $0.20 | 1M |
| grok-4.20-multi-agent-beta-latest | $1.25 | $2.50 | $0.20 | 1M |
| grok-4.20-multi-agent-experimental-beta-0304 | $1.25 | $2.50 | $0.20 | 1M |
| grok-4.20-multi-agent-experimental-beta-latest | $1.25 | $2.50 | $0.20 | 1M |
| grok-4.20-multi-agent-latest | $1.25 | $2.50 | $0.20 | 1M |
| grok-4.20-non-reasoning | $1.25 | $2.50 | $0.20 | 1M |
| grok-4.20-non-reasoning-gv2 | $1.25 | $2.50 | $0.20 | 1M |
| grok-4.20-non-reasoning-latest | $1.25 | $2.50 | $0.20 | 1M |
| grok-4.20-reasoning | $1.25 | $2.50 | $0.20 | 1M |
| grok-4.20-reasoning-gv2 | $1.25 | $2.50 | $0.20 | 1M |
| grok-4.20-reasoning-latest | $1.25 | $2.50 | $0.20 | 1M |
| grok-build-0.1 | $1.00 | $2.00 | $0.20 | 256K |
| grok-build-latest | $2.00 | $6.00 | $0.30 | 500K |
| grok-code-fast | $1.00 | $2.00 | $0.20 | 256K |
| grok-code-fast-1 | $1.00 | $2.00 | $0.20 | 256K |
| grok-code-fast-1-0825 | $1.00 | $2.00 | $0.20 | 256K |
| spacexai: grok 4.3 | $1.25 | $2.50 | $0.20 | 1M |
| spacexai: grok 4.3 (batch) | $1.00 | $2.00 | $0.16 | 1M |
| spacexai: grok 4.5 | $2.00 | $6.00 | $0.30 | 500K |
| spacexai: grok 4.6 | $2.00 | $6.00 | $0.50 | 500K |
| spacexai: grok 4.7 | $2.00 | $6.00 | $0.50 | 500K |
| spacexai: grok 4.20 | $1.25 | $2.50 | $0.20 | 2M |
| spacexai: grok 4.20 multi-agent | $1.25 | $2.50 | $0.20 | 2M |
| spacexai: grok build 0.1 | $1.00 | $2.00 | $0.20 | 256K |

## xiaomi

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| mimo-v2.5 | $0.40 | $2.00 | $0.08 | 1.05M |
| mimo-v2.5-pro | $0.48 | $1.80 | $0.10 | 1.05M |
| mimo-v2.6-flash | $0.14 | $0.28 | $0.0028 | 1.05M |
| mimo-v2.6-pro | $0.44 | $0.87 | $0.0036 | 1.05M |
| mimo-v2.6-pro-ultraspeed | $4.35 | $8.70 | $0.04 | 1.05M |

## xiaomi_mimo

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| mimo-v2.6-flash | $0.14 | $0.28 | $0.0028 | 1.05M |
| mimo-v2.6-pro | $0.44 | $0.87 | $0.0036 | 1.05M |

## xingchen-agi

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| xingchen: xing4.0 29b a4b (free) | $0.00 | $0.00 | — | 262.14K |

## zai

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| glm-4-32b-0414-128k | $0.10 | $0.10 | — | 128K |
| glm-4.5 | $0.60 | $2.20 | — | 128K |
| glm-4.5-air | $0.20 | $1.10 | — | 128K |
| glm-4.5-airx | $1.10 | $4.50 | — | 128K |
| glm-4.5-flash | $0.00 | $0.00 | — | 128K |
| glm-4.5-x | $2.20 | $8.90 | — | 128K |
| glm-4.5v | $0.60 | $1.80 | — | 128K |
| glm-4.6 | $0.60 | $2.20 | $0.11 | 200K |
| glm-4.7 | $0.60 | $2.20 | $0.11 | 200K |
| glm-4.7-flash | $0.00 | $0.00 | $0.00 | 200K |
| glm-5 | $1.00 | $3.20 | $0.20 | 200K |
| glm-5-code | $1.20 | $5.00 | $0.30 | 200K |
| glm-5.1 | $1.40 | $4.40 | $0.26 | 200K |
| glm-5.2 | $1.40 | $4.40 | $0.26 | 1M |
| glm-5.3 | $1.40 | $4.40 | $0.26 | 1M |
| glm-5.3-flash | $0.15 | $0.50 | $0.03 | 1.05M |
| z.ai: glm 4.5 | $0.60 | $2.20 | $0.11 | 131.07K |
| z.ai: glm 4.5 air | $0.13 | $0.85 | $0.02 | 131.07K |
| z.ai: glm 4.5v | $0.60 | $1.80 | $0.11 | 65.54K |
| z.ai: glm 4.6 | $0.55 | $2.20 | $0.11 | 204.8K |
| z.ai: glm 4.6v | $0.30 | $0.90 | $0.06 | 131.07K |
| z.ai: glm 4.7 | $0.54 | $1.98 | $0.10 | 204.8K |
| z.ai: glm 4.7 flash | $0.06 | $0.40 | — | 200K |
| z.ai: glm 5 | $1.00 | $3.20 | $0.20 | 204.8K |
| z.ai: glm 5 turbo | $1.20 | $4.00 | $0.24 | 202.75K |
| z.ai: glm 5.1 | $0.97 | $3.04 | $0.18 | 204.8K |
| z.ai: glm 5.2 | $0.03 | $7.00 | $0.03 | 1.05M |
| z.ai: glm 5.3 | $0.07 | $1.40 | $0.07 | 1.05M |
| z.ai: glm 5.3 (batch) | $0.45 | $2.00 | $0.10 | 1.05M |
| z.ai: glm 5.3 flash | $0.15 | $0.50 | $0.03 | 1.05M |
| z.ai: glm 5.3 flash (batch) | $0.05 | $0.18 | $0.01 | 1.05M |
| z.ai: glm 5.3 flashx | $0.37 | $1.25 | $0.09 | 1.05M |
| z.ai: glm 5.3 prime | $2.80 | $8.80 | $0.56 | 1M |
| z.ai: glm 5v turbo | $1.20 | $4.00 | $0.24 | 202.75K |
| z.ai: glm flash latest | $0.02 | $0.10 | $0.02 | 1.05M |
| z.ai: glm latest | $0.07 | $1.40 | $0.07 | 1.05M |

## ~unbiased

| Model | Input | Output | Cached input | Context |
| --- | ---: | ---: | ---: | ---: |
| pareto latest | $0.80 | $3.20 | $0.03 | 1.05M |

## About this dataset

- **Coverage:** API model offerings and hosted variants. The same underlying model may have different prices through different providers.
- **Pricing:** Standard input, output, and cached-input token rates when available. Discounts, batch tiers, and modality-specific charges may vary; confirm important purchasing decisions with the relevant provider.
- **Freshness:** The dataset is refreshed daily. `price_last_checked` in the JSON and CSV reflects the last successful retrieval of the selected record, which may be earlier than the publication date when cached data is used.
- **Formats:** [JSON](prices.json) for applications and [CSV](prices.csv) for analysis. Individual model records retain stable IDs across runs.

Find an issue or suggest an improvement? [Open a GitHub issue](https://github.com/jessejones/ai-model-prices/issues).
