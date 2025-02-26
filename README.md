# EVM Block Explorer

![EVM Block Explorer](http://localhost:3000/examples/_attachments/evm_block_explorer.png)

The EVM Block Explorer example demonstrates how an ICP smart contract can obtain information directly from other blockchain networks. Using HTTPS outcalls, smart contracts on ICP can interact with other networks without needing to go through a third-party service such as a bridge or an oracle. Supported interactions with other chains include querying network data, signing transactions, and submitting transactions directly to other networks.
In this example, you'll also see how to sign transactions with canister ECDSA or Schnorr signatures.

This application's logic is written in [Rust](https://internetcomputer.org/docs/current/developer-docs/backend/rust/).

### Project structure

The `/backend` folder contains the Rust smart contract:

- `Cargo.toml`, which defines the crate that will form the backend
- `lib.rs`, which contains the actual smart contract, and exports its interface

The `/frontend` folder contains web assets for the application's user interface. The user interface is written using the React framework.

## Continue building locally

To migrate your ICP Ninja project off of the web browser and develop it locally, follow these steps.

### 1. Download your project from ICP Ninja using the 'Download files' button.

### 2. Open the `BUILD.md` file for further instructions.
