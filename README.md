# ShelfSmart Android Releases

This repository is the **public binary distribution channel** for ShelfSmart. The application source code remains private.

## Downloading ShelfSmart

Use the latest GitHub Release on this repository. For direct APK distribution we publish device-specific Android builds rather than a single oversized universal APK:

- **`ShelfSmart-arm64-v8a.apk`** — recommended for almost all modern Android phones.
- **`ShelfSmart-armeabi-v7a.apk`** — compatibility build for older 32-bit Android phones when supported.

Do not download APKs from the repository source tree. Official binaries are attached to GitHub Releases and accompanied by SHA-256 checksums.

## Release integrity

Every public release records:

- ShelfSmart semantic version and Android version code
- exact private-source Git commit that produced the build
- APK architecture
- file size
- SHA-256 checksum
- release notes

The machine-readable [`latest.json`](./latest.json) file is intended for the ShelfSmart landing page and other trusted download surfaces.

## Installation

Android may ask permission to install apps from your browser or file manager. ShelfSmart should be installed only from this repository or another official aiDo/ShelfSmart download surface.

## Privacy

This repository contains **compiled release binaries only**. It does not expose ShelfSmart source code, signing keys, backend secrets, database credentials, or customer data.

---

ShelfSmart — Run your shop smarter.
