<div align="center">
<img src="mascot.png" width="140" />
<h1>Sagit</h1>
</div>

<p align="center">
  <strong>Your AI company, on your laptop.</strong><br>
  A thin harness for AI companies. Skills as markdown. Memory on disk. Bring your own provider.
</p>

<p align="center">
  <a href="https://github.com/sagitai/sagit-releases/releases/latest"><strong>⬇ Download for Mac (Apple Silicon)</strong></a><br>
  <sub>v1.2.0 · ~150 MB · macOS 12+ · Apple Silicon</sub>
</p>

---

## 🆕 New in v1.2

- **🌙 autoDream** — Daily memory consolidation. Sonnet 4.6 reviews your AI company's memory while you're idle: relative dates become absolute, duplicates merge, superseded entries get removed. 3-layer safety (backup + diary + restore).
- **🎯 Skill Self-Evolution** — Roles get smarter with use. Sagit scores how well each agent performed (1-5), and when a role consistently scores poorly, generates an improvement suggestion you can review. Human-in-the-loop accept/reject/restore.
- **📄 Document import** — Drop PDF, Word, or PowerPoint into the Knowledge Wiki. Sagit extracts the text via pure-JS converters (no Python install) and compiles a structured wiki entry.
- **🔄 OpenClaw migration** — Coming from OpenClaw? Settings → Import / Export → "Scan for OpenClaw". One click imports your skills, memories, and API keys. Your OpenClaw files are not modified.

---

## Quick Start

### 1. Install

- Download the DMG from [Releases](https://github.com/sagitai/sagit-releases/releases/latest)
- Open the DMG, drag `Sagit.app` to `/Applications`
- Double-click to open (signed & notarized — no Gatekeeper bypass needed)

### 2. Get an API key

Sagit needs an AI model provider to work. The default is **ClawAPI** (pay-per-use, no subscription):

1. Go to [clawapi.org](https://clawapi.org)
2. Register a free account
3. Go to Dashboard → Copy your API key
4. In Sagit: Settings → ClawAPI → Paste your key

**Other supported providers** (add any or all in Settings):

| Provider | Get key at | Models |
|----------|-----------|--------|
| ClawAPI (default) | [clawapi.org](https://clawapi.org) | Claude, GPT, Gemini via one key |
| Anthropic | [console.anthropic.com](https://console.anthropic.com) | Claude Opus / Sonnet / Haiku |
| OpenAI | [platform.openai.com](https://platform.openai.com) | GPT-5.5 / 5.4 / mini |
| Google | [aistudio.google.com](https://aistudio.google.com/app/apikey) | Gemini 3.x |
| Ollama (local) | [ollama.com](https://ollama.com) | Any local model, free |

### 3. Start

Type your first mission. Sagit picks the right agent automatically.

---

## Other features

- **39 specialist agents** — CEO, CTO, Researcher, Engineer... each is an editable `.skill.md` file
- **Auto / Fast / Expert modes** — Auto picks the cheapest agent; upgrades to Expert when needed
- **Knowledge Wiki** — import URLs and docs, agents reference them automatically
- **Document Delivery** — export as PowerPoint or Word with one click
- **4-layer memory** — Chairman profile, company culture, decisions, learnings, tech stack
- **Multi-provider routing** — switch models mid-conversation, automatic fallback

---

<p align="center">
  <a href="https://sagit.ai">sagit.ai</a> · <a href="https://x.com/sagit_ai">X @sagit_ai</a>
</p>

<p align="center">
  <em>You aim. Sagit fires.</em> ♐
</p>

<p align="center">
  <sub>© 2026 Sagit</sub>
</p>
