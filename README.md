## Foundry

**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**

Foundry consists of:

-   **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
-   **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
-   **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
-   **Chisel**: Fast, utilitarian, and verbose solidity REPL.

## Documentation

https://book.getfoundry.sh/

## Usage

### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```

### Format

```shell
$ forge fmt
```

### Gas Snapshots

```shell
$ forge snapshot
```

### Anvil

```shell
$ anvil
```

### Deploy

```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```

### Cast

```shell
$ cast <subcommand>
```

### Help

```shell
$ forge --help
$ anvil --help
$ cast --help
```


Running tests...
| File                            | % Lines          | % Statements     | % Branches     | % Funcs        |
|---------------------------------|------------------|------------------|----------------|----------------|
| src/UniswapV2Factory.sol        | 100.00% (12/12)  | 100.00% (19/19)  | 100.00% (6/6)  | 100.00% (1/1)  |
| src/UniswapV2Pair.sol           | 92.86% (65/70)   | 94.87% (111/117) | 82.14% (23/28) | 80.00% (8/10)  |
| src/UniswapV2Router.sol         | 96.34% (79/82)   | 91.85% (124/135) | 65.79% (25/38) | 60.00% (9/15)  |
| src/libraries/ERC20Mintable.sol | 0.00% (0/1)      | 0.00% (0/1)      | 100.00% (0/0)  | 0.00% (0/1)    |
| src/libraries/Math.sol          | 88.89% (8/9)     | 91.67% (11/12)   | 75.00% (3/4)   | 100.00% (2/2)  |
| test/UniswapV2Pair.t.sol        | 93.75% (15/16)   | 90.00% (18/20)   | 66.67% (4/6)   | 100.00% (4/4)  |
| Total                           | 94.21% (179/190) | 93.09% (283/304) | 74.39% (61/82) | 72.73% (24/33) |