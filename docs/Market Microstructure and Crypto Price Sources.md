# Market Microstructure and Crypto Price Sources

## Overview

This document explains the market microstructure perspective behind crypto price-source research.

Market microstructure studies how prices are formed through trading rules, order books, liquidity, transaction costs, information flow, and short-term market behavior.

For crypto assets such as BTC, ETH, and SOL, different data systems may observe the same asset but produce different price references.

This project compares exchange-based prices and oracle-based prices to understand how different market structures affect observed prices.

## Exchange Market Structure

Centralized exchanges such as Binance produce prices through active trading.

Exchange prices are influenced by:

- Limit orders
- Market orders
- Order book depth
- Bid-ask spread
- Liquidity providers
- Taker flow
- Short-term volatility
- Real transaction activity

Because exchange prices are formed through direct trading, they can react quickly to new information.

## Order Book Liquidity

An exchange order book contains buy and sell orders at different price levels.

Important order book concepts include:

- Best bid
- Best ask
- Mid price
- Spread
- Depth
- Slippage
- Liquidity concentration

A highly liquid order book usually has tighter spreads and deeper order depth.

A thin order book may produce larger short-term price jumps, especially when market orders consume available liquidity.

## Bid-Ask Spread

The bid-ask spread is the difference between the best ask price and the best bid price.

```text
spread = best_ask - best_bid
