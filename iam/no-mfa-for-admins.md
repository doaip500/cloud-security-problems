# 🚨 Problem: No MFA for Admin Accounts

## Description
Admin accounts are not protected with Multi-Factor Authentication (MFA).

---

## ⚠️ Risk
- If a password is compromised, attackers get full access  
- Root and high-privilege accounts are extremely vulnerable  

---

## 🔍 Scenario
An admin reused a weak password across multiple services.  
Without MFA, the account was easily compromised by phishing.

---

## ✅ Fix / Best Practice
- Enable MFA for all admin users  
- Use strong, unique passwords  
- Prefer temporary roles for high-privilege tasks  

---

## 🧠 Lesson Learned
MFA drastically reduces the risk of account compromise, even if credentials leak.
