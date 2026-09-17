# 🔐 Practical 04 — Cryptography

> **Subject:** Data Privacy  
> **Practical No.:** 04  
> **Topic:** Encryption, Hashing and Digital Signatures

---

## 🎯 Aim

To understand and implement basic cryptographic techniques including encryption, hashing, and digital signatures.

---

## 📚 Objectives

- Understand the role of cryptography in data privacy.
- Differentiate encryption and hashing.
- Understand symmetric and asymmetric cryptography.
- Understand digital signatures.
- Implement basic cryptographic operations.

---

## 🧠 Theory

**Cryptography** is the practice of protecting information using mathematical techniques.

### Major Techniques

| Technique | Purpose |
|---|---|
| Encryption | Protect confidentiality |
| Hashing | Verify integrity / securely represent data |
| Digital Signature | Authentication and integrity |
| Symmetric Cryptography | Same key for encryption and decryption |
| Asymmetric Cryptography | Uses public and private keys |

---

## 🔒 Symmetric Encryption

In symmetric encryption, the same secret key is used for encryption and decryption.

```text
Plaintext
    ↓
Encryption + Secret Key
    ↓
Ciphertext
    ↓
Decryption + Secret Key
    ↓
Plaintext
