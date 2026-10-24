# Hermosi Ad Creator

A reusable Codex skill that turns a product website and ad idea into a complete video and Facebook ad creative pack.

## Included in each pack

- 50 distinct hooks
- 3–5 ad bodies and 1–3 spoken CTAs
- 50 assembled video ad scripts
- Facebook primary text, headline, description, and button CTA for every variant
- Image generation prompts for every variant
- TTS-ready narration, voice direction, and fictional influencer casting profiles

The skill researches the supplied website and grounds commercial claims in available evidence. Audio rendering requires an available authorized speech tool. Creating a pack does not publish ads or spend an advertising budget.

## Install

Clone this repository into your Codex skills directory:

```sh
git clone https://github.com/bensblueprints/hermosi-ad-creator.git ~/.codex/skills/hermosi-ad-creator
```

If you use a custom `CODEX_HOME`, use its `skills` directory instead. If that folder already exists, use the existing installation rather than cloning over it.

## Use

```text
Use $hermosi-ad-creator for https://example.com/product.
We're selling [product]. The ad idea is [idea].
Audience: [audience]. Language: [language].
```

See [SKILL.md](SKILL.md) for the complete workflow. UI metadata is in [agents/openai.yaml](agents/openai.yaml).
