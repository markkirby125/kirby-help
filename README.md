# kirby-help

*This skill is part of the [Kirby Skills Collection](https://github.com/markkirby125/kirby-skills-collection).*

A centralized directory and helper skill for listing and accessing all installed Kirby Skills inside an active AI agent session.

When invoked with `/kirby` or `kirby skills`, this skill outputs an organized reference matrix of every Kirby skill available on the machine, including primary triggers, descriptions, and activation guidance.

## 🪄 The Magic Prompt

Copy and paste this directly to your AI (Cursor, Windsurf, Claude Code, Antigravity):

```markdown
@agent Please install the kirby-help skill into this workspace.
1. Read the `SKILL.md` file from this repository: https://github.com/markkirby125/kirby-help
2. Identify the correct rules system for our current environment (e.g., `.cursor/rules/` for Cursor, `.windsurfrules` for Windsurf, `.clinerules` for Cline, or `~/.agents/skills/` for Antigravity).
3. Save the contents appropriately.
4. Confirm when the installation is complete.
```

## Manual Installation

- **Cursor**: Save the contents of `SKILL.md` to `.cursor/rules/kirby-help.mdc`
- **Windsurf**: Save the contents of `SKILL.md` to `.windsurfrules`
- **Antigravity**: Clone this repository directly into `~/.agents/skills/kirby-help`

## Tech Stack

- **Format**: Markdown / YAML
- **Compatibility**: Antigravity, Claude Code, Cursor, Windsurf, Cline
