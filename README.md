# ShelfSmart Android Releases

This repository is the **public binary distribution channel** for ShelfSmart. The application source code remains private.

## Downloading ShelfSmart

Use the latest GitHub Release on this repository. ShelfSmart publishes device-specific Android APKs rather than one oversized universal APK:

- **`ShelfSmart-<version>-arm64-v8a.apk`** — recommended for almost all modern Android phones, including current Samsung devices.
- **`ShelfSmart-<version>-armeabi-v7a.apk`** — compatibility build for older supported 32-bit Android phones.

Do not download APKs from the repository source tree. Official binaries are attached to GitHub Releases and accompanied by SHA-256 checksums.

## Release integrity

Every public release records:

- ShelfSmart semantic version and Android version code
- exact private-source Git commit that produced the build
- APK architecture
- file size
- SHA-256 checksum
- release notes

The machine-readable [`latest.json`](./latest.json) manifest is the canonical pointer used by ShelfSmart download surfaces. A release is considered public only after its APKs are attached to a GitHub Release and `latest.json` has `"published": true`.

## Installation

For most phones, download the **ARM64** APK. Android may ask permission to install apps from your browser or file manager. Existing ShelfSmart installations signed with the same production key can be upgraded in place without removing app data.

ShelfSmart should be installed only from this repository or another official aiDo/ShelfSmart download surface.

## Privacy and security

This repository contains **compiled release binaries and public release metadata only**. It does not expose ShelfSmart source code, signing keys, backend secrets, database credentials, or customer data.

---

ShelfSmart — Run your shop smarter.
