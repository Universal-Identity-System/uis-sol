# Universal Identity System

The Universal Identity System is a DID standard for the future: free, scalable, and verifiable.

Supporting all EVM account types: EOA, Contract, and Smart Wallets.

## Getting Started

The UIS smart contracts utilize [EIP-3668](https://eips.ethereum.org/EIPS/eip-3668) for offchain data lookups.

Start Backend:

```sh
pnpm ts-node ./server/app.ts
```

Run Tests:
```sh
forge test --via-ir -vvv
```

## Usage

This is a list of the most frequently needed commands.

### Build

Build the contracts:

```sh
$ forge build
```

### Clean

Delete the build artifacts and cache directories:

```sh
$ forge clean
```

### Compile

Compile the contracts:

```sh
$ forge build
```

### Coverage

Get a test coverage report:

```sh
$ forge coverage
```

### Format

Format the contracts:

```sh
$ forge fmt
```

## License

This project is licensed under MIT.
