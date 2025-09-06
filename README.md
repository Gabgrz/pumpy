# Pumpy

A Solidity project featuring a PUMP token and NFT collection with ROI-based rewards.

## Overview

**Pumpy** consists of two main contracts:

- **PUMP Token** (`Pumpy.sol`) - An ERC20 token with 1 trillion total supply
- **PumpyNFT** (`PumpyNFT.sol`) - An ERC721 NFT collection with 650 max supply and ROI-based token types

## Features

### PUMP Token
- ERC20 standard implementation
- 1,000,000,000,000 PUMP total supply
- All tokens minted to deployer

### PumpyNFT
- 650 unique NFTs maximum
- 6 different ROI types (0.5% to 5%)
- Mint with PUMP tokens (burned on mint)
- Dynamic metadata based on ROI type
- Owner-controlled pricing and metadata

## Contracts

- `src/Pumpy.sol` - PUMP ERC20 token
- `src/PumpyNFT.sol` - NFT collection with ROI mechanics

## Setup

```bash
# Install dependencies
forge install

# Build contracts
forge build

# Run tests
forge test
```

## License

MIT