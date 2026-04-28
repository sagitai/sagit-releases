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
  <sub>v1.3.0 · ~150 MB · macOS 12+ · Apple Silicon</sub>
</p>

---

## 🆕 New in v1.3

- **🎩 39 universal roles** — Invoke any specialist regardless of company template. `software_engineer`, `founding_engineer`, `code_reviewer`, `experiment_evaluator`, `founding_pm`, `product_manager`, `research_reviewer` and 32 others. Your AI org chart adapts to the work.

- **⚙️ Per-role model + fallback chain** — New Settings → Roles tab. 39-row table where you change which model runs each role, set custom fallback chains, reset to defaults. Power user paradise.

- **🔌 GPT-5.5 in tier-default fallback** — When Anthropic API has issues, Sagit auto-tries GPT-5.5 (OpenAI's strongest reasoning model) before falling further down. `high`: Opus 4.7 → **GPT-5.5** → GPT-5.4 → Gemini 3.1 Pro.

- **⏰ Routines on main navigation** — Scheduled tasks promoted from a hidden Settings sub-tab to a first-class sidebar item. Daily market briefs, BTC trackers, weekly standups — set once, run forever.

- **🪶 Founding-stage role naming** — `founding_engineer` and `founding_pm` for startup-style work, alongside production-scale `software_engineer` and `product_manager`. YC vocabulary.

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
- **Chairman profile** — your preferences, language, style — always injected into every interaction
- **4-layer memory** — company culture, decisions, learnings, tech stack
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
