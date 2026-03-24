# 🚨 Problem: Open Security Group (0.0.0.0/0)

## Description
Security group allows inbound traffic from all IPs on all ports.

---

## ⚠️ Risk
- Any attacker can access services  
- Easy entry point for exploits  

---

## 🔍 Scenario
A web server had SSH open to the world.  
Automated bots scanned and brute-forced the password, gaining access.

---

## ✅ Fix / Best Practice
- Restrict IP ranges to trusted sources  
- Only open necessary ports  
- Enable logging and monitoring  

---

## 🧠 Lesson Learned
Default “open to all” = invitation for compromise.
