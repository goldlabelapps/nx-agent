# nx-agent Documentation

This repository keeps project documentation in the `docs/` directory.
The root README serves as the table of contents.

## Table of Contents

1. [Eve Overview](docs/eve-overview.md)
2. [Leida AI Chat Project Charter](docs/leida-ai-chat/project-charter.md)
3. [Leida AI Chat Architecture](docs/leida-ai-chat/architecture.md)
4. [Leida AI Chat MVP Backlog](docs/leida-ai-chat/mvp-backlog.md)
5. [Leida AI Chat Deployment Plan](docs/leida-ai-chat/deployment-plan.md)
6. [Leida AI Chat Local Setup](docs/leida-ai-chat/local-setup.md)
7. [Eve Init Comparison](docs/leida-ai-chat/eve-init-comparison.md)
8. [Leida AI Chat Verification](docs/leida-ai-chat/verification.md)

## Agent Scaffold

- `agent/instructions.md`
- `agent/agent.ts`
- `agent/channels/eve.ts`
- `agent/skills/research.md`
- `agent/tools/getProjectContext.ts`
- `agent/tools/proposeSensitiveAction.ts`

## Web Chat Scaffold

- `next.config.ts` (with `withEve` integration)
- `app/` (Next.js chat UI)
- `components/` (UI elements scaffolded by Eve web channel)

## Evals

- `evals/evals.config.ts`
- `evals/smoke.eval.ts`

## Docs Conventions

- Add and update documentation in `docs/`.
- Keep this README updated as the docs index.
- Prefer concise, implementation-focused docs with links to official sources.
