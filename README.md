# AUS200 2h OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-50_340_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full AUS200 dataset on ork.ad**](https://ork.ad/)

**AUS200 2h OHLCV Stock index historical data** — ultra high-quality 2h OHLCV for **Australia 200**. Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 2h OHLCV** for **Australia 200** (Stock index)
- **Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`2h`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **50,340** `2h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `2h` sample updated in sync

> **Sample on GitHub** · `AUS200_2h.csv` (2,141 rows, `2025-10-03` → `2026-07-03`). **Full archive on [ork.ad](https://ork.ad/)** — **50,340** `2h` rows (~2.72 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2008-09-10` → `2026-07-03`.

## Download sample

**[AUS200_2h.csv](https://github.com/ork-ad/aus200-2h-ohlcv-index-historical-data/blob/main/AUS200_2h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/aus200-2h-ohlcv-index-historical-data/main/AUS200_2h.csv)) · [GitHub Releases](https://github.com/ork-ad/aus200-2h-ohlcv-index-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/aus200-2h-ohlcv-index-historical-data/](https://ork-ad.github.io/aus200-2h-ohlcv-index-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | Australia 200 · Stock index | Australia 200 · Stock index |
| Timeframes | `2h` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 2h rows | 2,141 | **50,340** |
| Size | 0.12 MB | ~2.72 MB |
| Period | `2025-10-03` → `2026-07-03` | `2008-09-10` → `2026-07-03` |
| File | `AUS200_2h.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **`2h` evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `2h` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `2h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`AUS200_2h.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2025-10-03T20:00:00Z | 9013.96 | 9015.46 | 9010.94 | 9013.94 | 170.0 |
| 2025-10-05T22:00:00Z | 9013.94 | 9031.99 | 9011.0 | 9012.98 | 1386.0 |
| 2025-10-06T00:00:00Z | 9012.98 | 9014.0 | 8975.99 | 8980.5 | 1738.0 |
| 2025-10-06T02:00:00Z | 8980.5 | 8988.0 | 8975.48 | 8982.49 | 913.0 |
| 2025-10-06T04:00:00Z | 8982.49 | 8985.0 | 8970.98 | 8976.89 | 1130.0 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-07-03T12:00:00Z | 8809.24 | 8831.24 | 8808.74 | 8826.72 | 730.0 |
| 2026-07-03T14:00:00Z | 8826.72 | 8833.23 | 8821.23 | 8823.72 | 816.0 |
| 2026-07-03T16:00:00Z | 8823.72 | 8825.23 | 8817.74 | 8818.74 | 160.0 |
| 2026-07-03T18:00:00Z | 8818.74 | 8819.24 | 8811.72 | 8811.72 | 76.0 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('AUS200_2h.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('AUS200_2h.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

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

df = pd.read_csv('AUS200_2h.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='2h')
print(pf.stats())
```

## Download full data

The complete **AUS200** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **50,340** rows at `2h`, plus all other timeframes in the same ZIP.

**[→ Get the full AUS200 dataset on ork.ad](https://ork.ad/)**

---
*GetData · AUS200 2h OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-05 UTC*