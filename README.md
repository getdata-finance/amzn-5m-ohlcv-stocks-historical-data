# AMZN 5m OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-239_992_rows-blue)](https://getdata.finance/datasets/amzn) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/amzn)

### -> [**Download the full AMZN dataset on getdata.finance**](https://getdata.finance/datasets/amzn)

**AMZN 5m OHLCV us stocks historical data** — ultra high-quality 5m OHLCV for **AMZN**. US equity cash and extended sessions — institutional-style OHLCV candles for US stocks. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 5m OHLCV** for **AMZN** (US stocks)
- **US equity cash and extended sessions — institutional-style OHLCV candles for US stocks**
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`5m`) · **9 timeframes** on [getdata.finance](https://getdata.finance/datasets/amzn) · **239,992** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `5m` sample updated in sync

> **Sample on GitHub** · `AMZN_5m.csv` (9,740 rows, `2026-02-02` -> `2026-07-31`). **Full archive on [getdata.finance](https://getdata.finance/datasets/amzn)** — **239,992** `1m` rows (~19.01 MB), **9 timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W), `2011-05-09` -> `2026-07-31`.

## Download sample

**[AMZN_5m.csv](https://github.com/getdata-finance/amzn-5m-ohlcv-stocks-historical-data/blob/main/AMZN_5m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/amzn-5m-ohlcv-stocks-historical-data/main/AMZN_5m.csv)) · [GitHub Releases](https://github.com/getdata-finance/amzn-5m-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/amzn-5m-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/amzn-5m-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/amzn](https://getdata.finance/datasets/amzn)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/amzn))** |
|---|--:|---|
| Instrument | AMZN · US stocks | AMZN · US stocks |
| Timeframes | `5m` (sample) | **9** — 1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W |
| 1m rows | 9,740 | **239,992** |
| Size | 0.97 MB | ~19.01 MB |
| Period | `2026-02-02` -> `2026-07-31` | `2011-05-09` -> `2026-07-31` |
| File | `AMZN_5m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/amzn) |
| Coverage report | — | [AMZN coverage](https://getdata.finance/coverage/amzn) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`5m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/amzn)**, each full asset archive is delivered as a ZIP with **9 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **12H** · **3D** · **1W**

GitHub = `5m` sample · [getdata.finance](https://getdata.finance/datasets/amzn) = all **9** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `5m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`AMZN_5m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-02-02T15:20:00+00:00 | 247.22 | 247.67 | 246.93 | 247.38 | 1652 |
| 2026-02-02T15:25:00+00:00 | 247.38 | 247.53 | 246.19 | 246.8 | 1706 |
| 2026-02-02T15:30:00+00:00 | 246.8 | 246.84 | 245.97 | 246.26 | 2053 |
| 2026-02-02T15:35:00+00:00 | 246.26 | 247.36 | 246.26 | 247.07 | 1846 |
| 2026-02-02T15:40:00+00:00 | 247.07 | 247.16 | 246.38 | 246.53 | 1789 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-31T19:35:00+00:00 | 279.13 | 279.68 | 278.87 | 279.05 | 1071 |
| 2026-07-31T19:40:00+00:00 | 279.05 | 279.05 | 278.48 | 278.84 | 1115 |
| 2026-07-31T19:45:00+00:00 | 278.84 | 279.65 | 278.76 | 279.09 | 1115 |
| 2026-07-31T19:50:00+00:00 | 279.09 | 280.71 | 279.08 | 279.91 | 1357 |
| 2026-07-31T19:55:00+00:00 | 279.91 | 279.97 | 278.48 | 278.85 | 1758 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('AMZN_5m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('AMZN_5m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('AMZN_5m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **AMZN** archive on **[getdata.finance](https://getdata.finance/datasets/amzn)** includes **9 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W) — **239,992** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full AMZN dataset on getdata.finance](https://getdata.finance/datasets/amzn)**

---
*GetData · AMZN 5m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/amzn) · 2026-08-04 UTC*
