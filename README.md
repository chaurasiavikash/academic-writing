# Academic Writing AI Assistant

A collection of AI instructions and skills to help researchers write, proofread, and review academic manuscripts. Works with GitHub Copilot, Claude Code, and open-source LLMs.

---

## What is included

| File | Purpose |
|------|---------|
| `copilot-instructions.md` | Global instructions: anti-AI writing patterns applied to all generated prose |
| `.github/skills/proofreading/SKILL.md` | Skill: structured proofreading of academic manuscripts and LaTeX documents |
| `.github/skills/academic-reviewer/SKILL.md` | Skill: peer-review-style critique of papers for top-tier venues |

---

## Usage

### GitHub Copilot (VS Code)

1. Clone this repo and open it in VS Code.
2. `copilot-instructions.md` is picked up automatically as custom instructions for Copilot Chat.
3. The skills in `.github/skills/` are available as custom skills. Invoke them in chat:

   > "Proofread the methods section of my paper."

   > "Review this manuscript as a peer reviewer for NeurIPS."

   Copilot will automatically select the right skill based on your request, or you can reference it explicitly.

### Claude Code

1. Open this repo as your working directory (`claude` from the repo root).
2. The `CLAUDE.md` in your home directory (or a local `CLAUDE.md`) should point to the skill files. Add entries like:

   ```
   @.github/skills/proofreading/SKILL.md
   @.github/skills/academic-reviewer/SKILL.md
   ```

3. Claude Code will load these as context. Ask:

   > "Proofread my introduction following the proofreading skill."

   > "Give me a reviewer-style critique of this draft."

   Alternatively, paste the contents of a SKILL.md directly into the conversation as a system prompt.

### Open-source LLMs (Ollama, LM Studio, Jan, etc.)

The skill files are plain Markdown -- you can use them as system prompts with any model.

1. Open `.github/skills/proofreading/SKILL.md` and copy its contents.
2. Paste it as the system prompt in your LLM interface (e.g. the "System" field in Open WebUI, LM Studio, or Jan).
3. Paste your manuscript text as the user message.
4. For best results use a model with a long context window (32k+), such as `llama3.1:70b`, `qwen2.5:72b`, or `mistral-large`.

For quick one-shot use from the terminal with Ollama:

```bash
cat .github/skills/proofreading/SKILL.md your_manuscript.tex | ollama run llama3.1:70b
```

---

## Anti-AI writing guidelines

`copilot-instructions.md` applies automatically when using Copilot. When using other tools, prepend it to your prompt or load it as a system instruction to ensure generated prose avoids detectable AI writing patterns (e.g. "pivotal", "underscores", "-ing" padding phrases, media-coverage puffery).

---

## Adding your own skills

Create a new directory under `.github/skills/your-skill-name/` containing a `SKILL.md` with a YAML frontmatter block:

```markdown
---
name: your-skill-name
description: "One sentence description of when to use this skill."
---

# Your skill instructions here
```

Copilot will pick it up automatically. For Claude Code and open-source LLMs, reference or paste the file manually.
