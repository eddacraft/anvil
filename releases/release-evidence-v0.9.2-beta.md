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
| Source revision | `22f6a9bec8df7008bd4b58d8b8db0ccc84497ca0` |
| Public release | [`eddacraft/anvil`](https://github.com/eddacraft/anvil/releases/tag/v0.9.2-beta) |
| Public ref at publish | `5b8273a7880f8e4cd67fcbfa04742c14ad9cfe20` |
| Built (UTC) | 2026-08-03T18:46:42Z |
| Artefacts | 13 |

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
| `dist-manifest.json` | `53a067f13462a53059fc39729cf292d946348c2b03bf273aba76bc4bb2ad500a` | 27967 |
| `eddacraft-anvil-aarch64-apple-darwin.tar.xz` | `708953f7bc14eb73bb5f39279612e915bdd2546454d7570b1d89f21bb8f8b5d2` | 9318848 |
| `eddacraft-anvil-aarch64-pc-windows-msvc.zip` | `9a089043d9f5be8e796ce3c298a202e2194acdb2f43507de76a3dd7f9de92be2` | 15137594 |
| `eddacraft-anvil-aarch64-unknown-linux-gnu.tar.xz` | `a955bdf079a0021bc947283785e3d6db054989116e5a2cc92c13c6759827507c` | 9518228 |
| `eddacraft-anvil-installer.ps1` | `87b772fcff163c4a18c29385f3f663a974988daacc3fba169eca1220cdb9228e` | 24873 |
| `eddacraft-anvil-installer.sh` | `7938b0e36c3b6a40f31977213fd1ebd50c1f9a462a8708ae3ac1773e928486bf` | 55386 |
| `eddacraft-anvil-x86_64-apple-darwin.tar.xz` | `1f16d88232b21d7afc838c7a9bbf3478e810226bf4c1c3eb8e7094df9e89fbf7` | 10453248 |
| `eddacraft-anvil-x86_64-pc-windows-msvc.zip` | `5b95a3a5b7853af9ce3d8cced0a3887235405fe4ed4dea938b43dca0f13c4b84` | 16081450 |
| `eddacraft-anvil-x86_64-unknown-linux-gnu.tar.xz` | `269fff77cf10c53b9cb3330fa13713fce54b9cfc3380aa57edee4acbcf1d1b3d` | 10737004 |
| `eddacraft-anvil.rb` | `b63180bb9eaf13f4ca76817744cac8459715e29c6842cfc738d0a70819681d5b` | 2505 |
| `sha256.sum` | `783bde78b21b925de7e28cc4e1f98ea6b5d48ff4fe49fb875325934a9ed1091f` | 748 |
| `source.tar.gz` | `3635ddef29d855cd5e896027d32eb3f43f990dbc335e90da417fb13340c979ff` | 12946421 |

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
