# 🛡️ Detection & Monitoring Improvements – Splunk SIEM

---

## 🎯 Detection Engineering Enhancements

To improve visibility and reduce blind spots, the following detection improvements are recommended:

- 📊 Define normal request-rate baselines  
- 🚩 Alert on abnormal request spikes  
- 🔐 Monitor repeated authentication failures  
- 🧭 Detect repeated access to sensitive endpoints  
- 🤖 Flag suspicious or missing user-agent strings  

---

## 📥 Log Quality & Normalization

Effective detection requires consistent data.

Recommended actions:
- Normalize HTTP fields across logs  
- Ensure consistent timestamp formats  
- Retain logs for sufficient investigation periods  
- Protect log integrity from tampering  

---

## 🧠 SOC Monitoring Best Practices

- Build dashboards for traffic trends  
- Use time-based correlation  
- Track recurring anomalies  
- Tune alerts to reduce noise  
- Periodically review detection effectiveness  

---

## 🛡️ Preventive Controls (Beyond SIEM)

While SIEM focuses on detection, prevention strengthens outcomes:

- Implement rate limiting  
- Deploy Web Application Firewalls (WAF)  
- Enforce authentication protections  
- Monitor application error behavior  

---

## ✅ Summary

Detection effectiveness improves when **behavior is understood, thresholds are defined, and alerts are contextualized**. SIEM success depends as much on tuning as on tooling.
