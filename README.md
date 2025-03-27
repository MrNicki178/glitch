# 🪪 Decentralized Identity Website

This project is a **Decentralized Identity (DID) website** for secure financial transactions using **React** (frontend), **Flask** (backend), and **Ethereum** (blockchain). It allows users to manage their identities securely on the blockchain, ensuring data privacy and trustless verification.

---

## 🚀 Features
✅ User registration and authentication using MetaMask  
✅ Secure identity storage on the Ethereum blockchain  
✅ Decentralized identity verification  
✅ Flask-based backend for handling authentication and data requests  
✅ Clean and responsive UI with modern CSS styling  

---

## 🏗️ Project Structure
```plaintext
├── backend/             # Flask backend
│   ├── app.py           # Main Flask app
│   ├── identity.py      # Identity contract interaction
│   ├── .env             # Environment variables for Flask and Hardhat
│   ├── requirements.txt # Python dependencies
│   └── migrations/      # Database migrations (if applicable)
├── frontend/            # React frontend
│   ├── src/             
│   │   ├── components/  # UI Components (Button, Card, Input)
│   │   ├── contractConfig.js # Contract interaction settings
│   │   ├── App.js       # Main React app
│   │   ├── index.js     # React entry point
│   │   └── styles.css   # Main CSS file
│   ├── public/          # Static files
│   ├── .env             # Environment variables for frontend
│   ├── package.json     # Frontend dependencies
├── contracts/           # Solidity smart contracts
│   ├── Identity.sol     # Identity contract
│   └── migrations/      # Contract deployment scripts
└── hardhat.config.js    # Hardhat configuration for Ethereum deployment
