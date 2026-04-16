<p align="center">
  <img src="prism-dodeca.png" alt="PrismAI" width="140" height="140">
</p>

<h1 align="center">PrismAI Releases</h1>

<p align="center">
  Public desktop downloads and updater assets for PrismAI.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-0.3.26-blue" alt="Version 0.3.26">
  <img src="https://img.shields.io/badge/platform-macOS%20%7C%20Windows%20%7C%20Linux-lightgrey" alt="macOS | Windows | Linux">
  <img src="https://img.shields.io/badge/license-MIT-green" alt="MIT License">
</p>

---

## Latest Release

Current public release:

- [v0.3.26](https://github.com/Transformation-Agency/prismai-releases/releases/tag/v0.3.26)

## Downloads

| Platform | Architecture | Download | Status |
|---|---|---|---|
| macOS | Apple Silicon (M1/M2/M3/M4) | [PrismAI-0.3.26-macos-arm64.dmg](https://github.com/Transformation-Agency/prismai-releases/releases/download/v0.3.26/PrismAI-0.3.26-macos-arm64.dmg) | Signed + Notarized |
| macOS | Intel | [PrismAI-0.3.26-macos-x86_64.dmg](https://github.com/Transformation-Agency/prismai-releases/releases/download/v0.3.26/PrismAI-0.3.26-macos-x86_64.dmg) | Signed + Notarized |
| Windows | x64 | [PrismAI_0.3.26_x64-setup.exe](https://github.com/Transformation-Agency/prismai-releases/releases/download/v0.3.26/PrismAI_0.3.26_x64-setup.exe) | Signed |
| Linux | x64 (.deb) | [prism-ai_0.3.26_amd64.deb](https://github.com/Transformation-Agency/prismai-releases/releases/download/v0.3.26/prism-ai_0.3.26_amd64.deb) | Debian package |

> Windows users may still see a SmartScreen warning on first launch. Click `More info` and then `Run anyway` to continue.

## Auto-Update Assets

PrismAI's macOS auto-updater uses these public assets:

- [PrismAI-0.3.26-macos-arm64.app.tar.gz](https://github.com/Transformation-Agency/prismai-releases/releases/download/v0.3.26/PrismAI-0.3.26-macos-arm64.app.tar.gz)
- [PrismAI-0.3.26-macos-arm64.app.tar.gz.sig](https://github.com/Transformation-Agency/prismai-releases/releases/download/v0.3.26/PrismAI-0.3.26-macos-arm64.app.tar.gz.sig)
- [PrismAI-0.3.26-macos-x86_64.app.tar.gz](https://github.com/Transformation-Agency/prismai-releases/releases/download/v0.3.26/PrismAI-0.3.26-macos-x86_64.app.tar.gz)
- [PrismAI-0.3.26-macos-x86_64.app.tar.gz.sig](https://github.com/Transformation-Agency/prismai-releases/releases/download/v0.3.26/PrismAI-0.3.26-macos-x86_64.app.tar.gz.sig)

## Verify Downloads

The public release includes per-platform checksum files:

- `SHA256SUMS-arm64.txt`
- `SHA256SUMS-intel.txt`
- `SHA256SUMS-windows.txt`

Example:

```bash
shasum -a 256 -c SHA256SUMS-arm64.txt
```

## Notes

- macOS downloads are signed and notarized
- Windows downloads are built from the same tagged release workflow
- Linux downloads are published from the validated desktop matrix artifact

## License

MIT License. Built on [AnythingLLM](https://github.com/Mintplex-Labs/anything-llm) by [Mintplex Labs](https://mintplexlabs.com).
