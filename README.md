# ta-ema-cross

> ema 9/21 · paper · signal

[![Python 3.11+](https://img.shields.io/badge/python-3.11+-3776AB)](https://python.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Build](https://img.shields.io/badge/build-passing-brightgreen)]()

EMA 9/21 paper cross — stub closes, fee.

## Features

- Default venue binance / ETHUSDT
- Built-in ema strategy plus paper mode
- Risk manager with daily-loss kill switch
- OHLCV store and SHA-256 stub candles
- Backtester with fill + fee model
- Click CLI: backtest, paper, status, orders

## Prerequisites

- Python 3.11+
- Git

## Getting Started

```bash
git clone <repo-url>
cd ta-ema-cross
python -m pip install -e .
python -m taema --help
```

## CLI Usage

```bash
taema backtest --bars 200
# Replay stub candles

taema paper
# Start a paper session

taema status
# Print engine state

taema orders
# List simulated fills
```

## Project Structure

```
taema/
  core/        engine + risk
  strategy/    grid / dca / ema hooks
  exchange/    stub order client
  data/        candles + backtest
  cli.py
tests/
```

## Configuration

See `taema/config.py`.

| Setting | Default | Description |
|---------|---------|-------------|
| `exchange` | `binance` | Venue id |
| `symbol` | `ETHUSDT` | Default pair |
| `strategy` | `ema` | Active strategy |
| `mode` | `paper` | paper or backtest |

## Tests

```bash
python -m pytest -q
```

## Background

TA scripts still name the file ta-ema-cross.

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.


---

## Topics

![ta](https://img.shields.io/badge/ta-111827?style=flat-square) ![ema](https://img.shields.io/badge/ema-111827?style=flat-square) ![cross](https://img.shields.io/badge/cross-111827?style=flat-square) ![ta-ema-cross](https://img.shields.io/badge/ta%20ema%20cross-111827?style=flat-square) ![trading-bot](https://img.shields.io/badge/trading%20bot-111827?style=flat-square) ![crypto-trading](https://img.shields.io/badge/crypto%20trading-111827?style=flat-square) ![binance](https://img.shields.io/badge/binance-111827?style=flat-square) ![defi](https://img.shields.io/badge/defi-111827?style=flat-square)

`ta` `ema` `cross` `ta-ema-cross` `trading-bot` `crypto-trading` `binance` `defi` `algorithmic-trading` `quantitative-finance` `open-source` `python`

Search: ta-ema-cross · ema 9/21 · paper · signal · EMA 9/21 paper cross — stub closes, fee.

---

<sub>EMA 9/21 paper cross — stub closes, fee.</sub>
