# DownloadManager

A Windows download manager with HTTP/HTTPS transfers, BitTorrent support, and Microsoft Edge integration.

> **Release status:** The first public Windows installer is being prepared. There is no official downloadable release yet.

## Overview

DownloadManager is a desktop application for Windows designed to organize and manage file transfers in one place.

### Features

- **HTTP and HTTPS downloads** with segmented transfers when supported by the server.
- **BitTorrent and magnet links** in the desktop application.
- **Download queue controls** to pause, resume, and organize transfers.
- **Microsoft Edge integration** through a companion extension and a local Native Messaging Host.
- **Built-in update checks** for future signed Windows releases.

Features may vary by release. Please consult the release notes for the version you install.

## Downloads

Official Windows builds will be published under [Releases](https://github.com/nadyson1/downloadmanager-releases/releases) after testing and approval.

**No installer is available for public download yet.** Do not download packages from unofficial mirrors claiming to be DownloadManager releases.

## Browser extension

A companion extension for Microsoft Edge is being prepared for listing in Microsoft Edge Add-ons. It requires the DownloadManager Windows application and does not work as a standalone download manager.

The extension communicates with the locally installed application through Native Messaging. Availability and installation instructions will be added when the extension is approved.

## Language and platform

- **Operating system:** Windows
- **Current application language:** Brazilian Portuguese (pt-BR)
- **Planned:** English interface support in a future update

## Updates and security

Future release packages are intended to be distributed with updater signatures. Only install downloads linked from this repository's official Releases page. The signing public key is used by the app to validate update packages; private signing keys are not distributed here.

## Privacy

Read the [DownloadManager Edge Extension Privacy Notice](PRIVACY.md). This notice describes the browser extension; separate desktop-app privacy information may be provided as the public release is prepared.

## Source code

This repository is for public release artifacts and documentation. It does **not** contain the application's source code. Source code is maintained separately in a private development repository.

## Support

For privacy inquiries, use the contact listed in [PRIVACY.md](PRIVACY.md). Further support instructions will be added for the first public release.

---

*DownloadManager is an independent project and is not affiliated with Microsoft or Google.*
