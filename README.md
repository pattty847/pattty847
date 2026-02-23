# Hey, I'm Pat

Self-taught dev. Fell in love with code at 12 decompiling Minecraft and started writing hacked clients. Never really stopped pulling things apart.

Markets became the obsession in 2020. I always had urges to build my own tools, so my journey started and I built Trade Suite, then Trade Suite v2, then Sentinel. And here we are. 

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Qt](https://img.shields.io/badge/-Qt6-41CD52?style=flat-square&logo=qt&logoColor=white)
![Claude](https://img.shields.io/badge/-Claude-000000?style=flat-square&logo=anthropic&logoColor=white)
![InfluxDB](https://img.shields.io/badge/-InfluxDB-22ADF6?style=flat-square&logo=influxdb&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

---

## Now

- 🦅 **[Sentinel](https://github.com/pattty847/Sentinel-Trading-Terminal)** — C++20 + Qt6 market microstructure terminal featuring a GPU-accelerated order book heatmap (110+ FPS), custom Footprint + TPO charts, and a from-scratch SEC filing viewer. Integrates TradingView screeners and Finviz for stock/crypto scanning.
- ⚡ **[PromptAnywhere](https://github.com/pattty847/PromptAnywhere)** — Ctrl+Alt+X, anywhere on screen. Ask, screenshot, get an answer. No browser, no context switching.
- 🧠 **CopeNet** *(inside PromptAnywhere)* — Local AI daemon. Persistent sessions across CLI models (Codex, Claude, Gemini), WebSocket RPC gateway. Eventually the brain wired into everything below.

---

## The Ecosystem

These aren't isolated projects. They're converging on one idea: an AI that sees live market data, reads the news, understands order flow, and can speak about what it's watching in real time.

```
Sentinel          →  GPU heatmap, order book, microstructure (C++)
Trade-Suite-v2    →  market data, CVD, SEC filings, scanners (Python)
TranscriptAI      →  video/news download, transcription, analysis
PromptAnywhere    →  global hotkey UI into CopeNet
CopeNet           →  persistent AI sessions, provider abstraction, WS gateway
                          ↑
                    sees and uses all of it
```

It started with a TradingView screenshot pasted into ChatGPT. It actually understood the price action. So — what if instead of a screenshot, it saw live order book data? Real CVD? Parsed news? Trade absorption patterns? That question is still driving everything.

---

## How I Got Here

| Year | | |
|------|-|--|
| 2017 | [Space-Invaders](https://github.com/pattty847/Space-Invaders) | First repo. Python. |
| 2022 | [Trade-Suite](https://github.com/pattty847/Trade-Suite) | First real terminal. DearPyGUI + CCXT Pro. 34 ⭐ |
| 2023 | [Crypto-Market-Watch](https://github.com/pattty847/Crypto-Market-Watch) | CVD aggregator. Fish, whales, major whales. InfluxDB. |
| 2023 | [Trade-Suite-v2](https://github.com/pattty847/Trade-Suite-v2) | Full rearchitecture. Redis, AI, SEC filings. 26 ⭐ |
| 2025 | [Sentinel](https://github.com/pattty847/Sentinel-Trading-Terminal) | C++. GPU. No more Python performance ceiling. |
| 2026 | CopeNet | The AI layer. Wraps it all. |

---

## Metrics

<p align="center">
  <img src="github-metrics.svg" alt="GitHub Metrics" width="49%">
  <img src="github-metrics-extras.svg" alt="Achievements & Stars" width="49%">
</p>
