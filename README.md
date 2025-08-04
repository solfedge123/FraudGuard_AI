#  FraudGuard Real-Time Transaction Fraud Detector

**A production-ready, explainable AI system that detects fraudulent transactions in real time — and tells you *why*.**

Built with Python, XGBoost, SHAP, and Gradio, **FraudGuard** combines supervised and unsupervised learning to deliver accurate, transparent, and instant fraud predictions. Perfect for fintech, payment gateways, or any transaction-based platform.


##  Why This Stands Out

 **End-to-End ML Pipeline**  From synthetic data generation to real-time inference
 **Explainable AI (XAI)**  SHAP-powered waterfall plots show *exactly why* a transaction was flagged
 **Dual-Model Intelligence** Combines XGBoost (supervised) + Isolation Forest (anomaly detection)
 **Production-Ready** Modular code, model persistence, and Gradio UI for instant interaction

---

##  How It Works

### 1. **Synthetic Data Engine**
Generates realistic transaction data with:
- Log-normal amounts
- Risky countries (Nigeria, Russia, China)
- High-risk categories (Crypto, Gambling)
- 5% fraud rate (realistic imbalance)

### 2. **Dual-Model Detection**
| Model | Type | Role |
|------|------|------|
| **XGBoost Classifier** | Supervised | Predicts fraud probability |
| **Isolation Forest** | Unsupervised | Detects anomalous behavior |

### 3. **Explainability with SHAP**
Every prediction comes with a **waterfall plot** showing:
- Which features pushed the decision toward fraud
- Feature impact in real monetary/behavioral terms
- Transparency for compliance & trust

### 4. **Real-Time Gradio App**
Interactive web interface where users can:
- Input transaction details
- Get instant risk assessment
- See model reasoning (no black box!)

---


