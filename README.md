# Real-Time-Fraud-Detection-in-UPI-Transactions
**Real-Time UPI Fraud Detection System** — A live transaction monitor with rule-based and ML-powered fraud detection for UPI systems. Built using FastAPI, PostgreSQL, React, and WebSockets. Displays flagged transactions on a real-time dashboard. Inspired by BHIM and Juspay-grade systems.
# 💳 Real-Time UPI Fraud Detection System

This project is a real-time fraud detection system for UPI (Unified Payments Interface) transactions, designed to simulate and flag suspicious activity using both **rule-based logic** and **machine learning**.

---

## 🌟 Key Features

- 🚀 **Real-time transaction monitoring**
- ⚠️ **Fraud detection using ML (Isolation Forest)**
- 📊 **Live dashboard with analytics**
- 🔁 **Retry & rate-limiting logic**
- 🧠 **Rule-based + Anomaly detection**
- ☁️ **Deployed on AWS/Render with PostgreSQL**

---

## 📸 Screenshots

![Live Feed](https://your-screenshot-link.com)
![Fraud Alert UI](https://your-screenshot-link.com)

---

## ⚙️ Tech Stack

| Backend  | Frontend | ML | Database | Real-Time |
|----------|----------|----|----------|-----------|
| FastAPI  | React    | Sklearn | PostgreSQL | WebSocket |

---

## 🧠 Fraud Detection Logic

### ✅ Rule-Based (Basic)
- Amount > ₹50,000
- Same user → multiple recipients < 5s
- Suspicious keywords in remarks (e.g., “bet”, “crypto”)

### 🧠 ML-Based (Advanced)
- Anomaly Detection using Isolation Forest
- Flags transactions that deviate from normal patterns

---

## 📈 Dashboard Features

- 📊 Graph of transactions per second
- 🔍 Table view of flagged transactions
- 🟢 Auto-refreshing live stream
- 🔧 Admin panel to tweak thresholds

---

## 📂 Folder Structure

