# Claude Skills Collection

A curated repository of custom instruction packages, modular plugins, and workflows designed to supercharge your AI coding agents. These skills extend the functional boundaries of **Claude Code**, **Claude.ai**, and other compatible agent environments (like Cursor, Gemini CLI, or Windsurf) by adding domain-specific frameworks, guardrails, and tactical capabilities.

## 🧩 What are Claude Skills?

Claude Skills are portable, reusable instruction packages that teach an LLM agent how to tackle a specific class of problems in a consistent, repeatable way. While tools give an agent the *capability* to act, **Skills** dictate its *behavior*, defining the explicit workflows, steps, and guardrails to adhere to.

Each skill is isolated within its own folder and governed by a structured `SKILL.md` blueprint.

---

## 📂 Repository Structure

```text
├── .github/              # Automation workflows
├── skills/               # The active Skills library
│   ├── custom-skill-1/   # Example custom workflow
│   │   ├── SKILL.md      # Claude instructions & frontmatter
│   │   └── README.md     # Specific usage guide
│   └── custom-skill-2/
└── README.md             # This file
