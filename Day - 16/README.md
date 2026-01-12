# 🎄 Advent of Cyber 2025 — Day 16  
## 🗂️ Host & Registry Forensics Fundamentals

Day 16 focuses on **host-based forensics**, with particular emphasis on the **Windows Registry** and system-level artifacts that attackers often modify to gain persistence or hide malicious activity.

Understanding host artifacts is essential for identifying compromise and reconstructing attacker behavior.

---

## 🎯 Objective
- Understand what host-based forensics involves  
- Learn the role of the Windows Registry in system operation  
- Identify common forensic artifacts left by attackers  
- Develop investigation skills for endpoint compromise  

---

## 🧠 Key Concepts Covered

### 🔹 Host-Based Forensics
Host-based forensics involves analyzing data stored on an endpoint system to:
- Detect signs of compromise  
- Identify persistence mechanisms  
- Understand attacker actions after initial access  

Endpoints often contain the most detailed evidence of an attack.

---

### 🔹 Windows Registry Basics
The Windows Registry is a hierarchical database that stores:
- System configuration  
- User preferences  
- Application settings  

Because of its importance, attackers frequently modify the registry to maintain persistence or execute malware automatically.

---

### 🔹 Common Registry-Based Artifacts
Attackers may use the registry to:
- Create **autorun entries**  
- Modify startup behavior  
- Hide malicious configuration data  

These changes can indicate persistence or post-exploitation activity.

---

### 🔹 Persistence Mechanisms
Persistence allows attackers to maintain access after system reboots. Common methods include:
- Registry autorun keys  
- Scheduled tasks  
- Startup folders  

Identifying persistence is a key forensic objective.

---

## 🛠️ Tools & Environment
- :contentReference[oaicite:0]{index=0} interactive lab environment  
- Simulated compromised host scenarios  
- Guided forensic analysis tasks  

---

## 🔍 SOC & DFIR Perspective
From a SOC and DFIR perspective, host forensics helps:
- Confirm endpoint compromise  
- Identify attacker persistence techniques  
- Support containment and eradication  
- Preserve evidence for further analysis  

Host artifacts often reveal attacker intent and dwell time.

---

## ❓ Questions & Answers (Conceptual)

### Q1️⃣ What is host-based forensics?
**Answer:**  
Host-based forensics is the analysis of data stored on an endpoint system to investigate security incidents and identify malicious activity.

---

### Q2️⃣ Why is the Windows Registry important in forensic investigations?
**Answer:**  
Because it stores critical configuration data and is commonly modified by attackers to establish persistence or execute malicious code.

---

### Q3️⃣ What are common signs of registry-based persistence?
**Answer:**  
Unexpected autorun entries, modified startup keys, or registry values linked to unknown executables.

---

### Q4️⃣ How does host forensics support incident response?
**Answer:**  
It helps confirm compromise, identify attacker actions, locate persistence mechanisms, and guide system cleanup.

---

### Q5️⃣ Why is endpoint evidence valuable compared to network data?
**Answer:**  
Endpoints often contain detailed records of attacker activity, including executed commands, modified files, and persistence mechanisms.

---

## 🧩 Skills Developed
- Host-based forensic reasoning  
- Registry analysis awareness  
- Persistence detection concepts  
- SOC & DFIR-aligned investigation skills  

---

## 📝 Reflection
This challenge demonstrated that **endpoint systems provide deep insight into attacker behavior**. Understanding host and registry artifacts is critical for detecting persistence, reconstructing attacks, and ensuring complete remediation after a security incident.
