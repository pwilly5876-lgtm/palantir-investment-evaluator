# Palantir Investment Evaluator

A professional web-based investment analysis tool for evaluating companies that use Palantir software platforms.

## Features

- **Live Financial Metrics** — Pulls real-time company data (P/E, EV/EBITDA, Operating Margin, ROE, FCF Yield) using the Financial Modeling Prep API.
- **Deterministic Projections** — Scenario-based future value calculations (Bear / Base / Bull / S&P 500) with live-updating charts.
- **Monte Carlo Simulation** — Probabilistic risk analysis with 5,000+ simulations, percentile outcomes, and distribution histogram.
- **Adjustable CAGRs** — Easily modify scenario growth rates to run sensitivity analysis.

## How to Use

1. Open the tool: [https://pwilly5876-lgtm.github.io/palantir-investment-evaluator/](https://pwilly5876-lgtm.github.io/palantir-investment-evaluator/)
2. Enter a ticker symbol (default is `LMT`).
3. (Optional) Replace the API key with your own free [FMP API key](https://financialmodelingprep.com) for better reliability.
4. Click **Fetch Live Metrics** to load real company data.
5. Adjust the CAGR dropdowns as needed.
6. Scroll down and click **Run Monte Carlo** to see probabilistic outcomes.

## API Key Note

- The tool uses `demo` by default (limited).
- For full functionality, get a free API key from [Financial Modeling Prep](https://financialmodelingprep.com) and paste it in the field.

## Local Development

You can also run this tool locally by opening the `index.html` file in any modern browser, or by using VS Code + Live Server extension for the best experience.

## Built With

- Tailwind CSS
- Chart.js
- Financial Modeling Prep API

---

**Note**: This is a personal analysis tool and not financial advice. All projections are hypothetical.
