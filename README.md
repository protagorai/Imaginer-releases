# Imaginer downloads

Imaginer is a desktop image editor for macOS. This repository hosts its public installers as [GitHub Release assets](https://github.com/protagorai/Imaginer-releases/releases), separately from the private application source.

## Download

- [Latest Apple silicon DMG](https://github.com/protagorai/Imaginer-releases/releases/latest/download/Imaginer-latest-mac-arm64.dmg)
- [Installation guidance and current build details](https://imaginer.site/download.html)
- [All published releases](https://github.com/protagorai/Imaginer-releases/releases)

Version **0.3.13** has a 142,041,593-byte DMG with SHA-256 `2452ae6760a86835ccd07bf1d9a5370e1b92528a7f3b71d67bc85eecb385d92b`. Compare the digest shown on the relevant release page with your downloaded file before installing. On macOS, run `shasum -a 256 Imaginer-latest-mac-arm64.dmg` in the download directory. For a fixed version, use the [0.3.13 release page](https://github.com/protagorai/Imaginer-releases/releases/tag/v0.3.13).

This development build targets Apple silicon. Its Electron runtime requires macOS 13 or later. It has an ad hoc signature and is not Developer ID signed or notarized; see the [installation guidance](https://imaginer.site/download.html) for the current limitations and Apple's opening instructions.

The DMG is uploaded as a Release asset; cloning this repository does not download the installer. The application source is maintained separately and is currently private. This repository does not grant access to that source or imply an open-source license.
