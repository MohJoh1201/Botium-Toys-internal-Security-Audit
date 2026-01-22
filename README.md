# Botium Toys Internal Security Audit

## Project Overview

Botium Toys is a small business that develops and sells toys. This audit evaluates the company’s security posture based on current controls, threats, risks, and compliance standards. The goal is to identify weaknesses and recommend improvements to strengthen information security, protect customer data, and comply with applicable standards.

---

## 📂 Documents

The following documents are included in this repository:

- **Audit scope, goals, and risk assessment report**  
  `documents/Botium Toys Scope, goals, and risk assessment report.docx`

- **Controls and compliance checklist**  
  `documents/Controls and compliance checklist.docx`

---

## 🔍 Key Findings

The audit revealed several gaps in Botium Toys’ security posture, including:

- Lack of encryption for sensitive data (PII/SPII and payment information)  
- Missing backups and no documented disaster recovery plan  
- No intrusion detection system (IDS)  
- Lack of least privilege and separation of duties  
- Password management system not implemented

---

## 🧾 Compliance Evaluation Results

### **PCI DSS**
- Customer card data is not encrypted in transit or at rest  
- Secure storage and key management procedures are missing  
- Access is not limited only to authorized users

### **GDPR**
- E.U. customer data is maintained securely  
- Data breach notification policy exists (72-hour window)
- Data classification & inventory processes are incomplete

### **SOC (Type 1 / Type 2)**
- Data integrity and availability are ensured  
- Access policies need formal documented implementation  
- Sensitive data confidentiality protections are incomplete

---

## 🛠 Security Control Assessment

The following controls were reviewed:

| Control | Implemented |
|----------|-------------|
| Least Privilege | ❌ |
| Password Policies | ✔️ |
| Firewall | ✔️ |
| IDS | ❌ |
| Encryption | ❌ |
| Backups | ❌ |
| Antivirus | ✔️ |
| Physical locks & CCTV | ✔️ |
| Fire detection/prevention | ✔️ |

---

## 📸 Screenshots

Below are screenshots from the completed internal audit tasks:

![Checklist Screenshot](images/your-checklist-file.png)  
*Completed internal controls checklist overview.*

---

## 🧠 Recommendations

The following actions are highly recommended to improve Botium Toys’ security posture:

- Implement data encryption for all sensitive information  
- Establish backups and a formal disaster recovery plan  
- Deploy an intrusion detection system (IDS)  
- Enforce least privilege and separation of duties  
- Adopt a centralized password management system  
- Formalize user access policies and documentation

---

## 📌 Notes

This internal audit is based on the NIST Cybersecurity Framework (NIST CSF) and evaluates applicable security controls, best practices, and compliance standards such as PCI DSS, GDPR, and SOC 1/2.


