# Runway — Releases

Download builds of Runway, a local-first personal finance command center for macOS. Source code lives in a private repository; this repo hosts release artifacts only.

## Install with Homebrew

```bash
brew tap aliarain/tap
brew trust aliarain/tap
brew install --cask runway-finance --no-quarantine
```

The `--no-quarantine` flag skips Gatekeeper's prompt (builds are not yet notarized). Alternatively, install normally and allow the app once via System Settings → Privacy & Security → "Open Anyway".

## Direct download

Grab the `.dmg` from the latest release, drag Runway to Applications, and if macOS blocks the first launch, allow it as above (or run `xattr -cr /Applications/Runway.app`).

Apple Silicon (arm64) only for now.
