# 🎄 Advent of Cyber 2025 — Day 07  
## 🌐 Network Discovery & Scanning Fundamentals

Day 07 focuses on **network discovery and scanning**, which are commonly used by attackers to map systems and by defenders to understand network visibility and detect suspicious activity.

Understanding how networks are scanned is essential for identifying reconnaissance behavior during the early stages of an attack.

---

## 🎯 Objective
- Understand the purpose of network discovery  
- Learn how scanning is used to identify systems and services  
- Recognize reconnaissance activity from a defensive perspective  
- Develop awareness of early-stage attack indicators  

---

## 🧠 Key Concepts Covered

### 🔹 Network Discovery
Network discovery is the process of identifying:
- Active hosts on a network  
- Open ports and running services  
- Network structure and exposed assets  

Attackers use discovery to plan attacks, while defenders use it for asset management and monitoring.

---

### 🔹 Port Scanning
Port scanning is a technique used to identify open, closed, or filtered ports on a system.

Open ports may reveal:
- Services running on a host  
- Potential attack surfaces  
- Misconfigured or exposed services  

---

### 🔹 Reconnaissance in the Attack Lifecycle
Reconnaissance is typically the **first stage of an attack**. Early detection of scanning activity can prevent further exploitation.

Signs of reconnaissance may include:
- Repeated connection attempts  
- Access to multiple ports in short timeframes  
- Unusual network traffic patterns  

---

## 🛠️ Tools & Environment
- :contentReference[oaicite:0]{index=0} interactive lab environment  
- Simulated network scanning scenarios  
- Guided tasks demonstrating reconnaissance techniques  

---

## 🔍 Defensive & SOC Perspective
From a SOC perspective, detecting network scanning involves:
- Monitoring firewall and IDS/IPS logs  
- Identifying unusual traffic patterns  
- Correlating network events across systems  
- Responding to potential reconnaissance activity  

Early detection allows defenders to harden systems before exploitation occurs.

---

## ❓ Questions & Answers (Conceptual)

### Q1️⃣ What is network discovery?
**Answer:**  
Network discovery is the process of identifying active hosts, services, and network structure to understand available assets and potential attack surfaces.

---

### Q2️⃣ Why do attackers perform port scanning?
**Answer:**  
Attackers scan ports to identify running services, discover vulnerabilities, and plan further attacks.

---

### Q3️⃣ How does network scanning relate to the attack lifecycle?
**Answer:**  
Network scanning is part of the reconnaissance phase, which occurs before exploitation and helps attackers gather information about targets.

---

### Q4️⃣ How can SOC teams detect network scanning?
**Answer:**  
By monitoring network logs, firewall alerts, IDS/IPS events, and identifying abnormal traffic patterns or repeated connection attempts.

---

### Q5️⃣ Why is early detection of reconnaissance important?
**Answer:**  
Detecting reconnaissance early allows defenders to respond proactively, reduce attack surfaces, and prevent potential exploitation.

---

## 🧩 Skills Developed
- Understanding network reconnaissance techniques  
- Awareness of scanning indicators  
- Defensive thinking aligned with SOC monitoring  
- Foundational network security knowledge  

---

## 📝 Reflection
This challenge emphasized that **many attacks begin with reconnaissance**. Recognizing network discovery and scanning activity is critical for early threat detection and helps SOC teams disrupt attacks before they progress to exploitation stages.
