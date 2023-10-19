# SEP-0040 Oracle
Exposes the interface of the SEP-0040 Price Feed Oracle alongside a test price oracle contract.

SEP-0040 Definition: https://github.com/stellar/stellar-protocol/blob/master/ecosystem/sep-0040.md

## Getting Started

Add the package to your `Cargo.toml`:

```toml
[dependencies]
sep-40-oracle = "<desired version>"
```

You can optionally include the `testutils` feature in your `dev-dependencies` to deploy a mock version of the `sep-40-oracle` for testing:

```toml
[dev_dependencies]
sep-40-oracle = { version = "<desired version>", features = ["testutils"] }
```
