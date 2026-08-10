# Release evidence — v0.9.4-beta

A sanitised, public trust record for the `v0.9.4-beta` release of Anvil.
Anvil's source is private; this evidence proves the artefacts listed below
are the exact build published under the public `v0.9.4-beta` release. It
is generated automatically at release time from the signed build-provenance
manifest.

| Field | Value |
| --- | --- |
| Version | `0.9.4-beta` |
| Tag | `v0.9.4-beta` |
| Source revision | `165d33dfbb7b7ae33381118bedd4635238a878c5` |
| Public release | [`eddacraft/anvil`](https://github.com/eddacraft/anvil/releases/tag/v0.9.4-beta) |
| Public ref at publish | `fb50127393817b04fdb6900cea002445eb7d604b` |
| Built (UTC) | 2026-08-10T08:54:36Z |
| Artefacts | 13 |

## Validation

All blocking release gates passed for `v0.9.4-beta` on the readiness run before
publication. The full machine-readable build provenance — including the
gating workflow run and the build matrix — is the signed
`anvil-v0.9.4-beta-provenance.json` published alongside this evidence; this
document is its human-readable, sanitised summary.

## Artefacts

Each shipped artefact with its SHA-256 digest, computed at build time.

| Artefact | SHA-256 | Size (bytes) |
| --- | --- | --- |
| `anvil-icon-256.png` | `6a79d63f58210c7467159b414f6ddac5a7d545a0a5b3b90e6728535dc988778c` | 3876 |
| `dist-manifest.json` | `1a2be059c81f47cd8a6f4c8a0ee94af58a957307ef5b32d40cb867c6119c905b` | 27967 |
| `eddacraft-anvil-aarch64-apple-darwin.tar.xz` | `0ef290e489b4ed2cca163f9d9cdcea40654b024fc7cb475e1c9f5e2d4d952b27` | 9433232 |
| `eddacraft-anvil-aarch64-pc-windows-msvc.zip` | `d60c9e14274aaea39413bb800ecd0464c2076287866d0a18b418774baf1cc8fd` | 15356252 |
| `eddacraft-anvil-aarch64-unknown-linux-gnu.tar.xz` | `3ec84a7d93b4436733fd140046c73359bf65d48da58071955df4cd9ba86f0564` | 9624796 |
| `eddacraft-anvil-installer.ps1` | `41fdacb16f8888bc0a94bd86f73647d6b0517887668d45069cd5153c760dc38c` | 25216 |
| `eddacraft-anvil-installer.sh` | `d9e0b4fdcdde4bdce9f9ce9aef275110c26344e60016a3ffe7ae68be12b87ffd` | 55386 |
| `eddacraft-anvil-x86_64-apple-darwin.tar.xz` | `0d05be3acc891bfea2d9e0fc14429874d2976c347abd3421b72286b417205b90` | 10594332 |
| `eddacraft-anvil-x86_64-pc-windows-msvc.zip` | `d6a7ccea24c05dbcb8e2a158aea6652801d0a3f387b72509cf495453031da769` | 16326291 |
| `eddacraft-anvil-x86_64-unknown-linux-gnu.tar.xz` | `4c9a70487e4d91e9978a9a32e763cea9eb8d30ebbfe21a624e3264cff280e228` | 10880520 |
| `eddacraft-anvil.rb` | `f50030e78874f0b9585dcee715c709f52b36d330298ab992bb00979b33593603` | 2505 |
| `sha256.sum` | `366126d78690ed57ad3cbddefde077d642a58f2b809a779a4bc11dee8b83a036` | 748 |
| `source.tar.gz` | `41e83b16e6f130208b710f857925c19ea7133616efed248afff3b077e5a6f2d5` | 13610088 |

## Verifying an artefact

Download an artefact from the [release page](https://github.com/eddacraft/anvil/releases/tag/v0.9.4-beta) and compare
its digest against the table above:

```sh
sha256sum <downloaded-file>
```

The digests here, the per-artefact `.sha256` sidecars on the release, and
the signed `anvil-v0.9.4-beta-provenance.json` all agree by construction.

---

_Auto-generated from the signed build-provenance manifest (CIB-034). It
deliberately omits raw logs, secrets, internal hostnames, private workflow
URLs, and private development detail._
