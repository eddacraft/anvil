# Release evidence — v0.9.6-beta

A sanitised, public trust record for the `v0.9.6-beta` release of Anvil.
Anvil's source is private; this evidence proves the artefacts listed below
are the exact build published under the public `v0.9.6-beta` release. It
is generated automatically at release time from the signed build-provenance
manifest.

| Field | Value |
| --- | --- |
| Version | `0.9.6-beta` |
| Tag | `v0.9.6-beta` |
| Source revision | `07cd54c3a4de1345cd9b85adf4ed06eddf7a7a16` |
| Public release | [`eddacraft/anvil`](https://github.com/eddacraft/anvil/releases/tag/v0.9.6-beta) |
| Public ref at publish | `476c983216d3aa8202994a19803d17dc0e19f5dc` |
| Built (UTC) | 2026-08-18T13:00:46Z |
| Artefacts | 13 |

## Validation

All blocking release gates passed for `v0.9.6-beta` on the readiness run before
publication. The full machine-readable build provenance — including the
gating workflow run and the build matrix — is the signed
`anvil-v0.9.6-beta-provenance.json` published alongside this evidence; this
document is its human-readable, sanitised summary.

## Artefacts

Each shipped artefact with its SHA-256 digest, computed at build time.

| Artefact | SHA-256 | Size (bytes) |
| --- | --- | --- |
| `anvil-icon-256.png` | `6a79d63f58210c7467159b414f6ddac5a7d545a0a5b3b90e6728535dc988778c` | 3876 |
| `dist-manifest.json` | `d165fa9ec32fa122ca6693299cc044579eb33ec89c25e3197a95d2d4201bc053` | 28064 |
| `eddacraft-anvil-aarch64-apple-darwin.tar.xz` | `61a6d1b63872ab5fab115ee55954164fa9884afeb5c9827430c6819ac466d372` | 9712352 |
| `eddacraft-anvil-aarch64-pc-windows-msvc.zip` | `fdf0b733ed7f295597101fbf771e9a47cffdc4b6d289d306c897b3c61160aa48` | 15808052 |
| `eddacraft-anvil-aarch64-unknown-linux-gnu.tar.xz` | `69063b44d050a193a7268d50cc912d1a63798b3114abc7d0baa3051cc7561cb1` | 9912000 |
| `eddacraft-anvil-installer.ps1` | `91ec5253840c9b715addf06e1996a7e43395cf452acecdb3aad6393405ba73f8` | 25409 |
| `eddacraft-anvil-installer.sh` | `9423a16fbd764cbd8727847ee6cbcea422a06002388f152b5de328d70cabadde` | 55386 |
| `eddacraft-anvil-x86_64-apple-darwin.tar.xz` | `3376b27c35292635b9958657e0258cc9ce59746a7f4eb74f3e5fd785938e3f4d` | 10903952 |
| `eddacraft-anvil-x86_64-pc-windows-msvc.zip` | `644068b3abcd2e6b8ef3e0d30c2c2387993a0b1da8a2b61cee6259dc9f4fdadd` | 16834958 |
| `eddacraft-anvil-x86_64-unknown-linux-gnu.tar.xz` | `aa9c0c3faf9bd60fbfc4674382559b683d858febe738a38195f4b681fc3298d0` | 11206008 |
| `eddacraft-anvil.rb` | `3f7ef1684b8cd8e2bdd734fbbee09b94c97f1b2401669504ab64a7176053cabc` | 2505 |
| `sha256.sum` | `a031c569bf9e93bf7f67cef1f3c6511dde10566e14c741dadad6c72a6c6a003b` | 748 |
| `source.tar.gz` | `b65923472ee24d1a44ca52deb6ea3a46f84fcd650cd9a0dfd3e5ff8aa57d07a8` | 14590487 |

## Verifying an artefact

Download an artefact from the [release page](https://github.com/eddacraft/anvil/releases/tag/v0.9.6-beta) and compare
its digest against the table above:

```sh
sha256sum <downloaded-file>
```

The digests here, the per-artefact `.sha256` sidecars on the release, and
the signed `anvil-v0.9.6-beta-provenance.json` all agree by construction.

---

_Auto-generated from the signed build-provenance manifest (CIB-034). It
deliberately omits raw logs, secrets, internal hostnames, private workflow
URLs, and private development detail._
