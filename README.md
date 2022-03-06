# Margined Protocol Perpertuals

This repo contains a the Margined Protocol a decentralized perpetual contract protocol on the Terra Blockchain.
## Get started

### Environment Setup

- Rust v1.44.1+
- `wasm32-unknown-unknown` target
- Docker

1. Install `rustup` via https://rustup.rs/

2. Run the following:

```sh
rustup default stable
rustup target add wasm32-unknown-unknown
```

3. Make sure [Docker](https://www.docker.com/) is installed

### Unit / Integration Tests

Each contract contains Rust unit and integration tests embedded within the contract source directories. You can run:

```sh
cargo unit-test
cargo integration-test
```
### Build

Clone this repository and build the source code:
```
git clone git@github.com:margined-protocol/mrgnd-perpetuals.git
cd mrgnd-perpetuals
cargo build
```

## Reading / Docs

* [Perpetual Protocol](https://docs.perp.fi/getting-started/how-it-works/trading)
* [Audaces Protocol](https://docs.bonfida.org/collection/v/help/audaces-perpetuals/white-paper)
* [Perpetuals In-Depth](https://0xkowloon.substack.com/p/dissecting-the-perpetual-protocol)
* [Dawn of Decentralised Derivative](https://members.delphidigital.io/reports/the-dawn-of-decentralized-derivatives/)
# mrgnd-perpetuals-decimal
