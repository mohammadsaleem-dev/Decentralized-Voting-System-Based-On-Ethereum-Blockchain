# 🗳️ Decentralized Voting System on Ethereum Blockchain

A **secure, transparent, and tamper-resistant voting system** built using **Ethereum smart contracts**, a **Node.js backend**, and a **modern web interface**.  
This project demonstrates how blockchain technology can be used to ensure **data integrity, voter authenticity, and election transparency**.

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

### 🔹 Components
- **Frontend:** User voting interface & admin dashboard
- **Backend:** Authentication, data synchronization, and API logic
- **Blockchain:** Immutable vote storage and counting
- **Database:** User credentials and bloc management

---

## 🔐 Key Features

### 👤 User Side
- Secure login system
- MetaMask wallet integration
- One-vote-per-user enforcement
- University & college bloc voting
- Real-time result visualization (charts)
- Light/Dark mode UI

### 🛠️ Admin Panel
- Role-based admin access
- Add / edit / manage university blocs
- Add / edit / manage college blocs
- Real-time vote result charts
- Automatic blockchain synchronization

### 🔒 Security Highlights
- Blockchain immutability (votes cannot be changed)
- Cryptographic hashing of votes
- Wallet-based voter verification
- Backend + smart contract double validation

---

## 🧠 Technologies Used

| Layer | Technology |
|-----|-----------|
| Blockchain | Ethereum Smart Contracts (Solidity) |
| Wallet | MetaMask |
| Backend | Node.js, Express.js |
| Database | MySQL |
| Frontend | HTML, CSS, JavaScript |
| Charts | Chart.js |
| Web3 | Ethers.js / Web3.js |

---

## 🚀 Installation & Setup

### 1️⃣ Prerequisites
- Node.js (v16+)
- MySQL
- MetaMask browser extension
- Ganache (local Ethereum blockchain)

---

### 2️⃣ Clone Repository
```bash
git clone https://github.com/your-username/decentralized-voting-system.git
cd decentralized-voting-system
3️⃣ Install Dependencies
bash
Copy code
npm install
4️⃣ Environment Configuration
Create a .env file:

env
Copy code
PORT=5500
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=mydata
JWT_SECRET=your_secret_key
5️⃣ Start Services
Start Ganache

Deploy smart contract

Run backend server:

bash
Copy code
node backendwauto.js
6️⃣ Access the App
User Interface:
http://localhost:5500/index.html

Admin Panel:
http://localhost:5500/admin.html

🧪 Testing
Attempt duplicate voting → blocked

Refresh page → vote status preserved

Switch wallet → blockchain still prevents re-voting

Admin adds blocs → auto-sync to blockchain

📊 Screenshots & Demo
(Add screenshots or a demo video link here)

🎓 Academic Context
This project was developed as a graduation project in Computer Engineering, focusing on:

Blockchain security

Distributed systems

Secure web application design

It was later enhanced with:

Admin analytics

Responsive UI

Improved security checks

📜 License
This project is licensed under the MIT License – see the LICENSE file for details.

👨‍💻 Author
Mohammad Saleem
Computer Engineering Graduate
🔗 Portfolio: https://mohammadsaleem-dev.github.io/

⭐ Acknowledgments
Ethereum Developer Community

MetaMask

Open-source contributors

yaml
Copy code

---

# 🔐 Copyright & License (IMPORTANT)

## ✅ Do you automatically own copyright?
**Yes.**  
The moment you write code, **you own the copyright** — no registration required.

However, **GitHub strongly recommends adding a LICENSE file** to make usage rules clear.

📖 Source:  
https://www.copyright.gov/help/faq/faq-general.html

---

## 🥇 Best License for Your Project (Recommended)

### ✅ **MIT License** (BEST choice for you)

**Why MIT?**
- Protects you as the author
- Allows others to view & learn
- Requires attribution (your name stays)
- Very popular in academic & blockchain projects

📄 Official MIT License text:  
https://opensource.org/licenses/MIT
