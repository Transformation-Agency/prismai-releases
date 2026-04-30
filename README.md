<p align="center">
  <img src="prism-dodeca.png" alt="Scope" width="140" height="140">
</p>

<h1 align="center">Scope Releases</h1>

<p align="center">
  Public desktop downloads and updater assets for Scope.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-0.6.0-blue" alt="Version 0.6.0">
  <img src="https://img.shields.io/badge/platform-macOS%20%7C%20Windows-lightgrey" alt="macOS | Windows">
  <img src="https://img.shields.io/badge/license-MIT-green" alt="MIT License">
</p>

---

## Latest Release

Current public release:

- [v0.6.0](https://github.com/Transformation-Agency/prismai-releases/releases/tag/v0.6.0)

This mirror hosts the public installer artifacts used by Scope desktop distribution and the Tauri updater feed consumed by existing installed apps.

## Downloads

| Platform | Architecture | Download | Status |
|---|---:|---|---|
| macOS | Apple Silicon (M1/M2/M3/M4) | [Scope-0.6.0-macos-arm64.dmg](https://github.com/Transformation-Agency/prismai-releases/releases/download/v0.6.0/Scope-0.6.0-macos-arm64.dmg) | Signed + notarized |
| macOS | Intel | [Scope-0.6.0-macos-x86_64.dmg](https://github.com/Transformation-Agency/prismai-releases/releases/download/v0.6.0/Scope-0.6.0-macos-x86_64.dmg) | Signed + notarized |
| Windows | x64 | [Scope_0.6.0_x64-setup.exe](https://github.com/Transformation-Agency/prismai-releases/releases/download/v0.6.0/Scope_0.6.0_x64-setup.exe) | Signed installer |

## Auto-Update Feed

Scope desktop checks this updater endpoint:

- [update.json](https://raw.githubusercontent.com/Transformation-Agency/prismai-releases/main/update.json)

Current updater feed version: `0.6.0`.

### Active Auto-Update Assets

macOS auto-update uses signed `.app.tar.gz` bundles plus Tauri signatures:

- [Scope-0.6.0-macos-arm64.app.tar.gz](https://github.com/Transformation-Agency/prismai-releases/releases/download/v0.6.0/Scope-0.6.0-macos-arm64.app.tar.gz)
- [Scope-0.6.0-macos-arm64.app.tar.gz.sig](https://github.com/Transformation-Agency/prismai-releases/releases/download/v0.6.0/Scope-0.6.0-macos-arm64.app.tar.gz.sig)
- [Scope-0.6.0-macos-x86_64.app.tar.gz](https://github.com/Transformation-Agency/prismai-releases/releases/download/v0.6.0/Scope-0.6.0-macos-x86_64.app.tar.gz)
- [Scope-0.6.0-macos-x86_64.app.tar.gz.sig](https://github.com/Transformation-Agency/prismai-releases/releases/download/v0.6.0/Scope-0.6.0-macos-x86_64.app.tar.gz.sig)

Windows `0.6.0` is available as both a manual `.exe` installer and an in-app updater bundle. The live updater feed includes `windows-x86_64` pointing at the signed `.nsis.zip` artifact.

## Verify Downloads

The public release includes per-platform checksum files:

- [SHA256SUMS-arm64.txt](https://github.com/Transformation-Agency/prismai-releases/releases/download/v0.6.0/SHA256SUMS-arm64.txt)
- [SHA256SUMS-intel.txt](https://github.com/Transformation-Agency/prismai-releases/releases/download/v0.6.0/SHA256SUMS-intel.txt)
- [SHA256SUMS-windows.txt](https://github.com/Transformation-Agency/prismai-releases/releases/download/v0.6.0/SHA256SUMS-windows.txt)

Example:

```bash
shasum -a 256 -c SHA256SUMS-arm64.txt
```

## Release Notes

Scope `0.6.0` includes:

- Visible Scope rebrand across desktop shell, setup, sidebar, chat presence, app metadata, and native icons.
- Full CDISS intent/state orchestration integration for chat routing.
- Provider lane model detection improvements in settings.
- Desktop polish fixes for update notices, chat auto-scroll, and Lens sidebar behavior.
- macOS Apple Silicon and Intel signed/notarized builds.
- Windows x64 signed installer and updater bundle.

## Maintainer Notes

To publish a desktop update:

1. Upload installer assets to a tagged release in this repository.
2. Upload signed Tauri updater bundles and `.sig` files for every platform being auto-updated.
3. Update `update.json` on `main` with the new version, platform URLs, signatures, and publication date.
4. Keep normal user-facing release notes in the GitHub Release body; keep updater internals out of app chat/UI surfaces.

## License

MIT License. Scope is built on [AnythingLLM](https://github.com/Mintplex-Labs/anything-llm) by [Mintplex Labs](https://mintplexlabs.com).
