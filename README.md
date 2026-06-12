# Noble AI

A multi-model AI workbench running on my own infrastructure. Built for operators
who need real work done, not chatbot demos.

**Status:** Live (private alpha) · **Code:** Private — available for licensing

---

## What it does

- **Model board landing.** Live-populated dropdown of every model on the box —
  Ollama local models + hosted (OpenAI, Anthropic) side by side.
- **Per use case pages.** Skip-tracing, NuExtract structured extraction, voice,
  SMS, RAG, reasoning — each surfaced as its own tool with its own preset.
- **Pipelines + presets.** Chain models, pin presets, hot-swap without redeploy.
- **Health guardrails.** Every endpoint health-checked at the dropdown level —
  you don't get to pick a dead model.

## Architecture (sketch)

```
[Operator browser]
       │
       ▼
[Node frontend :11500] ──► [Ollama local models]
       │                 ──► [Hosted API providers]
       │                 ──► [Psych layer (deception/intent)]
       │                 ──► [Reasoning corpus + prefilter]
       ▼
[Per-use-case pages: skip-trace, voice, SMS, RAG, extract]
```

## Why it exists

Most AI tooling assumes you have one model and one task. I run a dozen models
across local and hosted providers, switch them per call, and need every dial
visible without code edits. Noble AI is the cockpit.

## Demo

Available on request. Email below.

---

📧 desertshibari@gmail.com
