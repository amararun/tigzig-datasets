# CRICKET

Ball-by-ball cricket from Cricsheet: Tests, ODIs, T20s and the IPL, men's and women's, with match info and a player registry.

Source: Cricsheet (cricsheet.org).

Browse on tigzig.com: https://www.tigzig.com/downloads#app-cricket · JSON for this group: https://api.tigzig.com/downloads/cricket

| Dataset | What it holds | Updated | Files |
|---|---|---|---|
| **Every delivery, all formats**<br>[Docs](https://www.tigzig.com/apis/database) | One row per ball across Test, ODI and T20 internationals, men's and women's, plus the IPL. Filter on the gender and team_type columns. | twice daily | [CSV.gz](https://api.tigzig.com/cricket/v1/download/ball_by_ball.csv.gz) · [Parquet](https://api.tigzig.com/cricket/v1/download/ball_by_ball.parquet) |
| **Match players**<br>[Docs](https://www.tigzig.com/apis/database) | Who played in each match, one row per player per match. | twice daily | [CSV.gz](https://api.tigzig.com/cricket/v1/download/match_players.csv.gz) · [Parquet](https://api.tigzig.com/cricket/v1/download/match_players.parquet) |
| **Matches**<br>[Docs](https://www.tigzig.com/apis/database) | One row per match across every format: teams, venue, date, toss and result. | twice daily | [CSV.gz](https://api.tigzig.com/cricket/v1/download/match_info.csv.gz) · [Parquet](https://api.tigzig.com/cricket/v1/download/match_info.parquet) |
| **Player register**<br>[Docs](https://www.tigzig.com/apis/database) | One row per person, with the identifiers used across the other tables. | twice daily | [CSV.gz](https://api.tigzig.com/cricket/v1/download/people.csv.gz) · [Parquet](https://api.tigzig.com/cricket/v1/download/people.parquet) |
| **Deliveries: IPL**<br>[Docs](https://www.tigzig.com/apis/database) | A slice of ball_by_ball with identical columns. The slices sum to it exactly, so take the slice or the whole, never both. | twice daily | [CSV.gz](https://api.tigzig.com/cricket/v1/download/ball_by_ball_ipl.csv.gz) · [Parquet](https://api.tigzig.com/cricket/v1/download/ball_by_ball_ipl.parquet) |
| **Deliveries: ODI, men**<br>[Docs](https://www.tigzig.com/apis/database) | A slice of ball_by_ball with identical columns. The slices sum to it exactly, so take the slice or the whole, never both. | twice daily | [CSV.gz](https://api.tigzig.com/cricket/v1/download/ball_by_ball_odi_men.csv.gz) · [Parquet](https://api.tigzig.com/cricket/v1/download/ball_by_ball_odi_men.parquet) |
| **Deliveries: ODI, women**<br>[Docs](https://www.tigzig.com/apis/database) | A slice of ball_by_ball with identical columns. The slices sum to it exactly, so take the slice or the whole, never both. | twice daily | [CSV.gz](https://api.tigzig.com/cricket/v1/download/ball_by_ball_odi_women.csv.gz) · [Parquet](https://api.tigzig.com/cricket/v1/download/ball_by_ball_odi_women.parquet) |
| **Deliveries: T20 internationals, men**<br>[Docs](https://www.tigzig.com/apis/database) | A slice of ball_by_ball with identical columns. The slices sum to it exactly, so take the slice or the whole, never both. | twice daily | [CSV.gz](https://api.tigzig.com/cricket/v1/download/ball_by_ball_t20_men.csv.gz) · [Parquet](https://api.tigzig.com/cricket/v1/download/ball_by_ball_t20_men.parquet) |
| **Deliveries: T20 internationals, women**<br>[Docs](https://www.tigzig.com/apis/database) | A slice of ball_by_ball with identical columns. The slices sum to it exactly, so take the slice or the whole, never both. | twice daily | [CSV.gz](https://api.tigzig.com/cricket/v1/download/ball_by_ball_t20_women.csv.gz) · [Parquet](https://api.tigzig.com/cricket/v1/download/ball_by_ball_t20_women.parquet) |
| **Deliveries: Test, men**<br>[Docs](https://www.tigzig.com/apis/database) | A slice of ball_by_ball with identical columns. The slices sum to it exactly, so take the slice or the whole, never both. | twice daily | [CSV.gz](https://api.tigzig.com/cricket/v1/download/ball_by_ball_test_men.csv.gz) · [Parquet](https://api.tigzig.com/cricket/v1/download/ball_by_ball_test_men.parquet) |
| **Deliveries: Test, women**<br>[Docs](https://www.tigzig.com/apis/database) | A slice of ball_by_ball with identical columns. The slices sum to it exactly, so take the slice or the whole, never both. | twice daily | [CSV.gz](https://api.tigzig.com/cricket/v1/download/ball_by_ball_test_women.csv.gz) · [Parquet](https://api.tigzig.com/cricket/v1/download/ball_by_ball_test_women.parquet) |
| **All cricket tables in one database file**<br>[Docs](https://www.tigzig.com/apis/database) | Every table above in a single file. Open it locally and every table is already loaded. | twice daily | [DuckDB.gz](https://api.tigzig.com/cricket/v1/download/cricket_all_tables.duckdb.gz) · [SQLite.gz](https://api.tigzig.com/cricket/v1/download/cricket_all_tables.sqlite.gz) |

Licence: ODC-BY 1.0. Match data from Cricsheet (cricsheet.org). TigZig is not affiliated with or endorsed by Cricsheet.
Terms: https://api.tigzig.com/cricket/v1/terms
Provided as is, with no guarantee of accuracy, completeness or availability.

[All groups](../README.md)
