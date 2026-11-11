<p align="center">
  <img src="assets/img/breachline-logo.png" alt="Breachline" width="140">
</p>

<h1 align="center">Breachline — Official Releases</h1>

<p align="center">
  A tactical multiplayer FPS built on Godot.<br>
  This is the <b>public</b> repository: downloadable builds, patch notes,
  manifests and checksums.
</p>

---

## What's here

| Path | Contents |
|------|----------|
| [`CHANGELOG.md`](CHANGELOG.md) | Versioned changelog for all public builds |
| [`releases/`](releases/) | Per-version build manifests, checksums, and patch notes |

## Getting the game

No public build is available yet. When the first release ships it will appear:

1. As a **GitHub Release** on this repository (downloadable binaries attached)
2. In [`CHANGELOG.md`](CHANGELOG.md) with full patch notes
3. With a verified SHA-256 manifest in [`releases/`](releases/) — always verify
   checksums before running downloaded builds

## Verifying a download

Each release ships a `manifest.json` and `SHA256SUMS.txt`. Verify on:

```powershell
# Windows (PowerShell)
Get-FileHash .\Breachline-<version>-win64.zip -Algorithm SHA256

# macOS / Linux
shasum -a 256 Breachline-<version>.zip
```

Compare the output against `SHA256SUMS.txt` for that release.

## Source code

Development happens in a private repository. No source code is published here;
this repository intentionally contains only public-facing material.

## Community & support

- **Issues for public releases:** use this repository's Issues tab
- **Announcements:** watch this repository (Releases only) to get notified

---

Breachline is a work in progress. All information subject to change.
Copyright © Benji-Bitter. All rights reserved.
