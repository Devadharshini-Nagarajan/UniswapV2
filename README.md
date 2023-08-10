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
| File                         | % Lines          | % Statements     | % Branches     | % Funcs        |
|------------------------------|------------------|------------------|----------------|----------------|
| src/UniswapV2Factory.sol     | 100.00% (12/12)  | 100.00% (19/19)  | 100.00% (6/6)  | 100.00% (1/1)  |
| src/UniswapV2Library.sol     | 100.00% (34/34)  | 88.73% (63/71)   | 50.00% (8/16)  | 75.00% (6/8)   |
| src/UniswapV2Pair.sol        | 95.59% (65/68)   | 96.52% (111/115) | 82.14% (23/28) | 100.00% (8/8)  |
| src/UniswapV2Router.sol      | 93.02% (40/43)   | 95.31% (61/64)   | 77.27% (17/22) | 100.00% (7/7)  |
| src/libraries/Math.sol       | 88.89% (8/9)     | 91.67% (11/12)   | 75.00% (3/4)   | 100.00% (2/2)  |
| src/libraries/UQ112x112.sol  | 0.00% (0/2)      | 0.00% (0/2)      | 100.00% (0/0)  | 0.00% (0/2)    |
| test/UniswapV2Pair.t.sol     | 93.75% (15/16)   | 90.00% (18/20)   | 66.67% (4/6)   | 100.00% (4/4)  |
| test/mocks/ERC20Mintable.sol | 0.00% (0/1)      | 0.00% (0/1)      | 100.00% (0/0)  | 0.00% (0/1)    |
| Total                        | 94.05% (174/185) | 93.09% (283/304) | 74.39% (61/82) | 84.85% (28/33) |
