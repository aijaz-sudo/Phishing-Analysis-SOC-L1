# 🛡️ Phishing Incident Report

## 1. Executive Summary
A phishing URL obtained from PhishTank was analyzed. The URL was designed to impersonate a legitimate service and trick users into entering sensitive information such as login credentials.

---

## 2. Investigation Details
- Source: PhishTank
- Analyst: Aijaz
- Date: 01-May-2026

---

## 3. Technical Analysis

### 🔹 URL Analysis (VirusTotal)
- The URL was analyzed using VirusTotal
- Multiple security vendors flagged it as malicious
- Indicates phishing or credential harvesting activity

### 🔹 Webpage Analysis (URLScan)
- The webpage mimics a legitimate login page
- Likely designed to steal user credentials
- Suspicious behavior observed

### 🔹 Domain Analysis (WHOIS)
- Domain was recently registered
- WHOIS information is hidden
- Common trait in phishing domains

### 🔹 IP Analysis (AbuseIPDB)
- The IP address has been reported for malicious activity
- High abuse confidence score

---

## 4. Indicators of Compromise (IOCs)
| Type   | Value | Description |
|--------|------|------------|
| URL    | (your URL) | Phishing link |
| Domain | (domain) | Suspicious domain |
| IP     | (IP) | Malicious IP |

---

## 5. MITRE ATT&CK Mapping
- T1566 – Phishing
- T1204 – User Execution

---

## 6. Conclusion
Based on multiple sources including VirusTotal, URLScan, WHOIS, and AbuseIPDB, the URL is confirmed as a phishing attack designed to steal user credentials.

---

## 7. Recommendations
- Block the domain and IP at firewall level
- Add URL to email filtering systems
- Conduct user awareness training
- Monitor for similar phishing attempts