# 🎄 Advent of Cyber 2025 — Day 10  
## 💉 Cross-Site Scripting (XSS) Fundamentals

Day 10 focuses on **Cross-Site Scripting (XSS)**, a common and dangerous web vulnerability that allows attackers to execute malicious scripts in a user’s browser.

XSS attacks target users rather than servers, making them particularly effective for session hijacking, data theft, and phishing.

---

## 🎯 Objective
- Understand what Cross-Site Scripting (XSS) is  
- Learn the different types of XSS attacks  
- Identify how XSS vulnerabilities occur  
- Develop defensive awareness from a SOC and web security perspective  

---

## 🧠 Key Concepts Covered

### 🔹 What is Cross-Site Scripting (XSS)?
XSS is a vulnerability that allows attackers to inject malicious scripts into web pages viewed by other users.

These scripts execute in the victim’s browser under the context of a trusted website.

---

### 🔹 Types of XSS

#### 🟠 Reflected XSS
- Malicious input is reflected immediately in the response  
- Often delivered through URLs or user input  
- Requires user interaction (e.g., clicking a link)

#### 🔵 Stored XSS
- Malicious script is permanently stored on the server  
- Affects every user who views the infected content  
- Considered the most dangerous type

#### 🟢 DOM-Based XSS
- Occurs entirely on the client side  
- Exploits unsafe JavaScript handling of user input  
- Harder to detect using traditional server-side defenses  

---

### 🔹 Impact of XSS Attacks
XSS attacks can lead to:
- Session hijacking  
- Credential theft  
- Unauthorized actions on behalf of users  
- Defacement or phishing attacks  

Because XSS executes in the user’s browser, it bypasses many server-side protections.

---

## 🛠️ Tools & Environment
- :contentReference[oaicite:0]{index=0} interactive lab environment  
- Browser-based vulnerable web application scenarios  
- Guided tasks demonstrating client-side exploitation risks  

---

## 🔍 Defensive & SOC Perspective
From a defensive standpoint, preventing and detecting XSS involves:
- Input validation and output encoding  
- Using Content Security Policy (CSP)  
- Avoiding unsafe JavaScript functions  
- Monitoring web logs and user behavior  

SOC teams may detect XSS attempts through:
- Unusual request parameters  
- Suspicious payload patterns  
- Repeated injection attempts in logs  

---

## ❓ Questions & Answers (Conceptual)

### Q1️⃣ What is Cross-Site Scripting (XSS)?
**Answer:**  
XSS is a web vulnerability that allows attackers to inject malicious scripts into web pages, which are then executed in a victim’s browser.

---

### Q2️⃣ How does XSS differ from other web vulnerabilities?
**Answer:**  
XSS targets users by executing code in their browsers, whereas many other vulnerabilities target servers or backend systems.

---

### Q3️⃣ Which type of XSS is the most dangerous and why?
**Answer:**  
Stored XSS is the most dangerous because the malicious script is permanently stored and executed for every user who accesses the affected page.

---

### Q4️⃣ How can developers prevent XSS vulnerabilities?
**Answer:**  
By validating input, encoding output, avoiding unsafe JavaScript practices, and enforcing Content Security Policy (CSP).

---

### Q5️⃣ How is XSS relevant to SOC operations?
**Answer:**  
SOC teams monitor web traffic and logs for injection attempts, investigate compromised user sessions, and respond to incidents caused by XSS exploitation.

---

## 🧩 Skills Developed
- Understanding of client-side web attacks  
- Awareness of different XSS attack types  
- Defensive thinking for web application security  
- SOC-aligned detection and response awareness  

---

## 📝 Reflection
This challenge highlighted how **client-side vulnerabilities can have serious security consequences**. Understanding XSS reinforced the importance of secure input handling, browser-side defenses, and continuous monitoring to protect users and web applications from exploitation.
