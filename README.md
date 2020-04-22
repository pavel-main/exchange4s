# exchange4s

[Blockchain Exchange API](https://exchange.blockchain.com/api) client implementation in Scala.

Features:

- Create market and limit orders
- Cancel an order
- Subscribe to balances
- Subscribe to market data
- Subscribe to symbol reference data

## Building

To build a JAR, execute:

```sh
sbt package
```

## Examples

Check [`examples`](src/example/scala) directory. To run one of examples, execute:

```sh
sbt example:run
`````