# ai-skill-effect-lookup

Find Effect TypeScript signatures, source, and idioms from the local Effect checkout and docs. Use when you need to confirm an Effect API's signature, behavior, or deprecation, or find how an Effect pattern is done idiomatically.

## Install

### Any agent

The [`skills`](https://github.com/vercel-labs/skills) CLI installs into Codex, OpenCode, Gemini CLI, Cursor, Copilot, Claude Code, and 70+ other agents:

```bash
npx skills add guillempuche/ai-skill-effect-lookup
```

### Claude Code

```bash
# Add marketplace (uses repo slug)
/plugin marketplace add guillempuche/ai-skill-effect-lookup

# Install plugin (plugin name is topic-only)
/plugin install effect-lookup@guillempuche-ai-skill-effect-lookup
```

### Gemini CLI

```bash
gemini skills install https://github.com/guillempuche/ai-skill-effect-lookup.git --path skills/effect-lookup
```

### Manual

Copy `skills/effect-lookup` into `.agents/skills/` (Codex, Gemini CLI, OpenCode, Mastra Code, Cursor, Copilot) or `.claude/skills/` (Claude Code).

## Requirements

See [REQUIREMENTS.md](./REQUIREMENTS.md) for setup instructions.

## Part of AI Standards

This skill is also available in the [ai-standards](https://github.com/guillempuche/ai-standards) bundle with other skills and agents.

## License

MIT
