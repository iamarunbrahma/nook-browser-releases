# Nook browser releases

Builds of [Nook](https://browser.arunbrahma.com), a small web browser for macOS. Ad and tracker blocking is built in, reader mode strips an article back to its text and pictures, and there is no account to create.

## Download

**[Nook.dmg (latest release)](https://github.com/iamarunbrahma/nook-browser-releases/releases/latest/download/Nook.dmg)**

Open the DMG and drag Nook to your Applications folder. One universal build runs on Apple silicon and Intel Macs. Every build is signed with a Developer ID certificate and notarized by Apple, so it opens without a Gatekeeper warning.

## Verify a download

Each release ships a `Nook.dmg.sha256` file next to the DMG. With both in the same folder:

```sh
shasum -a 256 -c Nook.dmg.sha256
```

## Links

- [browser.arunbrahma.com](https://browser.arunbrahma.com) for what Nook does, with a two minute demo
- [Privacy policy](https://browser.arunbrahma.com/privacy): no account, no sync, no telemetry, and cookies and cache cleared when you quit
- Questions or bug reports: contact@arunbrahma.com

Nook's source code is not published. This repository holds the released builds and nothing else.
