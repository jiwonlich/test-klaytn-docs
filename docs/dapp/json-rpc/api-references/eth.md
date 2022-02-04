---
description: >-
`eth` namespace APIs.
---

# Namespace eth <a id="namespace-eth"></a>

The namespace `eth` provides functions related to accounts, blocks, transactions,
configurations of networks or nodes, filters, and so on.

Klaytn now supports [eth namespace apis](https://eth.wiki/json-rpc/API). But Please note that
there are some fields returning correction values. Below is the overview of that fields.

And due to the fundamental design differences existing between Klaytn and Ethereum,
Klaytn's data structure (Transaction, Block, TransactionReceipt) cannot be fully supported via eth namespace APIs.

**NOTE**: `eth` namespace APIs are supported from Klaytn v1.8.0.