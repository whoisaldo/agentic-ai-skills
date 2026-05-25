# agentic-ai-skills

Personal library of agent skills and system prompts collected from major AI providers, tweaked over time for personal use.

## Structure

```
.
├── claude-markdowns/   ← Anthropic skills (Claude)
├── codex-markdowns/    ← OpenAI Codex (placeholder)
├── gemini-markdowns/   ← Google Gemini (placeholder)
└── grok-markdowns/     ← xAI Grok system prompts
```

## What's inside today

| Folder | Skill / Prompt | Source |
|---|---|---|
| `claude-markdowns/frontend-design/` | Build polished, responsive frontend UIs | [anthropics/skills](https://github.com/anthropics/skills) |
| `claude-markdowns/skill-creator/` | Meta-skill for authoring new Claude skills | [anthropics/skills](https://github.com/anthropics/skills) |
| `claude-markdowns/mcp-builder/` | Build MCP server integrations | [anthropics/skills](https://github.com/anthropics/skills) |
| `claude-markdowns/webapp-testing/` | End-to-end web app testing | [anthropics/skills](https://github.com/anthropics/skills) |
| `claude-markdowns/claude-api/` | Use the Claude API / Anthropic SDK | [anthropics/skills](https://github.com/anthropics/skills) |
| `grok-markdowns/grok4p1_thinking_system_turn_prompt_v2.j2` | Grok 4.1 thinking-mode system prompt | [xai-org/grok-prompts](https://github.com/xai-org/grok-prompts) |
| `grok-markdowns/grok4p1_non_thinking_system_turn_prompt.j2` | Grok 4.1 non-thinking system prompt w/ tools | [xai-org/grok-prompts](https://github.com/xai-org/grok-prompts) |

## How to use

Copy any skill folder into your agent's skills directory (e.g. `~/.claude/skills/<name>/` for Claude Code) and modify the markdown as needed. Each Anthropic skill is self-contained — `SKILL.md` plus any reference/example files travel together.

Tweaks to upstream skills are tracked via git history — no parallel `original/` folder.

## Roadmap

`codex-markdowns/` and `gemini-markdowns/` are placeholders. No official skill libraries exist upstream yet; will seed when useful sources emerge (community `AGENTS.md` collections, Gemini system prompts, etc.).

## Sources & credits

- Anthropic skills: <https://github.com/anthropics/skills>
- Grok prompts: <https://github.com/xai-org/grok-prompts> (AGPL-3.0)

The repo's [LICENSE](./LICENSE) covers original content only. Each upstream's license applies to its respective files.
