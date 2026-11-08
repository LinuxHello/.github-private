# .github-private

Member-only organisation profile for [LinuxHello](https://github.com/LinuxHello). GitHub shows [profile/README.md](profile/README.md) at the top of the organisation page to organisation members only. The public profile is in [`LinuxHello/.github`](https://github.com/LinuxHello/.github).

| Path | What |
| :-- | :-- |
| [profile/README.md](profile/README.md) | The organisation overview: the repositories, the architecture, the workflow and where things stand |
| [.github/CODEOWNERS](.github/CODEOWNERS) | Who reviews changes |
| [.github/workflows/dco.yml](.github/workflows/dco.yml) | The `dco` check |

This repository is private. The overview describes the private `linux-hello-workstation` repository, so do not copy it into a public repository ([invariant 8](https://github.com/LinuxHello/linux-hello/blob/main/AGENTS.md#invariants) keeps machine details out of those).

## Keeping the overview current

The overview is a snapshot, written by hand from the four repositories. Update it when a repository is added, a container changes state, an ADR changes status, or the workflow changes. Check each claim against `main` of the repository it describes, and date the snapshot in the first paragraph.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). Licence: LGPL-3.0-or-later ([COPYING.LESSER](COPYING.LESSER), [COPYING](COPYING)).
