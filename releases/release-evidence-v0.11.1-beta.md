# Release evidence — v0.11.1-beta

A sanitised, public trust record for the `v0.11.1-beta` release of Anvil.
Anvil's source is private; this evidence proves the artefacts listed below
are the exact build published under the public `v0.11.1-beta` release. It
is generated automatically at release time from the signed build-provenance
manifest.

| Field | Value |
| --- | --- |
| Version | `0.11.1-beta` |
| Tag | `v0.11.1-beta` |
| Source revision | `e7024b7a62d73a9b6fd69f58187ab59e7df4ba36` |
| Public release | [`eddacraft/anvil`](https://github.com/eddacraft/anvil/releases/tag/v0.11.1-beta) |
| Public ref at publish | `fe9158946c16e00f15ce333b88374196b307b975` |
| Built (UTC) | 2026-09-16T17:18:34Z |
| Artefacts | 13 |

## Validation

All blocking release gates passed for `v0.11.1-beta` on the readiness run before
publication. The full machine-readable build provenance — including the
gating workflow run and the build matrix — is the signed
`anvil-v0.11.1-beta-provenance.json` published alongside this evidence; this
document is its human-readable, sanitised summary.

## Artefacts

Each shipped artefact with its SHA-256 digest, computed at build time.

| Artefact | SHA-256 | Size (bytes) |
| --- | --- | --- |
| `anvil-icon-256.png` | `6a79d63f58210c7467159b414f6ddac5a7d545a0a5b3b90e6728535dc988778c` | 3876 |
| `anvil.rb` | `7efa81860477b70c6d9023a4d68198cb891bbc79ecc999fef25bfed68258e0b9` | 2501 |
| `dist-manifest.json` | `a484af25f0d18e870da536cce3ee32a3bff26a005423ced17d7ff6c2439bdbf5` | 29972 |
| `eddacraft-anvil-aarch64-apple-darwin.tar.xz` | `a219af063bb0e618edc5b9a7ef3014693a3cbd155d186e9e2915fcf078fdc4f3` | 10322224 |
| `eddacraft-anvil-aarch64-pc-windows-msvc.zip` | `7e8e6cf4bd0b8b5d6d50639b8b0f88b9151b94487ca4d8f5c14ed8082c37ea27` | 16969525 |
| `eddacraft-anvil-aarch64-unknown-linux-gnu.tar.xz` | `8fb9f3d7bd0741469caa4d71cc8f7adf3e3fe39441fb223b55b94996f11b90e0` | 10537288 |
| `eddacraft-anvil-installer.ps1` | `82f2705d3cec447524aaf52dfa65e9698c9f0a0827c215ef421e1d0d763e4ce9` | 25414 |
| `eddacraft-anvil-installer.sh` | `d0a072ff0add075d52ecc79094eda4dfba420b8f4c08026d130e150db0403630` | 55393 |
| `eddacraft-anvil-x86_64-apple-darwin.tar.xz` | `1090b532ce2b5716fa385bdddf11642d1b833fc6e0fbe133d2dd9592a58b3fb4` | 11623692 |
| `eddacraft-anvil-x86_64-pc-windows-msvc.zip` | `0c8cb74738295f693e7203112e48d69d2c7b9804391f98e266112b62faf70494` | 18074946 |
| `eddacraft-anvil-x86_64-unknown-linux-gnu.tar.xz` | `d4d599e97ac9ea4aa95947d5dbca9601b0324a8cef01b802d61c7994768b7812` | 11943172 |
| `sha256.sum` | `0de4175dd6500921f51c3d680a7410346e9cd7b617258bfdf3b60b00d8de7808` | 748 |
| `source.tar.gz` | `b5cbba86a3827d9d0c3b55504efdb75ce10d0288a20281525531a43c84f1d731` | 16494123 |

## Verifying an artefact

Download an artefact from the [release page](https://github.com/eddacraft/anvil/releases/tag/v0.11.1-beta) and compare
its digest against the table above:

```sh
sha256sum <downloaded-file>
```

The digests here, the per-artefact `.sha256` sidecars on the release, and
the signed `anvil-v0.11.1-beta-provenance.json` all agree by construction.

---

_Auto-generated from the signed build-provenance manifest (CIB-034). It
deliberately omits raw logs, secrets, internal hostnames, private workflow
URLs, and private development detail._
