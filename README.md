# Anvil

Deterministic governance for AI-assisted development.

Anvil is a structural governance tool that gives teams visibility and control
over AI-generated code changes. It runs gate checks, policy enforcement, and
architecture validation — ensuring AI assistants produce code that meets your
standards.

## Install

### Linux / macOS

```bash
curl --proto '=https' --tlsv1.2 -LsSf \
  https://github.com/EddaCraft/anvil/releases/latest/download/eddacraft-anvil-installer.sh | sh
```

### Windows (PowerShell)

```powershell
irm https://github.com/EddaCraft/anvil/releases/latest/download/eddacraft-anvil-installer.ps1 | iex
```

## Quick start

```bash
# Authenticate (device code flow)
anvil auth login

# Run governance checks on the current directory
anvil gate

# Watch for changes and run checks continuously
anvil watch

# Check system health
anvil doctor
```

## Platform support

| Platform | Architecture | Status |
| -------- | ------------ | ------ |
| Linux    | x86_64       | Supported |
| Linux    | aarch64      | Supported |
| macOS    | x86_64       | Supported |
| macOS    | aarch64      | Supported |
| Windows  | x86_64       | Supported |
| Windows  | aarch64      | Not yet supported |

## About

Anvil is developed by [EddaCraft](https://eddacraft.ai). This repository
hosts release binaries and install scripts. Source code is not published here.

All rights reserved. Anvil is proprietary software.

## Status

Anvil is currently in **closed beta**. Access requires an invitation.
