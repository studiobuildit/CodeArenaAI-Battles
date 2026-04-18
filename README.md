# CodeArenaAI Battles

[![YouTube — CodeArenaAI](https://img.shields.io/badge/YouTube-@CodeArenaAI-FF0000?style=flat&logo=youtube&logoColor=white)](https://www.youtube.com/@CodeArenaAI)

**Same prompt. Multiple AIs. One winner.**

[CodeArenaAI](https://www.youtube.com/@CodeArenaAI) is where AI tools compete under identical instructions. We line up models such as ChatGPT, Claude, Gemini, and DeepSeek (plus others as episodes evolve) on coding challenges, canvas animations, mini-games, and more. You watch the outputs side by side and pick what deserves the crown.

## What this repository contains

This is a **static archive of battle outputs**: self-contained HTML files and the **exact prompt** used for each round. There is no build step, no framework, and no backend—only files you can open in a browser.

| Item | Description |
|------|-------------|
| **Battle folders** | `battle-001-…` onward—one folder per battle, with a zero-padded index and a short slug (for example `battle-004-matrix-rain`). The export script rebuilds this list whenever you run it. |
| **Model outputs** | Four files per folder, always the same names: `chatgpt.html`, `claude.html`, `gemini.html`, `deepseek.html`. Each file is that model’s self-contained answer to the prompt (plain static HTML you can open in a browser). |
| **`prompt.md`** | **Only** the battle title and the **exact shared prompt** text. No wiring tables, no internal paths, no recording or sync notes. |

### What this archive does not include

Nothing here explains **how** CodeArenaAI produces or records episodes: no multi-panel app, no synchronized start, no preset formats, no iframe loader, no project layout from the private tooling repo. **Each folder is only:** `prompt.md` + the four HTML outputs. When you add or change battles in the recorder project, re-run the export so this tree stays a clean mirror of prompts and code only.

## How to view a battle locally

Browsers sometimes restrict `file://` for scripts or assets. A tiny local server is the most reliable approach:

```bash
# From the root of this repository (where this README lives)
python3 -m http.server 8080
```

Then open a URL such as:

`http://localhost:8080/battle-004-matrix-rain/chatgpt.html`

Repeat with `claude.html`, `gemini.html`, or `deepseek.html` in the same folder to compare outputs.

Alternatives: any static file server (for example `npx serve`) works the same way.

## For CodeArenaAI maintainers

Releases of this dataset are produced so that **only** prompts and per-model HTML appear here—never recorder apps, sync behavior, preset definitions, or internal file layout. When battles change upstream, refresh this tree the same way; the export tooling lives in the private recorder project and is intentionally not part of this public mirror.

## Series on the channel

- **Code Wars** — AI vs AI visual coding challenges  
- **Agent Wars** — Claude Code vs Cursor vs Codex vs Gemini CLI  
- **Automation Wars** — n8n vs Make vs Zapier  
- **Prompt Wars** — Algorithm and logic showdowns  

Tagline we live by: *Where AI tools fight for supremacy.*

## Contributing and reuse

These files are published for **education, comparison, and entertainment**. If you fork or share them, keep attribution to **CodeArenaAI** and link back to the channel when it makes sense. Suggestions for future battles belong in the YouTube community around the channel rather than as unsolicited bulk PRs of new HTML here—unless you are explicitly collaborating with the project maintainers.

## Stay connected

- **YouTube:** [youtube.com/@CodeArenaAI](https://www.youtube.com/@CodeArenaAI)  
- Subscribe for new battles, same rules every time: **one prompt, many models, your verdict.**

---

*Repository: curated battle outputs for the CodeArenaAI series.*
