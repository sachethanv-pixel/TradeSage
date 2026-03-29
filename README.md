# TradeSage 💹🤖

TradeSage is an advanced, AI-driven financial intelligence platform designed to transform raw market signals into actionable trading insights. By leveraging **Multi-Agent Systems** and **Retrieval-Augmented Generation (RAG)**, TradeSage provides a conversational interface for real-time market analysis and automated trading simulations.

---

## 🚀 Key Features

* **Multi-Agent Orchestration:** Utilizes specialized agents (Synthesis, Chat, and RAG agents) to process complex financial data.
* **Real-Time Data Integration:** Seamlessly fetches live market data via Yahoo Finance API.
* **Intelligent RAG Pipeline:** Context-aware analysis that grounds LLM responses in actual financial documents and historical trends.
* **Interactive Dashboard:** A modern frontend for visualizing agent outputs and trading simulations.
* **Cloud-Native Architecture:** Fully containerized and optimized for deployment on **Google Cloud Platform (GCP)**.

---

## 🛠️ Tech Stack

| Layer | Technology |
| :--- | :--- |
| **Language** | Python 3.9+, JavaScript (React/HTML) |
| **AI Frameworks** | Agent Development Kit (ADK), LLMs, RAG |
| **Cloud** | GCP (Cloud Run, Cloud SQL) |
| **Database** | PostgreSQL (Cloud SQL) |
| **DevOps** | Docker, Shell Scripting |

---

## 📂 Repository Structure

* `app/`: Core backend logic, agent definitions, and API endpoints.
* `frontend/`: React-based user interface for the trading dashboard.
* `scripts/`: Automation scripts for database initialization and cloud deployment.
* `test_simulation.py`: Suite for testing trading strategies and agent accuracy.

---

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/sachethanv-pixel/TradeSage.git](https://github.com/sachethanv-pixel/TradeSage.git)
   cd TradeSage
