# 🔐 SecureChat — Encrypted Minimal Messaging Prototype

**SecureChat** is a minimal Python + Flask-based secure messaging system focused on end-to-end encryption concepts and privacy-first communication. Built as a learning and demonstration project, it simulates secure channels between users without collecting any personal data beyond login credentials.

---

## 🚀 Features

- 📧 Sign-up & login system using email and password
- 🔑 Unique key assigned to every user (used for sending messages)
- 💬 Send & receive messages securely using user keys
- 🕰 Timestamped communication logs
- 🎯 SQLite backend for easy portability
- ☁️ Public access via Cloudflare Tunnel

---

## 🔒 Encryption & Security

While full cryptographic implementation is still in progress, the app is **designed with encryption in mind**. Placeholder architecture makes it easy to plug in:

- AES-256 for message content encryption
- RSA for key exchange (future goal)
- Hashed & salted password storage (planned)

> For demonstration purposes, passwords are currently stored in plain text. Do **not** use real credentials.

---

## 📦 Tech Stack

- **Backend**: Flask (Python)
- **Frontend**: HTML, CSS (minimal styling)
- **Database**: SQLite3
- **Hosting (dev)**: Cloudflare Tunnel (`trycloudflare.com`)

---


---

## ⚠️ Note on UI

This version focuses on **core functionality and backend flow**.  
The UI is intentionally minimal and will be improved in later releases.

---

## 🛠 Setup (Local Dev)

