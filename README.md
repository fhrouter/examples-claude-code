# Free Claude Code Setup — FHRouter

Point [Claude Code](https://fhrouter.com/docs/guides/claude-code) at FHRouter and use free frontier models in your terminal. One settings file, about three minutes.

> **Free tier:** frontier AI models (Grok, DeepSeek, GLM) free on every [FHRouter](https://fhrouter.com) account — no credit card. [Free LLM API](https://fhrouter.com/free-llm-api) · [How free models work](https://fhrouter.com/docs/free-models)

## Setup

1. Open the Claude Code config folder:

```bash
# Windows
start "" "%USERPROFILE%\.claude"
# macOS
open "$HOME/.claude"
# Linux / WSL
mkdir -p "$HOME/.claude" && cd "$HOME/.claude"
```

2. Create `settings.json` (see [`settings.json`](settings.json) in this repo) and put your FHRouter key from https://fhrouter.com/token into `ANTHROPIC_AUTH_TOKEN`.
3. Run `claude` and send a test message.

Full guide with troubleshooting: [https://fhrouter.com/docs/guides/claude-code](https://fhrouter.com/docs/guides/claude-code).

## Why

The [free tier](https://fhrouter.com/free-llm-api) includes frontier models (Grok 4.6, DeepSeek V4 Flash, GLM 5.3 Flash) free on every account — Claude Code works through the Anthropic-compatible endpoint at `https://api.fhrouter.com`.

## Links

- [FHRouter](https://fhrouter.com) — the gateway
- [Free LLM API](https://fhrouter.com/free-llm-api) — the free tier
- [Docs](https://fhrouter.com/docs) · [API reference](https://fhrouter.com/docs/api-reference) · [Blog](https://fhrouter.com/blog)
- Setup guides: [Claude Code](https://fhrouter.com/docs/guides/claude-code) · [Codex CLI](https://fhrouter.com/docs/guides/codex) · [Gemini CLI](https://fhrouter.com/docs/guides/gemini)

---

<sub>Examples only — FHRouter itself runs at [fhrouter.com](https://fhrouter.com). Sign up and start calling frontier models for free in minutes.</sub>
