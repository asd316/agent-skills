# Agent Skills by asd316

Public, portable skills that follow the [Agent Skills specification](https://agentskills.io/specification).

## Available skills

### experiential-explainer

Turns abstract technical, scientific, economic, strategic, or systems knowledge into grounded explanations that readers can mentally experience, predict, and transfer.

It is designed for requests such as:

- “Explain this through a concrete scenario.”
- “Give me a first-person demonstration.”
- “讲人话，让我真正有画面。”
- “Show me what actually happens when this mechanism runs.”

The skill preserves factual uncertainty and technical boundaries. Its scenes demonstrate a mechanism; they do not replace evidence for that mechanism.

## Install

List the skills in this repository:

```bash
npx skills add asd316/agent-skills --list
```

Install `experiential-explainer` interactively:

```bash
npx skills add asd316/agent-skills --skill experiential-explainer
```

Install it directly for Claude Code:

```bash
npx skills add asd316/agent-skills --skill experiential-explainer --agent claude-code
```

Install it directly for Codex:

```bash
npx skills add asd316/agent-skills --skill experiential-explainer --agent codex
```

Update an installed copy:

```bash
npx skills update experiential-explainer
```

## Repository layout

```text
skills/
└── experiential-explainer/
    └── SKILL.md
```

Each skill is self-contained and follows the standard `SKILL.md` format with `name` and `description` frontmatter.

## License

MIT
