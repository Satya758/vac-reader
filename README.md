# Qwen Reader releases

Qwen Reader reads web pages, PDF papers and Markdown aloud in Chrome with the
sentence highlighted, using speech models that run on your Mac.

This repository holds releases only: no source code and no models.

## Install

1. Open [Releases](https://github.com/Satya758/vac-reader/releases/latest)
   and download `QwenReader-<version>-<revision>.zip`.
2. Unzip it and follow its `README.md`.

You need a Mac with Apple Silicon (M1 or newer), macOS 14 or newer, and
Google Chrome 116 or newer.

## Updates

Qwen Reader 0.3.0 and newer checks this repository's latest release once a
day. To install a new version, open Settings → General and click
**Update to …**. The app updates its Chrome extension at the same time.

Before the app replaces itself, it checks that:

- `release.json` is signed with the release key built into the app (Ed25519,
  public key `+iOnkZtCtVQ2JupRavJDe6pzmmXTcRJn1hNEX46RKM8=`);
- the zip's size and SHA-256 match `release.json`;
- the new version passes its own self-test on your Mac.

If any check fails, the app keeps the version it has.
