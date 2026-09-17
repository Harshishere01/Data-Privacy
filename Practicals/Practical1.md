# 🔍 Practical 01 — Data Privacy Audit

> **Subject:** Data Privacy  
> **Practical No.:** 01  
> **Topic:** Data Privacy Audit

---

## 🎯 Aim

To conduct a data privacy audit of an organization to identify potential privacy risks and vulnerabilities in its data collection, storage, processing, and sharing practices.

---

## 📚 Objectives

- Understand the purpose of a data privacy audit.
- Identify different types of personal data.
- Examine how an organization handles personal information.
- Identify potential privacy risks.
- Recommend suitable privacy controls.

---

## 🧠 Theory

A **Data Privacy Audit** is a systematic examination of an organization's practices for collecting, processing, storing, sharing, and protecting personal data.

A privacy audit helps an organization identify weaknesses in its data-handling practices and implement appropriate technical and organizational controls.

For this practical, a hypothetical e-commerce company named **ABC Technologies Pvt. Ltd.** is considered.

---

## 🏢 Organization Profile

| Attribute | Details |
|---|---|
| Organization | ABC Technologies Pvt. Ltd. |
| Industry | E-Commerce |
| Services | Online Shopping |
| Data Subjects | Customers and Employees |
| Assessment Type | Data Privacy Audit |

---

## 📊 Data Inventory

| Data Category | Examples | Risk |
|---|---|---|
| Identity Data | Name, User ID | Medium |
| Contact Data | Email, Phone | Medium |
| Address Data | Delivery Address | High |
| Payment Data | Transaction Information | High |
| Account Data | Username, Password Hash | High |
| Technical Data | IP Address, Device Information | Medium |
| Transaction Data | Orders and Purchases | Medium |

---

## 🔎 Audit Checklist

| Audit Area | Observation | Status |
|---|---|:---:|
| Data collection is documented | Registration and checkout data are collected | ✅ |
| Purpose of collection is defined | Purpose should be clearly communicated | ⚠️ |
| User consent is managed | Consent mechanism is provided where applicable | ✅ |
| Passwords are protected | Password hashing is used | ✅ |
| Sensitive data is encrypted | Encryption should be reviewed | ⚠️ |
| Access is restricted | Role-based access is recommended | ⚠️ |
| Retention period is defined | Retention policy requires review | ⚠️ |
| Privacy policy exists | Privacy policy is available | ✅ |
| Third-party sharing is documented | Further verification required | ⚠️ |
| Breach response procedure exists | Formal procedure should be documented | ⚠️ |

### Status Legend

- ✅ Satisfactory
- ⚠️ Requires Improvement
- ❌ Unsatisfactory

---

## ⚠️ Identified Privacy Risks

### 1. Excessive Data Collection

Collecting unnecessary information can increase privacy risks.

**Recommendation:** Apply data minimization and collect only information necessary for the stated purpose.

### 2. Unauthorized Access

Employees or systems with unnecessary access to personal data may increase the risk of disclosure.

**Recommendation:** Implement role-based access control and multi-factor authentication.

### 3. Inadequate Encryption

Sensitive information may be exposed if appropriate encryption is not implemented.

**Recommendation:** Use appropriate encryption for data in transit and at rest.

### 4. Excessive Data Retention

Keeping personal information longer than necessary increases exposure.

**Recommendation:** Establish data retention and secure deletion procedures.

### 5. Third-Party Sharing

Personal data may be shared with payment processors, delivery providers, or other service providers.

**Recommendation:** Maintain records of third-party processors and review their privacy and security controls.

---

## 🛠️ Recommended Controls

| Risk | Recommended Control |
|---|---|
| Excessive collection | Data minimization |
| Unauthorized access | RBAC + MFA |
| Data interception | Secure communication protocols |
| Database exposure | Encryption |
| Excessive retention | Retention and deletion policy |
| Third-party exposure | Vendor assessment |
| Employee mistakes | Privacy training |
| Data breaches | Incident response plan |

---

## 📈 Risk Assessment

**Risk Score = Likelihood × Impact**

| Risk | Likelihood | Impact | Risk Level |
|---|:---:|:---:|---|
| Unauthorized access | 3 | 3 | 🔴 High |
| Excessive collection | 2 | 2 | 🟡 Medium |
| Data leakage | 2 | 3 | 🔴 High |
| Excessive retention | 2 | 2 | 🟡 Medium |
| Third-party exposure | 2 | 3 | 🔴 High |

**Scale:** 1 = Low, 2 = Medium, 3 = High

---

## 📝 Result

A data privacy audit was successfully conducted for the hypothetical organization. Potential risks related to data collection, access control, encryption, retention, and third-party sharing were identified and suitable mitigation measures were recommended.

---

## 🎤 Viva Questions

**Q1. What is a data privacy audit?**  
A data privacy audit is a systematic review of how an organization collects, processes, stores, shares, and protects personal data.

**Q2. What is data minimization?**  
Data minimization means collecting only the information necessary for a specific purpose.

**Q3. What is RBAC?**  
RBAC stands for Role-Based Access Control. It restricts access according to a user's organizational role.

**Q4. Why is encryption important?**  
Encryption helps protect information from unauthorized access.

---

## ✅ Conclusion

A privacy audit helps an organization identify weaknesses in its handling of personal information and implement suitable controls to reduce privacy risks.
