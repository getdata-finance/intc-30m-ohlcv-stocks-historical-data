# INTC 30m OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-40_547_rows-blue)](https://getdata.finance/datasets/intc) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/intc)

### -> [**Download the full INTC dataset on getdata.finance**](https://getdata.finance/datasets/intc)

**INTC 30m OHLCV stocks historical data** — ultra high-quality 30m OHLCV for **Intel**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 30m OHLCV** for **Intel** (US stocks)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`30m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/intc) · **40,547** `30m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `30m` sample updated in sync

> **Sample on GitHub** · `INTC_30m.csv` (1,651 rows, `2026-03-23` -> `2026-09-22`, 156.72 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/intc)** — **40,547** `30m` rows (full `1m`: 634,759), **11 timeframes**, `2011-05-09` -> `2026-09-22`.

## Download sample

**[INTC_30m.csv](https://github.com/getdata-finance/intc-30m-ohlcv-stocks-historical-data/blob/main/INTC_30m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/intc-30m-ohlcv-stocks-historical-data/main/INTC_30m.csv)) · [GitHub Releases](https://github.com/getdata-finance/intc-30m-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/intc-30m-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/intc-30m-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/intc](https://getdata.finance/datasets/intc)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/intc))** |
|---|--:|---|
| Instrument | Intel · US stocks | Intel · US stocks |
| Timeframes | `30m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 30m rows | 1,651 | **40,547** |
| Size | 156.72 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/intc) |
| Period | `2026-03-23` -> `2026-09-22` | `2011-05-09` -> `2026-09-22` |
| File | `INTC_30m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/intc) |
| Coverage report | — | [INTC coverage](https://getdata.finance/coverage/intc) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`30m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/intc)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `30m` sample · [getdata.finance](https://getdata.finance/datasets/intc) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `30m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`INTC_30m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-23T13:30:00+00:00 | 43.43 | 44.74 | 43.43 | 44.59 | 7516 |
| 2026-03-23T14:00:00+00:00 | 44.59 | 45.01 | 44.04 | 44.85 | 5940 |
| 2026-03-23T14:30:00+00:00 | 44.85 | 44.94 | 44.31 | 44.5 | 6917 |
| 2026-03-23T15:00:00+00:00 | 44.5 | 44.8 | 44.09 | 44.17 | 5234 |
| 2026-03-23T15:30:00+00:00 | 44.17 | 44.37 | 43.32 | 43.42 | 6319 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-22T17:30:00+00:00 | 121.64 | 122.24 | 121.43 | 121.78 | 4955 |
| 2026-09-22T18:00:00+00:00 | 121.78 | 123.17 | 121 | 122.85 | 5741 |
| 2026-09-22T18:30:00+00:00 | 122.85 | 123.1 | 122.27 | 122.67 | 5879 |
| 2026-09-22T19:00:00+00:00 | 122.67 | 123.1 | 122.62 | 122.73 | 5215 |
| 2026-09-22T19:30:00+00:00 | 122.73 | 124.03 | 122.6 | 123.78 | 8309 |

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

df = pd.read_csv('INTC_30m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('INTC_30m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('INTC_30m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='30min')
print(pf.stats())
```

## Download full data

The complete **INTC** archive on **[getdata.finance](https://getdata.finance/datasets/intc)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **40,547** rows at `30m`, plus all other timeframes in the same ZIP.

**[-> Get the full INTC dataset on getdata.finance](https://getdata.finance/datasets/intc)**

---
*GetData · INTC 30m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/intc)*
