# Security policy

## Supported versions

Security fixes land on the default branch of each repository and in its latest release. Older tags are not maintained.

## Reporting a vulnerability

Please **do not** open a public issue, discussion or pull request for a vulnerability.

1. Open the affected repository's **Security** tab → **Advisories** → **Report a vulnerability**. This creates a private draft advisory that only you and the maintainers can see.
2. If private reporting is not enabled for that repository, message an organization owner on GitHub and ask for a private channel first — leave the details out of the opening message.

A useful report contains:

- the affected repository, version or commit;
- the impact — what an attacker gains, and under which conditions;
- reproduction steps or a proof of concept;
- a suggested fix, if you have one.

## What to expect

- An acknowledgement, targeted within seven days.
- An assessment and a fix plan, or an explanation if we consider the report out of scope.
- Credit in the advisory once a fix ships, unless you would rather stay anonymous.

## Scope

Everything under [github.com/aidc-lab](https://github.com/aidc-lab) that we own. For forks of upstream projects, report upstream first:

| Fork | Upstream |
| :--- | :------- |
| LlamaFactory | [hiyouga/LlamaFactory](https://github.com/hiyouga/LlamaFactory) |
| ms-swift | [modelscope/ms-swift](https://github.com/modelscope/ms-swift) |
| CloudCLI | [siteboon/claudecodeui](https://github.com/siteboon/claudecodeui) |
| custom-openclaw | [openclaw/openclaw](https://github.com/openclaw/openclaw) |

## Out of scope

- Scanner output with no demonstrated impact.
- Social engineering, physical access, or denial of service through unrealistic load.
- Third-party services an app talks to — TMDB, IMDb, Douban, model providers, WebDAV and Netdisk hosts. Report those to the service.
- Misconfigured self-hosted deployments, such as an admin port deliberately exposed to the internet.
