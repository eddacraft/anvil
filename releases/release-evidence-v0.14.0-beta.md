# Release evidence — v0.14.0-beta

A sanitised, public trust record for the `v0.14.0-beta` release of Anvil.
Anvil's source is private; this evidence proves the artefacts listed below
are the exact build published under the public `v0.14.0-beta` release. It
is generated automatically at release time from the signed build-provenance
manifest.

| Field | Value |
| --- | --- |
| Version | `0.14.0-beta` |
| Tag | `v0.14.0-beta` |
| Source revision | `4f68857239775060b373f4b6ea810a716d666877` |
| Public release | [`eddacraft/anvil`](https://github.com/eddacraft/anvil/releases/tag/v0.14.0-beta) |
| Public ref at publish | `a831979fd45cff55c73a8e2f941c44168f6500b1` |
| Built (UTC) | 2026-10-03T07:24:23Z |
| Artefacts | 13 |

## Validation

All blocking release gates passed for `v0.14.0-beta` on the readiness run before
publication. The full machine-readable build provenance — including the
gating workflow run and the build matrix — is the signed
`anvil-v0.14.0-beta-provenance.json` published alongside this evidence; this
document is its human-readable, sanitised summary.

## Artefacts

Each shipped artefact with its SHA-256 digest, computed at build time.

| Artefact | SHA-256 | Size (bytes) |
| --- | --- | --- |
| `anvil-icon-256.png` | `6a79d63f58210c7467159b414f6ddac5a7d545a0a5b3b90e6728535dc988778c` | 3876 |
| `anvil.rb` | `6d444d75b76d791f7c01e3c622e027c0bca622e82055ca550d2bb5291568feca` | 2501 |
| `dist-manifest.json` | `3da2efa6cc66c9e8afb7b275dfb8816c492f95400519ad3515af5093abd1b314` | 43767 |
| `eddacraft-anvil-aarch64-apple-darwin.tar.xz` | `88a5c40e07d06e4702d0052d97a0fd4af5bf51e29242d95b5b0b141d2d46663e` | 10758360 |
| `eddacraft-anvil-aarch64-pc-windows-msvc.zip` | `9389ef0524c609202b7ea8d1a849465dbf610e0ca3d58d07444db26512629b5a` | 17969505 |
| `eddacraft-anvil-aarch64-unknown-linux-gnu.tar.xz` | `cd4dc7fd54aa6af19160c76982e5b9c47f17d937683ca768eba7051de992407e` | 10984856 |
| `eddacraft-anvil-installer.ps1` | `42828eca50dba5589fe0080d8a96be58eed39560173e07be5694518c702ad145` | 25470 |
| `eddacraft-anvil-installer.sh` | `417d25771c564f1b7e72ac3426f3629bcfa1d0915009f92f3f87e01e3ba40c0c` | 55441 |
| `eddacraft-anvil-x86_64-apple-darwin.tar.xz` | `b5515d0ef9bb4e3175de6ea2a65001fcabd3a7cd62ce1fd4e69360d54b88d043` | 12130660 |
| `eddacraft-anvil-x86_64-pc-windows-msvc.zip` | `d815a97be340dfebf42d512f20590093fcfb223fe190a67d66f6dbae9f0d4d99` | 19157293 |
| `eddacraft-anvil-x86_64-unknown-linux-gnu.tar.xz` | `8c062806800a37e293bc64dd7f5b11f88823746e123000167ab590519b21e764` | 12456052 |
| `sha256.sum` | `168107bcc70636a56abc97857059ae5446d928274282e5988cb93df2c0064548` | 748 |
| `source.tar.gz` | `1d7cf6325d77e6a8da1fe31b3d45fb417dbcbca0a44d737eaf1d9e4593783f5f` | 19334585 |

## Verifying an artefact

Download an artefact from the [release page](https://github.com/eddacraft/anvil/releases/tag/v0.14.0-beta) and compare
its digest against the table above:

```sh
sha256sum <downloaded-file>
```

The digests here, the per-artefact `.sha256` sidecars on the release, and
the signed `anvil-v0.14.0-beta-provenance.json` all agree by construction.

---

_Auto-generated from the signed build-provenance manifest (CIB-034). It
deliberately omits raw logs, secrets, internal hostnames, private workflow
URLs, and private development detail._
