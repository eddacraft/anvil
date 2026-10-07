# Release evidence — v0.14.2-beta

A sanitised, public trust record for the `v0.14.2-beta` release of Anvil.
Anvil's source is private; this evidence proves the artefacts listed below
are the exact build published under the public `v0.14.2-beta` release. It
is generated automatically at release time from the signed build-provenance
manifest.

| Field | Value |
| --- | --- |
| Version | `0.14.2-beta` |
| Tag | `v0.14.2-beta` |
| Source revision | `db220d624888c6b0a2f4cb072c0394d128c9ff00` |
| Public release | [`eddacraft/anvil`](https://github.com/eddacraft/anvil/releases/tag/v0.14.2-beta) |
| Public ref at publish | `ea139687dd14f3dba9831738d5c273b6383ed654` |
| Built (UTC) | 2026-10-07T19:12:13Z |
| Artefacts | 13 |

## Validation

All blocking release gates passed for `v0.14.2-beta` on the readiness run before
publication. The full machine-readable build provenance — including the
gating workflow run and the build matrix — is the signed
`anvil-v0.14.2-beta-provenance.json` published alongside this evidence; this
document is its human-readable, sanitised summary.

## Artefacts

Each shipped artefact with its SHA-256 digest, computed at build time.

| Artefact | SHA-256 | Size (bytes) |
| --- | --- | --- |
| `anvil-icon-256.png` | `6a79d63f58210c7467159b414f6ddac5a7d545a0a5b3b90e6728535dc988778c` | 3876 |
| `anvil.rb` | `831a0ef9ef6c6bc159e771f65f0eb6dc40822412e3067f227ebf085e6f3ed54a` | 2501 |
| `dist-manifest.json` | `2d69d2d855c4eb2d2077a2920cb7e73a27e50e9eba79e4eedc2e39cd466bcfc2` | 53183 |
| `eddacraft-anvil-aarch64-apple-darwin.tar.xz` | `da0d1670c72ebb5451ada422e7d3cc345455e2ad5fd6fa5e820fca97beed950d` | 10994904 |
| `eddacraft-anvil-aarch64-pc-windows-msvc.zip` | `5a1d929c3b6613e39bff51da6d676b50c3a15b44a246dd37e41419fc0c603aec` | 18369928 |
| `eddacraft-anvil-aarch64-unknown-linux-gnu.tar.xz` | `34695db588b32a960c0bc2ce1b4c32083e104f8a9ece7f354e77f1325a5e8cad` | 11215932 |
| `eddacraft-anvil-installer.ps1` | `3840a7692023aaa1e5c6ab0f26f7a7c10ec36349786e545dc1f3c422d17f2c11` | 25470 |
| `eddacraft-anvil-installer.sh` | `03de381e590594827f95fb3ea9012c344a765f4bd5a1bbee2ae08432fce8609d` | 55441 |
| `eddacraft-anvil-x86_64-apple-darwin.tar.xz` | `807429114ae8c58ea5499370e8022bd9b6ca42012762ca387b50b4bb4641d85b` | 12399016 |
| `eddacraft-anvil-x86_64-pc-windows-msvc.zip` | `c23261949fca8a543b915d8916ab24b87a899fa6ac1d86d41cf24697c931650c` | 19617943 |
| `eddacraft-anvil-x86_64-unknown-linux-gnu.tar.xz` | `478fb2e5ff8a6fe11223a54f0646f3ead6aa633174b083718fcb5d54356a44eb` | 12726256 |
| `sha256.sum` | `71c88791d65c3243ad64a353b083c19ae4998cbc2c715f592340f276615237d6` | 748 |
| `source.tar.gz` | `a60c932f0762e81e3a5989e8b78d204d8dfb152c99e3dbf8d5ceeefd57a69fad` | 20649171 |

## Verifying an artefact

Download an artefact from the [release page](https://github.com/eddacraft/anvil/releases/tag/v0.14.2-beta) and compare
its digest against the table above:

```sh
sha256sum <downloaded-file>
```

The digests here, the per-artefact `.sha256` sidecars on the release, and
the signed `anvil-v0.14.2-beta-provenance.json` all agree by construction.

---

_Auto-generated from the signed build-provenance manifest (CIB-034). It
deliberately omits raw logs, secrets, internal hostnames, private workflow
URLs, and private development detail._
