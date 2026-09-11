# claude-config-x

Agent instruction configs I sync across projects

Side project, maintained when I have time.

## Installation

```bash
# pick a template
cp templates/CLAUDE.api.md your-project/CLAUDE.md
```

## Features

- Review checklist baked into instructions
- Global coding-style rules in rules/
- Kept short: agents read every token every time
- Per-archetype CLAUDE.md templates (api / cli / lib)

## How to use

```bash
# Claude Code reads CLAUDE.md from the repo root automatically
```

## Project structure

```text
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── rules/
│   ├── review.md
│   └── style.md
├── templates/
│   ├── CLAUDE.api.md
│   └── CLAUDE.cli.md
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
└── LICENSE
```

## FAQ

**Is this production ready?**  
It works for my use case; review the code before relying on it.

**Why no framework?**  
The stdlib covers what this project needs.

## License

MIT. Do whatever you want.
