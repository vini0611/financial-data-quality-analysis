# Financial Data Quality Analysis

Practice project simulating a real-world data quality investigation task.

## Scenario
You are a Data Quality Analyst. A portfolio manager has flagged that
something looks "off" with a recent market data extract. Your job is to
investigate `data/market_data_raw.csv`, find the issues, quantify them,
and produce a short findings report.

## Structure
- `data/market_data_raw.csv` — raw market data extract (price, volume, sector, asset class)
- `notebooks/` — your working notebook(s)

## The Brief

> From: Sarah Chen, Portfolio Manager
> Subject: Something's off with the data export
>
> Hey — can you take a look at `market_data_raw.csv`? I was pulling together
> our daily monitoring report and a few numbers looked completely wrong
> (one ticker's price made no sense on one date). I don't have time to dig
> through it myself, but I need to know:
>
> 1. Can we trust this dataset, or are there real issues in it?
> 2. If there are issues, how bad are they — which tickers/dates are affected?
> 3. Can you give me a cleaned version I can actually use?
> 4. Anything you think should be flagged to the vendor?
>
> Thanks — need this before market open tomorrow.