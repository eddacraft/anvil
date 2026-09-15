# Release evidence — v0.11.0-beta

A sanitised, public trust record for the `v0.11.0-beta` release of Anvil.
Anvil's source is private; this evidence proves the artefacts listed below
are the exact build published under the public `v0.11.0-beta` release. It
is generated automatically at release time from the signed build-provenance
manifest.

| Field | Value |
| --- | --- |
| Version | `0.11.0-beta` |
| Tag | `v0.11.0-beta` |
| Source revision | `1e07021a78b1d201a77f9421229f8e79255889db` |
| Public release | [`eddacraft/anvil`](https://github.com/eddacraft/anvil/releases/tag/v0.11.0-beta) |
| Public ref at publish | `4c752954ea2002625faa5a1bd012ee59cc3ee99a` |
| Built (UTC) | 2026-09-15T04:44:32Z |
| Artefacts | 13 |

## Validation

All blocking release gates passed for `v0.11.0-beta` on the readiness run before
publication. The full machine-readable build provenance — including the
gating workflow run and the build matrix — is the signed
`anvil-v0.11.0-beta-provenance.json` published alongside this evidence; this
document is its human-readable, sanitised summary.

## Artefacts

Each shipped artefact with its SHA-256 digest, computed at build time.

| Artefact | SHA-256 | Size (bytes) |
| --- | --- | --- |
| `anvil-icon-256.png` | `6a79d63f58210c7467159b414f6ddac5a7d545a0a5b3b90e6728535dc988778c` | 3876 |
| `anvil.rb` | `3181f93201bfb0e5597fcd3e8f9a01227c9a3b7977ee63948e64d0ca617ce768` | 2501 |
| `dist-manifest.json` | `d3aa5fb656a6d3ba43f713eeec21c5accdb649ba85c982726a6205c8c8e0adb6` | 29862 |
| `eddacraft-anvil-aarch64-apple-darwin.tar.xz` | `fa4e9e796c8ff9eb18d9276640a3cad5e13ab06ba0679f6d42c2c3c224d503b9` | 10301444 |
| `eddacraft-anvil-aarch64-pc-windows-msvc.zip` | `293dd14bbe2a229432c795cbb028aaeb7ea85c96b3fe705b4dcbcf4d922bd989` | 16928575 |
| `eddacraft-anvil-aarch64-unknown-linux-gnu.tar.xz` | `b7c41c7bda97b6447f3bfa856156cb3436670b8ce3002a9be3ac3af7bdc85eea` | 10516036 |
| `eddacraft-anvil-installer.ps1` | `e87f0728f138b75bf4fe840f8060f99b0b3e5e943a02579f8af2e2fcada0a0ab` | 25414 |
| `eddacraft-anvil-installer.sh` | `6a92e617377d52a1b7d540289a9b6ffe908aa077a42fee96ad46592afa219865` | 55393 |
| `eddacraft-anvil-x86_64-apple-darwin.tar.xz` | `33178ef727272b5b84810673982a5443aadf5f70f0640236612be6ebcfa40dc5` | 11594332 |
| `eddacraft-anvil-x86_64-pc-windows-msvc.zip` | `06e47db4945eea87c0937daa0b4c54614b5fe1ef269ff22727e923c97711b93f` | 18023333 |
| `eddacraft-anvil-x86_64-unknown-linux-gnu.tar.xz` | `81411b6025663f94028a17b1ffef49d244341e2d2e202d358080d657f4c34016` | 11912600 |
| `sha256.sum` | `57277dda4ab9920459c74015cb1299f992450b98b9a2242186c830e14eaf2acc` | 748 |
| `source.tar.gz` | `f263bbe79a14799cf40c85675b0a589c5c170a502baa3996feeee9eed0ae1e5f` | 16401040 |

## Verifying an artefact

Download an artefact from the [release page](https://github.com/eddacraft/anvil/releases/tag/v0.11.0-beta) and compare
its digest against the table above:

```sh
sha256sum <downloaded-file>
```

The digests here, the per-artefact `.sha256` sidecars on the release, and
the signed `anvil-v0.11.0-beta-provenance.json` all agree by construction.

---

_Auto-generated from the signed build-provenance manifest (CIB-034). It
deliberately omits raw logs, secrets, internal hostnames, private workflow
URLs, and private development detail._
