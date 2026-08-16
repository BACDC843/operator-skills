# Installing in Claude Code

For developers. If you use Claude in a browser instead, see
[install-claude-ai.md](install-claude-ai.md) — that is the main path.

## Install

```
/plugin marketplace add BACDC843/operator-skills
/plugin install operator-skills@operator-skills
```

That installs all twenty-two skills. Check them with `/skills`.

## Update

```
/plugin marketplace update operator-skills
```

Releases are versioned, so you only receive an update when the version changes. See
[CHANGELOG.md](../CHANGELOG.md).

## Uninstall

```
/plugin uninstall operator-skills@operator-skills
/plugin marketplace remove operator-skills
```

## Requirements

Any Claude Code version that supports plugin marketplaces. The marketplace uses a `github`
plugin source, which has no minimum version — deliberately, because an `archive` source
requires v2.1.224 or later and fails the *entire* marketplace on older versions rather than
just the one entry.

## Where the brief goes

`business-brief` writes `business-brief.md` to the working directory. Every other skill
looks for it there or in the project's files.

Keep it at the root of the repo or folder you work in. Several skills also read files other
skills write:

| Skill | Reads |
|---|---|
| `landing-page` | `ads-<offer>-<platform>.md` from `ad-creative-lab` |
| `job-description` | `scorecard-<role>.md` from `role-scorecard` |
| `onboarding-plan` | `scorecard-<role>.md`, and any `sop-<process>.md` |

They degrade gracefully when those files are absent — they just ask you instead.

## A note on what these skills do

Twenty-one of the twenty-two only ever write files. `enquiry-reply` can send an email
through whatever mail connector you already have, and it shows the exact body and the exact
recipient and asks first, one message per confirmation.

No skill in the pack has `allowed-tools` set, so every tool call goes through your normal
permission flow.

See [what-acts-and-what-drafts.md](what-acts-and-what-drafts.md).
