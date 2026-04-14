<p align="center">
  <img src="assets/anvil-logo.svg" alt="anvil" width="120" />
</p>

<h1 align="center">anvil</h1>

<p align="center">
  deterministic governance for AI-assisted development
</p>

<p align="center">
  <a href="https://github.com/eddacraft/anvil/releases/latest"><img src="https://img.shields.io/github/v/release/eddacraft/anvil?include_prereleases&label=version&color=cc5500" alt="Latest release" /></a>
  <a href="https://github.com/eddacraft/anvil/releases/latest"><img src="https://img.shields.io/github/downloads/eddacraft/anvil/total?color=333" alt="Downloads" /></a>
</p>

---

anvil is a structural governance tool that gives teams visibility and control
over AI-generated code changes. It runs gate checks, policy enforcement, and
architecture validation — ensuring AI assistants produce code that meets your
standards.

## install

### linux / macOS

```bash
curl --proto '=https' --tlsv1.2 -LsSf \
  https://github.com/eddacraft/anvil/releases/latest/download/eddacraft-anvil-installer.sh | sh
```

### windows (PowerShell)

```powershell
irm https://github.com/eddacraft/anvil/releases/latest/download/eddacraft-anvil-installer.ps1 | iex
```

### homebrew

```bash
brew install eddacraft/tap/anvil
```

## quick start

```bash
# authenticate (device code flow)
anvil auth login

# run governance checks on the current directory
anvil gate

# watch for changes and run checks continuously
anvil watch

# interactive onboarding tutorial
anvil tutorial

# check system health
anvil doctor

# update to the latest version
anvil update
```

## platform support

| platform | architecture | status |
| -------- | ------------ | ------ |
| linux    | x86_64       | supported |
| linux    | aarch64      | supported |
| macOS    | x86_64       | supported |
| macOS    | aarch64      | supported |
| windows  | x86_64       | supported |
| windows  | aarch64      | supported |

## issues and feedback

Found a bug or have a feature request? Please
[open an issue](https://github.com/eddacraft/anvil/issues/new) on this
repository. When reporting bugs, include:

- anvil version (`anvil --version`)
- operating system and architecture
- steps to reproduce
- expected vs actual behaviour

For questions about beta access, email
[hello@eddacraft.ai](mailto:hello@eddacraft.ai).

## about

anvil is currently in **closed beta**. Access requires an invitation.

This repository hosts release binaries, install scripts, and issue tracking.
Source code is not published here.

All rights reserved.

---

<p align="center">
  <a href="https://eddacraft.ai">
    <img src="assets/eddacraft-logo.svg" alt="eddacraft" width="28" />
  </a>
</p>

<p align="center">
  <sub>built by <a href="https://eddacraft.ai">eddacraft</a></sub>
</p>
