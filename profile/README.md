YieldBack.Cash
Fixed and variable yield on Stellar.

YBC takes a yield-bearing vault position and splits it into two tokens that trade separately: a principal token that redeems for the deposit at a fixed date, and a yield token that collects everything the vault earns until then. Hold PT and you have locked in a rate. Hold YT and you float with the market. An AMM between the two prices the yield the market expects.

Everything is on Stellar, as Soroban contracts, against any vault that implements SEP-56. The protocol is live on testnet.

## Repositories

| Repository | What it is |
|---|---|
| [ybc-contracts](https://github.com/YieldBack-Cash/ybc-contracts) | The protocol: factory, yield manager, PT, YT, AMM, router, treasury. Rust, Soroban. Release binaries and the testnet deployment record. |
| [ybc-vaults](https://github.com/YieldBack-Cash/ybc-vaults) | SEP-56 vault adapters a market can be created on, one crate per yield protocol. |
| [ybc-docs](https://github.com/YieldBack-Cash/ybc-docs) | The documentation site. |
