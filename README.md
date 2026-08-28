# Politik — Releases

Installers for [Politik](https://github.com/bukayooo/Politik), a real-time game
of European diplomacy, 1815–1914.

This repository holds no source. It exists only so that the game's in-app
updater has somewhere public to look: the app is built from a private
repository, and electron-updater reads a release feed anonymously, which a
private repository answers with a 404. Publishing the installers here keeps the
source private while leaving the update check — and the download that follows
it — open to every player, with no credential shipped inside the app.

Every release is cut by CI. Nothing here is uploaded by hand.

**[Download the latest release →](https://github.com/bukayooo/Politik-releases/releases/latest)**

| File | For |
| --- | --- |
| `Politik-<version>-arm64.dmg` | macOS, Apple Silicon |
| `Politik Setup <version>.exe` | Windows, 64-bit |
| `Politik-<version>.AppImage` | Linux, 64-bit |

The `latest*.yml` files alongside them are the update manifests. They are read
by installed copies of the game and are not useful to download yourself.
