# SY Electronics Ltd: Scope, Goals, and Risk Assessment Report

## Scope and Goals of the Audit

**Scope:**  
The scope of this audit covers the entire security programme at SY Electronics Ltd., including their assets (employee equipment, devices, internal network, and systems). The audit will assess these assets and evaluate the controls and compliance practices in place.

**Goals:**  
- Assess existing assets and complete a controls and compliance checklist.
- Identify necessary improvements to enhance SY Electronics Ltd.'s security posture.

---

## Current Assets

### Assets managed by the IT Department:
- **On-premises equipment** for in-office business needs.
- **Employee equipment:** Desktops/laptops, smartphones, remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
- **Shopfront products** available for retail sale on-site and online, stored in the adjoining warehouse.
- **Management of systems, software, and services:** Accounting, telecommunication, database, security, e-commerce, and inventory management.
- **Internet access and internal network.**
- **Data retention and storage.**
- **Legacy system maintenance:** End-of-life systems requiring manual monitoring.

---

## Risk Assessment

### **Risk Description:**
Currently, there is inadequate asset management. Additionally, SY Electronics Ltd. lacks some necessary security controls and may not be fully compliant with UK and international regulations.

### **Control Best Practices:**
The first function of the NIST Cybersecurity Framework (CSF) is **Identify**. SY Electronics Ltd. must:
- Dedicate resources to identifying assets for proper management.
- Classify existing assets.
- Determine the impact of asset loss on business continuity.

### **Risk Score:**
📊 **8/10 (High Risk)**  
Lack of controls and compliance adherence increases vulnerability.

### **Additional Comments:**
- Potential asset loss impact: **Medium**, due to unknown at-risk assets.
- Risk of regulatory fines: **High**, due to missing compliance controls.

---

## Key Risk Factors

- 🔴 **All employees have access to sensitive customer data (PII/SPII, cardholder data).**
- 🔴 **No encryption is used to protect customer credit card data.**
- 🔴 **No implementation of least privilege access or separation of duties.**
- 🟡 **Firewall and endpoint protection software are in place but require further security enhancements.**
- 🔴 **No Intrusion Detection System (IDS) is installed.**
- 🔴 **No disaster recovery plans or backups of critical data exist.**
- 🟡 **Incident response plan exists but needs enforcement.**
- 🔴 **Weak password policy with no password management system.**
- 🟡 **Legacy system maintenance lacks a structured schedule.**
- ✅ **Physical security measures (locks, CCTV, fire prevention) are in place.**

---

## **Confidential Security Audit Report**
📅 **Audit Date:** 17th March 2024  
👤 **Auditor:** Genesis Varelli  

**Objective:** Assess the security posture of SY Electronics Ltd., focusing on SOC (Security Operations Centre) functions: log analysis, incident response, and compliance monitoring.

---

## Controls Assessment Checklist

| Control | Status | Explanation |
|---------|--------|-------------|
| Least Privilege | ❌ | All employees have access to sensitive data. |
| Disaster Recovery Plan | ❌ | No disaster recovery plans in place. |
| Password Policies | ❌ | Minimal password requirements, increasing risk. |
| Separation of Duties | ❌ | CEO manages both daily operations and payroll. |
| Firewall | ✅ | Properly configured security rules. |
| Intrusion Detection System (IDS) | ❌ | No IDS implemented. |
| Backups | ❌ | No data backups exist. |
| Antivirus Software | ✅ | Installed and monitored. |
| Legacy System Maintenance | ❌ | No structured maintenance schedule. |
| Encryption | ❌ | No encryption for sensitive data. |
| Password Management System | ❌ | No centralised password management system. |
| Physical Security (Locks, CCTV, Fire Prevention) | ✅ | All security measures are in place. |

---

## Compliance Checklist

### **PCI DSS Compliance**

| Requirement | Status | Explanation |
|------------|--------|-------------|
| Restricted access to cardholder data | ❌ | All employees can access customer credit card info. |
| Secure processing and storage of credit card data | ❌ | No encryption is used. |
| Encryption of financial transactions | ❌ | No encryption measures in place. |
| Secure password management policies | ❌ | Weak password policies, no password management system. |

### **GDPR Compliance**

| Requirement | Status | Explanation |
|------------|--------|-------------|
| Data privacy and security | ❌ | No encryption used for personal data. |
| Breach notification within 72 hours | ✅ | Incident response plan exists. |
| Data classification and inventory | ❌ | Assets are listed but not classified. |
| Privacy policies and documentation | ✅ | Policies exist but need better enforcement. |

### **SOC Type 1 & 2 Compliance**

| Requirement | Status | Explanation |
|------------|--------|-------------|
| User access policies | ❌ | Least privilege controls missing. |
| PII/SPII confidentiality | ❌ | No encryption measures in place. |
| Data integrity | ✅ | Integrity controls are in place. |
| Access control enforcement | ❌ | All employees have unrestricted access. |

---

## **Recommendations**

🔹 Implement **least privilege access** to restrict sensitive data exposure.  
🔹 Develop and enforce **strong password policies** and implement a **password management system**.  
🔹 Establish **disaster recovery plans** and ensure **regular data backups**.  
🔹 Implement **Intrusion Detection System (IDS)** for better security monitoring.  
🔹 Regularly **review and classify assets** to determine protection needs.  
🔹 **Encrypt sensitive data** to enhance security and compliance.  
🔹 Introduce **separation of duties** to improve operational security.  

---

📢 *Confidential Report - For Internal Use Only*

