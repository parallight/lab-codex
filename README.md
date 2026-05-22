# Parallight Lab — Codex CLI plugin

Learn to build AI agents by **directing** them, guided by a resident master
craftsman (Marvin) — inside Codex CLI. Zero API keys (the LLM runs through
Parallight's backend).

## Install (Codex CLI)

```
codex plugin marketplace add parallight/lab-codex
codex plugin add parallight-lab@parallight-cx
```

Restart Codex. Codex has no slash-command routing for plugins, so use the
`:lab` commands (the skill recognises them) or natural language:

```
:lab-login        # sign in with a 6-digit email code
:lab              # browse available labs
:lab-start lab-01 # begin — the master takes over
```

More: <https://parallight.ai>

---

This repo is the public Codex marketplace. The MCP server (`plugins/parallight-lab/bundle/`)
talks to the Parallight backend; it holds no secrets.
