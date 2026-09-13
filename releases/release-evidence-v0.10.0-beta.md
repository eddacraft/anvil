# Release evidence — v0.10.0-beta

A sanitised, public trust record for the `v0.10.0-beta` release of Anvil.
Anvil's source is private; this evidence proves the artefacts listed below
are the exact build published under the public `v0.10.0-beta` release. It
is generated automatically at release time from the signed build-provenance
manifest.

| Field | Value |
| --- | --- |
| Version | `0.10.0-beta` |
| Tag | `v0.10.0-beta` |
| Source revision | `bd6e4c98bfa8a6adb7511fa73c53690612a20c03` |
| Public release | [`eddacraft/anvil`](https://github.com/eddacraft/anvil/releases/tag/v0.10.0-beta) |
| Public ref at publish | `f8ac3181f09190bf7a4b0b6b0500da953f4aa88a` |
| Built (UTC) | 2026-09-13T17:39:05Z |
| Artefacts | 2 |

## Validation

All blocking release gates passed for `v0.10.0-beta` on the readiness run before
publication. The full machine-readable build provenance — including the
gating workflow run and the build matrix — is the signed
`anvil-v0.10.0-beta-provenance.json` published alongside this evidence; this
document is its human-readable, sanitised summary.

## Artefacts

Each shipped artefact with its SHA-256 digest, computed at build time.

| Artefact | SHA-256 | Size (bytes) |
| --- | --- | --- |
| `anvil-icon-256.png` | `6a79d63f58210c7467159b414f6ddac5a7d545a0a5b3b90e6728535dc988778c` | 3876 |
| `dist-manifest.json` | `ae89f9020e38df3191ef5e455d04c3dbd9da842e7fcd1a9234458c47273ea3aa` | 56757 |

## Verifying an artefact

Download an artefact from the [release page](https://github.com/eddacraft/anvil/releases/tag/v0.10.0-beta) and compare
its digest against the table above:

```sh
sha256sum <downloaded-file>
```

The digests here, the per-artefact `.sha256` sidecars on the release, and
the signed `anvil-v0.10.0-beta-provenance.json` all agree by construction.

---

_Auto-generated from the signed build-provenance manifest (CIB-034). It
deliberately omits raw logs, secrets, internal hostnames, private workflow
URLs, and private development detail._
