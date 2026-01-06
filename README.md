
# 🌐 Elparadisogonzalo Home
< interface built with ❤️ for Ethereum, BSC, and unstoppable Web3 infrastructure.

---
# *Author* [`Azeh agowa genyoungclip@gmail.com`] 
*Git user* [`koagonzalo11`] 
## 📌 Project Summary

### 1. Domain & Identity

- 🌍 **Domain:** [`elparadisogonzalo.com`](https://elparadisogonzalo.com) via Unstoppable Domains  
- 💳 Wallet & IPFS resolution enabled  
- ✅ Verified domain ownership with elparadisogonzalo

### 2. Wallet & Smart Contracts

- 🔐 Wallet: `0x802ba6a112f4a7bbbc2d63c8ef4bc14dfcbe6245`  
- ⚙️ Contracts deployed on Ethereum and BNB Smart Chain  
- ✅ ABI-integrated frontend interaction  
- 🛠 Tools: MetaMask · Infura · JSON-RPC · Etherscan

### 3. Infrastructure

- ⛓ Local Ethereum node via Geth (`1.15.5-stable`) on Android (Termux)  
- ☁️ Google Cloud CLI for automation and backend orchestration  
- 📡 DNS/IPFS managed through Unstoppable Domains  

### 4. Web3 Backend/API

- 🧠 Project: [`asset3`](https://github.com/koagonzalo11/asset3)  
- 📦 Tech Stack: Node.js · Web3.js · Google & GitHub CLI  
- 🔗 APIs for contract interaction and blockchain event streaming  

### 5. Frontend & Hosting

- 🖼 IPFS-based dApp frontend hosting  
- 🦊 MetaMask wallet connect integration  
- 🔒 Security draft audited for best practices  

### 6. CI/CD & Deployment

- ⚡ GitHub Actions pipeline for auto-deploy to IPFS  
- 🌐 Auto-update Unstoppable contenthash  
- 🔄 Continuous integration for ABI + frontend + contract updates  

---

## 🛠 Setup Instructions

```bash
git clone git@github.com:koagonzalo11/elparadisogonzalo-monorepo.git
cd elparadisohonzalo-monorepo 
npm install
npx hardhat compile
npm run dev    # For local development
# Compile contracts
npx hardhat compile

# Deploy using Infura or local Geth
npx hardhat run scripts/deploy.js --network mainnet
---

## 🔍 Project Overview

### 1. 🌍 Domain & Identity
- **Domain:** [`elparadisogonzalo.com`](https://elparadisogonzalo.com) via Unstoppable Domains  
- Used for wallet, IPFS resolution, and identity  
- Verified with `openai-domain-verification=...`

### 2. 🔐 Wallet & Smart Contracts
- Primary wallet: `0x802ba6a112f4a7bbbc2d63c8ef4bc14dfcbe6245`  
- Contracts on Ethereum & BNB Smart Chain  
- Uses ABI to connect with Web3 frontend  
- Tooling: Hardhat · MetaMask · Infura · Etherscan API

### 3. ☁️ Infra & Node
- Geth 1.15.5 node on Android (Termux)  
- Google Cloud CLI for automation & backups  
- IPFS + Unstoppable DNS integration  

### 4. ⚙️ Backend APIs
- Project: [`elparadisogonzalo-monorepo`](https://github.com/koagonzalo11/elparadisohonzalo-monorepo)  
- Web3.js / Node.js event scrapers & JSON-RPC  
- Event types: `Transfer`, `Claim`, `Mint`, `Burn`, `Ownership:koagonzalo11`, etc.

### 5. 🖼 Frontend
- React/Vite dApp frontend in `/frontend`  
- Connects via MetaMask + Web3.js  
- IPFS pinned + auto-updated with GitHub Actions

---

## 🚀 Dev Quickstart

```bash
git clone https://github.com/koagonzalo11/asset3.git
cd asset3
npm install

# Compile contracts
npx hardhat compile

# Start frontend
cd frontend && npm install && npm run dev
# Upload frontend to IPFS
npm run build
npx ipfs add -r ./dist

# Update Unstoppable Domain
curl -X POST https://unstoppable/api/update \
  -H 'Authorization: Bearer $UD_API_KEY' \
  -d '{ "cid": "..." }'
/contracts       → Solidity smart contracts
/scripts         → Deployment & event indexing scripts
/frontend        → IPFS-hosted dApp UI
/api             → Node.js Web3 & utility APIs
/.github/workflows → CI/CD definitions
📚 Docs
	•	API: /contracts/api/*.ts
	•	IPFS Push: /ipfs/api/update
	•	MetaMask Connect: /frontend/api/connect
	•	Auto Verify: /ethvalidate/api/verify
🙌 Contributions

We welcome PRs, Issues, and forks.
Check out the GitHub Octocat Profile for more.
📢 License

MIT © Elparadisogonzalo

