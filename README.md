
# 🔐 Blockchain-Based Document Verification with IPFS

This project creates a **secure, decentralized** system for document verification using **Blockchain** and **IPFS (InterPlanetary File System)** technologies. The system ensures documents are tamper-proof by storing their **hashes on the blockchain** while keeping the actual documents on **IPFS**.

---

## 🚀 Features

- 🔒 **Secure verification** using Ethereum & IPFS
- 🌐 **Decentralized**—no central authority or single point of failure
- ⚡ **Fast & easy** verification without third-party involvement
- 💻 **User-friendly** UI for uploading and verifying documents
- 🧾 Supports multiple **file types and formats**

---

## 📦 Requirements

- [Node.js & npm](https://nodejs.org/)
- [MetaMask Wallet](https://metamask.io/)
- IPFS API credentials from [Infura.io](https://infura.io/)

---

## 🛠️ Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/DevAloshe/BlockChain-Based-Document-Verfication-With-IPFS.git
   cd BlockChain-Based-Document-Verfication-With-IPFS
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Deploy the Smart Contract:**

   - Use [Remix IDE](https://remix.ethereum.org/) to deploy `contract.sol`
   - After deployment, copy the **contract address**
   - Paste the address into the `app.js` file
   - Also specify:
     - **Network URL** (e.g., from MetaMask settings)
     - **Explorer URL** for that network

4. **Configure IPFS with Infura:**

   - Create an account on [infura.io](https://infura.io/)
   - Generate **Project ID** and **Secret**
   - Add them in `app.js` inside the `uploadToInfura` function

5. **Run the Application:**

   - Open the project with **Live Server** extension (VS Code or similar)

---

## ⚙️ Usage

1. **Add Exporter:**
   - Click **"Add Exporter"** button
   - Enter the exporter's MetaMask address

2. **Upload Document:**
   - Click **"Upload Document"**
   - Choose a file to upload
   - The document is encrypted and stored on **IPFS**
   - Its **hash is recorded** on the blockchain

3. **Verify Document:**
   - Click **"Verify Document"**
   - Select a file
   - The app retrieves the file from IPFS, calculates the hash, and **compares** it with the one stored on the blockchain
   - A message confirms whether the document is **authentic or not**

---

## 🪪 License

Licensed under the [MIT License](LICENSE.md)

---

## 🙏 Acknowledgments

- MetaMask Documentation  
- Solidity & Web3.js Docs  
- IPFS Documentation  
- Truffle Suite Docs  

---

