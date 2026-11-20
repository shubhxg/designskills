<div align="center">

# 🎨 Awesome Design Skills for AI Agents

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Open Standard](https://img.shields.io/badge/Standard-SKILL.md-blue.svg)](https://agentskills.io)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#contributing)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

**A curated directory of portable `SKILL.md` registries, aesthetic guidelines, design systems, and UI/UX engineering workflows for AI coding agents.**

[Explore Registries](#skill-registries--hubs) • [What are Agent Skills?](#what-are-agent-skills) • [Quick Start](#quick-start) • [Contributing](#contributing)

</div>

---

## 📖 What are Agent Skills?

**Agent Skills** (`SKILL.md`) are modular, portable packages of procedural knowledge, aesthetic judgment, and engineering standards that AI coding agents (such as **Claude Code**, **Cursor**, **GitHub Copilot**, **Windsurf**, **Codex CLI**, and **Gemini CLI**) load dynamically on demand.

Rather than relying on repetitive, verbose prompting for visual polish, design skills allow agents to internalize:
- **Aesthetic Direction & Visual DNA:** Typography pairings, cohesive color palettes, spatial rhythm, and motion principles.
- **UI/UX Engineering Standards:** Component architecture, responsive grid systems, performance rules, and WCAG accessibility audits.
- **Design-to-Code Workflows:** Translating Figma tokens, brand guidelines, and design critiques into production-ready code.

---

## 🗂️ Contents

- [Skill Registries & Hubs](#skill-registries--hubs)
- [Aesthetic & Brand Systems](#aesthetic--brand-systems)
- [UI/UX & Frontend Engineering](#uiux--frontend-engineering)
- [Design Audits & Accessibility](#design-audits--accessibility)
- [Quick Start](#quick-start)
- [Contributing](#contributing)

---

## 🌐 Skill Registries & Hubs

Centralized directories, marketplaces, and CLI ecosystems for discovering, auditing, and installing agent skills.

| Platform | Description | Supported Agents & Tools | CLI / Quick Install |
| :--- | :--- | :--- | :--- |
| **[Design Skills Hub](https://designskills.xyz/)** | An open registry dedicated to portable design skills for AI agents. Features curated **Aesthetic Skills** (visual DNA, brand systems, motion) and **Engineering Skills** (a11y, performance), side-by-side visual output previews, and a Figma-to-Skill converter. | Claude Code, Cursor, Codex, Windsurf, any `SKILL.md`-compatible agent | `npx skills add VaporAviator/designskills-hub-skill` |
| **[AgentSkill.sh](https://agentskill.sh/)** | A comprehensive AI agent skills directory and marketplace housing 276,000+ community and official skills across design, frontend development, and workflows. Includes automated two-layer security scanning, quality scoring, and version tracking. | Claude Code, Cursor, GitHub Copilot, Windsurf, Zed, Gemini CLI, 20+ tools | `npx @agentskill.sh/cli@latest setup` |

---

## ✨ Aesthetic & Brand Systems

*Skills focused on visual craft, typography, color theory, and cohesive brand identity.*

- **[Design Skills Hub — Aesthetic Collection](https://designskills.xyz/)** — Browse curated visual styles, editorial layouts, and motion presets tested against standardized design briefs so you can compare aesthetic judgment side-by-side before installing.
- *(Add your favorite aesthetic `SKILL.md` repositories here)*

---

## 🛠️ UI/UX & Frontend Engineering

*Skills that enforce modern component patterns, responsive layouts, and clean CSS/Tailwind architecture.*

- **[AgentSkill.sh — Frontend & UI Directory](https://agentskill.sh/)** — Search thousands of vetted frontend, Tailwind CSS, React, and component-architecture skills directly from your terminal or mid-conversation via `/learn`.
- *(Add your favorite UI/UX engineering `SKILL.md` repositories here)*

---

## ♿ Design Audits & Accessibility

*Skills designed to critique layouts, verify contrast ratios, and enforce WCAG compliance.*

- *(Coming soon — submit a PR to add accessibility and design-critique skills)*

---

## ⚡ Quick Start

Most modern AI coding assistants follow the open `SKILL.md` standard. You can equip your agent with design capabilities in seconds:

### 1. Using the Design Skills Hub CLI
Install the hub skill to let your agent search and apply curated design systems directly:
```bash
npx skills add VaporAviator/designskills-hub-skill
```

### 2. Using the AgentSkill.sh CLI
Set up the `@agentskill.sh/cli` to enable `/learn` commands and security-vetted skill installations inside your workspace:
```bash
npx @agentskill.sh/cli@latest setup
```

### 3. Manual Installation
Drop any `SKILL.md` folder directly into your project's agent directory:
```text
your-project/
└── .claude/              # Or .cursor/, .github/, .agent/
    └── skills/
        └── your-design-skill/
            ├── SKILL.md  # Core instructions & visual rules
            └── assets/   # Optional tokens, palettes, or references
```

---

## 🤝 Contributing

Contributions are welcome! If you've built or discovered a high-craft design skill for AI agents, feel free to open a Pull Request.

1. Fork this repository.
2. Add your entry to the appropriate category using the format:
   `- **[Skill or Platform Name](https://link-to-skill)** — Concise description of the design capability.`
3. Ensure the linked skill includes a valid `SKILL.md` file and clear usage instructions.
4. Submit your PR!

---

<div align="center">
  <sub>Built for designers and developers crafting the next generation of AI-assisted interfaces.</sub>
</div>
