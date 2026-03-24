# 🚨 Problem: Publicly Accessible S3 Bucket

## Description
S3 bucket is open to the public without restrictions.

---

## ⚠️ Risk
- Anyone on the internet can access sensitive files  
- Data breach / leak  

---

## 🔍 Scenario
A developer uploaded logs containing PII to a public bucket.  
Search engines indexed it, exposing user data.

---

## ✅ Fix / Best Practice
- Block public access by default  
- Use bucket policies with least privilege  
- Encrypt sensitive data  

---

## 🧠 Lesson Learned
Never assume data is “safe” just because it’s in the cloud.
