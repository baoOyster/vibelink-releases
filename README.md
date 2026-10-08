# VibeLink Releases

Public Windows installers, updater metadata, signatures, and checksums for the VibeLink Desktop Companion. Source code is maintained separately.

- [Latest release](https://github.com/baoOyster/vibelink-releases/releases/latest)
- [Windows MSI download](https://github.com/baoOyster/vibelink-releases/releases/latest/download/VibeLink-Setup.msi)
- [Changelog](CHANGELOG.md)
- [Beta access and privacy information](https://baooyster.github.io/VibeLink/)

## Beta scope

The Desktop Companion targets Windows 11. The native Android companion uses separately configured Google Play closed testing; a beta application does not automatically grant Play access. Full phone-to-workstation integration remains beta and is not production-ready.

## Verification

Each versioned release includes installer checksums and Tauri updater signatures. `latest.json` identifies the release version, notes, signed Windows update, and versioned download URL. Updater signature verification is mandatory.

Tauri updater signatures are separate from Windows Authenticode publisher signatures. When no Authenticode provider is configured, Windows may display an unverified-publisher warning. Check the release's signing status rather than assuming a publisher certificate is present.
