![GitHub Pages](https://img.shields.io/badge/github-pages-live-brightgreen)
![License](https://img.shields.io/github/license/mohammadsaleem-dev/Decentralized-Voting-System-Based-On-Ethereum-Blockchain)
![Repo Size](https://img.shields.io/github/repo-size/mohammadsaleem-dev/Decentralized-Voting-System-Based-On-Ethereum-Blockchain)
![Last Commit](https://img.shields.io/github/last-commit/mohammadsaleem-dev/Decentralized-Voting-System-Based-On-Ethereum-Blockchain)
![Stars](https://img.shields.io/github/stars/mohammadsaleem-dev/Decentralized-Voting-System-Based-On-Ethereum-Blockchain?style=social)


# 🗳️ Decentralized Voting System on Ethereum Blockchain

A **secure, transparent, and tamper-resistant voting system** built using **Ethereum smart contracts**, a **Node.js backend**, and a **modern web interface**.  
This project demonstrates how blockchain technology can ensure **data integrity, voter authenticity, and election transparency**.

---

## 📚 Table of Contents
- Project Overview
- System Architecture
- Key Features
- Technologies Used
- Installation & Setup
- Testing
- Academic Context
- License
- Author

---

## 📌 Project Overview

Traditional electronic voting systems suffer from:

- Lack of transparency  
- Centralized trust  
- Risk of vote manipulation  
- Limited auditability  

This project solves these issues by leveraging **blockchain immutability**, **cryptographic hashing**, and **role-based access control**, ensuring that:

- Votes **cannot be altered**  
- Each voter can **vote only once**  
- Results are **verifiable and auditable**  

The system was **designed for university-level elections**, but it can be **easily adapted to any organization or institution**.

---

## ⚙️ System Architecture

Frontend (HTML/CSS/JS)
↓
Backend API (Node.js + Express)
↓
MySQL Database (Users & Blocs)
↓
Ethereum Smart Contract (Votes & Counts)

yaml
Copy code

### Components

- **Frontend:** User voting interface & admin dashboard  
- **Backend:** Authentication, data synchronization, and API logic  
- **Blockchain:** Immutable vote storage and counting  
- **Database:** User credentials and bloc management  

---

## 🔐 Key Features

### User Side

- Secure login system  
- MetaMask wallet integration  
- One-vote-per-user enforcement  
- University & college bloc voting  
- Real-time result visualization  
- Light/Dark mode interface  

### Admin Panel

- Role-based admin access  
- Add / edit / manage university blocs  
- Add / edit / manage college blocs  
- Real-time vote analytics  
- Automatic blockchain synchronization  

### Security Highlights

- Blockchain immutability  
- Cryptographic vote hashing  
- Wallet-based voter verification  
- Backend + smart contract double validation  

---

## 🧠 Technologies Used

| Layer | Technology |
------|-----------
Blockchain | Ethereum Smart Contracts (Solidity)
Wallet | MetaMask
Backend | Node.js, Express.js
Database | MySQL
Frontend | HTML, CSS, JavaScript
Charts | Chart.js
Web3 | Ethers.js / Web3.js

---

## 🚀 Installation & Setup

### Prerequisites

- Node.js (v16+)  
- MySQL  
- MetaMask Browser Extension  
- Ganache (Local Ethereum Blockchain)  

---

### Clone Repository

git clone https://github.com/mohammadsaleem-dev/Decentralized-Voting-System-Based-On-Ethereum-Blockchain.git
cd Decentralized-Voting-System-Based-On-Ethereum-Blockchain

yaml
Copy code

---

### Install Dependencies

npm install

yaml
Copy code

---

### Environment Configuration

Create a `.env` file:

PORT=5500
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=mydata
JWT_SECRET=your_secret_key

yaml
Copy code

---

### Start Services

1. Start Ganache  
2. Deploy smart contract  
3. Run backend server  

node backendwauto.js

yaml
Copy code

---

### Access the Application

User Interface:
http://localhost:5500/index.html

yaml
Copy code

Admin Panel:
http://localhost:5500/admin.html

yaml
Copy code

---

## 🧪 Testing

- Duplicate voting → blocked  
- Page refresh → vote status preserved  
- Wallet switching → blockchain prevents re-voting  
- Admin bloc creation → automatic blockchain synchronization  

---

## 🎓 Academic Context

This project was developed as a **Computer Engineering Graduation Project** focusing on:

- Blockchain security  
- Distributed systems  
- Secure web application development  

Later improvements included:

- Admin analytics  
- Responsive interface  
- Enhanced security validation  

---

## 📜 License

This project is licensed under the **MIT License**.

MIT License Reference:  
https://opensource.org/licenses/MIT  

---

## 👨‍💻 Author

**Mohammad Saleem**  
Computer Engineering Graduate  

Portfolio Website:  
https://mohammadsaleem-dev.github.io/

---

## ⭐ Acknowledgments

- Ethereum Developer Community  
- MetaMask  
- Open-source contributors  
