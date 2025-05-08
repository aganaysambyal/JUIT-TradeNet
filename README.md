PROJECT TITLE:
JUIT TradeNet Campus Management System

PROJECT DESCRIPTION:
TradeNet is a full-stack web application designed to help university students buy or sell items within their campus.
The platform allows users to post product listings, chat in real-time, manage wishlist, and filteration within a secure, student-specific environment.
It aims to reduce waste, save money, and encourage sustainable resource sharing among the student community.



FOLDER STRUCTURE
APP/
├── my-node-app/
│   ├── index.js
│   ├── package.json
│   ├── package-lock.json
│   └── node_modules/
│       ├── .bin/
│       │   ├── mime
│       │   ├── mime.cmd
│       │   ├── mime.ps1
│       │   ├── mkdirp
│       │   ├── mkdirp.cmd
│       │   ├── mkdirp.ps1
│       │   └── ...
│       └── @mongodb-js/
│           └── saslprep/
│               ├── LICENSE
│               ├── package.json
│               ├── readme.md
│               └── dist/
│                   ├── browser.js
│                   ├── code-points-data.js
│                   └── ...





# TradeNet – A Campus Marketplace for Students

TradeNet is a full-stack web application designed to help university students buy, sell, or rent items within their campus.
It solves the common problem of resource wastage by providing a secure and user-friendly platform for peer-to-peer trading.

## 🚀 Features

- 🔐 User authentication and role-based access (buyer/seller)
- 📦 Add, delete, and manage product listings
- 💬 Real-time chat between buyers and sellers
- 🛒 Cart and basic order management
- 📢 Notifications for order status changes
- 🖼️ Upload and display product images
- 🔍 Search and filter listings by category
- 🧾 Admin panel for monitoring and moderation

## 🛠️ Tech Stack

**Frontend:** React.js, HTML5, CSS3, JavaScript  
**Backend:** Node.js, Express.js  
**Database:** MongoDB  
**Authentication:** JWT (JSON Web Tokens)  
**Real-time Chat:** Socket.io  

## 📌 Installation Instructions

1. Clone the repository:
```bash
git clone https://github.com/yourusername/tradenet.git
cd tradenet
npm install
cd client && npm install
npm run dev
