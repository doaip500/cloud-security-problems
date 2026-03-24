# 🚨 Problem: Sharing Root Credentials

## Description
Root account credentials are shared among multiple team members.

---

## ⚠️ Risk
- No audit trail → cannot track actions  
- Full access for anyone → massive risk  

---

## 🔍 Scenario
A team shared AWS root login for convenience.  
One member accidentally deleted critical resources.

---

## ✅ Fix / Best Practice
- Never use root for daily operations  
- Create IAM users with least privilege  
- Enable MFA on root account  

---

## 🧠 Lesson Learned
Root accounts should remain untouched; use roles for delegation.
