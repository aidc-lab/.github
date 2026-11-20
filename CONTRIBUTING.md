# Contributing to aidc-lab

Thanks for spending time here. This guide is the default for every repository in the organization; if a repository ships its own `CONTRIBUTING.md`, that file wins.

## Before you start

- **Search first.** Someone may have filed the same bug or proposed the same feature already.
- **Open an issue before a large pull request.** A short discussion up front saves a rewrite later. Typos, docs fixes and one-line bug fixes need no ceremony.
- **Keep changes focused.** One concern per pull request.

## Reporting bugs

A good report is reproducible. Please include:

1. Which repository, and the version or commit you are running.
2. What you expected to happen, and what happened instead.
3. The smallest set of steps that triggers it.
4. Your OS and runtime (`go version`, `node -v`, `python -V`, …), when relevant.
5. Logs or a screenshot — paste text rather than photographing a screen.

## Suggesting features

Describe the problem before the solution: what you were trying to do, what got in the way, and what you have tried. It is much easier to evaluate an idea against a real workflow than against an imagined one.

## Pull requests

1. Fork the repository and branch from `main` (`fix/…`, `feat/…`, `docs/…` are fine).
2. Match the code around you — naming, structure, comment density. Do not reformat unrelated lines.
3. Add or update tests when behaviour changes; keep `go vet`, type checks and the existing test suite green.
4. Update the docs when you change something user-visible.
5. Write commit messages in the imperative mood, with a short subject line and a body that explains *why*.

### Style, per stack

| Stack | Expectation |
| :---- | :---------- |
| Go | `gofmt` and `go vet` clean; errors wrapped with context; no panics in library code |
| TypeScript / Vue | The repository's own `tsconfig` and lint config; no `any` unless it is genuinely unknown |
| Python | The repository's formatter and tests; type hints on public functions |

### Security

Never open a public issue or pull request that demonstrates a vulnerability. Follow [SECURITY.md](SECURITY.md) instead.

## Review

Maintainers review on a best-effort basis. A pull request may be asked to narrow its scope, add a test, or split unrelated changes — this is normal, not a rejection.

## Conduct

By participating you agree to the [Code of Conduct](CODE_OF_CONDUCT.md). Be generous with context, and assume the other person is acting in good faith.

## License

Contributions are accepted under the license of the repository you are contributing to — MIT for repositories owned by this organization, upstream licenses for forks.
