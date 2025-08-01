# 🤖 AI-Powered Incident Management System (ServiceNow Integration)

This project is an end-to-end intelligent incident management system that:

- Connects to **ServiceNow** to pull real incident data
- Trains a machine learning model to predict assignment groups
- Detects anomalies in incident patterns
- Sends alerts to **Slack**
- Provides an API via **FastAPI**
- Includes a UI dashboard in **Streamlit**
- Runs background automation to process incidents in real-time
- Supports full deployment via **Docker**

---

## 🏗️ Architecture

- **Incident Source**: ServiceNow API (incident table)
- **Model**: Random Forest Classifier + Isolation Forest
- **Alerting**: Slack Incoming Webhook
- **Frontend**: FastAPI (API) + Streamlit (UI)
- **Automation**: Python background scheduler
- **Logging**: All events stored in `incident_ai.log`

---

## ⚙️ Setup Instructions

### 1. Clone and Install

```bash
git clone https://github.com/yourname/incident-management-ai.git
cd incident-management-ai
pip install -r requirements.txt
