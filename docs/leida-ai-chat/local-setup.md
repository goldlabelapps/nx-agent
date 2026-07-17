# Leida AI Chat Local Setup

## Why This Exists

The Eve init command currently requires Node.js 24 or later. This repository includes a manual scaffold so development can proceed with a clear migration path to the official initializer.

## Prerequisites

- Node.js 24+
- npm 10+

## Setup Steps

1. Use Node.js 24.
2. Install dependencies.
3. Run type checks.
4. Start the Eve agent in dev mode.

## Commands

```bash
nvm use
npm install
npm run typecheck
npm run dev
```

## Agent Entry

The Leida agent path is:

- `agent`

## Notes

- `package.json` pins Eve and defines baseline scripts.
- `tsconfig.json` is scoped to `agent/**/*.ts` and `evals/**/*.ts`.
- `agent/tools/proposeSensitiveAction.ts` demonstrates approval-first action design.
- This repository now includes official-style Eve runtime defaults plus Leida-specific docs and tooling.
