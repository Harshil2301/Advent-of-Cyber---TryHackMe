# 🎄 Advent of Cyber 2025 — Day 05  
## 🌐 Web Security Fundamentals & IDOR Awareness

Day 05 focuses on **web application security**, introducing common weaknesses that arise when applications fail to properly control user access to resources. The primary concept explored is **Insecure Direct Object Reference (IDOR)**.

Web applications are a frequent attack target, making understanding access control flaws essential for both developers and security analysts.

---

## 🎯 Objective
- Understand the importance of access control in web applications  
- Learn what IDOR vulnerabilities are and why they occur  
- Identify how improper authorization can lead to data exposure  
- Develop awareness from a defensive and SOC monitoring perspective  

---

## 🧠 Key Concepts Covered

### 🔹 Web Application Security
Web applications handle sensitive data such as user accounts, personal information, and transactions. Weak security controls can allow attackers to:
- Access unauthorized data  
- Modify resources belonging to other users  
- Escalate privileges  

Proper authentication **and** authorization are critical for security.

---

### 🔹 Insecure Direct Object Reference (IDOR)
IDOR occurs when an application exposes internal object references (such as IDs) and fails to verify whether a user is authorized to access them.

Common examples include:
- Accessing another user’s data by changing an ID in a URL  
- Viewing restricted resources without proper permission checks  

IDOR is an **authorization flaw**, not an authentication issue.

---

### 🔹 Why IDOR Is Dangerous
- It can lead to sensitive data leakage  
- It often goes unnoticed without proper testing  
- Attackers do not require advanced tools to exploit it  
- It directly impacts confidentiality and privacy  

---

## 🛠️ Tools & Environment
- :contentReference[oaicite:0]{index=0} interactive lab environment  
- Browser-based web application scenarios  
- Guided tasks demonstrating access control weaknesses  

---

## 🔍 Defensive & SOC Perspective
From a defensive standpoint, mitigating IDOR requires:
- Proper authorization checks on every request  
- Avoiding predictable object identifiers  
- Logging and monitoring suspicious access attempts  

SOC teams may detect IDOR exploitation through:
- Unusual access patterns  
- Repeated unauthorized requests  
- Anomalies in application logs  

---

## ❓ Questions & Answers (Conceptual)

### Q1️⃣ What is web application security?
**Answer:**  
Web application security focuses on protecting applications from vulnerabilities that could allow unauthorized access, data exposure, or system compromise.

---

### Q2️⃣ What is an Insecure Direct Object Reference (IDOR)?
**Answer:**  
IDOR is a vulnerability where an application exposes internal object references and fails to verify whether a user is authorized to access the requested resource.

---

### Q3️⃣ How is IDOR different from authentication issues?
**Answer:**  
Authentication verifies who a user is, while IDOR is an authorization issue that occurs when access controls are not properly enforced after authentication.

---

### Q4️⃣ Why are IDOR vulnerabilities common?
**Answer:**  
They often arise due to missing or improperly implemented authorization checks and reliance on client-side controls.

---

### Q5️⃣ How can IDOR vulnerabilities be prevented?
**Answer:**  
By enforcing server-side authorization checks, using indirect references, validating user permissions, and monitoring access logs.

---

## 🧩 Skills Developed
- Understanding of web access control flaws  
- Awareness of authorization vulnerabilities  
- Ability to reason about web security risks  
- Defensive thinking aligned with SOC monitoring  

---

## 📝 Reflection
This challenge highlighted how **simple design oversights in web applications can lead to serious security issues**. Understanding IDOR vulnerabilities reinforced the importance of proper authorization checks and demonstrated why web security remains a critical focus area in modern cybersecurity.
