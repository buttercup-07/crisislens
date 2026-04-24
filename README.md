#  CrisisLens 

A unified platform that connects **NGOs**, **Donors (Users)**, and **Government Bodies** to enable **transparent, data-driven, and urgent humanitarian response** using **Artificial Intelligence**.

> **Theme:** AI for Social and Economic Good

---

## 🚀 Overview

This platform leverages **real-time disaster intelligence**, **machine learning**, and **transparent fund tracking** to:
- Detect and analyze crises automatically
- Identify NGOs that need funds the most
- Enable direct, transparent donations
- Ensure accountability through AI-verified reporting

Our goal is to **bridge the gap between crisis detection, resource allocation, and impact transparency**.

---

## 🧠 Core Features

### 1️⃣ AI-Powered Crisis Detection & Analysis
- Scrapes **live disaster-related news** from trusted sources like **Economic Times**
- Extracted data is passed through an **ML pipeline** to generate:
  - Severity score
  - Risk factor
  - Urgency level
  - AI-generated reasoning & explanations
  - Geographical coordinates (latitude & longitude)
- Uses **Hugging Face Transformers** and **Kimi (Moonshot AI)** for enhanced NLP understanding

✅ Output is structured, explainable, and location-aware

---

### 2️⃣ Smart NGO Prioritization & Donations
- Detected crises are mapped against:
  - NGO location
  - Available funds
  - Crisis severity
- NGOs are **ranked based on urgency and need**
- Donors can:
  - View AI-recommended NGOs
  - Track donation impact through verified reports

💡 Data-driven donations instead of guesswork

---

### 3️⃣ Transparency & Impact Verification (In Progress)
- NGOs can submit **work reports** for specific crises
- Reports include:
  - Images as proof of work
  - Location metadata
- AI-based verification:
  - Image tampering detection
  - AI-generated image authenticity checks
  - Location verification to match crisis area

🔒 Ensuring trust, accountability, and transparency

---

## 🏗️ System Architecture (High Level)

```
News Sources → Web Scraper → ML & NLP Pipeline (FastAPI) → Crisis Scoring & Geo-tagging → NGO Ranking Engine → Web Platform → Donations & Reports
```

---

## 🛠️ Tech Stack

### 🌐 Web Platform
- **MongoDB** – Database (local instance)
- **Express.js** – Backend API
- **Vanilla JS** – Frontend
- **Node.js** – Server runtime

### 🤖 AI / ML Stack
- **FastAPI** – ML service APIs
- **Hugging Face Transformers** – NLP & classification
- **Kimi (Moonshot AI)** – Advanced reasoning & explanation
- **NumPy & Pandas** – Data processing
- **Python** – ML pipeline implementation

---

## 🔐 Key Highlights

- AI-driven decision making
- Explainable ML outputs
- NGO performance scoring
- Donation tracking & transparency
- NGO transparency through AI
- Scalable microservice-based architecture

---

## 🎯 Use Cases

- Disaster response coordination
- NGO fund allocation optimization
- Government crisis monitoring
- Transparent donor engagement
- AI-assisted humanitarian operations

---

## 📌 Future Scope

- Real-time satellite data integration
- Government dashboard
- Blockchain-based report immutability
- Predictive disaster risk modeling

---
