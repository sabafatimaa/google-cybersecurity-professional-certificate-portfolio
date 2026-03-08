# Incident Report Analysis
### Applying the NIST Cybersecurity Framework to a Real-World DoS Attack

---

## Overview
This project analyzes a DoS attack on a multimedia company's internal network and builds a security improvement plan using the NIST Cybersecurity Framework (CSF) — covering Identify, Protect, Detect, Respond, and Recover.

---

## Incident Summary
- **Attack:** ICMP Flood DoS via unconfigured firewall
- **Impact:** Full internal network outage for ~2 hours
- **Response:** Blocked ICMP traffic, restored critical services, implemented IDS/IPS and network monitoring

---

## NIST CSF Actions
- **Identify** – Detected unconfigured firewall as root cause
- **Protect** – Applied rate-limiting, IP verification, firewall audits
- **Detect** – Deployed IDS/IPS, SIEM, and automated alerts
- **Respond** – Isolated devices, blocked traffic, defined team roles
- **Recover** – Restored critical services, conducted post-incident review

---

## Reference
[NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)
