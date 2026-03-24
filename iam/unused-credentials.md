# 🚨 Problem: Unused IAM Credentials

## Description
IAM users or keys that are created but never used remain active indefinitely.

---

## ⚠️ Risk
- Attackers can find and exploit dormant accounts  
- Unauthorized access without detection  

---

## 🔍 Scenario
A developer created a test IAM user months ago and never deleted it.  
The credentials were later leaked, giving attackers access to sensitive resources.

---

## ✅ Fix / Best Practice
- Regularly audit and remove unused users and access keys  
- Implement automated expiration for temporary credentials  
- Monitor inactive accounts  

---

## 🧠 Lesson Learned
Even “inactive” accounts are dangerous if left unchecked. Regular audits are critical.
