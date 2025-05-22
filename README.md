# 🚀 Fund Me Dapp

A secure, decentralized crowdfunding smart contract built with [Foundry](https://github.com/foundry-rs/foundry) and Solidity. Accepts ETH contributions, enforces a minimum USD value via Chainlink price feeds, and allows only the owner to withdraw funds.

---

## ✨ Features

- **Decentralized Crowdfunding:** Anyone can fund, only the owner can withdraw.
- **Chainlink Price Feeds:** Enforces a minimum funding amount in USD.
- **Gas Optimized:** Efficient withdrawal and error handling.
- **Comprehensive Testing:** Built with Foundry’s robust test suite.
- **Upgradeable & Auditable:** Modular, readable, and ready for audits.

---

## 🛠️ Getting Started

### Prerequisites

- [Foundry](https://getfoundry.sh/)
- [Node.js & npm](https://nodejs.org/)
- [Git](https://git-scm.com/)

### Installation

```bash
git clone https://github.com/0xAbubakarBL/Foundry-Fund-Me.git
cd Foundry-Fund-Me
forge install
```

### Environment Setup

Copy `.env.example` to `.env` and fill in your variables.

---

## 🚩 Usage

### Deploy

```bash
forge script script/DeployFundMe.s.sol --broadcast --rpc-url <YOUR_RPC_URL>
```

### Test

```bash
forge test
```

### Fund

Send ETH to the contract address using your wallet or scripts.

---

## 🌐 Demo

- **Sepolia Testnet Contract:**  
  [0x9CC301Aeb678a404eF21F43d3aAfEfCA7ac53199 on Etherscan](https://sepolia.etherscan.io/address/0x9CC301Aeb678a404eF21F43d3aAfEfCA7ac53199)

---

## 🧪 Testing

- Unit and integration tests are in the `test/` directory.
- Run all tests with `forge test`.

---

## 🔒 Security

- Uses [OpenZeppelin Contracts](https://github.com/OpenZeppelin/openzeppelin-contracts) for best practices.
- Chainlink price feeds for reliable USD conversion.
- Custom errors for gas savings and clarity.

---

## 🤝 Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

## 📄 License

This project is licensed under the MIT License.

---

## 📬 Contact

- Twitter: [@0xAbubakarBL](https://x.com/0xAbubakarBL)
- Email: 0xAbubakarBL@gmail.com

---

> Built with ❤️ using [Foundry](https://github.com/foundry-rs/foundry) and [OpenZeppelin](https://github.com/OpenZeppelin/openzeppelin-contracts)