# Security Policy

## Reporting a Vulnerability

If you discover a security vulnerability in anvil, please report it
**privately** rather than opening a public issue.

Preferred channels:

1. [Open a private security advisory](https://github.com/eddacraft/anvil/security/advisories/new)
   on this repository, or
2. Email [hello@eddacraft.ai](mailto:hello@eddacraft.ai) with the subject
   line `security: anvil`.

Please include:

- a description of the issue and its potential impact
- steps to reproduce, or a proof-of-concept
- the anvil version (`anvil --version`) and platform
- any suggested mitigation, if known

## Response Targets

- **Acknowledgement**: within 2 business days of receipt
- **Initial assessment**: within 7 business days
- **Remediation timeline**: shared after assessment, prioritised by severity

## Scope

In scope:

- the anvil CLI binaries published from this repository
- the installer scripts hosted from `install.eddacraft.ai` and the
  `eddacraft-anvil-installer.{sh,ps1}` release assets
- the Homebrew tap, winget manifest, and scoop bucket published by eddacraft

Out of scope:

- vulnerabilities in third-party dependencies that have already been
  disclosed upstream (please report those to the upstream project)
- social-engineering or physical-access attacks
- denial-of-service attacks against eddacraft infrastructure

## Disclosure

We follow coordinated disclosure. We ask that reporters give us a
reasonable window to investigate and ship a fix before any public
disclosure. Credit will be offered to reporters who request it.
