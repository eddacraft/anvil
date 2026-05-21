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

The one-liner for any platform lives at
**[install.eddacraft.ai](https://install.eddacraft.ai)** — it auto-detects your
OS and highlights the recommended command.

### linux / macOS

```bash
curl --proto '=https' --tlsv1.2 -LsSf \
  https://github.com/eddacraft/anvil/releases/latest/download/eddacraft-anvil-installer.sh | sh
```

### homebrew (macOS)

```bash
brew install eddacraft/tap/anvil
```

### windows (PowerShell)

```powershell
irm https://github.com/eddacraft/anvil/releases/latest/download/eddacraft-anvil-installer.ps1 | iex
```

### winget (Windows)

```powershell
winget install eddacraft.anvil
```

### scoop (Windows)

```powershell
scoop bucket add eddacraft https://github.com/eddacraft/scoop-bucket
scoop install anvil
```

Full usage guides live at
[docs.eddacraft.ai/anvil](https://docs.eddacraft.ai/anvil/overview).

## quick start

```bash
# new to anvil? pick a starting point
anvil welcome              # quick-start menu
anvil tutorial             # interactive walkthrough
anvil wizard               # guided project setup

# activate anvil in this repo
# (writes .anvilrc / .anvil.<ext> and installs MCP config
#  for cursor and claude code)
anvil start
anvil start --format json  # or `--format toml`
anvil start --verify       # read-only probe, no writes

# authenticate (device-code flow)
anvil auth login
anvil auth whoami

# run governance checks
anvil gate                 # full gate (profile + config driven)
anvil check                # planless scan: anti-patterns + secrets
anvil watch                # report findings as you save

# project state and diagnostics
anvil status               # project state + protection-claim summary
anvil doctor               # environment + daemon diagnostics
anvil insights             # local-only weekly activity summary

# witness-chain + policy
anvil audit                # full project audit
anvil audit-chain          # walk the branch, report missing L3 witnesses
anvil l4-validate          # validate commits against anvil/policy.yml

# launch an AI agent under anvil's protection
anvil-run --tool claude-code -- claude

# version + updates
anvil version --check      # check for newer releases and advisories
anvil update               # update to the latest version
```

Run `anvil --help` for the full command list, or
`anvil <command> --help` for any subcommand.

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

To report a security vulnerability, please follow [SECURITY.md](SECURITY.md)
rather than opening a public issue.

## about

anvil is currently in **closed beta**. Access requires an invitation.

This repository hosts release binaries, install scripts, and issue tracking.
Source code is not published here.

See [LICENSE](LICENSE) for terms. All rights reserved.

---

<p align="center">
  <a href="https://eddacraft.ai">
    <img src="assets/eddacraft-logo.svg" alt="eddacraft" width="28" />
  </a>
</p>

<p align="center">
  <sub>built by <a href="https://eddacraft.ai">eddacraft</a></sub>
</p>
