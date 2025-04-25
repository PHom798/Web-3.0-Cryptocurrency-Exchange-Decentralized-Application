# Web 3.0 Cryptocurrency Exchange dApp

A decentralized cryptocurrency exchange React application with Metamask pairing, live smart contract data fetching, and the ability to create your own ERC20 tokens, swap them, and more!


## 🚀 Features

- **Decentralized Exchange**: Trade cryptocurrencies directly from your wallet without intermediaries
- **Metamask Integration**: Seamless wallet connection for secure transactions
- **ERC20 Token Creation**: Deploy and manage your own ERC20 tokens effortlessly
- **Live Smart Contract Data**: Real-time fetching and display of smart contract information
- **Token Swapping**: Instantly swap between different ERC20 tokens
- **User-Friendly Interface**: Intuitive design for both novice and experienced users

## 🛠️ Technologies Used

- **Frontend**: React.js, Tailwind CSS
- **Blockchain Interaction**: Ethers.js, Web3.js
- **Smart Contracts**: Solidity, Hardhat
- **Wallet Integration**: Metamask


## 📋 Prerequisites

Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v14 or newer)
- [npm](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/)
- [Metamask Extension](https://metamask.io/download.html) for your browser
- [Hardhat](https://hardhat.org/) for smart contract development

## 📦 Installation

1. **Clone the repository**:
   ```
   git clone https://github.com/PHom798/Web-3.0-Cryptocurrency-Exchange-Decentralized-Application.git
   cd Web-3.0-Cryptocurrency-Exchange-Decentralized-Application
   ```

2. **Install dependencies**:
   ```
   npm install
   # or
   yarn install
   ```

3. **Start the development server**:
   ```
   npm start
   # or
   yarn start
   ```

4. **Compile smart contracts** (in a separate terminal):
   ```
   npx hardhat compile
   ```

## 🚀 Quick Start Guide

1. **Connect your wallet**:
   - Open the application in your browser
   - Click the "Connect Wallet" button
   - Approve the connection in your Metamask extension

2. **Create your first token**:
   - Navigate to the "Create Token" section
   - Fill in the token details (name, symbol, supply)
   - Deploy your token to the blockchain

3. **Make your first swap**:
   - Go to the "Swap" section
   - Select the tokens you want to exchange
   - Enter the amount and confirm the transaction

## 🔧 Usage

1. **Connect Wallet**: Open the application and connect your Metamask wallet
2. **Create ERC20 Token**: Navigate to the token creation section and deploy your custom token
3. **Swap Tokens**: Use the swap interface to exchange between different ERC20 tokens
4. **View Live Data**: Monitor real-time data fetched from smart contracts

## 📊 Smart Contract Details

The project includes the following main contracts:

- **TokenFactory.sol** - Creates new ERC20 tokens
- **Exchange.sol** - Handles token swaps and liquidity
- **Router.sol** - Routes transactions to the appropriate contracts

### Network Support

- Ethereum Mainnet
- Goerli Testnet
- Polygon
- Binance Smart Chain

## 📁 Project Structure

```
├── contracts/          # Solidity smart contracts
│   ├── Exchange.sol
│   ├── Router.sol
│   └── TokenFactory.sol
├── scripts/            # Deployment scripts
├── test/               # Test files
├── packages/           # Additional packages and modules
├── src/                # React frontend source code
│   ├── components/     # UI components
│   ├── contexts/       # React contexts
│   ├── hooks/          # Custom React hooks
│   ├── pages/          # Application pages
│   ├── services/       # API and blockchain services
│   └── utils/          # Utility functions
├── .env.example        # Environment variables example
├── .gitignore
├── hardhat.config.js   # Hardhat configuration
├── package.json
├── README.md
└── yarn.lock
```

## 🧪 Testing

1. **Start local blockchain**:
   ```
   npx hardhat node
   ```

2. **Run tests**:
   ```
   npx hardhat test
   ```

3. **Deploy to test network**:
   ```
   npx hardhat run scripts/deploy.js --network goerli
   ```

## 🔒 Security

- All smart contracts have been audited by [Security Firm]
- Non-custodial design ensures you always control your funds
- Open-source codebase for transparency

## 🚧 Roadmap

- **Q2 2025**: Mobile app release
- **Q3 2025**: Multi-chain support expansion
- **Q4 2025**: DAO governance implementation
- **Q1 2026**: Layer 2 integration

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some amazing feature'`)
5. Push to the branch (`git push origin feature/amazing-feature`)
6. Open a Pull Request

Please read our [Contributing Guidelines](CONTRIBUTING.md) for more details.


*Empowering decentralized finance through seamless and secure cryptocurrency exchanges.*
