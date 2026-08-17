# Stock Price Prediction Pipeline

A cloud-integrated educational pipeline for historical AAPL market-data analysis using **Amazon S3, AWS Glue, Athena, Google Colab, LSTM forecasting, and Power BI**.

## Architecture

Historical data is stored and catalogued through cloud analytics services, queried for analysis, used in an LSTM experiment, and presented in a business-intelligence dashboard. The repository demonstrates how data engineering, machine learning, and visual storytelling fit together.

## Repository contents

- `README.md` — workflow, assumptions, and responsible-use guidance.
- `Stock_Prediction_Pipeline-Results.png` — example visual output.
- `aaplcsv - Sheet1.csv` — sample historical data artifact; verify provenance and licensing before redistribution.
- `stock_prediction_visuals_powerBI.pbix` — Power BI report artifact.

## Cloud safety

Never commit AWS access keys, IAM secrets, private bucket names, or customer data. Prefer least-privilege roles, environment variables, and an `.env.example` file containing placeholders only.

## Interpretation

Market forecasts are uncertain and sensitive to lookback windows, leakage, regime changes, and evaluation design. Outputs are educational research, not investment advice or a trading recommendation.
