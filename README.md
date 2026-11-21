# ⚾ MLB Opening & Closing Odds — 9 US Books, Pinnacle, Kalshi & Polymarket (2019–2026)

**26 games — every season from 2019 to 2026, 5 World Series games, the first closing moneyline of 12 of the 13 sources**

Most MLB odds archives give you one closing number per game, from one book.

The full dataset puts **up to 13 sources side by side on each game, in American odds**: FanDuel, DraftKings, BetMGM,
Caesars, BetRivers, BetOnline, theScore, Fanatics and Hard Rock, with Pinnacle, Bet365, Kalshi and Polymarket.
Moneyline, run line and total, plus Pinnacle's team totals: **the opening and the closing price, each with the time it
was recorded**.

→ **[Get the full archive](https://sportsdataolivier.gumroad.com/l/vjrnqv?utm_source=github&utm_medium=readme&utm_campaign=mlb_us&utm_content=hero)** — 18,242 games, March 2019 to the 2026 World Series · also on [Whop](https://whop.com/oliviersportsdata/mlb-opening-closing-odds-9-us-books-pinnacle-2019-2026/?utm_source=github&utm_medium=readme&utm_campaign=mlb_us&utm_content=whop_hero)

This sample is cut from the full file: the same 294 columns, the rows copied byte for byte, 26 of the 18,242 games.

---

## One game, every source

Brewers at Rays, Tropicana Field, World Series game 5, 28 October 2026, moneyline. All 13 sources closed it, 12 of
them with an opening price in the file. Milwaukee won 4-1 and took the series.

| Source | Open, Rays / Brewers | Close, Rays / Brewers |
|---|---|---|
| Pinnacle | +133 / -147 | +122 / -132 |
| Bet365 | +108 / -128 | +115 / -145 |
| FanDuel | +116 / -136 | +122 / -136 |
| DraftKings | +121 / -147 | +123 / -139 |
| BetMGM | +110 / -135 | +120 / -145 |
| Caesars | +107 / -124 | +125 / -150 |
| BetRivers | +112 / -134 | +115 / -137 |
| BetOnline | +112 / -123 | +122 / -135 |
| theScore | +110 / -130 | +126 / -138 |
| Fanatics | +115 / -140 | +115 / -140 |
| Hard Rock | +110 / -130 | +125 / -145 |
| Kalshi | +113 / -150 | +127 / -133 |
| Polymarket | – | +127 / -133 |

---

## What's in this sample

| | |
|---|---|
| Games | 26 — every season from 2019 to 2026 |
| Stages | 21 regular season · 5 World Series games (2019, 2020, 2022, 2025 and 2026) |
| Endings | 20 in regulation, 4 in extra innings, 2 shortened by rain |
| Prices | 1,634 |
| Sources | 13 — Pinnacle, Bet365, FanDuel, DraftKings, BetMGM, Caesars, BetRivers, BetOnline, theScore, Fanatics, Hard Rock, Kalshi, Polymarket |
| Columns | 294 |
| File | `MLB_Opening_Closing_Odds_2019-2026_SAMPLE.csv`, plus the README of the full product |

| Date | Game | Stage | Final, away–home | Sources, closing / opening ML |
|---|---|---|---|---:|
| 20 Mar 2019 | Mariners @ Athletics | Regular season | 9–7 | 1 / 1 |
| 31 Mar 2019 | Orioles @ Yankees | Regular season | 7–5 | 3 / 1 |
| 13 Apr 2019 | Cardinals @ Reds | Regular season | 2–5 | 3 / 1 |
| 13 Jun 2019 | Tigers @ Royals | Regular season | 3–7 | 2 / 1 |
| 29 Jun 2019 | Yankees @ Red Sox | Regular season | 17–13 | 2 / 1 |
| 29 Aug 2019 | Indians @ Tigers | Regular season | 2–0 | 3 / 1 |
| 30 Oct 2019 | Nationals @ Astros | World Series | 6–2 | 4 / 1 |
| 23 Jul 2020 | Yankees @ Nationals | Regular season | 4–1 (6 inn., called) | 8 / 5 |
| 2 Aug 2020 | Reds @ Tigers | Regular season | 4–3 (7 inn.) | 4 / 1 |
| 16 Sep 2020 | Giants @ Mariners | Regular season | 9–3 | 8 / 5 |
| 27 Oct 2020 | Rays @ Dodgers | World Series | 1–3 | 8 / 1 |
| 1 Apr 2021 | Twins @ Brewers | Regular season | 5–6 (10 inn.) | 8 / 6 |
| 7 Jul 2021 | Brewers @ Mets | Regular season | 3–4 (8 inn.) | 7 / 7 |
| 12 Aug 2021 | Yankees @ White Sox | Regular season | 8–9 | 7 / 7 |
| 5 Nov 2022 | Phillies @ Astros | World Series | 1–4 | 8 / 3 |
| 18 Apr 2023 | Guardians @ Tigers | Regular season | 0–1 | 6 / 3 |
| 28 Apr 2023 | Braves @ Mets | Regular season | 4–0 (5 inn., called) | 8 / 7 |
| 29 Apr 2023 | Giants @ Padres | Regular season | 11–16 | 8 / 7 |
| 20 Mar 2024 | Dodgers @ Padres | Regular season | 5–2 | 9 / 2 |
| 20 Jun 2024 | Giants @ Cardinals | Regular season | 5–6 | 9 / 8 |
| 18 Mar 2025 | Dodgers @ Cubs | Regular season | 4–1 | 10 / 1 |
| 1 Jul 2025 | Reds @ Red Sox | Regular season | 3–5 | 7 / 7 |
| 1 Nov 2025 | Dodgers @ Blue Jays | World Series | 5–4 (11 inn.) | 7 / 3 |
| 25 Mar 2026 | Yankees @ Giants | Regular season | 7–0 | 9 / 1 |
| 8 Jun 2026 | Brewers @ Athletics | Regular season | 15–14 (12 inn.) | 10 / 8 |
| 28 Oct 2026 | Brewers @ Rays | World Series | 4–1 | 13 / 12 |

*Sources* counts, out of 13, the sources with a closing / opening moneyline for that game. Why each game is
here, game by game: `sample/README.md`.

---

## In this repository

| File | Content |
|---|---|
| `sample/MLB_Opening_Closing_Odds_2019-2026_SAMPLE.csv` | the 26 games, 294 columns |
| `sample/README.md` | why each game is here, then the README of the full product |
| `MLB_US_Verify_Before_You_Buy.ipynb` | the figures of the listing and of its README recomputed from the full file (all the file can show), results shown |

---

## Columns

| Block | Columns | Content |
|---|---:|---|
| Game | 24 | `League`, `Game_ID` (`YYYYMMDD_AWAY_HOME`, official date, `_1` or `_2` for a doubleheader), `MLB_Game_PK`, `Season`, `Stage`, `Round`, `Kickoff_UTC`, `Epoch`, teams, `Venue`, `Neutral_Site`, `Doubleheader`, `Game_Number`, `Scheduled_Innings`, `Innings_Played`, probable starting pitchers, final score, `Winner`, `Total_Score`, `Margin`, `Match_Ending` |
| Pinnacle | 38 | moneyline, run line and total, opening then closing, with the time of each, plus the team totals of both teams |
| Bet365 and the 9 US books | 22 each | moneyline, run line and total, opening then closing, with the time of each |
| Kalshi, Polymarket | 6 each | moneyline only |

`{Book}_ML_Home_Open` · `{Book}_ML_Home_Close` · `{Book}_ML_Close_Time` · `{Book}_Spread_Home_Line_Close` · `{Book}_Total_Line_Close` · `Pinnacle_Team_Total_Home_Line_Close` — the prefixes are `Pinnacle_`, `Bet365_`, `FanDuel_`, `DraftKings_`, `BetMGM_`, `Caesars_`, `BetRivers_`, `BetOnline_`, `theScore_`, `Fanatics_`, `HardRock_`, `Kalshi_`, `Polymarket_`.

### How to read it

**Prices are American odds**, as integers: `-150`, and `130` for +130. **The `Spread` columns are the run line, ±1.5, written as the home team's line:** `-1.5` means the home team must win by 2 runs or more. **Extra innings count in every market**, as US books settle them. **Times are UTC**, ISO 8601 with the T and the Z. **The opening price is the first price recorded for the game, posted at most 15 days before the first pitch; the closing price is the last pre-game one.** Each one carries its own time, so you can see how close to the first pitch it was taken.

```python
import pandas as pd

df = pd.read_csv("MLB_Opening_Closing_Odds_2019-2026_SAMPLE.csv")

def prob(us):  # American odds -> implied probability
    return (-us / (-us + 100)).where(us < 0, 100 / (us + 100))

# Pinnacle's no-vig probability of the home team at the close
h, a = prob(df["Pinnacle_ML_Home_Close"]), prob(df["Pinnacle_ML_Away_Close"])
pinnacle_home = h / (h + a)

# how far four US books moved the total, open to close, in runs
books = ["FanDuel", "DraftKings", "BetMGM", "Caesars"]
total_move = pd.DataFrame({b: df[b + "_Total_Line_Close"] - df[b + "_Total_Line_Open"] for b in books})

# how close to the first pitch Bet365's closing moneyline was recorded, in minutes
start = pd.to_datetime(df["Kickoff_UTC"])
bet365_close_min = (pd.to_datetime(df["Bet365_ML_Close_Time"]) - start).dt.total_seconds() / 60
```

---

## Said plainly

- **The file starts with the 2019 season, on 20 March 2019 in Tokyo; Pinnacle starts with the 2020 season**, on 69% of the 2020 games.
- **Extra innings count in every market**, as US books settle them. **232 games of 2020 and 2021 were 7-inning doubleheader games**: `Scheduled_Innings` says so, and their totals are lower.
- **The run line is ±1.5 for every book.** Pinnacle often lists ±1 as its main handicap: its ±1.5 line is taken from its other lines.
- **An opening price is the book's first price posted at most 15 days before the first pitch.** In 2019, FanDuel and DraftKings have an opening moneyline on 2% and 7% of the games.
- **BetRivers' prices come from market snapshots.** BetRivers, Fanatics and Hard Rock have few closing prices in 2025: their record that season is market snapshots, mostly stamped after the first pitch, in-game prices that were not used. In 2026, Fanatics has opening prices on 43% of the games but few closing prices; Hard Rock and BetRivers close on about one game in ten.
- **From 31 August to 12 September 2026, Pinnacle and the US books other than Bet365 are missing on most games**: 7 of the 173 games of those days have a Pinnacle closing moneyline.
- **In 2026, Pinnacle's closing total is often an older price**: 590 of its 1,874 closing totals of 2026 were recorded more than 3 hours before the first pitch. Its moneyline and run line close a minute or two before.
- **Kalshi and Polymarket: moneyline only**, from 25 March 2026. Their closing prices are identical in 1,021 of the 2,007 games where both have one.
- **Team totals come from Pinnacle only**, 1 April 2021 to 31 August 2026.
- **No spring training, no All-Star Game, no player props, no first-five or inning lines, no live odds, no futures.** One opening and one closing price per book and market, not every move in between. Every recorded move (timestamped odds), other books or another scope: built to order on request.

---

## Verify before you buy

The figures of the listing and of its README — games, prices, the sources and their first price, coverage, opening
and closing times, the gaps stated above, the games on the listing's images — recomputed from the full file and
printed PASS or FAIL, all but what the file cannot show (the counts of prices left out while it was built):
[on Kaggle](https://www.kaggle.com/code/oliviersportsdata/mlb-us-books-odds-verify-before-you-buy) · [on GitHub](https://github.com/ovignez-hash/mlb-opening-closing-odds-us-books-pinnacle/blob/main/MLB_US_Verify_Before_You_Buy.ipynb) (results shown).

---

## The full dataset

| | Sample | Full |
|---|---|---|
| Games | 26 | 18,242 |
| Seasons | 2019 to 2026 | 2019 to 2026, through the World Series (28 Oct 2026) |
| Prices | 1,634 | 1,530,594 |
| Columns | 294 | 294 |
| Files | 1 CSV + README | 1 CSV + README |

Once a year, after the World Series, the file adds the completed season. The 2027 season comes month by month with the
[MLB US books monthly updates](https://sportsdataolivier.gumroad.com/l/dyslux?utm_source=github&utm_medium=readme&utm_campaign=mlb_us&utm_content=monthly): each month's games, same 294 columns, ready to append.

→ **[Get the full archive](https://sportsdataolivier.gumroad.com/l/vjrnqv?utm_source=github&utm_medium=readme&utm_campaign=mlb_us&utm_content=footer)** · also on [Whop](https://whop.com/oliviersportsdata/mlb-opening-closing-odds-9-us-books-pinnacle-2019-2026/?utm_source=github&utm_medium=readme&utm_campaign=mlb_us&utm_content=whop_footer)

---

## Licence

Sample: free to explore and evaluate.
Full product: single commercial user. Use the data as you wish, including the models, predictions and products you sell.
Redistribution and resale of the files, or of the raw data in another format, are not permitted.

A question, an invoice or a custom extract: contact@oliviersportsdata.com

---

*Olivier Sports Data — From Chicken Area 🐔*
