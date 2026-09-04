# USOIL 30m OHLCV Commodities Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-205_497_rows-blue)](https://getdata.finance/datasets/usoil) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/usoil)

### -> [**Download the full USOIL dataset on getdata.finance**](https://getdata.finance/datasets/usoil)

**USOIL 30m OHLCV commodities historical data** — ultra high-quality 30m OHLCV for **WTI Crude Oil**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 30m OHLCV** for **WTI Crude Oil** (Commodities)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`30m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/usoil) · **205,497** `30m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `30m` sample updated in sync

> **Sample on GitHub** · `USOIL_30m.csv` (1,848 rows, `2026-07-07` -> `2026-09-02`, 137.78 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/usoil)** — **205,497** `30m` rows (full `1m`: 5,981,180), **11 timeframes**, `2008-09-10` -> `2026-09-02`.

## Download sample

**[USOIL_30m.csv](https://github.com/getdata-finance/usoil-30m-ohlcv-commodities-historical-data/blob/main/USOIL_30m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/usoil-30m-ohlcv-commodities-historical-data/main/USOIL_30m.csv)) · [GitHub Releases](https://github.com/getdata-finance/usoil-30m-ohlcv-commodities-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/usoil-30m-ohlcv-commodities-historical-data/](https://getdata-finance.github.io/usoil-30m-ohlcv-commodities-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/usoil](https://getdata.finance/datasets/usoil)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/usoil))** |
|---|--:|---|
| Instrument | WTI Crude Oil · Commodities | WTI Crude Oil · Commodities |
| Timeframes | `30m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 30m rows | 1,848 | **205,497** |
| Size | 137.78 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/usoil) |
| Period | `2026-07-07` -> `2026-09-02` | `2008-09-10` -> `2026-09-02` |
| File | `USOIL_30m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/usoil) |
| Coverage report | — | [USOIL coverage](https://getdata.finance/coverage/usoil) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`30m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/usoil)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `30m` sample · [getdata.finance](https://getdata.finance/datasets/usoil) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `30m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`USOIL_30m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-07T22:30:00+00:00 | 72.362 | 72.439 | 72.298 | 72.413 | 329 |
| 2026-07-07T23:00:00+00:00 | 72.413 | 72.439 | 72.228 | 72.394 | 383 |
| 2026-07-07T23:30:00+00:00 | 72.394 | 72.449 | 72.207 | 72.369 | 444 |
| 2026-07-08T00:00:00+00:00 | 72.369 | 72.659 | 72.308 | 72.504 | 1452 |
| 2026-07-08T00:30:00+00:00 | 72.504 | 72.509 | 71.913 | 71.938 | 1495 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-02T00:00:00+00:00 | 90.759 | 91.304 | 90.667 | 91.128 | 3344 |
| 2026-09-02T00:30:00+00:00 | 91.128 | 92.044 | 91.109 | 92.039 | 5077 |
| 2026-09-02T01:00:00+00:00 | 92.039 | 92.274 | 91.379 | 91.678 | 8823 |
| 2026-09-02T01:30:00+00:00 | 91.678 | 91.978 | 91.242 | 91.298 | 5347 |
| 2026-09-02T02:00:00+00:00 | 91.298 | 91.298 | 91.258 | 91.287 | 72 |

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

df = pd.read_csv('USOIL_30m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('USOIL_30m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('USOIL_30m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='30min')
print(pf.stats())
```

## Download full data

The complete **USOIL** archive on **[getdata.finance](https://getdata.finance/datasets/usoil)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **205,497** rows at `30m`, plus all other timeframes in the same ZIP.

**[-> Get the full USOIL dataset on getdata.finance](https://getdata.finance/datasets/usoil)**

---
*GetData · USOIL 30m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/usoil)*
