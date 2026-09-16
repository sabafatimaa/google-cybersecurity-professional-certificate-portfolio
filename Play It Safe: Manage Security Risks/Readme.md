# Internal Security Audit & Compliance Assessment: Botium Toys

## Scenario
Botium Toys is a growing U.S.-based toy developer and retailer combining a main office, storefront, and warehouse. As its online market expands internationally to customers in the U.S. and abroad, the IT department faces increasing pressure to support worldwide business operations. To address growing concerns about security posture, business continuity, and regulatory compliance, the IT manager initiated an internal IT audit.

## Project Overview
Using the **National Institute of Standards and Technology Cybersecurity Framework (NIST CSF)**, this project establishes an audit scope and goals, inventories IT-managed assets, performs a risk assessment, and completes a comprehensive controls and compliance checklist. The objective is to identify security gaps, evaluate risks to critical assets, and ensure adherence to international regulations such as **PCI DSS** (for payment card processing) and **GDPR** (for E.U. customer data protection).

## Tech Stack & Frameworks
* **Security Framework:** NIST Cybersecurity Framework (CSF)
* **Compliance Standards:** PCI DSS, GDPR, SOC Type 1 & Type 2
* **Core Concepts:** Internal IT Audit, Risk Assessment, Security Controls, Asset Management, Gap Analysis

## Key Findings & Checklist Summary
* **Controls Assessment:** Identified critical missing controls, including least privilege, separation of duties, disaster recovery plans, data backups, intrusion detection systems (IDS), encryption, and a centralized password manager. Verified existing controls such as firewalls, antivirus software, legacy system monitoring, and physical security (locks, CCTV, fire detection).
* **PCI DSS Compliance:** Flagged non-compliance due to unencrypted credit card data storage/transmission and lack of role-based access restrictions for cardholder data.
* **GDPR & SOC Compliance:** Identified gaps in asset inventory and user access policies, while confirming the presence of a 72-hour breach notification plan for E.U. customers and enforced internal privacy policies.

## Recommendations
* **Enforce Access Controls:** Implement least privilege and separation of duties to restrict employee access to credit card data and PII/SPII.
* **Deploy Encryption & Backups:** Introduce data encryption for payment touchpoints alongside robust disaster recovery plans and automated backups.
* **Enhance Monitoring & Infrastructure:** Install an Intrusion Detection System (IDS), adopt a centralized password management system, and establish a formal asset inventory and legacy system maintenance schedule.

## Documentation
 **[Controls and Compliance Checklist](./Controls_and_Compliance_Checklist.pdf)**

## Author
Saba Fatima

Aspiring Cybersecurity Analyst | SOC Analyst | Incident Response | Threat Detection | Network Security | Log Analysis
