# 🍽️ WEEKLIES — Intelligent Meal Planning and Delivery System

[![CI](https://github.com/Aum3010/ncsu-csc510-2025-s1-g3-weeklies/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/Aum3010/ncsu-csc510-2025-s1-g3-weeklies/actions/workflows/ci.yml)
[![Docs](https://github.com/Aum3010/ncsu-csc510-2025-s1-g3-weeklies/actions/workflows/docs.yml/badge.svg?branch=main&event=push)](https://github.com/Aum3010/ncsu-csc510-2025-s1-g3-weeklies/actions/workflows/docs.yml)
[![Python](https://img.shields.io/badge/Python-3.11%2B-blue.svg)]()
![Tests](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/Aum3010/0c223cf33bf0cc9b91667676c415aafa/raw/tests-badge.json)
![Code Coverage](https://img.shields.io/badge/coverage-91%25-green
)
[![Flask](https://img.shields.io/badge/Flask-2.x-lightgrey?logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![License](https://img.shields.io/github/license/Aum3010/ncsu-csc510-2025-s1-g3-weeklies.svg)](LICENSE)
[![GitHub last commit](https://img.shields.io/github/last-commit/Aum3010/ncsu-csc510-2025-s1-g3-weeklies.svg)](https://github.com/Aum3010/ncsu-csc510-2025-s1-g3-weeklies/commits)
[![GitHub issues](https://img.shields.io/github/issues/Aum3010/ncsu-csc510-2025-s1-g3-weeklies.svg)](https://github.com/Aum3010/ncsu-csc510-2025-s1-g3-weeklies/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/Aum3010/ncsu-csc510-2025-s1-g3-weeklies.svg)](https://github.com/Aum3010/ncsu-csc510-2025-s1-g3-weeklies/pulls)
[![Repo Size](https://img.shields.io/github/repo-size/Aum3010/ncsu-csc510-2025-s1-g3-weeklies.svg)](https://github.com/Aum3010/ncsu-csc510-2025-s1-g3-weeklies)
[![Contributors](https://img.shields.io/github/contributors/Aum3010/ncsu-csc510-2025-s1-g3-weeklies.svg)](https://github.com/Aum3010/ncsu-csc510-2025-s1-g3-weeklies/graphs/contributors)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![Lint: ruff](https://img.shields.io/badge/lint-ruff-46a2f1?logo=ruff&logoColor=white)](https://github.com/astral-sh/ruff)
[![DOI](https://zenodo.org/badge/1108504869.svg)](https://doi.org/10.5281/zenodo.17850780)
---

## 🧠 Project Overview

**Weeklies** is a **full-stack Flask web application** developed as part of *CSC 510* : Software Engineering (Fall 2025, NC State University)*.  
It models a modern food-delivery system where users can register, browse restaurants and menus, tag preferences, and schedule future meal orders via an integrated calendar.  
The project demonstrates **modular backend design**, **frontend interaction**, **LLM-assisted personalization**, and **continuous documentation & testing pipelines**.

---

## 🎬 Live Demo
[![Watch the demo video on YouTube](https://img.youtube.com/vi/yNC3aD4ZACk/0.jpg)](https://youtu.be/yNC3aD4ZACk)

---

## ⚙️ Tech Stack

| Layer | Technologies | Key Focus |
|-------|---------------|-----------|
| **Frontend** | HTML, CSS, JavaScript (templated views) | Dynamic forms, order interaction, user calendar |
| **Backend** | Python 3.11+, Flask 2.x | RESTful routes, modular blueprints, DB logic |
| **Database** | SQLite / Flask-SQLAlchemy | Lightweight persistence for menus, users, orders |
| **Automation** | GitHub Actions, pdoc, pytest, ruff, black | CI/CD, linting, testing, documentation |
| **Intelligent Module** | OpenAI / LLM API | Personalized recommendations & reasoning |
| **PDF Service** | ReportLab / FPDF | Automated PDF receipt generation |

---

## 🧩 Existing Features

- 👤 **User registration & authentication**
- 🍱 **Menu and restaurant search** with allergen + cuisine tagging
- 🧭 **User preference tagging** and filtering
- 📅 **Calendar-based scheduling** (order-on-selected-date logic)
- 🧾 **Dynamic PDF receipt generation**
- 🧪 **Automated test suite** with `pytest`
- 🧰 **CI/CD workflows** for tests, linting, and documentation deployment

## 🧩 Our Enhancements
- 🤖 **LLM integration** for context-aware meal suggestions and planning weekly meals
- ⚙️ **Admin Dashboard** for managing orders
- ✉️ **Support Ticket System** for customer support
- 📈 **User Insights** to understand user behaviour
- ⭐ **Restaurant Reviews** to share user reviews
- 📊 **Restaurant Rating** to quickly identify good restaurants
- 💰 **Functional Wallet and Currency System** to experience proper ordering flow

---

## 🧱 Architecture

SE25Fall/   
├── proj2/  
│   ├── Flask_app.py       
│   ├── templates/  
│   ├── static/  
│   ├── pdf_receipt.py  
│   ├── sqlQueries.py   
│   ├── tests/  
│   ├── llm_toolkit.py      
│   ├── menu_generation.py       
│   ├── requirements.txt    
│   ├── CSC510_DB.db    
│   └── orders_db_seed.txt  
├── .github/    
│   └── workflows/  
│           ├── ci.yml  
│           └── docs.yml    
├── INSTALLATION.md   
├── LICENSE   
├── CODE_OF_CONDUCT.md     
├── README.md   
├── scripts/       
├── pytest.ini  
├── pdoc.toml   
└── coverage.xml    

---

## 🧪 Continuous Integration

Every push or pull request to the `main` branch triggers:
1. **CI tests** via `pytest` and `coverage`  
2. **Documentation build & deployment** to GitHub Pages (`gh-pages` branch)  
3. **Static analysis** via `ruff` and `black` 

You can view live status from the badges above.

---

## 📚 Documentation

Auto-generated API documentation is available through **pdoc** and deployed automatically.  
You can view it online (via GitHub Pages) or build it locally:

🔗 **Live Docs:** [Food Delivery Documentation](https://taylorbrown96.github.io/SE25Fall/)  
🧰 **Local Build:** See [INSTALLATION.md](./INSTALLATION.md#7-build-documentation-locally)

---

## 🚀 Installation & Usage

Setup, environment creation, and execution instructions have been moved to a dedicated guide:  
➡️ **[See Installation Guide →](./INSTALLATION.md)**

---

##  👥 Team & Contributors
Project developed collaboratively as part of **CSC 510 — Software Engineering (Fall 2025, NC State University)**.
This project was extended using the prior work done by Section 001 Group 9: Taylor J. Brown, Kunal Jindal, Ashritha Bugada, Daniel Dong.

| Member | GitHub Handle | Key Contributions |
|---------|----------------|-------------------|
| **Aum Pandya** | [@Aum3010](https://github.com/Aum3010) | Added LLM based weekly plan generation. Implemented user-specific Insights dashboard to provide detailed feedback. |
| **Pranav Bhagwat** | [@alt-Pranav](https://github.com/alt-Pranav) | Added a functional currency system using the wallet for managing orders, topping up balance and gifting to other users. Implemented restaurant specific ratings and review system shared across all users. |
| **Tayo Olukotun** | [@tysjosh](https://github.com/tysjosh) | Developed an admin dashboard to manage orders and manage state. Implemented a support ticket system to help users get customer support by raising tickets. |

---

## 🤝 Contributing
We welcome contributions from everyone.  
Please make sure to review our [Code of Conduct](CODE_OF_CONDUCT.md) before submitting pull requests.

---

## 📜 License
Distributed under the MIT License.  
See [LICENSE](./LICENSE) for more information.

---

> “Build software that’s clean, testable, and transparent not just functional.”

