# Release evidence — v0.9.1-beta

A sanitised, public trust record for the `v0.9.1-beta` release of Anvil.
Anvil's source is private; this evidence proves the artefacts listed below
are the exact build published under the public `v0.9.1-beta` release. It
is generated automatically at release time from the signed build-provenance
manifest.

| Field | Value |
| --- | --- |
| Version | `0.9.1-beta` |
| Tag | `v0.9.1-beta` |
| Source revision | `6a97118866b388208d0221584e1253bf99d6fd89` |
| Public release | [`eddacraft/anvil`](https://github.com/eddacraft/anvil/releases/tag/v0.9.1-beta) |
| Public ref at publish | `ca1c4ff8e5503643d1d4c3860069bd1c584f9c0f` |
| Built (UTC) | 2026-08-02T12:41:06Z |
| Artefacts | 13 |

## Validation

All blocking release gates passed for `v0.9.1-beta` on the readiness run before
publication. The full machine-readable build provenance — including the
gating workflow run and the build matrix — is the signed
`anvil-v0.9.1-beta-provenance.json` published alongside this evidence; this
document is its human-readable, sanitised summary.

## Artefacts

Each shipped artefact with its SHA-256 digest, computed at build time.

| Artefact | SHA-256 | Size (bytes) |
| --- | --- | --- |
| `anvil-icon-256.png` | `6a79d63f58210c7467159b414f6ddac5a7d545a0a5b3b90e6728535dc988778c` | 3876 |
| `dist-manifest.json` | `2292092e6611795e4d78d5aed94690d29e802ef71b73b7d06ee4ac6abcf19a4a` | 27967 |
| `eddacraft-anvil-aarch64-apple-darwin.tar.xz` | `c89b3307eb4ddb129625075c5c9daa509595cdc55055b5d0d0692ef195aae587` | 9316756 |
| `eddacraft-anvil-aarch64-pc-windows-msvc.zip` | `45de74c45334df60a78ce768d2df43aa10cd1550fbccad5f56f5359c6680fc41` | 15126817 |
| `eddacraft-anvil-aarch64-unknown-linux-gnu.tar.xz` | `73bb3d70defe711dc52792cbf20aae1d3347ffc620582371965a2653762bfcbb` | 9513032 |
| `eddacraft-anvil-installer.ps1` | `29a9899b31902fa8511f353f515d24b6589eaabd0b6477515251df27117ce5b4` | 24873 |
| `eddacraft-anvil-installer.sh` | `e609fb1b175bb047fb3e86d801b320941c6605a4ce1810c33238fbb35223dcea` | 55386 |
| `eddacraft-anvil-x86_64-apple-darwin.tar.xz` | `af42c4828c48e1e964acf8462ab68544f451672f9a77ca6fbaf31cda83b70324` | 10448516 |
| `eddacraft-anvil-x86_64-pc-windows-msvc.zip` | `b784f2503db0fd0e869041af38b35fd28d9da9e66d4775a7a5dd216cbe21993d` | 16067099 |
| `eddacraft-anvil-x86_64-unknown-linux-gnu.tar.xz` | `4a100ff1956f408f7e871eeda603cd99c4a3a8990abf19b6a26b0b0653faa3fc` | 10736156 |
| `eddacraft-anvil.rb` | `204c23f58a2e5b0932980ed888db7ecfc08156c2176c7281dc625931b7f7f6e7` | 2505 |
| `sha256.sum` | `ba7e4be0038959754d1bb6520973a7c499f46a7dc0e3ee0fd66adeeff9ae8460` | 748 |
| `source.tar.gz` | `4bbe5bcae4160d75ab1877cd8025ee4660fcc4647eab3f3b708b5c0c14877eba` | 12883212 |

## Verifying an artefact

Download an artefact from the [release page](https://github.com/eddacraft/anvil/releases/tag/v0.9.1-beta) and compare
its digest against the table above:

```sh
sha256sum <downloaded-file>
```

The digests here, the per-artefact `.sha256` sidecars on the release, and
the signed `anvil-v0.9.1-beta-provenance.json` all agree by construction.

---

_Auto-generated from the signed build-provenance manifest (CIB-034). It
deliberately omits raw logs, secrets, internal hostnames, private workflow
URLs, and private development detail._
