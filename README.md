# Vishnu Vekaria

**Full-Stack & AI Engineer** — Python · FastAPI · Azure · Applied NLP

Building systems that are *auditable* — where every output can be traced back to the evidence that produced it.

[Portfolio](https://vishnupro.netlify.app) · [LinkedIn](https://linkedin.com/in/vekaria-vishnu) · [Email](mailto:vekariyavishnu63@gmail.com)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

---

## Snapshot

| | |
| --- | --- |
| **Status** | Open to graduate SWE / AI / Cloud roles — full-time from September 2026 |
| **Degree** | BSc (Hons) Computer Science, Ulster University London |
| **Location** | London, UK |
| **Focus** | Backend services, applied NLP, cloud deployment, verifiable systems |
| **Languages** | English, Gujarati, Hindi |

---

## Featured Work

Each project below solves one specific hard problem.

### 🔍 [VerifyPulse](https://github.com/V-Vekaria/verifypulse) — real-time news verification

Scores breaking news by how many independent, credible outlets corroborate it — instead of asserting truth, it shows the evidence.

**Problem** — a single-source story and a ten-source story look identical in a feed.

**Approach** — RSS + GDELT ingestion → MiniLM sentence embeddings → cosine clustering → 3-factor confidence score (source count, source credibility, source diversity) → FastAPI + live dashboard.

**Stack** — `Python` `FastAPI` `sentence-transformers` `SQLite`

**Concepts** — semantic clustering, weighted scoring design, scheduled ingestion pipelines, deduplication

---

### 🔐 [SecureTransfer](https://github.com/V-Vekaria/privacy-preserving-file-transfer-platform) — zero-knowledge file transfer

Client-side encrypted transfer where the server can detect abuse without ever reading a file.

**Problem** — end-to-end encryption normally kills your ability to detect malicious usage.

**Approach** — browser-side encryption before upload, server stores ciphertext only, anomaly detection runs purely on transfer *metadata* (size, frequency, timing).

**Stack** — `Python` `Flask` `WebCrypto` `SQLite`

**Concepts** — threat modelling, zero-knowledge architecture, metadata-only anomaly detection

---

### 🧾 [Longhand](https://github.com/V-Vekaria/longhand) — auditable US-expat tax assistant

Built with one teammate for the AMD Developer Hackathon (ACT II). Every figure the assistant produces links back to the rule and input that generated it.

**Problem** — LLM tax advice is unusable if you cannot show *why* a number is that number.

**Approach** — deterministic rule layer for computation, model layer only for explanation; full citation trail per line item.

**Concepts** — grounded generation, deterministic/LLM separation, audit trails

**Live** — [amd-hackathon-sepia.vercel.app](https://amd-hackathon-sepia.vercel.app)

---

### ☁️ [SaaS Usage Monitoring API](https://github.com/V-Vekaria/saas-usage-api) — multi-tenant metering backend

REST API with tenant scoping, usage aggregation, and rate accounting.

**Stack** — `Python` `Flask` `MongoDB` `JWT`

---

## Stack

| Layer | Tools |
| --- | --- |
| **Languages** | Python, TypeScript, JavaScript, SQL |
| **Backend** | FastAPI, Flask, REST design, JWT auth, RBAC, input validation |
| **AI / NLP** | sentence-transformers, TF-IDF, embedding search, semantic clustering, RAG patterns |
| **Cloud** | Azure App Service, Azure Functions, Netlify, Vercel, Docker |
| **Data** | MongoDB, PostgreSQL, SQLite |
| **Practice** | Git, GitHub Actions, Postman, pytest, API testing |

---

## Currently

- Extending **VerifyPulse** into multilingual claim tracking (Phase 3)
- Contributing to **[google/adk-python](https://github.com/google/adk-python)** — agent development kit
- Dissertation: privacy-preserving transfer with metadata-driven anomaly detection

---

## Contact

Open to graduate roles in the UK (Skilled Worker sponsorship required) and, longer term, East Asia.

**Portfolio:** [vishnupro.netlify.app](https://vishnupro.netlify.app)
**LinkedIn:** [linkedin.com/in/vekaria-vishnu](https://linkedin.com/in/vekaria-vishnu)
