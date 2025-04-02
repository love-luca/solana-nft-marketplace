# Solana NFT Marketplace

## Introduction
Welcome to the **Solana NFT Marketplace**, a decentralized platform for buying, selling, and trading **NFTs (Non-Fungible Tokens)** built on the **Solana blockchain**. Designed for **fast transactions, low fees, and seamless user experience**, our marketplace empowers creators and collectors alike.

## Features
- **Fast & Low-Cost Transactions**: Powered by Solana's high throughput and minimal fees.
- **On-Chain Royalties**: Supports Metaplex standard royalties for NFT creators.
- **Auction & Fixed-Price Listings**: List NFTs at a fixed price or auction them to the highest bidder.
- **Wallet Integration**: Compatible with Phantom, Solflare, and other Solana wallets.
- **Verified Collections**: Ensure authenticity with blue-check verification.
- **Multi-Currency Support**: Accept SOL, USDC, and SPL tokens.
- **User-Friendly UI**: Designed for seamless navigation and trading experience.

## Tech Stack
- **Solana Blockchain**
- **Rust (Smart Contracts - Anchor Framework)**
- **Metaplex Protocol**
- **TypeScript & React (Frontend)**
- **Phantom, Solflare, and Sollet Wallets**
- **IPFS & Arweave for NFT Metadata Storage**

##  Smart Contract Architecture
### 1️⃣ **NFT Listing Contract**
- Enables users to list NFTs for sale at a fixed price.
- Enforces **creator royalties** and **transaction security**.

### 2️⃣ **Auction Contract**
- Supports **English Auctions** (highest bid wins).
- Automatic **bid management** and **settlement processing**.

### 3️⃣ **Trade Execution Contract**
- Handles **instant NFT purchases**.
- Ensures **secure and atomic transactions** using Solana's **Sealevel runtime**.

## 🔧 Installation & Deployment
### **1. Install Dependencies**
```sh
npm install -g @project-serum/anchor
```

### **2. Clone Repository**
```sh
git clone https://github.com/love-luca/solana-nft-marketplace.git
cd solana-nft-marketplace
```

### **3. Build & Deploy**
```sh
anchor build
anchor deploy
```

## 📖 Usage Guide
### **1. List an NFT for Sale**
```sh
ts-node scripts/listNFT.ts --nftAddress "NFT_ADDRESS" --price 10
```

### **2. Place a Bid on an Auction**
```sh
ts-node scripts/placeBid.ts --auctionId "AUCTION_ID" --bidAmount 20
```

### **3. Buy an NFT Instantly**
```sh
ts-node scripts/buyNFT.ts --nftAddress "NFT_ADDRESS"
```

## Socials & Contact
- Twitter:  [@defai_maxi](https://twitter.com/defai_maxi)
- Telegram: [Rhett](https://t.me/rhettjel)

---


