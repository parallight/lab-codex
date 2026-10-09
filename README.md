# OpenLabs — Codex CLI plugin

Learn to build AI agents by **directing** them, guided by a resident master craftsman — inside Codex CLI. Draw what you want to learn as a teachboard board. Zero API keys (the LLM runs through Parallight's backend).

## Install (Codex CLI)

```
codex plugin marketplace add parallight/lab-codex
codex plugin add openlabs@parallight-cx
```

Restart Codex. Codex has no slash-command routing for plugins, so use `:openlabs` / `:lab` style tokens (the skill recognises them) or natural language:

```
:openlabs connect   # connect your teachboard account
:lab-login        # sign in with a 6-digit email code
:lab              # browse available labs
```

More: <https://parallight.ai>

---

This repo is the public Codex CLI marketplace. The MCP server (`plugins/openlabs/bundle/`) talks to the Parallight backend; it holds no secrets.
