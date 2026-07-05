# ADSync

A free macOS menu bar app that keeps your Active Directory password in sync with all local credential stores — login Keychain, FileVault passphrase, and Kerberos tickets.

**Requires macOS 14 (Sonoma) or later.**

## Download

See the [Releases](https://github.com/Cortexa-LLC/ADSync-releases/releases) page for the latest signed and notarized DMG.

## Features

- Unified mode — change AD password and update all local stores in one step
- Local sync mode — auto-detected when AD was already updated elsewhere  
- Sync Only — re-key Keychain/FileVault without changing AD
- FileVault passphrase rotation via privileged helper (no sudo prompt)
- Offline fallback — continue with local-only sync if domain is unreachable

## Installation

1. Open `ADSync.dmg`
2. Drag **ADSync** to your Applications folder
3. Launch — approve the helper in **System Settings › General › Login Items & Extensions**

---

© 2026 Cortexa LLC. All rights reserved.
