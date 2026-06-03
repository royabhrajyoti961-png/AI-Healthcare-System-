# AI Healthcare System

** MedAI Nexus is an intelligent healthcare platform that combines Machine Learning, Generative AI, Retrieval-Augmented Generation (RAG), and Clinical Decision Support Systems to provide predictive diagnostics, medical report understanding, and AI-assisted healthcare services.

The platform is designed to bridge the gap between patients and healthcare professionals through accessible, explainable, and secure AI technologies.**

---

## 📑 Quick Navigation

| [📥 Download](#quick-start) | [✨ Features](#feature-highlights) | [🏗️ Architecture](#architecture) | [📚 Documentation](docs/) | [🐛 Issues](../../issues) | [💬 Discussions](../../discussions) |
|:---:|:---:|:---:|:---:|:---:|:---:|

###  Detailed Docs
- **[Installation Guide](docs/INSTALLATION.md)** - Setup for development & production
- **[Usage Guide](docs/USAGE.md)** - API endpoints & features
- **[FAQ](docs/FAQ.md)** - Common questions & answers
- **[Troubleshooting](docs/TROUBLESHOOTING.md)** - Debug common issues
- **[Contributing](docs/CONTRIBUTING.md)** - How to contribute
- **[Changelog](docs/CHANGELOG.md)** - Version history

---



<br/>



<p>
  <img src="https://img.shields.io/badge/Python-3.12-3776AB?style=for-the-badge&logo=python" alt="Python" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Next.js_15-000000?style=for-the-badge&logo=next.js" alt="Next.js" />
  <img src="https://img.shields.io/badge/LangGraph-FF6F00?style=for-the-badge&logo=chainlink" alt="LangGraph" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql" alt="PostgreSQL" />
</p>

</div>

---

## Feature Highlights

| 5 ML Diagnostic Models | 3-Tier AI Inference | RAG Medical Chat |
|---|---|---|
| Diabetes, Heart, Liver, Kidney, Lungs — trained on real clinical datasets with SHAP explainability | **Ollama > Gemini > Cloud** automatic fallback. Local inference for sensitive workflows | Gemini embeddings + vector store + LangGraph agent with patient history |

| Enterprise Security | 5 Deployment Options | 8 CI/CD Pipelines |
|---|---|---|
| JWT + bcrypt auth, RBAC (patient/doctor/admin), audit logging, rate limiting, PII redaction | Docker Compose, Enterprise Stack, Render, Kubernetes, Terraform AWS | Pytest + coverage, CodeQL, Docker builds, HuggingFace, Dependabot |

## 🧠 Other Features 
🧠 Multi-Disease Prediction System

Advanced machine learning models trained on healthcare datasets:

Disease	Prediction Status
Diabetes	✅
Heart Disease	✅
Liver Disease	✅
Kidney Disease	✅
Lung Disease	✅
Explainable AI
SHAP Interpretability
Risk Scoring
Feature Importance Analysis
Confidence Estimation

## 🤖 AI Medical Assistant

An intelligent healthcare chatbot capable of:

Symptom-based guidance
Medical knowledge retrieval
Healthcare FAQs
Treatment awareness
Medication information
Patient support interactions

## 📄 Smart Lab Report Analysis

Upload laboratory reports and receive:

Automated report summaries
Abnormal parameter detection
Clinical observations
Health risk indicators
Easy-to-understand explanations

## 📚 Retrieval-Augmented Medical Intelligence

Powered by modern RAG architecture:

Medical knowledge retrieval
Semantic search
Context-aware responses
Patient history understanding
Intelligent recommendations

## 👨‍⚕️ Multi-Role Healthcare Dashboard
Patient Portal
Medical Records
Prediction History
AI Consultations
Lab Reports
Doctor Dashboard
Patient Monitoring
Diagnostic Assistance
Medical Analytics
Report Reviews
Admin Console
User Management
System Analytics
Audit Logs
Security Controls

---

## 🚀 Quick Start

```bash
git clone https://github.com/pavanbadempet/AI-Healthcare-System.git
cd AI-Healthcare-System

# Backend
pip install -r backend/requirements.txt
uvicorn backend.main:app --reload --port 8000

# Frontend (new terminal)
cd frontend && npm install && npm run dev -- -p 3000
```

Visit: http://localhost:3000

**Full setup:** [Installation Guide](docs/INSTALLATION.md)

---

## 🏗️ Architecture

┌─────────────────────────┐ │ Next.js Frontend │ └────────────┬────────────┘ │ ▼ ┌─────────────────────────┐ │ FastAPI Backend │ └────────────┬────────────┘ │ ┌───────────┼───────────┐ │ │ │ ▼ ▼ ▼ Disease AI Chat Report Models Engine Analysis │ │ │ └───────────┼───────────┘ │ ▼ AI Inference Layer ├─ Ollama ├─ Gemini ├─ OpenAI └─ Anthropic │ ▼ PostgreSQL

- **Frontend**: Next.js 15 with TypeScript & Tailwind CSS
- **Backend**: FastAPI with async/await, middleware stack
- **AI Engine**: 3-tier inference (Ollama → Gemini → OpenAI/Anthropic)
- **Database**: SQLite (dev) / PostgreSQL (prod)
- **ML Models**: 5 scikit-learn/XGBoost classifiers with SHAP

## 🛠️ Technology Stack
Frontend
Next.js 15
React
TypeScript
Tailwind CSS
ShadCN UI
Backend
FastAPI
Python 3.12+
Async API Architecture
Pydantic
Artificial Intelligence
Scikit-Learn
XGBoost
LangChain
LangGraph
Gemini
Ollama
OpenAI APIs
Database
PostgreSQL
SQLite
DevOps
Docker
Kubernetes
Terraform
GitHub Actions

 [API Reference](docs/USAGE.md#api-endpoints)

---

## 📖 Documentation

| Document | Purpose |
|----------|---------|
| [Installation](docs/INSTALLATION.md) | Local setup, Docker, production deployment |
| [Usage Guide](docs/USAGE.md) | API endpoints, dashboards, authentication |
| [FAQ](docs/FAQ.md) | Common questions & troubleshooting |
| [Contributing](docs/CONTRIBUTING.md) | Development setup, code style, testing |
| [Changelog](docs/CHANGELOG.md) | Version history & roadmap |

---

## ⚕️ Medical Disclaimer

⚠️ **This tool is for educational and screening purposes only.** It is NOT a medical diagnosis. Always consult qualified healthcare professionals. See [docs/FAQ.md](docs/FAQ.md) for details.

---

## 📊 Project Stats
--------------------------------------------------------------------

- **5** ML diagnostic models
- **8** CI/CD pipelines
- **5** deployment options
- **7** middleware layers
- **95%+ test coverage**
- **HIPAA-friendly** design

---

## 🤝 Contributing For -----
---------------------------------------------------------------------

We welcome contributions! See [CONTRIBUTING.md](docs/CONTRIBUTING.md) for:
- Development setup
- Code style guidelines
- Testing requirements
- Pull request process

---

## 📄 License 
----------------------------------------------------------------------

MIT License - See [LICENSE](LICENSE)

---

**🌟 If this project helps you, please consider giving it a star!**

Made with ❤️ by 
