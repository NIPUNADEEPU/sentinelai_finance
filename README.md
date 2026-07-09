# 🛡️ SentinelAI Finance Master Orchestrator

An enterprise-grade digital safety platform and financial threat analysis dashboard powered by **IBM Watsonx.ai** and **Streamlit**. This platform performs real-time security orchestration, intent detection, and threat mapping on suspicious financial communications (SMS, emails, alerts) while exposing explicit agentic execution traces.

---

## 🚀 Core Features

- **🔍 Sentinel Intent Detection:** Automatically classifies incoming digital communications into precise safety profiles (e.g., SMS/Text Scam Analysis, Valid Transactions, URL Verification).
- **⚙️ Agentic Execution Traces:** Displays step-by-step visibility into the backend processing logic (Routing, Knowledge Fetching, and Action Planning).
- **🛡️ Sentinel Advanced Response:** Generates context-aware mitigation roadmaps, warning thresholds, and immediate safety steps for end-users.
- **✅ Legitimate Message Interception:** Features an inline fallback safety engine that gracefully validates clean, official institutional communications without payload truncation or hallucinations.

---

## 🛠️ Architecture & Flow

1. **User Ingestion Window:** Captures text payloads through a sanitized Streamlit input container.
2. **Dynamic IAM Authentication Layer:** Handshakes dynamically with IBM Cloud IAM servers to provision a high-security, ephemeral OAuth access token.
3. **Deterministic Inference Optimization:** Dispatches variables into a customized model deployment via a zero-temperature `greedy` decoding execution pathway.
4. **Fallback Evaluation Engine:** Intercepts null/truncated structural payloads to explicitly confirm legitimate banking alerts with clean verification layouts.

---

## 💻 Installation & Quickstart

### 1. Prerequisites
Ensure you have Python 3.8+ installed on your local workstation.

### 2. Clone the Repository
```bash
git clone [https://github.com/NIPUNADEEPU/sentinelai_finance.git](https://github.com/NIPUNADEEPU/sentinelai_finance.git)
cd sentinelai_finance
