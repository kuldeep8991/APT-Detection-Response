# APT-Detection-Response
# 🔐 Advanced Persistent Threat (APT) Detection & Automated Incident Response

## 📌 Project Overview

This project focuses on detecting Advanced Persistent Threats (APT) and automating incident response using **Wazuh EDR** and **n8n workflow automation**.

The system continuously monitors endpoints, analyzes logs, detects suspicious activities, and automatically triggers response actions like alerts, notifications, and threat containment.

---

## 🚀 Features

* Real-time APT detection using Wazuh
* Log analysis and correlation
* Automated incident response using n8n
* Email & Slack alerts
* Threat filtering (high-risk detection)
* Optional auto-block mechanism
* Centralized logging and monitoring

---

## 🏗️ Architecture

* Wazuh Manager (SIEM + EDR)
* Wazuh Agents (Windows/Linux)
* n8n (SOAR Automation)
* Database (MySQL)
* Alert systems (Email / Slack)

---

## ⚙️ Technologies Used

* Wazuh EDR
* n8n Automation
* OpenSearch
* Linux (Ubuntu/Kali)
* Windows Endpoints
* SMTP / Slack API

---

## 🔄 Workflow

1. Collect logs from endpoints
2. Analyze using Wazuh rules
3. Detect APT patterns
4. Send alerts to n8n
5. Filter high-risk threats
6. Trigger automated response:

   * Email alerts
   * Slack notifications
   * Auto-block (optional)

---

## 📸 Screenshots

Screenshots of:

* Wazuh Dashboard
* Agent Status
* Logs & Alerts
* n8n Workflow
* Email Alerts

---

## 📂 Project Structure

```
APT-Detection-Response/
│── Screenshots/
│── n8n-workflows/
│── wazuh-config/
│── scripts/
│── database/
│── docs/
```

---

## 📊 Results

* Successfully detected APT-like behavior
* Automated alert generation
* Reduced response time
* Improved SOC efficiency

---

## 🔮 Future Scope

* Machine Learning-based detection
* Cloud integration
* Threat intelligence feeds
* Full automated response (auto isolation)

---

## 👨‍💻 Author

Kuldeep Singh
PG Diploma in IT Infrastructure, Systems & Security
C-DAC Bangalore

---

## 📜 License

This project is for educational and research purposes.
