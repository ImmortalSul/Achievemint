# Achievemint - Monorepo

Achievemint is a decentralized platform that rewards gamers with NFTs based on their in-game achievements. This monorepo contains all related components, including architecture diagrams, middleware, and the NFT minting Anchor program.

## Repository Structure

```
Achievemint-Monorepo/
│-- Diagrams/                 # Architecture diagrams and system design docs
│-- Achievemint-Middleware/   # Backend service for Steam achievement processing
│-- Achievemint-NftMinting/   # Solana Anchor program for NFT minting
```

## **Folder Descriptions**

### **1. Diagrams/**
Contains all architectural diagrams and system design documents for Achievemint, including:
- System architecture overview
- Interaction between middleware and blockchain
- Data flow diagrams

### **2. Achievemint-Middleware/**
The backend service responsible for fetching, processing, and categorizing Steam achievements, then generating metadata for NFT minting on Solana.

### **3. Achievemint-NftMinting/**
The Solana Anchor program that handles NFT minting based on Steam achievements, ensuring uniqueness and integrating with Metaplex in future updates.

## **License**

MIT License © 2025 Sulaiman


