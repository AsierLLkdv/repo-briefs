# CLAUDE.md

## Project
Small REST API. Keep dependencies minimal.

## Commands
- dev: `npm run dev`
- test: `npm test`
- lint: `npx eslint src`

## Rules
- Validate all request bodies before touching the store.
- Errors always return `{ "error": string }`.
- No new dependencies without asking.
