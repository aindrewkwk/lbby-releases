<!-- Copy this to aindrewkwk/lbby-releases/README.md -->
# Lbby — Releases

This repository hosts the **downloadable installers** for [Lbby](https://lbby.app) and
the auto-update manifest (`latest.json`) the app reads to update itself.

It does **not** contain the application source code. Lbby's source is private.
The installers here are built in CI from the private source and published as
release assets — there is nothing in this repository to clone, build, or fork
into a working copy of the app.

## Download

Grab the latest installer from the [Releases page](../../releases).

| Platform | File |
|---|---|
| Windows | `Lbby_*_x64-setup.exe` |
| macOS (Apple Silicon) | `Lbby_*_aarch64.dmg` |
| macOS (Intel) | `Lbby_*_x64.dmg` |
| Linux (AppImage) | `lbby_*_amd64.AppImage` |
| Linux (Debian) | `lbby_*_amd64.deb` |

Installed copies of Lbby update themselves automatically from this repo's
releases — you normally won't need to download manually after the first install.
