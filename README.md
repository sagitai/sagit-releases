# Sagit 🏹

> "You aim. Sagit fires."

**Sagit Code inside. Any model.**
Point it at a project · reads, writes, runs · always asks first.

## ⬇️ Download

**Latest**: [Sagit v2.8 — Reliable Edits](https://github.com/sagitai/sagit-releases/releases/latest)

`Sagit-2.8.0-arm64.dmg` · Apple Silicon · signed · notarized · stapled

100% local · BYOK · macOS Apple Silicon

---

## ✨ New in v2.8 — Reliable Edits

**Checks its own work.** Before saying done on a TypeScript project, Sagit Code runs the compiler, fixes what it finds, and only then reports complete — with a "verified" badge to prove it.

- 🩺 **Verified before done** — after making changes, Sagit Code runs your project's own type check; if anything broke, it fixes it before finishing
- ✓ **The verified badge** — completed runs show at a glance that the project check passed; if issues remain, it says so honestly
- ⏱️ **Alive, not stuck** — long-running commands show a live elapsed counter, so you always know work is happening
- 🎯 **Zero setup** — works automatically on TypeScript projects with a local compiler; everywhere else, nothing changes

[Full release notes →](https://github.com/sagitai/sagit-releases/releases/tag/v2.8.0)

---

## 🏗 Built on a foundation that won't go away

**Endless Context** (v2.7) — Long sessions, light context. Sagit Code now carries only what it needs — reading files in slices, compacting old history automatically, and searching its own session memory on demand. Faster, cheaper, sharper — on any model, any window. Reads in slices: large files come in by the region, not the whole thing; the agent asks for exactly the lines it needs. Compacts itself: older history is pruned and summarized automatically as sessions grow, recent conversation kept verbatim. Remembers by searching: the agent searches its own session history; past decisions and pruned details are one lookup away. Window-aware: context budgeting adapts to each model's real window, from 192K to 1M.

**Checkpoints** (v2.6) — Sagit Code works autonomously — and now every change it makes is one click reversible. Each run automatically checkpoints the files it's about to touch. Don't like the result? Restore, instantly. Every run, auto-checkpointed: before Sagit Code modifies a file, the original is saved; zero setup, invisible until needed. Restore your way: one click reverts everything a run changed, or pick just the files you want; new files cleanly removed. Safe by design: restores guarded while a run is in progress; every restore shows exactly what it will do first. Context at a glance: a usage bar shows how full the model's context is, before it becomes a problem.

**Expert Mode, Supercharged** (v2.5.2) — Expert mode's research roles now go deeper — sharper web research, live market data, and figures computed from real inputs. Professional-grade answers, faster. Deeper research: research roles run a full think-act-observe loop: search, verify, compute — live data in one round. Live stock quotes: stocks join crypto in the price feed; international tickers (like 000660.KS) handled automatically. Computed, not copied: fast-moving figures like market cap are calculated from live inputs, not quoted from stale pages. Right-sized models: tool-carrying roles always run on mid-tier models or above.

**Codebase Understanding** (v2.5) — Sagit Code knows your codebase — 100% locally. It keeps a local index of your whole project, finds the right files across the codebase on its own, and never uploads a line — no cloud, no pointing the way. Understands your code, 100% on your machine: Sagit Code keeps a local index of the whole project and finds relevant code across the codebase — no cloud, no upload, no vendor servers. Codebase understanding with zero privacy trade-off. No need to point the way: ask for a change and it locates the right files itself, even when you don't know where the logic lives: it searches, reads, then edits. Fewer steps, less back-and-forth. Zero setup, always current: the index builds itself on first use and refreshes only what changed; it respects your ignore rules and skips oversized and binary files. No reindex button, no waiting.

**Project Memory** (v2.4) — Every project gets its own memory: Sagit Code keeps a `sagit.md` in each project and reads it on every run, so the agent always starts with the full picture. Per-project memory: each project gets a `sagit.md`; Sagit Code reads it on every run, so the agent always has the project's full context — plan, progress, decisions, gotchas. Maintained automatically: the agent updates `sagit.md` after meaningful work and keeps it concise — a one-page brief, not a log. Editable panel: a collapsible Project Memory panel lets you read and edit it anytime; it auto-refreshes after each run, and your edits are preserved.

**Long Memory** (v2.3) — Sagit Code now has long memory: conversations are saved and restored automatically, so no session is ever lost to a restart. Persistent conversations: quit and reopen; every Sagit Code session continues with its full history — what you discussed, which files it touched, what you decided. Per-session memory: each project tab keeps its own independent thread. Clearer limits: when a conversation grows too long, you get a plain "start a new session — this one stays saved", not a cryptic error.

**Sagit Code** (v2.2) — Your built-in coding agent: point it at a project, describe what you want, and it gets to work — reading files, writing code, running commands. Run any model as your coding agent through ClawAPI, and you stay in control the whole way: it asks when it's unsure — no guessing on decisions only you can make; it confirms before deleting — destructive operations always wait for your OK, everything else just runs, no friction; you see every change — each edit shows a clear, expandable diff of exactly what changed; and Stop means stop — hit Stop and the run halts instantly, no work happening in the background.

**One app for Claude Code and Codex** (v2.1) — Drive Claude Code and OpenAI Codex side by side, tabbed by project — no `cd` in a terminal; start, restart, and stop with one click. Claude Code reaches Anthropic's most capable `claude-opus-4-8` through ClawAPI — the new default for Chat and Code Manager (with `claude-opus-4-7` on hand); Codex runs on your own ChatGPT subscription or API key (`~/.codex/`), zero extra setup. Bring your own key three ways — Claude Pro / Max subscription (zero-touch), Anthropic API key (pay per token), or ClawAPI key (recommended). A single ClawAPI key reaches `claude-fable-5`, `claude-sonnet-5`, `claude-opus-4-8`, `gpt-5.6-sol`, `gpt-5.6-terra`, `gpt-5.6-luna`, and `gemini-3.1-pro` — more on the way. Crypto-native payment with USDC / USDT — no credit card, no Anthropic account. 中文 / English UI auto-switches with your system language. Zero-config onboarding — install the DMG, paste your ClawAPI key, running in five seconds.

**Self-driving Missions** (v1.6) — Missions run in the background while you work elsewhere; a built-in review loop checks each result and reworks it until it holds up. Interrupted runs wait in the Archive — one click to resume.

**Open Brain** (v1.5) — A dedicated Knowledge layer (4th autonomous Curator) for URLs, docs, and notes, with LLM-powered cleanup and locks. Full-text Mission Search across missions, memory, and knowledge with BM25 ranking — SQLite FTS5, sub-millisecond. The Sagit MCP server exposes the same brain to Claude Code, Codex, Gemini CLI, or any MCP-compatible tool.

**Self-driving Company** (v1.4) — Autonomous Curators with auto + manual lanes (autoDream, Skill, Memory, Knowledge). Per-mission directory storage handles 10K+ records. Parallel DELEGATE for 3.0× faster multi-role workflows. Reviewer headroom 4× so long missions never silently truncate.

**Org chart** — 39 universal roles, 5 company templates (Default / YC Startup / Trading Desk / Research Lab / Software Dev), more on SagitMall.

**4-layer memory** — Chairman profile (your preferences) / Company Memory partitions (culture, decisions, learnings, tech stack) / Mission Archive / Session context. All on local disk, all yours.

**Skill system** — Markdown skills with frontmatter `model_tier`. Skill Self-Evolution improves agents based on past missions. markitdown ingests URL / PDF / DOCX / XLSX into context.

**BYOK** — ClawAPI / Anthropic / OpenAI / Gemini / Ollama. No lock-in, no rev-share, no surprises.

**Local-first** — All data on disk, no telemetry, zero external CDN dependencies, Apple Silicon native, signed + notarized + stapled.

---

## 🔗 Links

- Website: [sagit.ai](https://sagit.ai)
- Twitter/X: [@sagit_ai](https://x.com/sagit_ai)
- GitHub Org: [github.com/sagitai](https://github.com/sagitai)

---

100% local · BYOK · macOS Apple Silicon · 🏹
