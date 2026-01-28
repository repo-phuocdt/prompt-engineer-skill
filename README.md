# Prompt Engineer — Claude Code Skill

A Claude Code custom skill that transforms rough prompts/ideas into production-ready LLM prompts. Supports Claude, GPT, Llama, and other models with advanced techniques like Chain-of-Thought, Constitutional AI, RAG optimization, and more.

## Features

- **Multi-model support** — optimized prompts for Claude, GPT, Llama, Gemini, etc.
- **Advanced techniques** — CoT, Tree-of-Thoughts, few-shot, Constitutional AI, prompt chaining
- **Production-ready output** — structured prompts with implementation notes, test cases, and usage guidelines
- **Model-specific optimization** — leverages each model's strengths (XML for Claude, JSON mode for GPT, etc.)
- **Enterprise patterns** — templates for agents, RAG, data extraction, and multi-step workflows

## Installation

### Via npx (recommended)

```bash
npx prompt-engineer-skill
```

Custom install path:

```bash
npx prompt-engineer-skill --path ~/.claude/custom-skills/prompt-engineer
```

### Via git

```bash
git clone https://github.com/repo-phuocdt/prompt-engineer-skill.git \
  ~/.claude/skills/prompt-engineer
```

### Uninstall

```bash
npx prompt-engineer-skill --uninstall
```

## Usage

In Claude Code, invoke the skill:

```
/prompt-engineer
```

Then describe what you need:

- "Create a system prompt for a code review agent"
- "Optimize this prompt for RAG retrieval"
- "Design a multi-step reasoning prompt for medical diagnosis"

## Output Format

Every response includes:

1. **The Prompt** — complete, copyable code block
2. **Implementation Notes** — techniques used, model-specific optimizations, parameter recommendations
3. **Testing & Evaluation** — test cases, edge cases, optimization suggestions
4. **Usage Guidelines** — when/how to use, customization options

## References

The skill includes curated reference materials:

- `references/techniques.md` — Advanced prompting techniques catalog
- `references/model-specific-optimization-guide.md` — Per-model optimization strategies
- `references/production-patterns-and-enterprise-templates.md` — Enterprise-grade templates

## License

MIT — see [LICENSE](LICENSE).
