# Split Protocol

A Solidity smart contract protocol for splitting payments or assets among multiple recipients with customizable share logic.

---

## ✨ Features

- **Split Payments:** Distribute ETH or tokens among a group of recipients.
- **Custom Shares:** Define precise shares for each participant.
- **Trustless:** No intermediaries; funds are split by contract logic.
- **Supports ETH & ERC20:** Flexible for native or tokenized payouts.

---

## 🛠️ Tech Stack

- **Solidity** (smart contract language)
- **Ethereum** (EVM-compatible chains)
- **Hardhat** or **Foundry** (recommended for local development & testing)

---

## 🚀 Quick Start

1. Clone the repo:
    ```bash
    git clone https://github.com/kyisaiah47/Split-Protocol.git
    cd Split-Protocol
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Compile contracts:
    ```bash
    npx hardhat compile
    ```

4. Run tests:
    ```bash
    npx hardhat test
    ```

---

## 📄 Usage

- **Deploy the contract** and specify recipient addresses and their respective shares.
- **Send ETH or tokens** to the contract.
- **Withdrawals** can be triggered for recipients, distributing funds based on their share.

---

## 📁 Project Structure

- `/contracts`: Solidity smart contracts
- `/test`: Test scripts (JS/TS)
- `hardhat.config.js`: Project configuration

---

## 📄 License

MIT

---

## 🙋‍♂️ Contact

For questions or collaboration: [Isaiah Kim](https://github.com/kyisaiah47)
