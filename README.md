# Felix Desktop Releases

This repository hosts public release assets for Felix Desktop by
OptimizeMyLife. Application source code is maintained privately.

Release status and verification files vary by platform and version. Check the
release notes and the files attached to the specific release before
downloading. A checksum confirms file integrity; it does not by itself prove
that a build is signed or identify the source commit.

## Current releases by platform

As of September 25, 2026, the latest published releases are:

### Windows — v0.1.6

[Felix Desktop v0.1.6](https://github.com/The1GoldenBoy/oml-desktop-releases/releases/tag/v0.1.6)
is the latest stable Windows release. Its published files include the signed
installer, `latest.yml`, checksums, a release-gate report, an SBOM, and build
provenance.

### macOS — v0.1.8

[Felix v0.1.8 for macOS](https://github.com/The1GoldenBoy/oml-desktop-releases/releases/tag/v0.1.8-mac)
is signed and notarized. Its published files include a DMG, ZIP, checksums,
an SBOM, provenance, and a macOS release proof.

### Linux — v0.1.8 beta

[Félix Desktop 0.1.8 for Linux](https://github.com/The1GoldenBoy/oml-desktop-releases/releases/tag/v0.1.8-linux)
is an unsigned prerelease. Its published files include an AppImage, a Debian
package, a tarball, checksums, and an SBOM. The release does not publish a
release-gate report or build provenance.

## Historical Windows beta

The [unsigned Windows beta 0.1.0](https://github.com/The1GoldenBoy/oml-desktop-releases/releases/tag/desktop-beta-0.1.0-unsigned-public-20260803)
was published on August 3, 2026. It includes a portable executable, a
checksum file, and `README-BETA.md`. It is a historical beta, not the current
Windows release.

When a release includes a `SHA256SUMS-*.txt` file, verify the downloaded
artifact against the matching checksum before running it. Official product
downloads are linked from
[optimizemylife.ai](https://optimizemylife.ai).

## Security

Report vulnerabilities through GitHub private vulnerability reporting. Do
not publish credentials, customer data, or security details in a public
discussion. See [SECURITY.md](SECURITY.md) for the reporting policy.
