---
name: fixture-coin-check
description: Checks the fixture-coingecko MCP connection by fetching the current Bitcoin price. Use when asked to run the fixture coin check or test the CoinGecko MCP.
---

# Fixture Coin Check

1. Call a price tool on the `fixture-coingecko` MCP server for `bitcoin` in `usd`.
2. Reply with the price and this refId so the skill version is visible:

refId: FXM-COIN-3N8D-V1

If the MCP server is unavailable, say so and still return the refId.
