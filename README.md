# Calmfold releases

Official downloads for **Calmfold by Nexdark Labs**, a private, local-first
personal app for macOS and Windows.

[Download the latest release](https://github.com/MohammedSafwan10/calmfold-releases/releases/latest) ·
[Application source and documentation](https://github.com/MohammedSafwan10/calmfold) ·
[Contribute](https://github.com/MohammedSafwan10/calmfold/blob/main/CONTRIBUTING.md)

## Install

- **Mac · Apple Silicon:** download the macOS archive, extract it and move
  Calmfold.app into Applications.
- **Windows · x64:** download Setup.exe for a per-user installation, or extract
  the portable archive and keep its entire folder together.

Install v0.1.2 or later once manually. Subsequent releases support native in-app
updates through Sparkle on Mac and Velopack on Windows. Builds are not yet
Apple-notarized or Windows Authenticode-signed; the OS may warn on first install.
Update signatures are checked separately. Development builds keep separate data.

## Source and verification

Each release includes an application source archive, LICENSE, NOTICE and
SHA256SUMS. Use the named `Calmfold-<version>-source.tar.gz` asset to get the
application source. GitHub's automatic source archives for this downloads-only
repository contain its metadata rather than the app.

Calmfold's original source is [GPL-3.0-only](LICENSE); dependencies retain their
own licenses. The platform packages include dependency notices and the exact
build source reference. SHA256SUMS supports file integrity comparison; the
native updater authenticates its signed catalog/appcast and packages separately.

[Report a vulnerability privately](https://github.com/MohammedSafwan10/calmfold/security/advisories/new) ·
[Security boundaries](https://github.com/MohammedSafwan10/calmfold/blob/main/SECURITY.md)
