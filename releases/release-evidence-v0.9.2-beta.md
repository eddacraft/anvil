# Release evidence — v0.9.2-beta

A sanitised, public trust record for the `v0.9.2-beta` release of Anvil.
Anvil's source is private; this evidence proves the artefacts listed below
are the exact build published under the public `v0.9.2-beta` release. It
is generated automatically at release time from the signed build-provenance
manifest.

| Field | Value |
| --- | --- |
| Version | `0.9.2-beta` |
| Tag | `v0.9.2-beta` |
| Source revision | `c3f67c4f7b51f8a9b733ec9a9b73beebc21a9446` |
| Public release | [`eddacraft/anvil`](https://github.com/eddacraft/anvil/releases/tag/v0.9.2-beta) |
| Public ref at publish | `b0721311d1d3df96e3ee8c22d8187a5ad885f2bd` |
| Built (UTC) | 2026-08-03T17:17:07Z |
| Artefacts | 2 |

## Validation

All blocking release gates passed for `v0.9.2-beta` on the readiness run before
publication. The full machine-readable build provenance — including the
gating workflow run and the build matrix — is the signed
`anvil-v0.9.2-beta-provenance.json` published alongside this evidence; this
document is its human-readable, sanitised summary.

## Artefacts

Each shipped artefact with its SHA-256 digest, computed at build time.

| Artefact | SHA-256 | Size (bytes) |
| --- | --- | --- |
| `anvil-icon-256.png` | `6a79d63f58210c7467159b414f6ddac5a7d545a0a5b3b90e6728535dc988778c` | 3876 |
| `dist-manifest.json` | `ef0ba3a4dd6ad7ca73009306008e9d84dd9b8cecc7029496fa4a5f3134fd27d2` | 17614 |

## Verifying an artefact

Download an artefact from the [release page](https://github.com/eddacraft/anvil/releases/tag/v0.9.2-beta) and compare
its digest against the table above:

```sh
sha256sum <downloaded-file>
```

The digests here, the per-artefact `.sha256` sidecars on the release, and
the signed `anvil-v0.9.2-beta-provenance.json` all agree by construction.

---

_Auto-generated from the signed build-provenance manifest (CIB-034). It
deliberately omits raw logs, secrets, internal hostnames, private workflow
URLs, and private development detail._
