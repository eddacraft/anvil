# Release evidence — v0.12.0-beta

A sanitised, public trust record for the `v0.12.0-beta` release of Anvil.
Anvil's source is private; this evidence proves the artefacts listed below
are the exact build published under the public `v0.12.0-beta` release. It
is generated automatically at release time from the signed build-provenance
manifest.

| Field | Value |
| --- | --- |
| Version | `0.12.0-beta` |
| Tag | `v0.12.0-beta` |
| Source revision | `fa60ebf1bdf0504dcaac12db58eef52db0fd226e` |
| Public release | [`eddacraft/anvil`](https://github.com/eddacraft/anvil/releases/tag/v0.12.0-beta) |
| Public ref at publish | `bea54b89d46b729419d23371f0b8ae0e273c5097` |
| Built (UTC) | 2026-09-23T11:49:18Z |
| Artefacts | 13 |

## Validation

All blocking release gates passed for `v0.12.0-beta` on the readiness run before
publication. The full machine-readable build provenance — including the
gating workflow run and the build matrix — is the signed
`anvil-v0.12.0-beta-provenance.json` published alongside this evidence; this
document is its human-readable, sanitised summary.

## Artefacts

Each shipped artefact with its SHA-256 digest, computed at build time.

| Artefact | SHA-256 | Size (bytes) |
| --- | --- | --- |
| `anvil-icon-256.png` | `6a79d63f58210c7467159b414f6ddac5a7d545a0a5b3b90e6728535dc988778c` | 3876 |
| `anvil.rb` | `4c5310f5f493dd8827f7a210dfb46bf73060943ec44863955c0983635fb6075e` | 2501 |
| `dist-manifest.json` | `024480c1b118ce6ff3e4a78feff1f6fe22c73bf8e17924610b66bc353586180a` | 38640 |
| `eddacraft-anvil-aarch64-apple-darwin.tar.xz` | `0dd5eb77bc86e167ce6ac3b57c2701e447da6aff09f7f06f5c6c3ffd95fa5d99` | 10563392 |
| `eddacraft-anvil-aarch64-pc-windows-msvc.zip` | `c5a0ea0dbec17dc2734444f28eeca942d7ea26c055d3932291a77b31b7fb4650` | 17410601 |
| `eddacraft-anvil-aarch64-unknown-linux-gnu.tar.xz` | `134c987221b593d8c60a9909caa579301d295c623b8045de93c6f1b40085e0d9` | 10783972 |
| `eddacraft-anvil-installer.ps1` | `80d6ead39edd34f318e72ad4143a5992c41adef042b7a9604756ab72a522f32c` | 25414 |
| `eddacraft-anvil-installer.sh` | `eec2ebcf37d140080007a8dab5e81d97279d348fabc3b460e33e6e01dc1e2037` | 55393 |
| `eddacraft-anvil-x86_64-apple-darwin.tar.xz` | `f042415cf8f637c5b2adaebad9c40d19e32259f62fd6b01b5f58f7b273f2c42a` | 11904568 |
| `eddacraft-anvil-x86_64-pc-windows-msvc.zip` | `707082c21dc1fdd8340ae0031bd71c3b3fcac57e10b149f75cddd31a573c5ea9` | 18545850 |
| `eddacraft-anvil-x86_64-unknown-linux-gnu.tar.xz` | `b4ccb9d3ad6c6f10bbaaea672b91ee6de963b9f0e7b340349f4f1bda04418128` | 12228400 |
| `sha256.sum` | `1f9a3e4a99a07d9c1e7c17df10a001a07fc823a0e2836f245a78a954b12096e4` | 748 |
| `source.tar.gz` | `29a82e23d2067ce4c9d24ddb40ab3ac16a04ed2f1ea948e5e3767c4240880f27` | 17331025 |

## Verifying an artefact

Download an artefact from the [release page](https://github.com/eddacraft/anvil/releases/tag/v0.12.0-beta) and compare
its digest against the table above:

```sh
sha256sum <downloaded-file>
```

The digests here, the per-artefact `.sha256` sidecars on the release, and
the signed `anvil-v0.12.0-beta-provenance.json` all agree by construction.

---

_Auto-generated from the signed build-provenance manifest (CIB-034). It
deliberately omits raw logs, secrets, internal hostnames, private workflow
URLs, and private development detail._
