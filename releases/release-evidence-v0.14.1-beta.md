# Release evidence — v0.14.1-beta

A sanitised, public trust record for the `v0.14.1-beta` release of Anvil.
Anvil's source is private; this evidence proves the artefacts listed below
are the exact build published under the public `v0.14.1-beta` release. It
is generated automatically at release time from the signed build-provenance
manifest.

| Field | Value |
| --- | --- |
| Version | `0.14.1-beta` |
| Tag | `v0.14.1-beta` |
| Source revision | `cf23a32a0a8510fbdd1494d38c28c25064f24242` |
| Public release | [`eddacraft/anvil`](https://github.com/eddacraft/anvil/releases/tag/v0.14.1-beta) |
| Public ref at publish | `852b60deec2dc70295fb68451b1fafeefe3328ef` |
| Built (UTC) | 2026-10-04T10:55:30Z |
| Artefacts | 13 |

## Validation

All blocking release gates passed for `v0.14.1-beta` on the readiness run before
publication. The full machine-readable build provenance — including the
gating workflow run and the build matrix — is the signed
`anvil-v0.14.1-beta-provenance.json` published alongside this evidence; this
document is its human-readable, sanitised summary.

## Artefacts

Each shipped artefact with its SHA-256 digest, computed at build time.

| Artefact | SHA-256 | Size (bytes) |
| --- | --- | --- |
| `anvil-icon-256.png` | `6a79d63f58210c7467159b414f6ddac5a7d545a0a5b3b90e6728535dc988778c` | 3876 |
| `anvil.rb` | `b3b1a301e9b5b41249c0d9facab2dad23661031046511313971bed2632831bda` | 2501 |
| `dist-manifest.json` | `5a0ee3798aae6cc17875a97c115b424cdb446d929dac5305e3d46862817bd12f` | 35523 |
| `eddacraft-anvil-aarch64-apple-darwin.tar.xz` | `6d5050611a4409826bed77449006101b985e2d34b1a657d5ea7550fd3c7cf4d6` | 10786732 |
| `eddacraft-anvil-aarch64-pc-windows-msvc.zip` | `82cae1f3a2ba14520bf86269b51ebe097425a226f91d59c67e36f8e066bc9f27` | 18000223 |
| `eddacraft-anvil-aarch64-unknown-linux-gnu.tar.xz` | `4b2ff8fa74a5c21646bf0ffcd29533dc69f01c073211e720db360c8a08e9e659` | 11001892 |
| `eddacraft-anvil-installer.ps1` | `3db2c4f9e93270e02fa2a81226334e473b373e917c55d3f433a97176506e0b83` | 25470 |
| `eddacraft-anvil-installer.sh` | `d1375a11c43b17af77dd1721415a9a739706ee740a05ff2ab545eefaacc1549a` | 55441 |
| `eddacraft-anvil-x86_64-apple-darwin.tar.xz` | `d4d387164ed421cc8c2b5719d0fa49cf624190b5dd85bd36a9d8fb2e4b0028bd` | 12149880 |
| `eddacraft-anvil-x86_64-pc-windows-msvc.zip` | `65d93c720aa677d29aacbd3248ad16d6462c5cbd4e6b488ef25fe1d1db976c45` | 19194398 |
| `eddacraft-anvil-x86_64-unknown-linux-gnu.tar.xz` | `aacf33985d0129c8ba9d3195e73234c77c60a139cf2bdfe77a3d8fcb64107c6a` | 12472372 |
| `sha256.sum` | `1842b6e2143600bb0e56767d8615b080a4c0bcfec01680d8ac0e19cd15e5eb31` | 748 |
| `source.tar.gz` | `f859df12e3988d28e69300c4d7cbb3369f20a5a3d1b56952bc4ca11716d38fa6` | 20043126 |

## Verifying an artefact

Download an artefact from the [release page](https://github.com/eddacraft/anvil/releases/tag/v0.14.1-beta) and compare
its digest against the table above:

```sh
sha256sum <downloaded-file>
```

The digests here, the per-artefact `.sha256` sidecars on the release, and
the signed `anvil-v0.14.1-beta-provenance.json` all agree by construction.

---

_Auto-generated from the signed build-provenance manifest (CIB-034). It
deliberately omits raw logs, secrets, internal hostnames, private workflow
URLs, and private development detail._
