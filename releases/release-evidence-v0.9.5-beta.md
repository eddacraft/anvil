# Release evidence — v0.9.5-beta

A sanitised, public trust record for the `v0.9.5-beta` release of Anvil.
Anvil's source is private; this evidence proves the artefacts listed below
are the exact build published under the public `v0.9.5-beta` release. It
is generated automatically at release time from the signed build-provenance
manifest.

| Field | Value |
| --- | --- |
| Version | `0.9.5-beta` |
| Tag | `v0.9.5-beta` |
| Source revision | `5c4b61a78dc75bbcbb09d21f97c53165abdc893a` |
| Public release | [`eddacraft/anvil`](https://github.com/eddacraft/anvil/releases/tag/v0.9.5-beta) |
| Public ref at publish | `0d2e766f51d387f2a082d860f92cc8c6813beb2d` |
| Built (UTC) | 2026-08-16T23:02:05Z |
| Artefacts | 13 |

## Validation

All blocking release gates passed for `v0.9.5-beta` on the readiness run before
publication. The full machine-readable build provenance — including the
gating workflow run and the build matrix — is the signed
`anvil-v0.9.5-beta-provenance.json` published alongside this evidence; this
document is its human-readable, sanitised summary.

## Artefacts

Each shipped artefact with its SHA-256 digest, computed at build time.

| Artefact | SHA-256 | Size (bytes) |
| --- | --- | --- |
| `anvil-icon-256.png` | `6a79d63f58210c7467159b414f6ddac5a7d545a0a5b3b90e6728535dc988778c` | 3876 |
| `dist-manifest.json` | `d058f2be804d411f0ce0bc32d4ffdeb4c228f564522c7ca9f27993f90e5c1bfd` | 27967 |
| `eddacraft-anvil-aarch64-apple-darwin.tar.xz` | `9fd994c814c43e589c0672fbba4bb7631ddcc6ba44fa8b3071b13fef04c858d7` | 9700524 |
| `eddacraft-anvil-aarch64-pc-windows-msvc.zip` | `24da07698ff007effdc6b83c5197cab76a97a4352db8937d791df076a483b91f` | 15803754 |
| `eddacraft-anvil-aarch64-unknown-linux-gnu.tar.xz` | `548eac0a4120c753dce99e32e37b7236ace46cdd0c8e7e9e539b48cad9938a7a` | 9899256 |
| `eddacraft-anvil-installer.ps1` | `9173a49028f0afe704bb69c35e043561f961d23184278a387444ed56d4ee95e5` | 25409 |
| `eddacraft-anvil-installer.sh` | `b8155b81ac4469a13635ee377a331b555395349076b852d47f8b9533f691b1df` | 55386 |
| `eddacraft-anvil-x86_64-apple-darwin.tar.xz` | `95154fe6bc6b5ccf43eb5ed855bec19f7fc81725d1ffa0ed84e411d1bb4bc173` | 10893532 |
| `eddacraft-anvil-x86_64-pc-windows-msvc.zip` | `7131113328d9308b6acc1d435e2991ae83e8ba8bec8c7011f12f7c944f0dbd93` | 16821088 |
| `eddacraft-anvil-x86_64-unknown-linux-gnu.tar.xz` | `37637e8619146a41ee90e251c0415552d101d925181621d4afec44171727d80a` | 11194752 |
| `eddacraft-anvil.rb` | `aaf9719fa50e9fa0796a13bef4b23c6f53e4b09dd0dc51dd868d13e9a548ec0d` | 2505 |
| `sha256.sum` | `22bdaf9e6d1570ba71a5e974b2b571b0a2da4da54e8d50ebc8113e8f0149e0f9` | 748 |
| `source.tar.gz` | `0204dc57456d7f19c64e165d0c8684b72b696a12ad31e948782df60e2b329558` | 14531917 |

## Verifying an artefact

Download an artefact from the [release page](https://github.com/eddacraft/anvil/releases/tag/v0.9.5-beta) and compare
its digest against the table above:

```sh
sha256sum <downloaded-file>
```

The digests here, the per-artefact `.sha256` sidecars on the release, and
the signed `anvil-v0.9.5-beta-provenance.json` all agree by construction.

---

_Auto-generated from the signed build-provenance manifest (CIB-034). It
deliberately omits raw logs, secrets, internal hostnames, private workflow
URLs, and private development detail._
