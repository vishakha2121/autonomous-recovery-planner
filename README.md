<div align="center">

# 🔥 Phoenix DR
### AI Autonomous Disaster Recovery Planner

> *Rise from any disaster. Automatically. Powered by AI + Digital Twins.*

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.109-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com)
[![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev)
[![Gemini](https://img.shields.io/badge/Gemini-AI-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://ai.google.dev)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

**[Overview](#-overview) • [Features](#-features) • [Tech Stack](#-tech-stack) • [Setup](#-setup) • [Screenshots](#-screenshots) • [API](#-api-endpoints)**

</div>

---

## 🌟 Overview

**Phoenix DR** is an intelligent, AI-powered disaster recovery planning system that **autonomously generates recovery strategies** for cloud failures, cyberattacks, and infrastructure outages.

It combines **Digital Twin** technology, **Google Gemini AI**, and **Cloud API simulations** to provide end-to-end failover planning and business continuity testing — all visualized through an interactive React dashboard.

### 🎯 The Problem It Solves

- ⏱️ **Manual DR planning is slow** — takes days to design recovery strategies
- 🧠 **Human error** — critical steps get missed under pressure
- 🔬 **No safe testing** — can't test failover on live production
- 📊 **No visibility** — teams don't know their actual RTO/RPO

### 💡 The Solution

Phoenix DR creates a **digital twin** of your infrastructure, lets you **simulate disasters safely**, and uses **AI to generate step-by-step recovery plans** with automatic failover orchestration.

---

## ✨ Features

### 🧠 AI-Powered Planning
- Google **Gemini AI** generates step-by-step recovery strategies
- Risk analysis and impact assessment per service
- Automatic RTO/RPO estimation
- Multi-scenario plan generation (worst-case, best-case, balanced)

### 🌐 Digital Twin
- Virtual replica of your cloud infrastructure
- Interactive **topology visualization** (React Flow)
- Real-time state simulation of nodes & edges
- Dependency mapping between services

### ⚡ Disaster Simulation
- Trigger simulated disasters: **cyberattacks, outages, failures, data corruption**
- Severity levels: **Low / Medium / High / Critical**
- Cascading failure simulation
- Business impact analysis

### 🔄 Failover Automation
- Auto-generated failover sequences
- Service dependency-aware recovery
- Zero-downtime strategies
- Rollback plans

### 📊 Business Continuity
- RTO (Recovery Time Objective) simulation
- RPO (Recovery Point Objective) tracking
- Continuity metrics & charts
- Cost vs. recovery-time trade-offs

### 🎨 Interactive Dashboard
- Real-time system health cards
- Incident trend charts (Recharts)
- Topology viewer with live status
- Recovery plan timeline
- Dark mode with cyber-disaster aesthetic

---

## 🛠 Tech Stack

### Backend
| Tech | Purpose |
|------|---------|
| **Python 3.10+** | Core language |
| **FastAPI** | REST API framework |
| **SQLAlchemy** | ORM for database |
| **SQLite** | Lightweight database (practice) |
| **Pydantic** | Data validation |
| **JWT (python-jose)** | Authentication |
| **Google Generative AI** | Gemini API integration |
| **Uvicorn** | ASGI server |

### Frontend
| Tech | Purpose |
|------|---------|
| **React 18** | UI framework |
| **Vite** | Build tool |
| **TailwindCSS** | Styling |
| **React Router** | Navigation |
| **Axios** | API calls |
| **React Flow** | Topology visualization |
| **Recharts** | Charts & graphs |
| **Lucide React** | Icons |
| **React Hot Toast** | Notifications |
| **Framer Motion** | Animations |

### AI & External
- **Google Gemini API** — Recovery strategy generation
- **Cloud API Simulation** — AWS/Azure/GCP mock integration

---

## 📁 Project Structure



---

## 🚀 Setup

### Prerequisites
- Python **3.10+**
- Node.js **18+**
- Google Gemini API Key ([get free here](https://ai.google.dev))

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/vishakha2121/autonomous-recovery-planner.git
cd autonomous-recovery-planner

cd backend

# Create virtual environment
python -m venv venv

# Activate (Windows)
venv\Scripts\activate

# Activate (Mac/Linux)
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt