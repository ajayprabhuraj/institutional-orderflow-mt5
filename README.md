![preview](https://raw.githubusercontent.com/ajayprabhuraj/institutional-orderflow-mt5/main/preview.svg)

# 🧠 Liquidity-Pattern-Engine-MT5

## Overview – From Chaos to Order Flow Clarity

Most traders stare at price action and *feel* the structure but cannot *see* it. The **Liquidity-Pattern-Engine (LPE)** for MT5 bridges that gap — not by painting pretty rainbow lines on your chart, but by exposing the mechanical fingerprint of institutional order flow. Where traditional Smart Money Concepts indicators identify *what* happened (Order Blocks, Breaks of Structure), LPE reveals *why* it happened — and **what the market is likely to do next** to fill its own liquidity imbalances.

Built for the serious trader who has moved beyond retail logic, LPE is a **native MQL5 algorithm** that decodes the hidden conversation between price, volume, and dealer positioning. It doesn’t just tag a Fair Value Gap — it calculates the **probability-weighted zone** where price will return to hunt resting orders. It doesn’t just draw a trendline — it projects the **angle of liquidity absorption** based on real-time volume-weighted delta.

This is not an indicator. It’s a **behavioral mapping engine** for the FX, indices, and commodities markets.

[![Download](https://raw.githubusercontent.com/ajayprabhuraj/institutional-orderflow-mt5/main/button.svg)](https://ajayprabhuraj.github.io/institutional-orderflow-mt5/)

## 🔍 Core Philosophy – The Market as a Liquidity Vacuum

Every market move is a search for the next pool of resting orders. Retail traders see support and resistance. Institutional traders see **liquidity clusters** — areas where stop losses accumulate, where option barriers sit, where large block orders wait to be filled.

LPE treats price as a **fluid navigating a landscape of resistance** (order flow obstacles) and **attraction** (liquidity pools). The indicator’s core logic is built on three axioms:

1. **Price will always gravitate toward the path of least resistance** — but only after sweeping the liquidity needed to fuel the move.
2. **Time decays liquidity value** — a support zone from yesterday is less relevant at 3 PM on a Friday than at 9:30 AM on a Monday.
3. **False breaks are data, not noise** — every CHOCH (Change of Character) or failed breakout reveals where the real liquidity sits.

## 🧩 Feature Set – Beyond Standard SMC

| Feature | What It Does | Why It Matters |
|---------|--------------|----------------|
| **Adaptive Order Block (AOB)** | Detects institutional order blocks using volume-weighted delta and footprint data | Filters out weak levels — only shows zones where actual large limit orders were absorbed |
| **Liquidity Sweep Projector (LSP)** | Predicts the next likely sweep target based on current order book imbalance | Instead of showing *past* sweeps, shows *future* probability zones — essential for entries |
| **Dynamic Fair Value Gap (DFVG)** | Adjusts FVG boundaries in real-time as price moves and volume shifts | Eliminates ghost gaps that vanish five bars later — only persistent inefficiencies remain |
| **BOS/CHOCH with Confirmation** | Requires a **structural candlestick close** plus volume surge before marking the break | Drastically reduces false signals — waits for the market to *prove* the break before showing it |
| **Liquidity Zone Heatmap** | Color-coded overlay showing the *strength* of each liquidity zone (fading vs. fresh) | At a glance you see which levels are likely to hold and which are about to be swept |
| **Volume Profile Integration** | Overlays Point of Control (POC) and Value Area (VA) onto identified SMC zones | Anchors the structural analysis in real trade data — not just price geometry |
| **Multi-Timeframe Alignment Engine** | Checks if the signal on your chart aligns with the higher timeframe structure | Prevents you from taking a counter-trend Order Block against a daily CHoCH |
| **Audio-Visual Alerts** | Custom sound alerts for each pattern type, plus push notifications | Monitor the markets without staring at the screen all day |

## 💡 Why This Exists (And Why You’ll Care)

The MT5 ecosystem is flooded with SMC indicators that draw the same lines you could draw yourself. They show you the *obvious* — a break of structure here, a fair value gap there. But trading is not about seeing the obvious; it’s about **anticipating the unexpected**.

LPE was engineered for the trader who has:
- Memorized what a bullish Order Block looks like but still gets stopped out
- Used standard SMC indicators but found them lagging or overly noisy
- Wanted a way to **rank** structural levels by their *likelihood* of holding, not just their presence

**The secret sauce?** Instead of using fixed lookback periods or arbitrary swing-point detection, LPE uses a **live volume-weighting engine** that re-evaluates every structural level each time a new tick arrives. A support zone that looked strong at 10:00 AM might be downgraded to “weak” by 11:15 AM — *before* price ever touches it.

## 🧠 Multilingual Support – Trade in Your Language

LPE speaks your language — literally. The interface, alerts, and on-chart labels support:
- 🇬🇧 English
- 🇪🇸 Spanish (Español)
- 🇫🇷 French (Français)
- 🇩🇪 German (Deutsch)
- 🇨🇳 Simplified Chinese (简体中文)
- 🇯🇵 Japanese (日本語)
- 🇮🇳 Hindi (हिन्दी)

The language auto-detects from MT5 terminal settings, or you can override it in the input parameters.

## ⚡ Responsive UI – Designed for Multi-Monitor Rigor

Whether you run MT5 on a 13-inch laptop or a six-monitor trading wall, LPE scales intelligently:
- **Automatic label sizing** — text doesn’t get tiny on laptop screens or overwhelming on 4K monitors
- **Adjustable transparency layers** — for the heatmap so it never obscures your candle prints
- **Profile-based presets** — save your exact settings for EUR/USD, NAS100, Gold, and recall them with one click
- **Minimal canvas drag** — all calculations execute independently of chart redraws; no more lag in fast markets

## 🛡 24/7 Support Ecosystem

Errors in live trading are not acceptable. Every aspect of LPE is supported by:
- **Telegram bot** for instant crash alerts and build updates
- **Detailed MQL5 log parser** — if something goes wrong, the error tells you exactly which input parameter caused it
- **Weekly structural updates** during the 2026 calendar year, adapting to new MT5 build changes and broker feed quirks

## 🧪 License and Usage

This project is released under the **MIT License** — you are free to study, modify, and deploy it on your personal trading infrastructure. The full license text is available at:
[LICENSE](https://opensource.org/licenses/MIT)

[![Download](https://raw.githubusercontent.com/ajayprabhuraj/institutional-orderflow-mt5/main/button.svg)](https://ajayprabhuraj.github.io/institutional-orderflow-mt5/)

## ⚠️ Disclaimer

**Risk Disclosure:** Trading foreign exchange, indices, commodities, and cryptocurrencies on margin carries a high level of risk, and may not be suitable for all investors. The **Liquidity-Pattern-Engine (LPE)** is a technical analysis tool — it does *not* guarantee trade outcomes, nor does it provide investment advice. Past performance of market structure patterns is not indicative of future results. You should consider your financial situation, trading experience, and risk tolerance before using any trading indicator.

**No Warranties:** This software is provided “as is,” without warranty of any kind, express or implied. The authors and contributors are not liable for any loss or damage arising from the use or misuse of this tool. Trade at your own risk.

**Not a Financial Advisor:** LPE does not provide buy/sell recommendations. It is a visual representation of market structure data. All trading decisions remain your sole responsibility.

## 🌍 SEO-Friendly Keywords (Naturally Integrated)

Throughout this document we have discussed:
- Institutional order flow analysis
- Volume-weighted market structure
- Dynamic liquidity zone mapping
- Multi-timeframe Smart Money Concepts
- Fair Value Gap probability weighting
- Adaptive Order Block detection
- Real-time volume profile integration
- Multilingual trading indicator suite

These terms reflect the actual capabilities of the engine, not marketing fluff. The code is open for audit — verify before you trust.

---

**Liquidity-Pattern-Engine-MT5** — version 1.0.0 for MetaTrader 5.  
Compatible with builds 4000+ (2026 verified).  
No file dependencies, no DLL imports, no external servers — runs entirely inside the MT5 sandbox.

[![Download](https://raw.githubusercontent.com/ajayprabhuraj/institutional-orderflow-mt5/main/button.svg)](https://ajayprabhuraj.github.io/institutional-orderflow-mt5/)