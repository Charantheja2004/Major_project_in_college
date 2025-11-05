# Major_project_in_college

#  Implementing Smart Contracts for Automated and Transparent Supply Chain Management in Agriculture

## Project Overview

This project aims to develop an **automated and transparent supply chain management system** for the **agriculture sector** using **blockchain-based smart contracts**.  

Traditional agricultural supply chains often suffer from inefficiency, lack of trust, data manipulation, and delays in payment settlements. By integrating **smart contracts** on a blockchain platform (such as Ethereum), this system ensures **trustless automation**, **data transparency**, and **tamper-proof transactions** between farmers, distributors, and retailers.

This project was developed as part of the **B.Tech Final Year Project (4th Year)** to demonstrate the real-world application of **blockchain technology** in solving agricultural logistics and trust issues.

---

##  Objectives

- To automate transactions and agreements between participants in the agriculture supply chain.
- To enhance transparency and traceability of goods from farmer to consumer.
- To eliminate intermediaries and reduce fraud.
- To ensure timely payments through self-executing smart contracts.
- To create a decentralized platform for agricultural product tracking.

---

##  Features

-  Blockchain-based Smart Contracts:** Automates trust and transactions using Solidity.
- Product Traceability:** Each product batch can be traced through every stage of the supply chain.
- Automated Payments:** Payments are released automatically upon successful product delivery.
- Data Integrity:** All records are immutable and verifiable.
- User Dashboard:** Front-end interface for farmers, distributors, and retailers to interact with the system.

---

##  System Architecture

1. Farmer: Registers and uploads product information (batch ID, quantity, price, etc.).  
2. Distributor:** Verifies and purchases the product from the farmer.  
3. Retailer:** Purchases from the distributor and confirms product receipt.  
4. Smart Contract:** Validates each transaction, updates product status, and triggers payments.  
5. Blockchain Network:** Stores all transactions transparently and immutably.

---

##  Tech Stack

| Layer | Technology Used |
|-------|------------------|
| **Frontend** | HTML, CSS, JavaScript, React.js |
| **Backend** | Node.js, Express.js |
| **Blockchain** | Ethereum, Solidity, Web3.js |
| **Database (optional)** | IPFS / MongoDB (for metadata) |
| **Development Tools** | Remix IDE / Truffle / Hardhat, Ganache |
| **Version Control** | Git & GitHub |

---

## 🚀 Installation & Setup

Follow these steps to run the project locally:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Charantheja2004/Major_project_in_college.git
cd Major_project_in_college

### 2️⃣ Install Dependencies
npm install

### 3️⃣ Start Local Blockchain (Ganache)
ganache-cli

### 4️⃣ Compile and Deploy Smart Contracts
truffle migrate --network development

### 5️⃣ Start the Application
npm start

