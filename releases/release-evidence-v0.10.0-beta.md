# Release evidence — v0.10.0-beta

A sanitised, public trust record for the `v0.10.0-beta` release of Anvil.
Anvil's source is private; this evidence proves the artefacts listed below
are the exact build published under the public `v0.10.0-beta` release. It
is generated automatically at release time from the signed build-provenance
manifest.

| Field | Value |
| --- | --- |
| Version | `0.10.0-beta` |
| Tag | `v0.10.0-beta` |
| Source revision | `5ce7aa2eb416de12528820c782cf943164a633aa` |
| Public release | [`eddacraft/anvil`](https://github.com/eddacraft/anvil/releases/tag/v0.10.0-beta) |
| Public ref at publish | `2f923cd54676792af27ebfd996bd2dcc0cd3033f` |
| Built (UTC) | 2026-09-13T18:44:34Z |
| Artefacts | 13 |

## Validation

All blocking release gates passed for `v0.10.0-beta` on the readiness run before
publication. The full machine-readable build provenance — including the
gating workflow run and the build matrix — is the signed
`anvil-v0.10.0-beta-provenance.json` published alongside this evidence; this
document is its human-readable, sanitised summary.

## Artefacts

Each shipped artefact with its SHA-256 digest, computed at build time.

| Artefact | SHA-256 | Size (bytes) |
| --- | --- | --- |
| `anvil-icon-256.png` | `6a79d63f58210c7467159b414f6ddac5a7d545a0a5b3b90e6728535dc988778c` | 3876 |
| `anvil.rb` | `3508c2cc26719a1b731c46ee72b70884745b1b442effc21715fae968e7aad56f` | 2501 |
| `dist-manifest.json` | `61af5b2f0807b55aee1aea565b57b7ab37470a61561107b05254f90677e5e8ab` | 67110 |
| `eddacraft-anvil-aarch64-apple-darwin.tar.xz` | `5dbe8fc6179dc321b80fe8bfa35609e1f3756084da268a3c773c680a7ee059c5` | 10214088 |
| `eddacraft-anvil-aarch64-pc-windows-msvc.zip` | `582389f39b761dc457f07fe460de3d90340a874a2e514a7db15168b7a1e21786` | 16778446 |
| `eddacraft-anvil-aarch64-unknown-linux-gnu.tar.xz` | `d59d985e79a3490799385b686b7e5edbaa193c364f8d5e08ee16ea7506806089` | 10432404 |
| `eddacraft-anvil-installer.ps1` | `1e35dbe80f7393c2e40041471bd84b867a5be48c2ceb5726a5c8afa7aabd2d17` | 25414 |
| `eddacraft-anvil-installer.sh` | `9b345c81d86382b749f1f06028a4db08ca978ce4ef23a5a2a8789ed548b092e1` | 55393 |
| `eddacraft-anvil-x86_64-apple-darwin.tar.xz` | `00634893c1d02a710293ba19ea21b4fb397faa24c976e473aae6c510449f444c` | 11497436 |
| `eddacraft-anvil-x86_64-pc-windows-msvc.zip` | `a8b0720160ea53cdc5f626aa8253808d80fe3259ae9475a38d16e9da817f853b` | 17862704 |
| `eddacraft-anvil-x86_64-unknown-linux-gnu.tar.xz` | `fa5d59217e12c1ee8df51c76d3578261450dedc1a57cc2fb13bb719598f2794e` | 11815624 |
| `sha256.sum` | `43b23925a6378df4aa2c5e1a6a92e27e50bb341b153d2ed4b225356deac5bc21` | 748 |
| `source.tar.gz` | `cd7f7fa45ed0e1ad41c730e3ae395f9bad5483d63ced9a20e210e339cdda8c34` | 16332878 |

## Verifying an artefact

Download an artefact from the [release page](https://github.com/eddacraft/anvil/releases/tag/v0.10.0-beta) and compare
its digest against the table above:

```sh
sha256sum <downloaded-file>
```

The digests here, the per-artefact `.sha256` sidecars on the release, and
the signed `anvil-v0.10.0-beta-provenance.json` all agree by construction.

---

_Auto-generated from the signed build-provenance manifest (CIB-034). It
deliberately omits raw logs, secrets, internal hostnames, private workflow
URLs, and private development detail._
