# Homebrew Tap for MacToys

MacToys is a suite of power-user utilities for macOS. The cask is written by the
[MacToys release workflow](https://github.com/PetrGuan/MacToys/blob/main/.github/workflows/release.yml)
after each signed, notarized release.

```bash
brew install --cask PetrGuan/mactoys/mactoys
brew upgrade --cask mactoys
brew uninstall --zap --cask mactoys
```

`brew uninstall --zap` removes `MacToys.app`, the privileged helper launch
daemon, and `~/Library/Application Support/MacToys`.

No cask exists until the first release is published. Until then use the
[source build](https://github.com/PetrGuan/MacToys#build-macos).
