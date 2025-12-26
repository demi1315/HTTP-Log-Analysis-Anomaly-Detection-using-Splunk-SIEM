# 📸 Screenshot Reference – HTTP Log Analysis (Splunk SIEM)

All screenshots in this directory were captured from a **controlled lab environment** and are included strictly for **documentation and learning purposes**.

Screenshots focus on **log ingestion, field extraction, SPL-based analysis, and investigation outputs**, not dashboards or automated alerts.

---

## 📥 Log Ingestion & Validation

- **log-upload.png**  
  Manual upload of sample HTTP access logs using *Splunk → Add Data → Upload*.

- **sourcetype-index-selection.png**  
  Review and configuration of sourcetype and index during ingestion.

- **ingestion-verification.png**  
  SPL search confirming that HTTP events were indexed and searchable.

---

## 🧱 Field Extraction & Parsing

- **field-extraction-overview.png**  
  Using *Extract New Fields* to identify relevant HTTP log components.

- **regex-field-mapping.png**  
  Regular expression–based extraction of source IP, destination IP, method, and status fields.

- **extracted-fields-validation.png**  
  Verification of newly extracted fields appearing under *Interesting Fields* in search results.

---

## 🔍 SPL-Based Analysis Evidence

- **method-distribution-analysis.png**  
  SPL query analyzing HTTP request method distribution.

- **status-code-frequency.png**  
  Analysis of HTTP status code patterns to identify error trends.

- **time-based-error-analysis.png**  
  Time-based SPL analysis highlighting abnormal error spikes.

---

## 🚨 Anomaly & Investigation Evidence

- **high-error-source-ips.png**  
  Identification of source IPs generating repeated HTTP errors.

- **high-volume-request-sources.png**  
  SPL results showing high-frequency request origins.

- **endpoint-access-patterns.png**  
  Analysis of frequently accessed URIs to detect potential enumeration behavior.

---

## 📝 Notes

- All log data is **sample or lab-generated**
- No real user or production data is included
- Screenshots represent **manual analysis outputs**, not dashboards
- Evidence supports analyst-driven investigation workflows only
