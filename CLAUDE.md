# FlyRank Capstone — AI-Assisted Development

This file guides AI coding assistants (Claude, Cursor, and similar tools) working in this repository.

## Project status

This is a FlyRank Frontend AI Engineering capstone repository.

- Current task: FE-01 (environment and AI toolchain)
- Capstone idea: not decided
- Application source: do not create until the idea is finalized
- Product requirements and architecture: TBD

**The stack and project requirements in this file are provisional until the capstone idea is finalized.** Update this document when those decisions are made.

## Provisional stack

Until the idea is confirmed, assume:

- React
- TypeScript
- Vite

Do not introduce another framework, bundler, or language without an explicit request. Do not create `package.json`, source files, components, or application code unless asked.

## Coding conventions

When application code exists, follow these defaults:

- TypeScript throughout; avoid `any` unless there is a clear, documented reason
- Functional React components and hooks
- Clear, descriptive names; prefer readability over cleverness
- Keep files focused; extract only when reuse or complexity justifies it
- Prefer composition over large, tightly coupled modules
- Match existing style, formatting, and file structure before inventing new patterns
- Colocate related UI, styles, and types when that is the project pattern

## Git / commit conventions

- Do not commit, push, or amend unless the user explicitly asks
- Do not update git config
- Commit messages should be concise, written in the imperative mood, and explain *why* when it is not obvious
- Keep commits focused; do not mix unrelated changes
- Do not commit secrets, `.env` files, credentials, or generated artifacts such as `node_modules`, `dist`, or `coverage`

## AI-assisted development rules

- Follow this file and the user's current request; do not expand scope
- Inspect the repository before making changes
- Prefer small, reviewable diffs
- Explain non-obvious decisions briefly when they matter
- If requirements are ambiguous, choose the conservative option or ask rather than inventing product decisions
- Do not generate application features, pages, or demo data while the capstone idea is still TBD

## Dependencies and unrelated changes

- Do not add dependencies unless they are necessary for the requested work
- Prefer the existing provisional stack over new libraries
- Do not refactor, restyle, or reorganize files that are unrelated to the task
- Do not create extra documentation, configs, or source trees that were not requested
- Leave the working tree free of secrets and generated build output
