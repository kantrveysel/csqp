# CSQP (Customizable System for Query and Panel)

**Lightweight, secure, and flexible SQL automation and dashboard platform.**  
Connect your database. Run SQL queries. Build and share custom panels. No heavy setup, no expensive licenses.

---

## 🌟 Features

- 🔐 **Secure Auth & 2FA** — bcrypt-hashed passwords, optional TOTP-based 2FA (QR supported)
- 🔌 **Database Connector** — Encrypted access to your own MariaDB or MSSQL instances
- 📝 **Raw SQL Support** — Write and run SQL queries through a browser interface
- 📊 **Panel Builder (MVP)** — Save queries and visualize them via Chart.js (Bar, Line, Pie)
- 👥 **Solo or Team Workflows** — Create your own team or stay solo; assign access per module
- 🧱 **Modular Architecture** — Panels, procedures, jobs, and more are pluggable modules

> **Note:** This is an early-stage MVP. The core system is not open-sourced for security and architectural reasons.

---

## 🔗 Live Demo (Landing Page)

👉 [https://csqp-project.github.io](https://csqp-project.github.io)  
Browse public panel templates or learn about the system.

---

## 🎨 Community Panel Templates

This repository includes **open panel layouts** and SQL templates for different use cases:
- 📦 Inventory dashboards (MMORPG servers, small businesses)
- 📈 Financial data panels
- 📋 CRUD templates for internal apps

> You can create your own `.sql` + `.json` template and contribute via pull request.

---

## 🏗️ Technologies Used

| Layer | Tech |
|-------|------|
| Backend | Python 3.10, Flask, SQLAlchemy |
| Auth | Flask-Login, bcrypt, pyotp |
| Encryption | cryptography (Fernet) |
| DB Support | MariaDB, MSSQL, SQLite (test) |
| Frontend | HTML5, CSS3, Chart.js |
| Tests | pytest, pytest-flask |

---

## 📦 Repository Structure

/ 
├── index.html # Landing page (static) 
├── static/ # CSS, logos, etc. 
├── panels/ # Example panel definitions (SQL + layout config) 
└── README.md


---

## 📬 Contributing

Since the main system is closed-source, this repository is for:
- Community-contributed panel templates
- Demo page and documentation
- Suggestions, bug reports, and feature requests

Feel free to open issues or discussions!

---

## 🛡️ License

This repository is provided under the **MIT License**.  
CSQP Core Platform is proprietary and closed-source for now.

---

Made with ❤️ for developers, data enthusiasts, and small teams.

