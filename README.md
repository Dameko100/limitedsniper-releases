# Limited Sniper — Downloads

![Limited Sniper](https://github.com/Dameko100/limitedsniper-releases/releases/download/v1.0.27/limited-sniper-banner.png)

Local desktop sniper for Roblox limited items. It watches the marketplace and buys below your target price. It runs on your own machine, and your Roblox cookie never leaves it.

## Download

The latest official version is always in [**Releases**](https://github.com/Dameko100/limitedsniper-releases/releases/latest).

| Platform | File |
|----------|------|
| Windows 10/11 (x64) | [`LimitedSniper.exe`](https://github.com/Dameko100/limitedsniper-releases/releases/latest/download/LimitedSniper.exe) |
| macOS (Apple Silicon) | [`LimitedSniper-mac-arm64.zip`](https://github.com/Dameko100/limitedsniper-releases/releases/latest/download/LimitedSniper-mac-arm64.zip) |
| macOS (Intel) | [`LimitedSniper-mac-x64.zip`](https://github.com/Dameko100/limitedsniper-releases/releases/latest/download/LimitedSniper-mac-x64.zip) |

Builds marked **Pre-release** in the [release list](https://github.com/Dameko100/limitedsniper-releases/releases) are tester builds. Use the one marked **Latest** unless you want to try new features early.

### Windows SmartScreen

The app is not code-signed yet, so Windows may show "Windows protected your PC" the first time you run a new version. Click **More info**, then **Run anyway**.

### Verify your download

Every release includes `SHA256SUMS.txt`. Compare it with the hash of your file:

```powershell
Get-FileHash .\LimitedSniper.exe -Algorithm SHA256
```

## Pricing

| Plan | Price | Includes |
|------|-------|----------|
| **Free** | $0 | 1 monitored item, 1 account, real-time alerts |
| **Pro Monthly** | $9.99 / 31 days | Everything in Pro |
| **Pro Annual** | $54.99 / 365 days | Everything in Pro |
| **Pro Lifetime** | $69.99 one-time | Everything in Pro |

**Pro** unlocks unlimited items and accounts, auto-buy on snipe detection, automatic ms mode, Discord webhooks and spike alerts, and optional support for your own proxies.

Nothing auto-renews. Get Pro at **[limitedsniper.app/pricing](https://limitedsniper.app/pricing)**.

## Links

- Website: [limitedsniper.app](https://limitedsniper.app)
- Market values and charts: [limitedsniper.app/values](https://limitedsniper.app/values)
- Discord: [discord.gg/UCX8Rp7SJ6](https://discord.gg/UCX8Rp7SJ6)
- Cookie-handling code, public for audit: [Dameko100/limited-sniper-audit](https://github.com/Dameko100/limited-sniper-audit)

## Important

- This repository **only hosts release binaries**. The source code is private, except the cookie-handling code linked above.
- Not affiliated with, endorsed, or sponsored by Roblox Corporation. Use at your own discretion.

## Support

Open an [issue](https://github.com/Dameko100/limitedsniper-releases/issues) or ask in the Discord.
