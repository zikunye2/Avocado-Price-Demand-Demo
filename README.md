# Sales Dashboard Demo

A live demo for coding agents: turn a raw sales CSV into an executive dashboard.

## What's Inside

```
data/sales_data.csv   ← 1,400+ sales records (2024–2025)
prompt.md             ← Starter prompt for the coding agent
```

## How to Use

1. Open this folder in a coding agent (Claude Code, Codex, Cursor, etc.)
2. Paste the prompt from `prompt.md`
3. Let the agent inspect the data, clean it, and build a dashboard
4. Review the output and iterate

## Dataset

| Column | Description |
|--------|-------------|
| order_id | Unique order identifier |
| date | Order date (2024-01-01 to 2025-12-30) |
| region | West, East, South, Midwest |
| category | Electronics, Office Supplies, Furniture, Software |
| sales_rep | 12 sales representatives across 4 regions |
| channel | Direct, Online, Partner (~2% missing) |
| units | Quantity sold |
| unit_price | Price per unit |
| revenue | Total revenue |
| cost | Cost of goods |
| profit | Revenue minus cost |
| customer_satisfaction | 1.0–5.0 rating (~3% missing) |

The dataset includes built-in seasonality (Q4 spike), YoY growth (~12% in 2025), and missing values for the agent to handle.
