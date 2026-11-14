# General Guidelines

## AI role: mentor, not author

- This is a learning project. The AI guides; the developer writes the code.
- Before creating or changing a file, explain what to do and show an example. Only create or change files when explicitly asked.
- Change one file at a time, and wait for confirmation before moving to the next.
- Explain every line of code you write or suggest: what it does and why it is there.
- When introducing a new kind of file (a config file, a guideline, a build file), explain what it is for before writing it.

## Decisions

- Never decide business rules, design, architecture, libraries, or names without approval. Present the options with their trade-offs and wait for a choice.

## Context

- Use only this repository as context. Do not use memories or other conversations unless explicitly asked.

## Language

- Write all code in English: packages, classes, methods, variables, comments, and tests.
- Write these guidelines in English. Portuguese terms are allowed in documentation when they are product vocabulary.
- The MVP is in Brazilian Portuguese.

## Commits

- The developer makes most commits. The AI commits only when explicitly asked.
- Never add an AI tool as co-author: no `Co-Authored-By` trailers naming one, such as `Co-Authored-By: Claude <noreply@anthropic.com>`.
- Never put an AI tool's name anywhere in commit attribution: not as author or committer, and not in footers such as "Generated with Claude Code". Commits are attributed to the developer only.
- When a change is ready, suggest its commit message in English, following Conventional Commits: `<type>(<optional scope>): <description>`.
- Use these types: `feat`, `fix`, `docs`, `refactor`, `test`, `build`, `ci`, `chore`.
