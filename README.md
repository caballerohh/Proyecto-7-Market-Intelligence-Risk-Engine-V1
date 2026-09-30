# Market Intelligence & Risk Monitor — V1

A Python workflow that combines cross-asset market data, risk diagnostics and automated PDF reporting into a concise market-monitoring framework.

## Purpose

The project was developed to translate market data into a structured view of risk conditions, diversification and tactical context. It connects macro-sensitive indicators, volatility measures, yield-curve information and portfolio stress scenarios within one reporting workflow.

The portfolio, observation window and written commentary remain configurable while the reporting series is being standardized.

## Analytical Scope

- Cross-asset market and risk monitoring
- Implied-volatility and volatility-regime diagnostics
- Yield-curve tracking
- Rolling correlation and diversification analysis
- Drawdown measurement
- Scenario-based portfolio stress testing
- Automated chart and PDF generation

## Report Workflow

1. Retrieve market and rate data.
2. Calculate returns, changes and risk indicators.
3. Build volatility, curve, correlation and drawdown diagnostics.
4. Apply configurable portfolio stress scenarios.
5. Render charts, tables and analytical commentary in PDF format.

## Repository Contents

| File | Description |
|---|---|
| [market_intelligence_v1.py](./market_intelligence_v1.py) | End-to-end data, analytics, visualization and reporting workflow |
| [Market_Monitoring_Executive_Report_V1.pdf](./Market_Monitoring_Executive_Report_V1.pdf) | Example output produced by the V1 workflow |

## Methods and Tools

- Market-risk indicators and implied-volatility ranges
- Relative-strength and regime diagnostics
- Yield-curve and cross-asset correlation analysis
- Drawdown and scenario stress testing
- Python: Pandas, NumPy, Matplotlib, Seaborn, yfinance and ReportLab

## Model and Data Limitations

The monitor is a decision-support tool rather than a forecasting system. Signals are sensitive to selected inputs, observation windows and market-data availability. Scenario results are hypothetical and should not be read as expected returns or guaranteed loss estimates.

## Development Context

V1 documents the initial reporting architecture. The expanded monitoring framework is available in [Market Intelligence Monitor V2](https://github.com/caballerohh/Proyecto-8-Market-Intelligence-Monitor-V2-Macro-Risk-Engine), while consolidated macro-market work is organized in [Macro Outlook & Markets Analysis](https://github.com/caballerohh/Macro-Outlook-and-Markets-Analysis).

---

This project is provided for research, education and professional portfolio purposes. It does not constitute investment advice.
