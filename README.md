# AGENTS.md

## Project overview
- What this app does
- Main stack and frameworks
- Key folders to know

## Setup commands
- Install deps: `pnpm install`
- Start dev server: `pnpm dev`
- Run tests: `pnpm test`

## Code style
- Use TypeScript strict mode
- Prefer small reusable components
- Follow existing lint/format rules

## Architecture notes
- `app/` contains routes
- `lib/` contains shared utilities
- `api/` contains backend integrations

## Rules for changes
- Do not rename public API endpoints without approval
- Add tests for bug fixes
- Keep changes minimal and scoped

## Validation
- Run lint before finishing
- Run tests relevant to changed files
