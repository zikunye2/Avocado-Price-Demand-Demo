# Avocado Price & Demand Demo

A live demo for coding agents: analyze the relationship between avocado prices and demand, then build an executive dashboard.

## What's Inside

```
workspace/avocado.csv   ← 33,000+ weekly records (2015–2020)
prompt.md               ← Starter prompt for the coding agent
examples/               ← Sample outputs from Claude Code and Codex
```

## How to Use

1. Open this folder in a coding agent (Claude Code, Codex, Cursor, etc.)
2. Paste the prompt from `prompt.md`
3. The agent will work inside the `workspace/` folder — that's where the data lives
4. Review the output and iterate

## Dataset

Real data from the [Hass Avocado Board](https://hassavocadoboard.com), sourced via [Kaggle](https://www.kaggle.com/datasets/timmate/avocado-prices-2020).

| Column | Description |
|--------|-------------|
| date | Weekly observation date (2015–2020) |
| average_price | Average price of a single avocado |
| total_volume | Total avocados sold |
| 4046, 4225, 4770 | Volume by PLU code (size) |
| total_bags, small_bags, large_bags, xlarge_bags | Volume by bag type |
| type | Conventional or organic |
| year | Year |
| geography | City, region, or "Total U.S." (54 markets) |

## The Question

*When avocado prices go up, how much does demand drop?* A classic price elasticity problem — the coding agent will run a regression and visualize the answer.
