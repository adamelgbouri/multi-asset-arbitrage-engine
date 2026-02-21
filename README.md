# Multi-Asset Arbitrage Engine

Implementation of a cross-asset arbitrage detection framework in Excel.

The model covers:

- Equities (Cash-and-Cary & Reverse Cash-and-Carry)
- Commodities (Cost-of-Carry model)
- Foreign Exchange (Covered Interest Parity)

For each asset class, the engine:

- Computes the theoretical forward/futures price
- Measures market mispricing
- Automatically determines the appropriate arbitrage strategy
- Calculates the associated theoretical PnL

Arbitrage logic is entirely driven by the sign of the mispricing variable.

## Documentation

Full technical report available in:

`Arbitrage_for_Futures_and_Forwards - Report.pdf`
