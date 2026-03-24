# 🚨 Problem: Privileged Container Running as Root

## Description
A container is running with root privileges or unnecessary capabilities.

---

## ⚠️ Risk
- Container escape → full host compromise  
- Malware can affect the entire environment  

---

## 🔍 Scenario
A Docker container ran as root to simplify development.  
A misconfigured image allowed attacker to access host filesystem.

---

## ✅ Fix / Best Practice
- Run containers as non-root users  
- Drop unnecessary capabilities  
- Use security-focused base images  

---

## 🧠 Lesson Learned
Least privilege applies to containers too — never give root unless absolutely necessary.
