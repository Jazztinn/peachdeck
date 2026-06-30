# peachdeck

Peachdeck is a cross-compatible Codex and Claude skill for creating high-quality startup pitch decks, including hackathon, demo-day, seed-stage, and investor decks.

## Install

Use the repository root as the skill folder.

Codex:

```bash
mkdir -p ~/.codex/skills
ln -s "$(pwd)" ~/.codex/skills/peachdeck
```

Claude:

```bash
mkdir -p ~/.claude/skills
ln -s "$(pwd)" ~/.claude/skills/peachdeck
```

## Use

```text
Use $peachdeck to create a 7-slide hackathon pitch deck for our AI scheduling app.
Use $peachdeck to review this seed deck and rewrite the weak slides.
```

The skill keeps the main workflow in `SKILL.md` and loads deeper deck guidance from `references/` only when needed.
