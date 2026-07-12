# Security Policy

eddacraft takes security reports seriously. This policy explains which versions
of anvil are supported and how to report a vulnerability responsibly.

## Supported Versions

The `eddacraft/anvil` repository is a public release mirror for the anvil app.
It contains release assets, installers, documentation, and distribution
metadata. It is not the public source repository for the proprietary anvil
application.

Unless a release states otherwise, security fixes are provided for the latest
public release and the current release channel.

| Version / Channel | Supported |
| --- | --- |
| Latest public release | Yes |
| Current beta release | Yes |
| Older releases | Best effort |
| Unreleased or locally modified builds | No |

Users should upgrade to the latest release when a security update is published.

## Reporting a Vulnerability

Please do not report security vulnerabilities through public GitHub issues,
discussions, or pull requests.

To report a vulnerability, use one of the following channels:

- GitHub private vulnerability reporting, if enabled for this repository
- Email: `security@eddacraft.ai`

Please include as much detail as you can safely provide:

- anvil version, from `anvil --version`
- Operating system, architecture, and install method
- Affected release asset, installer, package, or update channel
- Description of the vulnerability and likely impact
- Steps to reproduce or proof of concept
- Any relevant logs, screenshots, configuration, or environment details
- Whether the issue is already public or known to be exploited

Because this repository is a release mirror, we do not expect vulnerability
reports to include source-code patches. If the issue is accepted, eddacraft will
fix it in the proprietary source, publish updated release artefacts where
appropriate, and coordinate disclosure.

## Scope

This policy covers vulnerabilities in the distributed anvil app and its public
release surfaces, including:

- anvil CLI binaries and release artefacts published by eddacraft
- Installer scripts and installation instructions
- Published package metadata for supported package managers
- Update, download, and verification paths controlled by eddacraft
- Documentation that could cause users to install, configure, or trust anvil
  unsafely

The following are generally out of scope unless they demonstrate a clear
security impact:

- Feature requests or product behaviour that is not a security boundary
- Vulnerabilities in third-party dependencies already disclosed upstream
- Denial-of-service claims without practical impact
- Social engineering or physical attacks
- Issues requiring compromised developer machines, leaked credentials, or
  malicious maintainers
- Automated scanner output without validation

## What To Expect

We aim to acknowledge valid reports within 3 business days.

After acknowledgement, we will triage the report and may ask for additional
information. For accepted vulnerabilities, we will work on a fix, publish a
security update where appropriate, and credit the reporter if they want to be
credited.

For declined reports, we will explain the reason where it is safe and practical
to do so.

We aim to provide status updates at least every 14 days while an accepted report
remains unresolved.

## Coordinated Disclosure

Please give us a reasonable opportunity to investigate and fix the issue before
publishing details publicly.

We will not ask you to keep a vulnerability confidential forever, but we do ask
that disclosure timing be coordinated to reduce harm to users.

## Safe Harbour

We will not pursue legal action against good-faith security research that:

- Avoids privacy violations, data destruction, service disruption, or
  unauthorised access to third-party systems
- Uses only the minimum access necessary to demonstrate the issue
- Reports the vulnerability promptly and privately
- Does not use the vulnerability for extortion, persistence, or lateral
  movement

This safe harbour does not authorise testing against systems, accounts, data, or
infrastructure you do not own or do not have permission to test.

## Secrets and Sensitive Data

If you accidentally discover secrets, tokens, private keys, credentials, or
sensitive data, stop testing and report the issue immediately. Do not copy,
reuse, disclose, or retain sensitive material beyond what is necessary to
demonstrate the finding.
