# Valuation Screener

A lightweight Jupyter + Excel workflow to build an equity **valuation screener** from vendor data, then produce a **cleaned valuation analysis** ready for filtering and presentation.

## What it does

* Pulls fundamentals/price data (via vendor API) in a notebook.
* Computes core valuation metrics (e.g., **Enterprise Value**, **EV/EBITDA**, **ROE**, **ROIC**, Debt, Cash, Market Cap).
* Exports a raw screener to Excel.
* Cleans and formats the screener into an analysis workbook for quick filtering/sorting.

Make sure to have EIKON_APP_KEY in .env in order to run
