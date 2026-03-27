Analyze the avocado price and sales volume dataset in `data/avocado.csv` and build an interactive executive dashboard as a single HTML file.

1. Inspect the dataset and summarize what you find (columns, data types, time range, any issues)
2. Analyze the relationship between price and demand (total_volume):
   - Run a regression of log(total_volume) on average_price, controlling for geography (market fixed effects), type (organic vs conventional), and year
   - Report the price coefficient, R², and interpret the result in business terms (price elasticity)
   - Compare this to a naive regression without controls to show why controls matter
3. Build `dashboard.html` in this folder with:
   - KPI cards: average price, total volume sold, number of markets, price elasticity estimate
   - Price vs. Volume scatter plot with regression line (use residuals after controlling for geography, or facet by a few representative markets)
   - Average price trend over time (monthly, 2015–2020)
   - Organic vs. Conventional comparison (price and volume)
   - Top 10 markets by total volume

Use Python for analysis. The dashboard must be a single self-contained HTML file (inline CSS/JS, no external dependencies) that opens in any browser. Make it professional and executive-ready.
