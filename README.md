# 💰 MyToken ERC20 Contract

A professionally implemented and deployed ERC20 token smart contract using Solidity and OpenZeppelin.

## ✨ Features

- ✅ ERC20 standard compliant
- 🏷️ Token metadata (name, symbol, decimals)
- 🪙 Configurable initial supply
- 🔒 Secure implementation via OpenZeppelin

## 🧰 Technologies Used

- ⚙️ Solidity ^0.8.0
- 📦 OpenZeppelin Contracts
- 🧪 Remix IDE
- 🔐 MetaMask

## 🚀 Getting Started

### 🔽 Clone the Repository

git clone repository
cd mytoken-erc20

🛠️ Deployment (via Remix)
Open Remix IDE

Create a new file and write the contract code

Compile with Solidity version ^0.8.0

In the Deploy & Run Transactions panel:

Select Remix

Set initial supply (e.g., 100)

## Deploy

🧪 Interacting with the Contract
Use the following functions post-deployment:

🔢 totalSupply() – View total supply

👛 balanceOf(address) – Check token balance

🔁 transfer(address to, uint256 amount) – Send tokens

📝 approve(address spender, uint256 amount) – Authorize spender

🚚 transferFrom(address from, address to, uint256 amount) – Delegated transfer

🔍 allowance(address owner, address spender) – Check approved amount

📄 License
This project is licensed under the MIT License.
