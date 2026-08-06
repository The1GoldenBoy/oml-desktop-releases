# Felix Desktop Releases

This repository hosts the official Windows release assets for Felix Desktop
by OptimizeMyLife. Application source code is maintained privately.

Every release - signed or not - ships with its own checksums and a release
gate summary, so you can verify exactly what you're running before you run
it.

## Current release: unsigned beta

The current release is an **unsigned** beta build. Windows code signing is
in progress; until it's approved, this is the real build with a plain
warning attached, not a placeholder. It includes:

- `Felix-beta-<version>-portable.exe`
- `SHA256SUMS-beta-unsigned.txt`
- `README-BETA.md` - what the unsigned warning means and how to verify the
  file before you run it

## Signed releases (once code signing clears)

Once code signing is approved, signed releases will additionally include:

- `Felix-Setup-<version>.exe`
- `Felix-Setup-<version>.exe.blockmap`
- `latest.yml`
- `SHA256SUMS-public-signed.txt`
- `release-gate-public-signed.json`

Always verify the installer hash against the matching `SHA256SUMS-*.txt`
file before running it. Official product downloads are linked from
[optimizemylife.ai](https://optimizemylife.ai).

## Security

Report vulnerabilities through GitHub private vulnerability reporting. Do not
publish credentials, customer data, or security details in a public discussion.
See [SECURITY.md](SECURITY.md) for the reporting policy.
