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

### sage-explorer

Researches a domain or question by finding its deepest thinkers and schools of thought — selected for quality of insight, not fame or orthodoxy — then distills their thinking methods into a progressive, richly illustrated single-file HTML report, while incrementally building a local knowledge base (one folder per thinker) under the skill directory.

It is designed for requests such as:

- "这个领域谁看得最透？"
- "想了解 XX 领域的高人/学派怎么看这个问题。"
- "帮我深度研究一下 XX，别只讲主流观点。"
- "Research who really understands XX and synthesize their thinking methods."

The skill always includes at least one high-quality heterodox or marginal perspective when one exists, labels each thinker's mainstream/edge status honestly, and organizes the answer with thinkers as the skeleton, their thinking methods as the spine, and AI-reorganized evidence as the flesh.

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

Install `sage-explorer` interactively:

```bash
npx skills add asd316/agent-skills --skill sage-explorer
```

Update an installed copy:

```bash
npx skills update experiential-explainer
```

## Repository layout

```text
skills/
├── experiential-explainer/
│   └── SKILL.md
└── sage-explorer/
    ├── SKILL.md
    ├── references/
    │   ├── finding-sages.md
    │   ├── knowledge-base.md
    │   └── answer-format.md
    ├── assets/
    │   └── report-template.html
    └── knowledge/          # created at runtime; one folder per thinker
```

Each skill is self-contained and follows the standard `SKILL.md` format with `name` and `description` frontmatter.

## License

MIT
