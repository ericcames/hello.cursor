# hello.cursor

A small repository created from Cursor.

## Cursor / AI context for this repo

Cursor does **not** store chat transcripts inside the repo. To carry **durable, repo-scoped** guidance into future sessions, use:

| Mechanism | Location | Role |
|-----------|----------|------|
| **Project rules** | [`.cursor/rules/`](.cursor/rules/) | Short `.mdc` files with YAML frontmatter (`alwaysApply`, `globs`, `description`). Best for enforceable, repeatable instructions. |
| **Agent doc** | [`AGENTS.md`](AGENTS.md) | Long-form “how this repo works” for the AI (stack, commands, conventions). |
| **Index scope** | [`.cursorignore`](.cursorignore) | Excludes paths from codebase indexing (not the same as hiding secrets—still avoid committing secrets). |

This repo includes **stubs** for all three; replace the placeholders as the project grows.

## License

This project is licensed under the MIT License — see [LICENSE](LICENSE).
