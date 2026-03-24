# 🚨 Problem: Overly Permissive IAM Policy

## Description
An IAM user or role has a policy that grants `"*"` permissions on `"*"`.  
This gives full access to all AWS resources, far beyond what the user needs.

---

## ⚠️ Risk
- Any compromised account can take full control over the cloud environment  
- Sensitive data can be exposed, deleted, or modified  
- Entire infrastructure can be destroyed or misused  

---

## 🔍 Scenario
A developer accidentally attaches the `AdministratorAccess` policy to a temporary user created for testing.  
Later, the credentials are leaked or misused, allowing attackers unrestricted access.

---

## ✅ Fix / Best Practice
1. **Principle of Least Privilege**: Give only the permissions required for the specific task.  
2. **Use roles over permanent users**: Assign temporary credentials where possible.  
3. **Regularly audit IAM policies**: Look for `*:*` permissions and reduce them.  
4. **Enable MFA (Multi-Factor Authentication)** for sensitive accounts.  

---

## 🧠 Lesson Learned
- IAM misconfigurations are one of the **most common causes of cloud breaches**  
- Controlling **who can do what** is more important than securing servers or network alone  

---

## 📌 References
- [AWS IAM Best Practices](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html)  
- [Real-world Breach Examples](https://www.cloudsecurityalliance.org/blog/2021/12/15/top-cloud-misconfigurations/)
