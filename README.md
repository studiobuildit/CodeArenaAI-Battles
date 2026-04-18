<div align="center">

# CodeArenaAI Battles

**Same prompt · Multiple AIs · You pick the winner**

[![YouTube — CodeArenaAI](https://img.shields.io/badge/Watch-CodeArenaAI-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@CodeArenaAI)

*Where AI tools fight for supremacy.*

<br>

</div>

---

## Welcome

[CodeArenaAI](https://www.youtube.com/@CodeArenaAI) is a YouTube series that pits leading AI assistants against each other on **the exact same brief**—coding challenges, canvas animations, mini-games, and more. This repository is the **open archive** of those duels: every battle’s **shared prompt** and each model’s **standalone HTML** answer, so you can read, run, and compare the results yourself.

No install, no build, no database—just prompts and pages you can open in a browser.

---

## What you will find here

Each folder is **one battle**, named with an index and a short slug (for example `battle-004-matrix-rain/`). Inside you always get:

| File | What it is |
|------|----------------|
| **`prompt.md`** | The battle title and the **full prompt** every entry answered—the same brief, in full. |
| **`chatgpt.html`** | A complete, self-contained HTML page—one competitor’s answer. |
| **`claude.html`** | Another full HTML answer to the **identical** prompt. |
| **`gemini.html`** | A third answer—same challenge, different implementation. |
| **`deepseek.html`** | The fourth answer—same rules, new code. |

The four `.html` names are fixed on purpose: easy links, easy diffs, and a simple story—**one prompt, four solutions**—whether you are browsing on GitHub or opening files locally.

---

## Try a battle in thirty seconds

From the **root of this repository** (the folder that contains this `README.md`), start a tiny local server:

```bash
python3 -m http.server 8080
```

Then open something like:

**http://localhost:8080/battle-004-matrix-rain/chatgpt.html**

Open the other three HTML files from the **same** folder in new tabs—same prompt, four interpretations. If you prefer another static server (for example `npx serve`), that works too.

> **Tip:** A local server avoids quirks some browsers have with `file://` and scripts or canvas-heavy demos.

---

## On the channel

CodeArenaAI is more than one format. On YouTube you will find:

- **Code Wars** — AI vs AI visual coding challenges  
- **Agent Wars** — CLI and agent tooling face-offs  
- **Automation Wars** — workflow and automation stacks compared  
- **Prompt Wars** — logic, algorithms, and problem-solving under pressure  

Subscribe for new drops, same rule every time: **one prompt, many models, your verdict.**

---

## Share and credit

These materials are here for **learning, comparison, and fun**. If you use them in a video, article, or classroom, a nod to **CodeArenaAI** and a link to [youtube.com/@CodeArenaAI](https://www.youtube.com/@CodeArenaAI) is appreciated.

---

<div align="center">

**[Subscribe on YouTube](https://www.youtube.com/@CodeArenaAI)** · *May the best model win.*

</div>
