# Release evidence — v0.9.7-beta

A sanitised, public trust record for the `v0.9.7-beta` release of Anvil.
Anvil's source is private; this evidence proves the artefacts listed below
are the exact build published under the public `v0.9.7-beta` release. It
is generated automatically at release time from the signed build-provenance
manifest.

| Field | Value |
| --- | --- |
| Version | `0.9.7-beta` |
| Tag | `v0.9.7-beta` |
| Source revision | `89a6d2050b7a93e69ac6ea99848d9dfa7c63be3c` |
| Public release | [`eddacraft/anvil`](https://github.com/eddacraft/anvil/releases/tag/v0.9.7-beta) |
| Public ref at publish | `08be7976df4267837ce95421d537c0ccef4e7424` |
| Built (UTC) | 2026-08-21T01:10:12Z |
| Artefacts | 13 |

## Validation

All blocking release gates passed for `v0.9.7-beta` on the readiness run before
publication. The full machine-readable build provenance — including the
gating workflow run and the build matrix — is the signed
`anvil-v0.9.7-beta-provenance.json` published alongside this evidence; this
document is its human-readable, sanitised summary.

## Artefacts

Each shipped artefact with its SHA-256 digest, computed at build time.

| Artefact | SHA-256 | Size (bytes) |
| --- | --- | --- |
| `anvil-icon-256.png` | `6a79d63f58210c7467159b414f6ddac5a7d545a0a5b3b90e6728535dc988778c` | 3876 |
| `dist-manifest.json` | `b0c3dd155ece8628247eb2141a5807a33369f1111e7937efe8b34379b105d0d3` | 27967 |
| `eddacraft-anvil-aarch64-apple-darwin.tar.xz` | `9935fa588c5e8bf12b48229bbc0d54306f34e166715c52d98d0459950678fd17` | 9732060 |
| `eddacraft-anvil-aarch64-pc-windows-msvc.zip` | `3722e3915b33babd87930696e3bcc1a187d6bd097f7def34f212281ce4acf7bd` | 15829948 |
| `eddacraft-anvil-aarch64-unknown-linux-gnu.tar.xz` | `7e23a7bc0c832b245084a4cd427114eba3c5b606495e9b0a20b085b4839f2252` | 9928596 |
| `eddacraft-anvil-installer.ps1` | `6e4460e8dd3379ea121376982414bb9f386ae87340a5d87cf51b976fe2b9e54f` | 25409 |
| `eddacraft-anvil-installer.sh` | `41cbf8c7e73cbd74666f4d0a70d3649b86287a7dee0f5d9ac5a5e47d4da92003` | 55386 |
| `eddacraft-anvil-x86_64-apple-darwin.tar.xz` | `c0a19420ba5df23745f2b6737920eb25be04da2ec11ee01595bef07a09ccd691` | 10921764 |
| `eddacraft-anvil-x86_64-pc-windows-msvc.zip` | `14a7fc30a4aa4d7e6b700a3914998bc03d7f122309a04d54526f06ced15dc399` | 16855823 |
| `eddacraft-anvil-x86_64-unknown-linux-gnu.tar.xz` | `55bd25d9da79ca96b3c49d1ec832d2f50854cd19ca87c8c1c56b92b2120c6b04` | 11225640 |
| `eddacraft-anvil.rb` | `7e276a888f9e575a4c4c84ac6b0964359c92c0aebb31bcaf4d2a9bf6cc3559ae` | 2505 |
| `sha256.sum` | `56b3cc68019c437e371d449b758ef85ae4ab261725fc6b9b7e8a4a40ca5a2930` | 748 |
| `source.tar.gz` | `389d9907be02fbe38b55a26eea5cc4ea775649cf79b0c5e63a59468e2abeb920` | 14686608 |

## Verifying an artefact

Download an artefact from the [release page](https://github.com/eddacraft/anvil/releases/tag/v0.9.7-beta) and compare
its digest against the table above:

```sh
sha256sum <downloaded-file>
```

The digests here, the per-artefact `.sha256` sidecars on the release, and
the signed `anvil-v0.9.7-beta-provenance.json` all agree by construction.

---

_Auto-generated from the signed build-provenance manifest (CIB-034). It
deliberately omits raw logs, secrets, internal hostnames, private workflow
URLs, and private development detail._
