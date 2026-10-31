# TigZig datasets

**Most datasets refresh daily or several times a day.** Each group page shows every dataset's schedule. Last checked 31 Oct 2026.

Free data downloads from TigZig: Indian mutual funds and SIF, global macro and markets, Indian listed-company signals, and ball-by-ball cricket. No sign-up is needed. The files are hosted on tigzig.com and this repository is the index.

| Group | What it holds | Datasets |
|---|---|---|
| [MFPRO](mf/) | Indian mutual funds from AMFI: daily NAV for every scheme since 2006, scheme details and data-quality notes. | 5 |
| [SIF (Specialized Investment Funds)](sif/) | Indian Specialized Investment Funds from AMFI: daily NAV for every SIF scheme since the category began in October 2025, the scheme master, quarterly average AUM, scheme details and a list of open data issues. | 5 |
| [TREMOR](tremor/) | Global macro, credit, valuation and market series (FDIC, NCUA, FRED, NY Fed, MoSPI, RBI, OECD, ECB and others), plus data behind the TREMOR tools. | 15 |
| [VIGIL](vigil/) | Indian listed-company signals from NSE filings: credit ratings, insider trades, pledges, takeovers, encumbrance, surveillance flags and related party transactions. | 11 |
| [CRICKET](cricket/) | Ball-by-ball cricket from Cricsheet: Tests, ODIs, T20s and the IPL, men's and women's, with match info and a player registry. | 12 |

## How to get the files

Every dataset page links straight to its files: CSV, Parquet and single-file SQLite or DuckDB databases. Each link is a plain download, so a browser, curl, wget or a Python script can fetch it. Parquet files also support HTTP range reads, so engines such as DuckDB or polars can query them in place without downloading the whole file.

- Browse every dataset: https://www.tigzig.com/downloads
- The same catalog as JSON, for scripts and AI agents: https://api.tigzig.com/downloads

## Also on Kaggle and Hugging Face

- [IPL & International Cricket Ball-by-Ball, Daily (Kaggle)](https://www.kaggle.com/datasets/amarharolikar/ipl-international-cricket-ball-by-ball)
- [IPL and International Cricket Ball-by-Ball Data, Updated Daily (Hugging Face)](https://huggingface.co/datasets/amarharolikar/ipl-international-cricket-ball-by-ball)

## Terms

Each group page names its source and links to its terms. Every dataset is provided as is, with no guarantee of accuracy, completeness or availability.
