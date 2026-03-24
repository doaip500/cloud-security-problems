# 🚨 Problem: Overly Broad Bucket Policy

## Description
Bucket policies grant excessive permissions to multiple users or roles.

---

## ⚠️ Risk
- Users can accidentally or intentionally access sensitive objects  
- Misconfigurations can lead to data leaks  

---

## 🔍 Scenario
A bucket policy allowed all IAM users read/write access to critical logs.  
A junior developer mistakenly deleted files needed for compliance.

---

## ✅ Fix / Best Practice
- Apply least privilege  
- Limit policies to specific users/roles  
- Monitor policy changes  

---

## 🧠 Lesson Learned
Fine-grained policies prevent accidental exposure and maintain control.
