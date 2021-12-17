# EVM-based Chains

 * [chainlist.org](https://chainlist.org)
 * [chainid.network](https://chainid.network)

Listed by chainId according to EIP-155

Data source available on [~/ethereum-lists/chains/_data/chains.json](https://github.com/ethereum-lists/chains/tree/master/_data/chains)

## Example

```json
{
  "name": "Ethereum Mainnet",
  "chain": "ETH",
  "network": "mainnet",
  "rpc": [
    "https://mainnet.infura.io/v3/${INFURA_API_KEY}",
    "https://api.mycryptoapi.com/eth"
  ],
  "faucets": [],
  "nativeCurrency": {
    "name": "Ether",
    "symbol": "ETH",
    "decimals": 18
  },
  "infoURL": "https://ethereum.org",
  "shortName": "eth",
  "chainId": 1,
  "networkId": 1
}
```
