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
  <sub>v1.4.0 · ~150 MB · macOS 12+ · Apple Silicon</sub>
</p>

---

## 🆕 New in v1.4 — Self-driving Company

- **🤖 4 autonomous Curators** — autoDream, Skill, Memory, plus the shared framework that runs them. They work in the background on their own cadence; every action is logged to `~/.sagit/curator/audit.jsonl` so you can review what they did and why.

- **🎯 Unbounded mission storage** — The 100-mission cap is gone. Per-mission directory layout (`~/.sagit/missions/<id>/`) handles 10K+ missions; v1.3 history auto-migrates on first boot.

- **🔒 Per-skill / per-partition locks** — Manual 🔒 toggles plus 24h auto-lock on hash drift. Skills and memory partitions you've hand-edited won't get overwritten by a Curator.

- **💰 Daily LLM budget cap** — Set a per-day spend limit for autonomous Curators in Settings → Curator Activity. Hot-reloads — no restart, no risk of a runaway dream.

- **⚡ Parallel team delegation** — Multi-role delegations now run concurrently via `Promise.all`. Measured 3.0× wall-time speedup on a 3-delegate batch.

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

- **39 universal specialists, every one an editable file** — CEO, CTO, Researcher, founding_engineer, founding_pm, software_engineer, product_manager and 32 others. Every agent is a `.skill.md` file you can read, fork, and hot-reload. Pick any role for any mission — same org chart whether you're founding-stage or production-scale.
- **Per-role model + fallback chain** — Settings → Roles. A 39-row table where you pick the model for each role and set custom fallback chains. Power user paradise.
- **GPT-5.5 in the fallback chain** — When Anthropic has issues, Sagit auto-tries GPT-5.5 before falling further: Opus 4.7 → GPT-5.5 → GPT-5.4 → Gemini 3.1 Pro.
- **Routines on main nav** — Scheduled tasks promoted to a first-class sidebar item. Daily briefs, BTC trackers, weekly standups — set once, run forever.
- **Auto / Fast / Expert modes** — Auto picks the cheapest agent; upgrades to Expert when needed.
- **Knowledge Wiki** — import URLs and docs, agents reference them automatically.
- **Document Delivery** — export reports as PowerPoint or Word with one click.
- **Document Import** — Drop PDF, Word, or PowerPoint into the Knowledge Wiki. Pure-JS converters extract text — no Python install, no external services.
- **Chairman profile** — your preferences, language, style — always injected into every interaction.
- **4-layer memory** — company culture, decisions, learnings, tech stack.
- **autoDream reflection** — Sagit reflects on completed missions and writes the lessons into typed memory files (`learnings.md`, `decisions.md`, `tech-stack.md`). The shared brain that grows with the work.
- **Skill scoring & rewrite** — every skill gets a 1-5 quality score after each mission. Underperformers surface as rewrite candidates so your prompts sharpen over time.
- **Multi-provider routing** — switch models mid-conversation, automatic fallback.
- **OpenClaw migration** — Settings → Import / Export → "Scan for OpenClaw". One click imports your skills, memories, and API keys. Your OpenClaw files are not modified.

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
