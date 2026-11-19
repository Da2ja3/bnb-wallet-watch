# BNB Wallet Watch

Paste any BSC address and see the BNB balance, its dollar value, the live BNB price, the outgoing transaction count and the latest block. No wallet connection, no keys, nothing to install.

## How to use

Open the page, paste a BSC address (0x...) and it looks the balance up live.

## How it works

- Balance: BSC public RPC (`eth_getBalance`)
- BNB price: Binance data API, with a CoinGecko fallback
- Transaction count: `eth_getTransactionCount`
- Recent transactions are not rendered in the page: no keyless history API works from a browser page, so the page shows the transaction count and links the address out to BscScan.

## Run it locally

Just open `index.html` in a browser. It is a single self-contained page.

## License

MIT
