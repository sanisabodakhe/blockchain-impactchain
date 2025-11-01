# blockchain-impactchain

Blockchain-based Impact Measurement Platform for NGOs

## Overview

ImpactChain is a decentralized platform that enables transparent tracking and measurement of social impact for NGO projects. The platform uses blockchain technology to ensure accountability, transparency, and trust in the donation and project execution process.

## Features

- **Smart Contracts**: ERC721 Impact Tokens and Project Escrow system
- **Transparent Fund Management**: Milestone-based payment system
- **Impact Measurement**: NFT tokens for completed projects
- **Modern Frontend**: Next.js-based Web3 application
- **Wallet Integration**: Seamless MetaMask and other wallet support

## Project Structure

```
blockchain2/
├── contracts/              # Smart contracts
│   ├── ImpactToken.sol    # NFT contract for impact tokens
│   └── ProjectEscrow.sol  # Main project management contract
├── scripts/               # Deployment scripts
│   └── deploy.js         # Automated deployment script
├── test/                  # Test files
│   └── ProjectEscrow.test.js
├── frontend/              # Next.js frontend application
├── DEPLOYMENT_GUIDE.md   # Deployment instructions
└── IMPLEMENTATION_SUMMARY.md  # Implementation details
```

## Getting Started

### Prerequisites

- Node.js 18+
- Git
- MetaMask wallet
- Hardhat

### Installation

1. Clone the repository:
```bash
git clone https://github.com/sanisabodakhe/blockchain-impactchain.git
cd blockchain-impactchain
```

2. Install dependencies:
```bash
npm install
cd frontend
npm install
```

### Running the Frontend

```bash
cd frontend
npm run dev
```

The application will be available at `http://localhost:3000`

### Running Tests

```bash
npx hardhat test
```

### Deployment

See [DEPLOYMENT_GUIDE.md](./DEPLOYMENT_GUIDE.md) for detailed deployment instructions.

## Tech Stack

- **Smart Contracts**: Solidity 0.8.24, OpenZeppelin, Hardhat
- **Frontend**: Next.js 14, React 18, TypeScript, Tailwind CSS
- **Web3**: Wagmi, RainbowKit, Ethers.js
- **Testing**: Chai, Hardhat

## Documentation

- [Implementation Summary](./IMPLEMENTATION_SUMMARY.md)
- [Deployment Guide](./DEPLOYMENT_GUIDE.md)

## License

MIT
