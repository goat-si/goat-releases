# GOAT releases

This repository hosts **binary releases** of GOAT, a multi-device control surface for coding agents. GOAT's source code is not published here.

## Status

No releases yet. The first nightly will appear under [Releases](https://github.com/goat-si/goat-releases/releases) as a prerelease named `v0.1.0-nightly.YYYYMMDD.N`.

## Channels

| Channel | What it is |
|---|---|
| nightly | Built automatically from the development branch after CI passes. Prerelease. May break. |
| latest | Not available yet. |

## Platforms and signing

| Platform | Artifacts | Signing |
|---|---|---|
| macOS (Apple Silicon, Intel) | DMG, ZIP | Signed with a Developer ID and notarized by Apple |
| Windows (x64, arm64) | NSIS installer | Not signed yet; Windows SmartScreen will warn |
| Linux (x64, arm64) | AppImage, DEB | Not signed; verify with `SHA256SUMS` |

Every release includes a `SHA256SUMS` file. Verify downloads against it.

## License

GOAT binaries are proprietary and provided for your own use; see [LICENSE.md](LICENSE.md) for the terms.

GOAT includes software derived from [T3 Code](https://github.com/pingdotgg/t3code), which is distributed under the MIT License. Its copyright and permission notice is reproduced in [NOTICE.md](NOTICE.md).

