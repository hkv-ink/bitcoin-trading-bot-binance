# MountAlpha Bitcoin Trading Bot for Binance

**MountAlpha Binance Edition (MountAlpha Flow)** is an English-language Windows desktop application for Binance USDT perpetual futures. It includes a simulated account, live-account controls, a positions and activity dashboard, and encrypted support messaging.

## Download for Windows

Open [GitHub Releases](../../releases/latest) and download `MountAlpha-Binance-Setup.exe` and `SHA256SUMS.txt` from the same release. This is the English Binance edition. For the Chinese OKX edition, see [MountAlpha OKX Edition](https://github.com/hkv-ink/bitcoin-trading-bot-okx).

## Installation and First Launch

1. Use a 64-bit Windows computer with Microsoft Edge WebView2. Before running the installer, verify that its SHA-256 matches `SHA256SUMS.txt`:
   ```powershell
   Get-FileHash -Algorithm SHA256 .\MountAlpha-Binance-Setup.exe
   ```
2. Open **MountAlpha Flow** from its Start menu or desktop shortcut. Start with the simulated account; a Binance API key is not needed for simulation.
3. Live execution is separate and starts paused. It requires a valid device license, a configured Binance account, and explicit start. Do not enable live trading in two installations against the same account. Do not uninstall an existing live installation to resolve an update refusal.

## FAQ

**Does this support OKX or Binance spot?** No. This download is for Binance USDT perpetual futures. The Chinese OKX version is a separate download with separate settings and authorization.

**Does the installer include customer data?** Installers are distributed without customer account credentials or ledgers. Never share your API secret or paste it into GitHub Issues or support messages.

**Is simulated performance a promise of live performance?** No. Leveraged trading can result in substantial losses. Simulation and historical results do not predict future results. Verify that the software and the exchange product are permitted where you live. MountAlpha is not an official Binance product.

## Support

Use **Support** inside the app for compatibility and licensing questions. Include the application version and the problem description, with account identifiers and secrets removed.
