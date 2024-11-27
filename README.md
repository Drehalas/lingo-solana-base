# Lingo Token Bridge

## Overview
The **Lingo Token Bridge** enables seamless cross-chain transfer of the $LINGO token between the **Solana** and **Base** blockchains using the **Wormhole Protocol**. It leverages **Solana's Token 2022** standard to support advanced features such as customizable royalty fees and address whitelisting.

## Features
- **Cross-Chain Transfers**: Transfer $LINGO between Solana and Base via Wormhole.
- **Dynamic Royalties**: Adjustable transfer fees (0-5%) on Solana.
- **Whitelist Support**: Exempt selected addresses from royalties.
- **DEX Compatibility**: $LINGO is compatible with Solana DEXes like Raydium and Jupiter.
- **NTT Compliance**: Implements Wormhole's Native Token Transfer (NTT) framework for smooth integration.

---

## File Structure
```plaintext
.
├── contracts/                 # Smart contracts for Solana and Base
│   ├── solana/                # Solana Token 2022 program
│   ├── base/                  # Base (EVM) contracts
│   └── shared/                # Wormhole interface contracts
├── scripts/                   # Deployment and utility scripts
├── tests/                     # End-to-end and unit tests
├── frontend/                  # UI for interacting with the bridge
├── config/                    # Configuration files
├── README.md                  # Project overview and instructions
└── .env                       # Environment variables
