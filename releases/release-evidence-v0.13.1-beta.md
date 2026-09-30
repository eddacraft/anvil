# Release evidence — v0.13.1-beta

A sanitised, public trust record for the `v0.13.1-beta` release of Anvil.
Anvil's source is private; this evidence proves the artefacts listed below
are the exact build published under the public `v0.13.1-beta` release. It
is generated automatically at release time from the signed build-provenance
manifest.

| Field | Value |
| --- | --- |
| Version | `0.13.1-beta` |
| Tag | `v0.13.1-beta` |
| Source revision | `c50fca08d38dfc0154fc0698677db6733dedce6a` |
| Public release | [`eddacraft/anvil`](https://github.com/eddacraft/anvil/releases/tag/v0.13.1-beta) |
| Public ref at publish | `f9c8c18ad1dba5e7e46da947399f228f918fc704` |
| Built (UTC) | 2026-09-30T18:05:53Z |
| Artefacts | 13 |

## Validation

All blocking release gates passed for `v0.13.1-beta` on the readiness run before
publication. The full machine-readable build provenance — including the
gating workflow run and the build matrix — is the signed
`anvil-v0.13.1-beta-provenance.json` published alongside this evidence; this
document is its human-readable, sanitised summary.

## Artefacts

Each shipped artefact with its SHA-256 digest, computed at build time.

| Artefact | SHA-256 | Size (bytes) |
| --- | --- | --- |
| `anvil-icon-256.png` | `6a79d63f58210c7467159b414f6ddac5a7d545a0a5b3b90e6728535dc988778c` | 3876 |
| `anvil.rb` | `acf3178d4e87ab09817bcdb1b59c2c5c8d1c267eba1ebf13505c38328ae13a33` | 2501 |
| `dist-manifest.json` | `245f0b38edfbc0d7570671796edae9e7520802da99f5f22cea6d70eacb3f66b7` | 32742 |
| `eddacraft-anvil-aarch64-apple-darwin.tar.xz` | `e4acd0fbb51c973e47e13bbd9fead09ccba59fd0a0d4bc534d07ef0d010286d8` | 10651868 |
| `eddacraft-anvil-aarch64-pc-windows-msvc.zip` | `12e10421ee14c884a55ceb0a36d4c593028567e54bce84966c49bd72af0bd54d` | 17746910 |
| `eddacraft-anvil-aarch64-unknown-linux-gnu.tar.xz` | `4d301bbc65f1a10c0f8c2fe7890ed91091a9a3c4893c3d706fa420ab5c7e33cb` | 10879776 |
| `eddacraft-anvil-installer.ps1` | `82435fd13c302771606f2006522e12773d4fe183ed7fdb40481c71e7bb6d401b` | 25470 |
| `eddacraft-anvil-installer.sh` | `e64ca4b1ddaeea2f661be7dff75f2411a9cbe46ff86cf8cec66905750762c0cd` | 55441 |
| `eddacraft-anvil-x86_64-apple-darwin.tar.xz` | `0e52999ee871026ee9d538fb2e00e9bbf1b29f0db3e79b096a7e23ddfa2a12c1` | 12014904 |
| `eddacraft-anvil-x86_64-pc-windows-msvc.zip` | `55383cbaef66563ce90ae20f18d27e335c0a8272c7a244d5a989156a79afdf9d` | 18910847 |
| `eddacraft-anvil-x86_64-unknown-linux-gnu.tar.xz` | `566623b8d26910c071161ec8f2060a2b5512baefc0a3275b1f18cc40a7c17322` | 12337676 |
| `sha256.sum` | `b3a5d8eddce06a37af4c7599696c729f3490ac32040a9acb82ccfd2e38696fe4` | 748 |
| `source.tar.gz` | `80fc09da3fd4d3f9917add17bb1d4766ffd6dfc53584dc1b09e76427d72f5c19` | 18964205 |

## Verifying an artefact

Download an artefact from the [release page](https://github.com/eddacraft/anvil/releases/tag/v0.13.1-beta) and compare
its digest against the table above:

```sh
sha256sum <downloaded-file>
```

The digests here, the per-artefact `.sha256` sidecars on the release, and
the signed `anvil-v0.13.1-beta-provenance.json` all agree by construction.

---

_Auto-generated from the signed build-provenance manifest (CIB-034). It
deliberately omits raw logs, secrets, internal hostnames, private workflow
URLs, and private development detail._
