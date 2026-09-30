# Release evidence — v0.13.0-beta

A sanitised, public trust record for the `v0.13.0-beta` release of Anvil.
Anvil's source is private; this evidence proves the artefacts listed below
are the exact build published under the public `v0.13.0-beta` release. It
is generated automatically at release time from the signed build-provenance
manifest.

| Field | Value |
| --- | --- |
| Version | `0.13.0-beta` |
| Tag | `v0.13.0-beta` |
| Source revision | `28f30cf200d66a2e150526436e8964fe88a95829` |
| Public release | [`eddacraft/anvil`](https://github.com/eddacraft/anvil/releases/tag/v0.13.0-beta) |
| Public ref at publish | `25541c0df0caf907a31619bb3cd479abf2298f3f` |
| Built (UTC) | 2026-09-30T03:38:53Z |
| Artefacts | 13 |

## Validation

All blocking release gates passed for `v0.13.0-beta` on the readiness run before
publication. The full machine-readable build provenance — including the
gating workflow run and the build matrix — is the signed
`anvil-v0.13.0-beta-provenance.json` published alongside this evidence; this
document is its human-readable, sanitised summary.

## Artefacts

Each shipped artefact with its SHA-256 digest, computed at build time.

| Artefact | SHA-256 | Size (bytes) |
| --- | --- | --- |
| `anvil-icon-256.png` | `6a79d63f58210c7467159b414f6ddac5a7d545a0a5b3b90e6728535dc988778c` | 3876 |
| `anvil.rb` | `c1e853850d3c44cda5c951aeef67bb821deef2ae33d0ca90811cd44ea5749910` | 2501 |
| `dist-manifest.json` | `219a9939643994a32d544d9b660e7b268d8941557cda8aab86fc05fddfc5ad53` | 49205 |
| `eddacraft-anvil-aarch64-apple-darwin.tar.xz` | `3d18a649cf58fcca394b771d0bb1f2f6f1d5339063d5af43c9ee56dca2c8829b` | 10638212 |
| `eddacraft-anvil-aarch64-pc-windows-msvc.zip` | `14e939248eed201c28a101e3b6b757e63399c6a254e79b410fa5f2ca10484aad` | 17710103 |
| `eddacraft-anvil-aarch64-unknown-linux-gnu.tar.xz` | `a7087d5f510fad5f080e419c058134e2bbb622ac6f14424824411807d2c920c8` | 10867216 |
| `eddacraft-anvil-installer.ps1` | `f9b380711d9b31d69eb0f7d619acc2123b77d91e4efe61f33a4d921466cc0b06` | 25470 |
| `eddacraft-anvil-installer.sh` | `1655dcff0e3d4ffb6353dbf29bb10c72d8023ec0a8c589cfef869991a22b2c20` | 55441 |
| `eddacraft-anvil-x86_64-apple-darwin.tar.xz` | `81000d7cd46b85dfa6c8f7e0b782e98e550ca11601e14a4f75b2d8b39d944ceb` | 11997952 |
| `eddacraft-anvil-x86_64-pc-windows-msvc.zip` | `9ca7dadd1f3a082fecce202b255db3cd7a3d9deac7c1cdd823c4a6f6573da4d9` | 18868833 |
| `eddacraft-anvil-x86_64-unknown-linux-gnu.tar.xz` | `82267287b6df72239921e4b7afab49ca7b33f7c9cedcf7f62d90136d80b97edc` | 12317768 |
| `sha256.sum` | `4daeb014c59b3303d65e72f34341ee30b6940dd7f6455e2234a7d3910fbfbb6f` | 748 |
| `source.tar.gz` | `f34ec01a50e71d6b413ef3d9fd380ff6ed86fd42c12f91c4578c57cf192ce6b4` | 18937991 |

## Verifying an artefact

Download an artefact from the [release page](https://github.com/eddacraft/anvil/releases/tag/v0.13.0-beta) and compare
its digest against the table above:

```sh
sha256sum <downloaded-file>
```

The digests here, the per-artefact `.sha256` sidecars on the release, and
the signed `anvil-v0.13.0-beta-provenance.json` all agree by construction.

---

_Auto-generated from the signed build-provenance manifest (CIB-034). It
deliberately omits raw logs, secrets, internal hostnames, private workflow
URLs, and private development detail._
