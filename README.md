# galxe-token-list
This repo contains the default token list used in the Galxe token reward campaign

## How to add token

### 1. Modify tokens.json
  Navigate to the src/tokens.json file in this repository and add your token's details in the format provided:
```json
{
   "name": "YOUR_TOKEN_NAME",
   "address": "YOUR_TOKEN_CONTRACT_ADDRESS",
   "symbol": "YOUR_TOKEN_SYMBOL",
   "decimals": TOKEN_DECIMALS,
   "chainId": YOUR_CHAIN_ID,
   "logoURI": "YOUR_TOKEN_LOGO_URL"
}
```

### 2. Submit a Pull Request (PR)
Confirm your changes and submit the PR with a meaningful title and description.
Our team will review your PR and, if everything looks good, your token will be added to the Galxe Token Reward Campaign.

### Example Token Format

```json
{
   "name": "Wrapped Ether",
   "address": "0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2",
   "symbol": "WETH",
   "decimals": 18,
   "chainId": 1,
   "logoURI": "https://raw.githubusercontent.com/trustwallet/assets/master/blockchains/ethereum/assets/0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2/logo.png"
}
```

### Common Chain IDs
Chain IDs are unique numerical identifiers for different blockchain networks.
Below are some common chain IDs:
* Ethereum Mainnet: 1
* BNB Smart Chain Mainnet: 56
* Arbitrum One: 42161
* OP Mainnet: 10
* Polygon Mainnet: 137

If you are unsure about the correct chain id for your token or if you need to find the ID for another blockchain, you can visit https://chainlist.org/ to find the appropriate ID for your desired chain.
