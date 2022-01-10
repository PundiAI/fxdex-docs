# What is f(x)Dex

`f(x)Dex` is the name of the Cosmos SDK application for FunctionX.

About the FunctionX Dex: The FunctionX Dex also known as a dex is the first Dex to be launched on the FunctionX Network. The role of a Dex is to facilitate stock pepetural dex. The FunctionX Dex is a public Proof-of-Stake chain. It's native coin is the FX.

* `fxdexd`: The f(x)Dex Daemon and command-line interface (CLI) runs a full-node of the `fxdexd` application.

`f(x)Dex` is built on the Cosmos SDK using the following modules:

* `x/auth`: Accounts and signatures.
* `x/bank`: Token transfers.
* `x/staking`: Staking logic.
* `x/distribution`: Fee distribution logic.
* `x/slashing`: Slashing logic.
* `x/gov`: Governance logic.
* `ibc-go/modules`: Inter-blockchain communication. Hosted in the `cosmos/ibc-go` repository.
* `x/params`: Handles app-level parameters.

Next, learn how to [install f(x)Dex](installation.md).
