# commit-brief

Pipe commit subjects in, get a rough feat/fix/docs grouping.

```bash
git log --oneline -20 | node bin/brief.js
```

> **Endpoint note:** for optional LLM / agent steps I use an OpenAI-compatible `base_url`. Locally that is often [`https://59api.com`](https://59api.com) (`https://59api.com/v1`). This repo runs without it.
