# 🚀 Saber Pump  

**Saber Pump** is a **decentralized token launch platform** designed to simplify and automate **token creation, liquidity provision, and fair launches** on the blockchain. Inspired by **Pump.fun**, this platform enables users to **launch tokens effortlessly** with a seamless and trustless process.  

---

## 🔥 Features  
- **Instant Token Creation**: Deploy a new token with a single click.  
- **Liquidity Management**: Automatically adds liquidity to ensure a smooth launch.  
- **Fair Launch Mechanism**: Prevents pre-mine advantages and ensures equal access.  
- **On-Chain Transparency**: All transactions and token launches are publicly verifiable.  
- **Secure & Decentralized**: Uses **smart contracts** to eliminate middlemen.  

---

## 🛠 Technologies Used  
- **Frontend**: React, Next.js, Tailwind CSS, Wagmi  
- **Backend**: Solidity Smart Contracts (Foundry)  
- **Blockchain**: Ethereum Virtual Machine (EVM)  
- **State Management**: React Hooks  
- **Wallet Connection**: Wagmi & Viem  
- **Private Key Management: Foundry's cast for secure private key storage and transaction signing
- **File Storage (Images)**: Pinata (IPFS)

---

## 📌 Getting Started  

### ✅ Prerequisites  
Ensure you have the following installed:  
- **Node.js** (v16 or higher)  
- **npm** or **yarn**  
- **Metamask** (Browser Extension)  
- **Ethereum testnet access** (Goerli, Sepolia)  
- **Foundry** (for Solidity smart contract development)  
- **Wagmi & Viem** (for blockchain interaction)  


### Installation
1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/crowdfunding-dapp.git
   cd crowdfunding-dapp
   
3. Install Dependencies:
   ```bash
   npm install  # or yarn install

4. Start Development Server:
   ```bash
   npm run dev  # or yarn dev

### Smart Contract Deployment Using Foundry

1. install Foundry (If not already installed):
   ```bash
   curl -L https://foundry.paradigm.xyz | bash
   foundryup

2. Compile the Contract: 
   ```bash
   forge build

3. Run test:
   ```bash
   forge test

4. Deploy to a testnet (e.g., Sepolia or Goerli):
   
  ```bash
  forge script script/DeploySimpleStorage.s.sol --rpc-url $RPC_URL --broadcast --private-key $PRIVATE_KEY
  forge script script/DeploySimpleStorage.s.sol --rpc-url http://127.0.0.1:8545 --broadcast --account nameOfAccountGoesHere --sender 0xf39fd6e51aad88f6f4ce6ab8827279cfffb92266
