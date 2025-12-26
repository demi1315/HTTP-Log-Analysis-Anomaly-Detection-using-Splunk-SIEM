# ⚠️ Detection Gaps & Security Blind Spots – HTTP Log Analysis

---

## 🔍 Overview

This document analyzes **visibility gaps and detection weaknesses** identified during HTTP log analysis.  
The focus is not on missing data, but on **what could go unnoticed without proper detection logic**.

---

## 🚫 Absence of Defined Traffic Baselines

Without an established baseline, abnormal behavior blends into normal traffic.

**Why this matters:**
- Anomalies cannot be measured accurately  
- SOC teams rely on intuition instead of data  
- Attackers can operate under the radar  

---

## 🚨 Lack of Behavioral Detection Rules

Repeated suspicious behaviors were observable but not automatically flagged.

Examples include:
- Excessive requests from a single IP  
- Repeated access to sensitive endpoints  
- High error response frequency  

**Impact:**  
Reconnaissance and brute-force activity may go undetected.

---

## 🧱 No Rate-Limiting Indicators

Traffic patterns suggested automation, but no thresholds were in place to highlight it.

**Impact:**  
- Credential abuse may continue unchecked  
- Application resources may be stressed  

---

## 👁️ Limited User Behavior Correlation

Analysis showed limited correlation between:
- Source IP  
- Request patterns  
- User-agent characteristics  

**Impact:**  
Difficult to distinguish malicious automation from legitimate users.

---

## 🔕 Missing Alert Context

Even when suspicious behavior exists, lack of alerting context prevents prioritization.

**Impact:**  
- Analyst fatigue  
- Delayed response  
- Missed early indicators  

---

## 🧠 Root Cause Summary

Most gaps stemmed from:
- Lack of detection engineering  
- No defined thresholds  
- Overreliance on manual searches  
- Absence of behavioral correlation  

These are **common SIEM maturity issues**, even in real organizations.
