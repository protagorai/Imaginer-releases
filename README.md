# Imaginer downloads

Imaginer is a desktop image editor for macOS. This repository hosts its public installers as [GitHub Release assets](https://github.com/protagorai/Imaginer-releases/releases), separately from the private application source.

## Download

- [Latest Apple silicon DMG](https://github.com/protagorai/Imaginer-releases/releases/latest/download/Imaginer-latest-mac-arm64.dmg)
- [Product website and feature guides](https://imaginer.site/)
- [All published releases](https://github.com/protagorai/Imaginer-releases/releases)

Version **0.3.13** has a 142,041,593-byte DMG with SHA-256 `2452ae6760a86835ccd07bf1d9a5370e1b92528a7f3b71d67bc85eecb385d92b`. Compare the digest shown on the relevant release page with your downloaded file before installing. On macOS, run `shasum -a 256 Imaginer-latest-mac-arm64.dmg` in the download directory. For a fixed version, use the [0.3.13 release page](https://github.com/protagorai/Imaginer-releases/releases/tag/v0.3.13).

This development build targets Apple silicon. Its Electron runtime requires macOS 13 or later. It has an ad hoc signature and is not Developer ID signed or notarized. After checking the file, open the DMG and drag Imaginer into Applications. If macOS blocks it, use [Apple's guidance for opening an app from an unknown developer](https://support.apple.com/guide/mac-help/open-a-mac-app-from-an-unknown-developer-mh40616/mac). The release notes and checksum on each version's release page are authoritative for that version; the product website is deployed separately.

The DMG is uploaded as a Release asset; cloning this repository does not download the installer. The application source is maintained separately and is currently private. This repository does not grant access to that source or imply an open-source license.
