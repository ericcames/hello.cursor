# Contributing

## Workflow

**Every change follows this sequence — no exceptions:**

```
Open issue → branch from main → implement → open PR (Closes #N) → merge → issue closes
```

1. **Open an issue first** — describe what you are fixing or adding and why before substantial implementation work.
2. **Branch from `main`** — use `<type>/<short-description>` (e.g. `fix/readme-typo`, `feat/ci-check`, `docs/changelog`).
3. **One concern per PR** — group changes by shared root cause. The test: would you revert these together? If yes, ship them together.
4. **Reference the issue** — include `Closes #<number>` in the PR description so the issue closes on merge.
5. **PRs target `main`** — non-trivial changes should go through a PR for review and traceability.
6. **Update CHANGELOG.md** — add an entry under `## [Unreleased]` (Added / Changed / Fixed / Removed).

## Branch naming

| Prefix | When to use |
|--------|-------------|
| `feat/` | New capability |
| `fix/` | Bug fix |
| `docs/` | Documentation only |
| `chore/` | CI, dependencies, housekeeping |
| `refactor/` | Restructure with no intended behavior change |

## Commit messages

```
<type>: <short description>

<optional body explaining why, not what>
```

Types: `feat`, `fix`, `docs`, `refactor`, `chore`

## Project conventions

- See [AGENTS.md](AGENTS.md) and [README.md](README.md) for how this repo is meant to evolve.
- Prefer **Cursor-first** repo and file workflows documented in `AGENTS.md` (Repository bootstrap).

## Sensitive data

Never commit credentials, tokens, private keys, or other secrets. See [.github/SECURITY.md](.github/SECURITY.md).
