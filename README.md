# Hey, I'm Pat

Self taught developer building trading terminals and AI systems.

I started at 12 decompiling Minecraft clients and writing hacked mods. Pulling software apart became the habit.

In 2020 markets took over my brain. I started building the tools I wanted to trade with.

Trade Suite → Trade Suite v2 → Sentinel.

The goal now is bigger than a terminal. I am building systems where AI can watch markets the way a trader does.

![Codex](https://img.shields.io/badge/-Codex-412991?style=flat-square\&logo=openai\&logoColor=white)
![Claude](https://img.shields.io/badge/-Claude-000000?style=flat-square\&logo=anthropic\&logoColor=white)
![Gemini](https://img.shields.io/badge/-Gemini-4285F4?style=flat-square\&logo=google\&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square\&logo=cplusplus\&logoColor=white)
![Qt](https://img.shields.io/badge/-Qt6-41CD52?style=flat-square\&logo=qt\&logoColor=white)
![InfluxDB](https://img.shields.io/badge/-InfluxDB-22ADF6?style=flat-square\&logo=influxdb\&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square\&logo=redis\&logoColor=white)

---

<img width="1920" height="1080" alt="Sentinel Trading Terminal" src="https://github.com/user-attachments/assets/7061229b-e925-42e6-9d01-7f7e5ece7ca0" />

---

## Now

🦅 **[Sentinel](https://github.com/pattty847/Sentinel)**
C++20 + Qt6 market microstructure terminal.

GPU accelerated order book heatmap with 110+ FPS rendering, custom Footprint and TPO charts, and a from scratch SEC filing viewer. Integrates TradingView screeners and Finviz to scan stock and crypto markets.

📈 **[Sentinel Lite](https://github.com/pattty847/Sentinel-Lite)**
The terminal that started everything.

Originally built with DearPyGui. Features candlestick charts, real time order book DOM, multi exchange market data, dockable layouts with persistence, and an SEC filings viewer. Currently being ported and expanded in PySide6.

⚡ **[PromptAnywhere](https://github.com/pattty847/PromptAnywhere)**
Ctrl + Alt + X anywhere on screen.

Ask a question, screenshot something, get an answer instantly. No browser. No context switching.

🧠 **CopeNet** *(inside PromptAnywhere)*
Local AI daemon with persistent sessions across Codex, Claude, and Gemini. WebSocket RPC gateway that will eventually power the entire ecosystem.

---

## The Ecosystem

These are not isolated projects. They are converging toward a single idea.

An AI that can see market data, read news, observe order flow, and explain what is happening in real time.

```
Sentinel          →  GPU heatmap, order book, microstructure (C++)
Trade-Suite-v2    →  market data, CVD, SEC filings, scanners (Python)
TranscriptAI      →  video and news download, transcription, analysis
PromptAnywhere    →  global hotkey UI into CopeNet
CopeNet           →  persistent AI sessions, provider abstraction, WS gateway
                          ↑
                    sees and uses all of it
```

The idea started with a simple moment.

I pasted a TradingView screenshot into ChatGPT and it correctly explained the price action.

Then the obvious question appeared.

What happens if the AI sees live order book data instead of a screenshot?

That question is still driving everything.

---

## Current Experiments

AI agents that observe live market microstructure
GPU rendering pipelines for dense financial data
Persistent multi model AI sessions across CLI agents
Real time anomaly detection in order flow and liquidity

---

## Build Philosophy

Ship real software, not prototypes.
Performance matters.
AI should amplify developers, not replace thinking.
Visual tools reveal patterns that raw numbers hide.

---

## How I Got Here

| Year |                                                                         |                                                                     |
| ---- | ----------------------------------------------------------------------- | ------------------------------------------------------------------- |
| 2017 | [Space-Invaders](https://github.com/pattty847/Space-Invaders)           | First repo. Python.                                                 |
| 2022 | [Trade-Suite](https://github.com/pattty847/Trade-Suite)                 | First trading terminal. DearPyGui + CCXT Pro.                       |
| 2023 | [Crypto-Market-Watch](https://github.com/pattty847/Crypto-Market-Watch) | CVD aggregator with whale tracking. InfluxDB.                       |
| 2023 | [Trade-Suite-v2](https://github.com/pattty847/Trade-Suite-v2)           | Full rearchitecture with Redis, AI integration, SEC filings viewer. |
| 2025 | [Sentinel](https://github.com/pattty847/Sentinel-Trading-Terminal)      | C++ GPU trading terminal.                                           |
| 2026 | CopeNet                                                                 | The AI layer tying everything together.                             |

---

## Activity

<p align="center">
  <img src="github-metrics.svg" alt="GitHub Metrics" width="49%">
  <img src="github-metrics-extras.svg" alt="Achievements & Stars" width="49%">
</p>
