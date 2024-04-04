# Lotso Token and Lotso Airdrop

## Introduction

This repository contains the contract ABI as well as the source code written in Solidity for the Lotso Token and the Lotso Airdrop. These contracts are designed to introduce an innovative approach to digital tokens and airdropping techniques, leveraging Ethereum's powerful smart contract capabilities.

## Installation

To set up this project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone git@github.com:BTI-US/Lotso-Contract.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd lotso-token-and-airdrop
   ```

3. **Install Dependencies**:
   ```bash
   npm install
   ```

4. **Compile the Contracts**:
   ```bash
   truffle compile
   ```

## Usage

### Running Tests

Run tests to ensure the contracts are functioning as expected:

```bash
truffle test
```

### Deployment

Deploy the contracts to a local development network:

1. Start the Truffle development console:
   ```bash
   truffle develop
   ```

2. Deploy the contracts inside the development console:
   ```bash
   migrate
   ```

## Project Structure

- `contracts/`: Contains the Solidity code for Lotso Token and Lotso Airdrop.
- `migrations/`: Migration scripts for deploying the contracts.
- `test/`: JavaScript test files for the smart contracts.
- `truffle-config.js`: Configuration file for the Truffle framework.

## Contributing

Contributions are what make the open-source community an amazing place to learn, inspire, and create. Any contributions you make to the Lotso Token and Lotso Airdrop project are **greatly appreciated**.

Please read the contributing guidelines for details on our code of conduct, and the process for submitting pull requests to us.

## License

This project is licensed under the [LICENSE TYPE] - see the [LICENSE](LICENSE) file for details.

## Contract ABI for Lotso Token

[Lotso-Token-ABI.json](./Lotso-Token-ABI.json)

### Read Contract

[_buy_enabled](https://basescan.org/token/0xfafDA17EDEEe4413aC99F6D6443429742593e7Ac#readContract#F1)

[_previousTaxFee](https://basescan.org/token/0xfafDA17EDEEe4413aC99F6D6443429742593e7Ac#readContract#F2)

[_taxFee](https://basescan.org/token/0xfafDA17EDEEe4413aC99F6D6443429742593e7Ac#readContract#F3)

[_trading_permission](https://basescan.org/token/0xfafDA17EDEEe4413aC99F6D6443429742593e7Ac#readContract#F4)

[allowance](https://basescan.org/token/0xfafDA17EDEEe4413aC99F6D6443429742593e7Ac#readContract#F5)

[balanceOf](https://basescan.org/token/0xfafDA17EDEEe4413aC99F6D6443429742593e7Ac#readContract#F6)

[decimals](https://basescan.org/token/0xfafDA17EDEEe4413aC99F6D6443429742593e7Ac#readContract#F7)

[ethLimit](https://basescan.org/token/0xfafDA17EDEEe4413aC99F6D6443429742593e7Ac#readContract#F8)

[getReserves](https://basescan.org/token/0xfafDA17EDEEe4413aC99F6D6443429742593e7Ac#readContract#F9)

[maxHolding](https://basescan.org/token/0xfafDA17EDEEe4413aC99F6D6443429742593e7Ac#readContract#F10)

[name](https://basescan.org/token/0xfafDA17EDEEe4413aC99F6D6443429742593e7Ac#readContract#F11)

[owner](https://basescan.org/token/0xfafDA17EDEEe4413aC99F6D6443429742593e7Ac#readContract#F12)

[symbol](https://basescan.org/token/0xfafDA17EDEEe4413aC99F6D6443429742593e7Ac#readContract#F13)

[totalSupply](https://basescan.org/token/0xfafDA17EDEEe4413aC99F6D6443429742593e7Ac#readContract#F14)

[uniswapV2Router](https://basescan.org/token/0xfafDA17EDEEe4413aC99F6D6443429742593e7Ac#readContract#F16)

### Write Contract

[approve](https://basescan.org/token/0xfafDA17EDEEe4413aC99F6D6443429742593e7Ac#writeContract#F1)

[buy_enabled](https://basescan.org/token/0xfafDA17EDEEe4413aC99F6D6443429742593e7Ac#writeContract#F2)

[enable_buying](https://basescan.org/token/0xfafDA17EDEEe4413aC99F6D6443429742593e7Ac#writeContract#F3)

[excludeAccountsFromFee](https://basescan.org/token/0xfafDA17EDEEe4413aC99F6D6443429742593e7Ac#writeContract#F4)

[excludeFromFee](https://basescan.org/token/0xfafDA17EDEEe4413aC99F6D6443429742593e7Ac#writeContract#F5)

[includeAccountsInFee](https://basescan.org/token/0xfafDA17EDEEe4413aC99F6D6443429742593e7Ac#writeContract#F6)

[includeInFee](https://basescan.org/token/0xfafDA17EDEEe4413aC99F6D6443429742593e7Ac#writeContract#F7)

[renounceOwnership](https://basescan.org/token/0xfafDA17EDEEe4413aC99F6D6443429742593e7Ac#writeContract#F8)

[setFee](https://basescan.org/token/0xfafDA17EDEEe4413aC99F6D6443429742593e7Ac#writeContract#F9)

[tradingPermission](https://basescan.org/token/0xfafDA17EDEEe4413aC99F6D6443429742593e7Ac#writeContract#F10)

[transfer](https://basescan.org/token/0xfafDA17EDEEe4413aC99F6D6443429742593e7Ac#writeContract#F11)

[transferFrom](https://basescan.org/token/0xfafDA17EDEEe4413aC99F6D6443429742593e7Ac#writeContract#F12)

[transferOwnership](https://basescan.org/token/0xfafDA17EDEEe4413aC99F6D6443429742593e7Ac#writeContract#F13)

## Contract ABI for Lotso Airdrop

[Lotso-Airdrop-ABI.json](./Lotso-Airdrop-ABI.json)

### Read Contract

[_airdropAmounts](https://basescan.org/address/0x23da3D470325660208c8beB29c3b80f70f08bcac#readContract#F1)

[getAirdropAmounts](https://basescan.org/address/0x23da3D470325660208c8beB29c3b80f70f08bcac#readContract#F2)

[owner](https://basescan.org/address/0x23da3D470325660208c8beB29c3b80f70f08bcac#readContract#F3)

[tokenAddress](https://basescan.org/address/0x23da3D470325660208c8beB29c3b80f70f08bcac#readContract#F4)

### Write Contract

[claimAirdrop](https://basescan.org/address/0x23da3D470325660208c8beB29c3b80f70f08bcac#writeContract#F1)

[renounceOwnership](https://basescan.org/address/0x23da3D470325660208c8beB29c3b80f70f08bcac#writeContract#F2)

[setAirdrop](https://basescan.org/address/0x23da3D470325660208c8beB29c3b80f70f08bcac#writeContract#F3)

[setToken](https://basescan.org/address/0x23da3D470325660208c8beB29c3b80f70f08bcac#writeContract#F4)

[transferOwnership](https://basescan.org/address/0x23da3D470325660208c8beB29c3b80f70f08bcac#writeContract#F5)

[withdrawAirdrop](https://basescan.org/address/0x23da3D470325660208c8beB29c3b80f70f08bcac#writeContract#F6)