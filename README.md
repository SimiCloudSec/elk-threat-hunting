# elk-threat-hunting
# ELK Threat Detection Room – TryHackMe Lab

This project documents my work in the **"Investigating with ELK 101"** TryHackMe room. I used the Elastic Stack (Elasticsearch, Logstash, Kibana) to analyze network logs and simulate real-world threat detection in a SOC workflow.

---

## 🔍 Lab Overview

- **Platform:** TryHackMe
- **Environment:** Elastic Stack via Kibana interface
- **Goal:** Investigate anomalies in VPN logs using Kibana's Discover, Visualization, and Dashboard features
- **Lab Tasks Completed:**
  - Log filtering by IP, username, and country
  - Building time-based dashboards
  - Creating custom queries to trace suspicious activity
  - Reviewing event history tied to specific users and IPs

---

## 📸 Screenshots

All relevant Kibana screenshots (Discover tab, event spikes, filter usage, dashboard graphs) are stored in the `/screenshots` folder.

---

## 🧠 SOC Takeaways

- Mastered use of Kibana's Discover tab for field analysis  
- Gained experience using **KQL** for log filtering and pattern recognition  
- Investigated suspicious VPN activity including:
  - Excessive logins from the same source IP
  - Region-based filters (e.g., excluding New York)
  - Spike detection via event count histograms

---

## ⚙️ Tools Used

- Kibana (ElasticSearch frontend)
- TryHackMe AttackBox
- KQL (Kibana Query Language)

---

## 📂 Folder Structure

