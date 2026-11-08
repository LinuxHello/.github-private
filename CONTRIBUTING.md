# Contributing

This repository follows the conventions of [linux-hello](https://github.com/LinuxHello/linux-hello/blob/main/CONTRIBUTING.md).

## Developer Certificate of Origin

Every commit must be signed off (`git commit -s`), certifying the [DCO](https://developercertificate.org/). The human who submits a commit signs it off and is accountable for it; an agent never signs off for anyone else.

## Changing the overview

- Branch from `main` and open a pull request; it is squash merged. Never push to `main`.
- Check a claim against the repository it describes before you write it, and say when it is a snapshot.
- Links to other repositories are absolute `https://github.com/LinuxHello/...` URLs, because the page renders on the organisation page, not in this repository.

## AI-assisted contributions

Name the tool behind a substantial part of a change with an `Assisted-by:` trailer, one per tool, for example `Assisted-by: Claude Code (<model>)`. Name a local model by family and size at most.

## Secrets

Never write secrets, tokens, personal data, hostnames, home paths, hardware or local endpoints into files, commit messages or pull requests, even though this repository is private.

## Writing

Plain, direct prose. Describe what something does; no unfalsifiable superlatives.

## Licence

By contributing you agree that your contribution is licensed under LGPL-3.0-or-later.
