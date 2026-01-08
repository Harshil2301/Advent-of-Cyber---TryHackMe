# 🎄 Advent of Cyber 2025 — Day 11  
## 🧪 Malware Indicators & Detection Fundamentals

Day 11 focuses on **malware indicators and detection techniques**, introducing how security teams identify compromised systems using observable evidence known as **Indicators of Compromise (IOCs)**.

This challenge emphasizes a defensive, SOC-oriented approach to detecting malicious activity rather than reverse engineering malware.

---

## 🎯 Objective
- Understand what Indicators of Compromise (IOCs) are  
- Learn common types of malware indicators  
- Identify how SOC teams use indicators for detection  
- Develop awareness of early-stage malware detection  

---

## 🧠 Key Concepts Covered

### 🔹 Indicators of Compromise (IOCs)
IOCs are observable artifacts that suggest a system may be compromised.

They provide evidence of:
- Malicious activity  
- Policy violations  
- System misuse  

IOCs are critical for **detection, investigation, and response**.

---

### 🔹 Common Types of Malware Indicators

#### 🟠 File-Based Indicators
- Suspicious file names  
- Unusual file locations  
- Unexpected file hashes  

#### 🔵 Network-Based Indicators
- Connections to malicious IP addresses or domains  
- Unusual outbound traffic patterns  
- Unexpected communication with external servers  

#### 🟢 Host-Based Indicators
- Abnormal processes or services  
- Unexpected registry changes  
- Persistence mechanisms  

---

### 🔹 Detection vs Prevention
- **Prevention** aims to block threats before execution  
- **Detection** focuses on identifying threats that bypass preventive controls  

SOC teams rely heavily on detection to uncover hidden or advanced threats.

---

## 🛠️ Tools & Environment
- :contentReference[oaicite:0]{index=0} interactive lab environment  
- Simulated malware indicators  
- Guided exercises focused on identifying suspicious activity  

---

## 🔍 SOC Analyst Perspective
From a SOC perspective, malware detection involves:
- Collecting indicators from alerts and logs  
- Correlating IOCs across multiple systems  
- Validating indicators to reduce false positives  
- Escalating confirmed detections for response  

Detection accuracy improves with context and correlation.

---

## ❓ Questions & Answers (Conceptual)

### Q1️⃣ What is an Indicator of Compromise (IOC)?
**Answer:**  
An IOC is an observable piece of evidence that suggests a system may be compromised or involved in malicious activity.

---

### Q2️⃣ What are examples of file-based IOCs?
**Answer:**  
Unusual file names, unexpected file locations, suspicious file hashes, or files created by unknown processes.

---

### Q3️⃣ Why are network-based IOCs important?
**Answer:**  
They can reveal communication between infected systems and malicious external servers, which is common in malware infections.

---

### Q4️⃣ How do SOC teams use IOCs effectively?
**Answer:**  
By correlating multiple indicators across logs, endpoints, and network data to confirm malicious activity before escalation.

---

### Q5️⃣ Why is detection critical even with preventive controls?
**Answer:**  
Because advanced threats can bypass preventive defenses, making detection essential for identifying and responding to compromises.

---

## 🧩 Skills Developed
- Understanding of malware detection concepts  
- IOC identification and analysis  
- Defensive security reasoning  
- SOC-aligned investigation awareness  

---

## 📝 Reflection
This challenge highlighted that **malware detection relies on recognizing patterns and indicators rather than single events**. Understanding IOCs strengthens a SOC analyst’s ability to detect threats early, validate alerts, and support effective incident response.
