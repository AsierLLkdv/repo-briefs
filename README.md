# repo-briefs

CLAUDE.md templates + cursor rules that actually help

Started as a weekend hack, grew on me.

## What it does

- Global coding-style rules in rules/
- Kept short: agents read every token every time
- Per-archetype CLAUDE.md templates (api / cli / lib)
- Review checklist baked into instructions

## Usage

```bash
# Claude Code reads CLAUDE.md from the repo root automatically
```

## Install

```bash
# pick a template
cp templates/CLAUDE.api.md your-project/CLAUDE.md
```

## Project structure

```text
├── docs/
│   ├── faq.md
│   └── usage.md
├── rules/
│   ├── review.md
│   └── style.md
├── templates/
│   ├── CLAUDE.api.md
│   └── CLAUDE.cli.md
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
└── SECURITY.md
```

## Notes

- mostly stable, edge cases remain
