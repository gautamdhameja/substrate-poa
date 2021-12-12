# Substrate PoA

A sample Substrate runtime for a PoA blockchain that allows:

* Dynamically add/remove authorities.
* Automatically remove authorities when they go offline, to recover block period.
* Add authorities again when they come back online.

The runtime uses the [Substrate Validator Set pallet](https://github.com/gautamdhameja/substrate-validator-set) for the above functionalities.

To understand the concepts in detail, read this blog post - ["Building a resilient PoA network with Substrate"](https://www.gautamdhameja.com/resilient-poa-network-substrate/).

## Run

Follow the steps in [this guide](https://github.com/gautamdhameja/substrate-validator-set/blob/master/docs/local-network-setup.md) to run a local network using this node.

## Disclaimer

This code not audited and reviewed for production use cases. You can expect bugs and security vulnerabilities. Do not use it as-is in real applications.
