<div align="center">

# Electrum ZEC

**Lightweight desktop wallet for Zcash (ZEC)**

![Zcash](https://img.shields.io/badge/Zcash-ZEC-F4B728?style=flat-square)
![Wallet](https://img.shields.io/badge/Client-Electrum--based-343A40?style=flat-square)
![Desktop](https://img.shields.io/badge/Interface-Desktop-343A40?style=flat-square)

</div>

Electrum ZEC is a desktop wallet project built around the Electrum client model. It focuses on wallet management, local transaction signing, and server-assisted blockchain access without downloading the full chain.

## Overview

| | |
| --- | --- |
| **Network** | Zcash |
| **Currency** | ZEC |
| **Client type** | Lightweight / Electrum-style |
| **Interface** | Desktop |
| **Synchronization** | Remote wallet server |

## Wallet Operations

- Create or restore a wallet from recovery data
- Manage addresses and transaction history
- Prepare, sign, and send ZEC transactions
- Monitor balances and transaction status
- Configure server connectivity

> Zcash transparent and shielded transactions use different protocols. Supported address types and transaction modes depend on the implementation in this repository.

## Installation

Download available desktop packages from [Releases](../../releases). Choose the build for your operating system and check the release notes before installing.

For a source build, use the dependency and launch instructions shipped with the corresponding version of the code.

## Development

The project follows an Electrum-style separation between wallet logic, network communication, transaction handling, and desktop UI. Consult the source tree for the current entry point, build scripts, and test commands.

## Security

Wallet keys and recovery phrases must remain private. Test the wallet with a small amount before transferring significant funds.

## License

See the `LICENSE` or equivalent license file in the repository for terms covering the included code.
