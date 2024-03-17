# 🎟️ Stablepoint

Unified and direct stable asset "restaking" protocol enabling decentralized applications. Using v4 Hooks with Uniswap / PancakeSwap. Built using Scaffold-Eth2, Foundry, Solidity, and Uniswap/PancakeSwap v4s.

## Requirements

Following setup tools may be necessary 
- [Foundry] (https://github.com/foundry-rs/foundry)
- [Git](https://git-scm.com/downloads)
- Connection to Arbitrum Sepolia Testnet


## Quickstart

1. Clone this repo & install dependencies

```
git clone https://github.com/SamuelMoor-Smith/ETHGlobal-hooks-foundry
yarn install
```

2. Note the necessary existing deployments on Arbitrum Sepolia

Deployments (Uniswap) 
```
https://sepolia-rollup.arbitrum.io/rpc
PoolManager deployed to 0xE5dF461803a59292c6c03978c17857479c40bc46
PoolModifyLiquidityTest deployed to 0xd962b16F4ec712D705106674E944B04614F077be
```

3. Customize and Deploy necessary contracts

- [Initialize Uniswap v4 Pool](https://www.v4-by-example.org/), via provided scripts and existing contracts
- Stablepoint token contract
- Tokensale
- Vault (Stake Router)
- Game1 (or custom Application)

4. Mint $STBPT

Using modifyLiquidity after initializing liquidity


  

