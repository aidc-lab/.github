# aidc-lab · organization profile

This repository is the public face of the **aidc-lab** organization on GitHub. It contains no application code — only the files GitHub reads when it renders the organization page and when repositories inherit org-wide defaults.

**Profile:** <https://github.com/aidc-lab> · **中文版:** [`profile/README.zh-CN.md`](profile/README.zh-CN.md)

## What's in here

| Path | Purpose |
| :--- | :------ |
| `profile/README.md` | The organization profile, rendered on the org page |
| `profile/README.zh-CN.md` | 简体中文版 |
| `profile/assets/` | Banner artwork, light and dark (2400 × 600, displayed at 1200 × 300) |
| `CODE_OF_CONDUCT.md` | Applies to every repository in the organization |
| `CONTRIBUTING.md` | Default contribution guide |
| `SECURITY.md` | How to report vulnerabilities privately |
| `.github/ISSUE_TEMPLATE/` | Default issue forms for repositories without their own |

## Editing the profile

1. Edit `profile/README.md` and keep `profile/README.zh-CN.md` in sync.
2. Commit and push to `main` — GitHub re-renders the org page within a minute.

A few rules that keep it rendering everywhere:

- **Images must live in this repository.** README files here are rendered in two places — the org page and the repo file view — so point at absolute raw URLs (`https://raw.githubusercontent.com/aidc-lab/.github/main/…`) rather than relative paths.
- **Ship both banner variants.** The `<picture>` element swaps on `prefers-color-scheme`; a missing dark variant makes the banner unreadable in dark mode.
- **Keep tables narrow.** The profile column is about 880 px; wide tables get squeezed rather than scrolled.
- **Leave the HTML blocks breathing.** Markdown inside `<div align="center">` only parses when blank lines separate it from the tags.

## License

[MIT](LICENSE). The banner artwork is part of this repository and covered by the same license.
