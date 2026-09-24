# MacPress Homebrew Tap

This repository is the custom Homebrew tap for [MacPress](https://github.com/SagarBajpai/MacPress), an open-source macOS menu-bar utility that automatically compresses screen recordings locally.

It intentionally contains only Homebrew packaging metadata. The MacPress source code, documentation, releases, DMG files, and issue tracker are maintained in the [main MacPress repository](https://github.com/SagarBajpai/MacPress).

## Install

```bash
brew tap SagarBajpai/macpress
brew install --cask macpress
```

The cask downloads the versioned `MacPress.app` DMG from the main repository’s [GitHub Releases](https://github.com/SagarBajpai/MacPress/releases). Homebrew does not build or host the application.

## Update

```bash
brew update
brew upgrade --cask macpress
```

## Notes

- MacPress currently targets Apple Silicon Macs running macOS 14 or later.
- Releases are currently ad-hoc signed and not notarized; macOS may require **Open Anyway** on first launch.
- This is a personal tap, not the official Homebrew Cask repository.

For usage, source code, privacy details, support, and release notes, visit the [main MacPress repository](https://github.com/SagarBajpai/MacPress).
