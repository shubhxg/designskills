# Design Skills for AI Agents

A curated collection of `SKILL.md` files, registries, and resources that help AI coding agents produce better design and frontend work.

[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
[![Format: SKILL.md](https://img.shields.io/badge/Format-SKILL.md-blue.svg)](https://agentskills.io)

## Contents

- [About](#about)
- [Registries and Hubs](#registries-and-hubs)
- [Aesthetic and Brand Systems](#aesthetic-and-brand-systems)
- [UI/UX and Frontend Engineering](#uiux-and-frontend-engineering)
- [Design Audits and Accessibility](#design-audits-and-accessibility)
- [Getting Started](#getting-started)
- [Contributing](#contributing)

## About

An Agent Skill is a folder containing a `SKILL.md` file: a set of instructions that an AI coding agent loads when a task calls for it. Skills work with tools such as Claude Code, Cursor, GitHub Copilot, Windsurf, Codex CLI, and Gemini CLI, and follow the open [Agent Skills](https://agentskills.io) format.

For design and frontend work, a good skill saves you from repeating the same guidance in every prompt. It can capture:

- **Visual direction:** typography pairings, color palettes, spacing, and motion principles.
- **Engineering standards:** component structure, responsive layouts, performance, and accessibility.
- **Design-to-code workflows:** turning design tokens, brand guidelines, and critique feedback into production code.

This repository collects the skills and resources I have found useful as a reference for designers and frontend developers.

## Registries and Hubs

Directories where you can discover, review, and install skills.

| Name | Description | CLI install |
| :--- | :--- | :--- |
| [Design Skills Hub](https://designskills.xyz/) | An open registry of portable design skills, split into aesthetic skills (visual style, brand systems, motion) and engineering skills (accessibility, performance). Includes side-by-side output previews and a Figma-to-skill converter. | `npx skills add VaporAviator/designskills-hub-skill` |
| [AgentSkill.sh](https://agentskill.sh/) | A large directory of community and official skills covering design, frontend development, and general workflows, with security scanning, quality scoring, and version tracking. Supports 20+ agent tools. | `npx @agentskill.sh/cli@latest setup` |

## Aesthetic and Brand Systems

Skills focused on typography, color, layout, and brand identity.

- [Design Skills Hub: Aesthetic Collection](https://designskills.xyz/): Curated visual styles, editorial layouts, and motion presets. Each is tested against the same design briefs, so you can compare results before installing.

## UI/UX and Frontend Engineering

Skills for component patterns, responsive layout, and maintainable CSS and Tailwind.

- [AgentSkill.sh: Frontend and UI](https://agentskill.sh/): Searchable frontend, Tailwind CSS, React, and component-architecture skills. Install from the terminal or mid-conversation with `/learn`.

## Design Audits and Accessibility

Skills for reviewing layouts, checking color contrast, and verifying WCAG compliance.

This section does not have entries yet. See [Contributing](#contributing) if you would like to add one.

## Getting Started

### Install from a registry

Install the Design Skills Hub skill so your agent can search and apply its design systems:

```bash
npx skills add VaporAviator/designskills-hub-skill
```

Or set up the AgentSkill.sh CLI for `/learn` commands and vetted installs:

```bash
npx @agentskill.sh/cli@latest setup
```

### Install manually

Copy a skill folder into your project's agent directory. The exact directory depends on your tool (`.claude/`, `.cursor/`, `.github/`, and so on).

```text
your-project/
└── .claude/
    └── skills/
        └── your-design-skill/
            ├── SKILL.md      # Instructions and design rules
            └── assets/       # Optional: tokens, palettes, references
```

## Contributing

Contributions are welcome. To add a skill or resource:

1. Fork this repository.
2. Add your entry to the most fitting section, using this format:

   ```markdown
   - [Skill or Platform Name](https://link-to-skill): One-sentence description of what it does.
   ```

3. Make sure the linked skill includes a valid `SKILL.md` and clear usage instructions.
4. Open a pull request.

## License

This work is released under [CC0 1.0 Universal](http://creativecommons.org/publicdomain/zero/1.0/).
