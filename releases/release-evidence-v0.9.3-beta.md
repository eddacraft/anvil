# Release evidence — v0.9.3-beta

A sanitised, public trust record for the `v0.9.3-beta` release of Anvil.
Anvil's source is private; this evidence proves the artefacts listed below
are the exact build published under the public `v0.9.3-beta` release. It
is generated automatically at release time from the signed build-provenance
manifest.

| Field | Value |
| --- | --- |
| Version | `0.9.3-beta` |
| Tag | `v0.9.3-beta` |
| Source revision | `cfe0857cb63692103553686a29fb3a646502c75c` |
| Public release | [`eddacraft/anvil`](https://github.com/eddacraft/anvil/releases/tag/v0.9.3-beta) |
| Public ref at publish | `8907de92141a9e0aa6224a6b45cb7ecde0b764e2` |
| Built (UTC) | 2026-08-07T20:39:31Z |
| Artefacts | 13 |

## Validation

All blocking release gates passed for `v0.9.3-beta` on the readiness run before
publication. The full machine-readable build provenance — including the
gating workflow run and the build matrix — is the signed
`anvil-v0.9.3-beta-provenance.json` published alongside this evidence; this
document is its human-readable, sanitised summary.

## Artefacts

Each shipped artefact with its SHA-256 digest, computed at build time.

| Artefact | SHA-256 | Size (bytes) |
| --- | --- | --- |
| `anvil-icon-256.png` | `6a79d63f58210c7467159b414f6ddac5a7d545a0a5b3b90e6728535dc988778c` | 3876 |
| `dist-manifest.json` | `a27398dddc61e9a037c1cb7ace9d24699abf679ec0234d0268118454078be1b8` | 27967 |
| `eddacraft-anvil-aarch64-apple-darwin.tar.xz` | `3e4092d1e9190dc84cca4ec70ace8929f8690514fb0d4c6bf18eb557fe842c5c` | 9427504 |
| `eddacraft-anvil-aarch64-pc-windows-msvc.zip` | `e8f66a9f919d1806e3213f21dbfaf22c3be63f8f016b00df5c4785bca56f9366` | 15350615 |
| `eddacraft-anvil-aarch64-unknown-linux-gnu.tar.xz` | `e11f9040e1cb6cd1dfca58cb295d9cc2bf3ea20882b44b63e5beee9bd7ceae66` | 9622568 |
| `eddacraft-anvil-installer.ps1` | `0acb73d38210c3e52ee62d2ebedb38bd3d795218c1b0674fcb4b3dd03636e9bf` | 25084 |
| `eddacraft-anvil-installer.sh` | `b66d5659cd25c024e4ad056556ad4a71cb0f7d3ff47305d89751b1955cc1f0eb` | 55386 |
| `eddacraft-anvil-x86_64-apple-darwin.tar.xz` | `7b2b35ca3c762e3099885cb9d7ee6f20fe8a5ca3653f56d163c5d850570661f5` | 10588796 |
| `eddacraft-anvil-x86_64-pc-windows-msvc.zip` | `1f95f590f3cf078aa29fa14946fd4c2b220f5c2fcd6cf09149843d9e14a59874` | 16319905 |
| `eddacraft-anvil-x86_64-unknown-linux-gnu.tar.xz` | `c10d31d8d4b2880e0fef9de20adeffb7f1e29af0969a74ec83a85de379734dc1` | 10874824 |
| `eddacraft-anvil.rb` | `95180cd3071d5ba7246c550f84546f61e0ebfbbc9f3de3c3ddd053603e14051a` | 2505 |
| `sha256.sum` | `603859d57e9e23933d0b3fa200e9cd7a148f7e371473801fc8724e7c933da547` | 748 |
| `source.tar.gz` | `51d2b4ccbb0cfa6c7961768cf1e086a95ca0ec71b1800cbc410fd986c0ce2f02` | 13544658 |

## Verifying an artefact

Download an artefact from the [release page](https://github.com/eddacraft/anvil/releases/tag/v0.9.3-beta) and compare
its digest against the table above:

```sh
sha256sum <downloaded-file>
```

The digests here, the per-artefact `.sha256` sidecars on the release, and
the signed `anvil-v0.9.3-beta-provenance.json` all agree by construction.

---

_Auto-generated from the signed build-provenance manifest (CIB-034). It
deliberately omits raw logs, secrets, internal hostnames, private workflow
URLs, and private development detail._
