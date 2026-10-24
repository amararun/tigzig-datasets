# SIF (Specialized Investment Funds)

Indian Specialized Investment Funds from AMFI: daily NAV for every SIF scheme since the category began in October 2025, the scheme master, quarterly average AUM, scheme details and a list of open data issues.

Source: AMFI (Association of Mutual Funds in India).

Browse on tigzig.com: https://www.tigzig.com/downloads#app-sif · JSON for this group: https://api.tigzig.com/downloads/sif

| Dataset | What it holds | Updated | Files |
|---|---|---|---|
| **SIF average AUM by quarter**<br>[Docs](https://sif.tigzig.com/README.txt) | One row per SIF scheme per quarter: AMFI's quarterly average AUM, in Rs lakhs as filed and in Rs crore. | weekly | [csv](https://api.tigzig.com/downloads/sif_aaum.csv) · [parquet](https://api.tigzig.com/downloads/sif_aaum.parquet) |
| **SIF NAV history, every scheme, every day**<br>[Docs](https://sif.tigzig.com/README.txt) | One row per SIF scheme per date, every NAV AMFI has published since the category began in October 2025. | twice daily | [csv](https://api.tigzig.com/downloads/sif_nav.csv) · [parquet](https://api.tigzig.com/downloads/sif_nav.parquet) |
| **SIF scheme details: open data issues**<br>[Docs](https://sif.tigzig.com/README.txt) | The open issues behind blanks or as-filed values in the SIF scheme details file: funds with no scheme document at AMFI, TER filings that stopped, manager entries not split. A row disappears once the issue clears. | 3x daily | [csv](https://api.tigzig.com/downloads/sif_data_quality.csv) · [parquet](https://api.tigzig.com/downloads/sif_data_quality.parquet) |
| **SIF scheme details: scheme document, expense ratio, fund size**<br>[Docs](https://sif.tigzig.com/README.txt) | One row per SIF scheme, latest values only: what the fund's scheme summary document at AMFI says (managers, launch date, benchmark, risk band, exit load, terms), the latest TER and base expense ratio, and the latest quarterly average AUM with its quarter. Same first 60 columns as the MF scheme details file. | 3x daily | [csv](https://api.tigzig.com/downloads/sif_scheme_details_latest.csv) · [parquet](https://api.tigzig.com/downloads/sif_scheme_details_latest.parquet) |
| **SIF scheme master**<br>[Docs](https://sif.tigzig.com/README.txt) | One row per SIF scheme: codes, ISINs, fund house, SEBI strategy, plan and option, first and latest NAV, and the latest quarterly average AUM. | twice daily | [csv](https://api.tigzig.com/downloads/sif_meta.csv) · [parquet](https://api.tigzig.com/downloads/sif_meta.parquet) |

Terms: https://api.tigzig.com/mf/v1/terms
Provided as is, with no guarantee of accuracy, completeness or availability.

[All groups](../README.md)
