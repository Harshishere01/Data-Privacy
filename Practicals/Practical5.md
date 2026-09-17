
---

# `05-Anonymization-Techniques.md`

```markdown
# 🕵️ Practical 05 — Anonymization Techniques

> **Subject:** Data Privacy  
> **Practical No.:** 05  
> **Topic:** k-Anonymity, Data Masking and Differential Privacy

---

## 🎯 Aim

To study and apply common data anonymization and privacy-preserving techniques to reduce the risk of identifying individuals from datasets.

---

## 📚 Objectives

- Understand data anonymization.
- Understand k-anonymity.
- Learn data masking.
- Understand differential privacy.
- Apply privacy-preserving transformations to sample data.

---

## 🧠 Theory

Data anonymization techniques attempt to reduce the possibility of linking data to an identifiable individual.

Common techniques include:

1. Data masking
2. Generalization
3. Suppression
4. k-anonymity
5. Differential privacy

---

## 📊 Original Dataset

| Name | Age | City | Disease |
|---|---:|---|---|
| Rahul | 21 | Delhi | Flu |
| Amit | 22 | Delhi | Flu |
| Neha | 21 | Delhi | Cold |
| Priya | 23 | Mumbai | Cold |

---

## 🔒 Data Masking

Data masking replaces part of sensitive information.

Example:

```text
9876543210
