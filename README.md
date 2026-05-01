# Crypto Price Source Research

This is an academic research project comparing Binance spot market data with Chainlink Data Streams for BTC/USD, ETH/USD, and SOL/USD 5-minute price windows.

## Research Goal

The project studies:

- Timestamp alignment between exchange price data and oracle price data
- Oracle-vs-exchange basis
- 1-minute to 5-minute window construction
- Data quality checks
- Direction disagreement between different price sources
- Historical price-source behavior

## Scope

This project only collects and analyzes price-source data.

It does not:

- Execute trades
- Place orders
- Manage funds
- Connect to wallets
- Store private keys
- Provide trading signals

## Data Sources

Planned data sources:

- Binance public spot market data
- Chainlink Data Streams, subject to API access approval

If Chainlink Data Streams access is unavailable, mock data may be used only for engineering tests. Mock data is not used for research conclusions.

## Assets

- BTC/USD
- ETH/USD
- SOL/USD

## Methodology

The project builds 5-minute windows and compares Binance spot prices with Chainlink oracle prices using:

- Basis percentage
- Timestamp difference
- Direction agreement/disagreement
- Missing data ratio
- Window completeness
- Price-source quality checks

## Status

Current version:

- Binance public data collector
- 5-minute window builder
- Mock Chainlink fallback for engineering tests
- Data quality reports
- Basis comparison reports

Pending:

- Chainlink Data Streams API credentials
- BTC/USD, ETH/USD, SOL/USD stream IDs
- Historical report access
