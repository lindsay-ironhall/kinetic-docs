# Oracles and Pricing

Kinetic on Flare leverages the network's native oracle infrastructure as its primary data source, with external oracle support for assets not covered natively.

Kinetic uses a layered oracle system to resolve asset prices. For each asset, the protocol works through the following priority order until a valid price is found:

1. **FTSO (Flare Time Series Oracle)** the primary oracle. FTSO is Flare's native, decentralized oracle system, built directly into the network. It provides continuously updated, community-validated price feeds for assets native to the Flare ecosystem.
2. **RedStone** the primary external oracle. For assets not covered by FTSO, Kinetic integrates RedStone price feeds. RedStone is a Modular Oracle that delivers frequently updated, reliable, and diverse data feeds — including yield-bearing assets such as LSTs, LRTs, Bitcoin LSTs, and yield-accruing stablecoins.

All price data is subject to staleness thresholds. If a price exceeds its allowed age, the protocol rejects it and automatically moves to the next source in the priority order. This ensures that lending decisions are always based on current, reliable market data.
