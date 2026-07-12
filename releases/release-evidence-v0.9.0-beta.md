# Release evidence — v0.9.0-beta

A sanitised, public trust record for the `v0.9.0-beta` release of Anvil.
Anvil's source is private; this evidence proves the artefacts listed below
are the exact build published under the public `v0.9.0-beta` release. It
is generated automatically at release time from the signed build-provenance
manifest.

| Field | Value |
| --- | --- |
| Version | `0.9.0-beta` |
| Tag | `v0.9.0-beta` |
| Source revision | `6b0ed1d1d7d7662d1033403ae6291d907afe262d` |
| Public release | [`eddacraft/anvil`](https://github.com/eddacraft/anvil/releases/tag/v0.9.0-beta) |
| Public ref at publish | `0a8c93a364d651776ddfc063608340793cb7b6ec` |
| Built (UTC) | 2026-07-12T17:06:41Z |
| Artefacts | 13 |

## Validation

All blocking release gates passed for `v0.9.0-beta` on the readiness run before
publication. The full machine-readable build provenance — including the
gating workflow run and the build matrix — is the signed
`anvil-v0.9.0-beta-provenance.json` published alongside this evidence; this
document is its human-readable, sanitised summary.

## Artefacts

Each shipped artefact with its SHA-256 digest, computed at build time.

| Artefact | SHA-256 | Size (bytes) |
| --- | --- | --- |
| `anvil-icon-256.png` | `6a79d63f58210c7467159b414f6ddac5a7d545a0a5b3b90e6728535dc988778c` | 3876 |
| `dist-manifest.json` | `dd96a553ca8c32b6e5a8f9b1fb590ab01e0334299cc1cec8d6e90de1b7b0da74` | 27967 |
| `eddacraft-anvil-aarch64-apple-darwin.tar.xz` | `3e68f54f1b15335863106631def7f23f06acbde548011af3e91b34f7889d18e7` | 8394228 |
| `eddacraft-anvil-aarch64-pc-windows-msvc.zip` | `482247c9cbcd6c84d72ea49be7cba73fbdafdbf1442834221b55c5ceb1b45e48` | 13809305 |
| `eddacraft-anvil-aarch64-unknown-linux-gnu.tar.xz` | `5a4e35d717c97260b6eb892080cbfa51306252d0c7bea0de0503e1a3cf74637a` | 8582512 |
| `eddacraft-anvil-installer.ps1` | `dfe078b86dbcf824361e1eee5d0cc6b851eb3c6a070dd234c0f0286f686f5762` | 22081 |
| `eddacraft-anvil-installer.sh` | `5d7deef97bc8072b8ff737a7ebdc31174c298b6720287d67f4c0871bed00730b` | 55386 |
| `eddacraft-anvil-x86_64-apple-darwin.tar.xz` | `a25133d211c8d74c70e3feb84c169ab71dbdf614a9770c874b82148477ffbd7e` | 9488672 |
| `eddacraft-anvil-x86_64-pc-windows-msvc.zip` | `1454063c60bf36d3f3f521b6c19514793a5b3691006028d95cc66678caef9c51` | 14598617 |
| `eddacraft-anvil-x86_64-unknown-linux-gnu.tar.xz` | `ddffd0a673bbfccc234ac99e3b8fb563407af0f28ef46c00f53c8fdefbdf89c9` | 9763328 |
| `eddacraft-anvil.rb` | `a76d77b5c9911b259e48bc718a81b0091f6b3ead82a8076dda4db3897a5041af` | 2505 |
| `sha256.sum` | `960cb506f08b1de1fd97687425887312ba5a788cb5faa3e0ef461848b7b66cb2` | 748 |
| `source.tar.gz` | `76c015827cf23f6475fa216ed9260eb9d1a49a99eb9026fd534926fa6084ee82` | 12738522 |

## Verifying an artefact

Download an artefact from the [release page](https://github.com/eddacraft/anvil/releases/tag/v0.9.0-beta) and compare
its digest against the table above:

```sh
sha256sum <downloaded-file>
```

The digests here, the per-artefact `.sha256` sidecars on the release, and
the signed `anvil-v0.9.0-beta-provenance.json` all agree by construction.

---

_Auto-generated from the signed build-provenance manifest (CIB-034). It
deliberately omits raw logs, secrets, internal hostnames, private workflow
URLs, and private development detail._
