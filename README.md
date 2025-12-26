# 🔎 HTTP Log Analysis & Anomaly Detection using Splunk SIEM

This repository documents a **SOC-style HTTP log analysis project** using **Splunk SIEM**, focused on ingesting, parsing, and analyzing web server logs to identify **abnormal behavior and security-relevant patterns**.

The project emphasizes **manual log onboarding, field extraction, and analyst-driven investigation**, rather than real-time alerting or automated detection.

---

## 🎯 Project Objective

The objective of this project was to:

- Ingest sample HTTP access logs into Splunk  
- Configure appropriate source types and indexing  
- Perform **manual field extraction using regex**
- Analyze web traffic patterns using **SPL queries**
- Identify anomalies such as abnormal errors and request behavior
- Investigate suspicious source activity from HTTP logs
- Practice SOC-aligned log analysis workflows  

---

## 🧪 Environment Overview

| Component | Description |
|--------|-------------|
| SIEM Platform | Splunk Enterprise |
| Log Type | HTTP Access Logs |
| Ingestion Method | Manual file upload |
| Parsing Method | Regex-based field extraction |
| Analysis Method | SPL-based searches |
| Scope | Detection & analysis (no alerting) |

---

## 🧭 SOC Workflow Demonstrated

1️⃣ Log ingestion and validation  
2️⃣ Source type and index handling  
3️⃣ Field extraction and normalization  
4️⃣ Baseline traffic analysis  
5️⃣ Anomaly identification  
6️⃣ Suspicious source investigation  
7️⃣ Analyst interpretation  

---

## 🔍 Core Analysis Use Cases

- HTTP method distribution analysis  
- Status code frequency and error patterns  
- Time-based anomaly observation  
- High-frequency source identification  
- Endpoint and resource access concentration  

---

## ⚠️ Ethical & Usage Notice

- All log data is sample or lab-generated  
- No live systems were monitored  
- No exploitation or unauthorized access occurred  
- Project is intended for **defensive learning only**  

---

📌 *This repository is part of my cybersecurity portfolio and demonstrates hands-on experience with SIEM-based HTTP log ingestion, parsing, and anomaly analysis.*


