# CODTECH Task 3: Intrusion Detection System (Snort Simulation)

## 👤 Intern Information
* **Name:** Avni Goyal
* **Intern ID:** CITS9080
* **Domain:** Cyber Security & Ethical Hacking / Python Development
* **Duration:** September 8, 2026 - October 8, 2026
* **Mentor:** CodTech IT Solutions Evaluation Team

---

## 📌 Project Overview
This project is an automated network security monitoring simulation designed to function like a basic **Intrusion Detection System (IDS)** using a Snort-like signature matching engine. 

The script processes simulated packet data traffic in real time and inspects source IPs against a rule-set to trigger immediate flags and alerts for malicious behaviors like port scanning, DDoS spikes, or unauthorized login attempts.

---

## ⚙️ Features
* **Real-time Packet Simulation:** Continuously generates live network logs to demonstrate how traffic streams work.
* **Signature-Based Detection:** Cross-references incoming metadata against known hacker threat vectors.
* **Distinct Visual Flags:** Marks harmless traffic as `PASS` and malicious traffic with clear `[ALERT]` flags for easy triage.
* **Graceful Exit:** Built-in loop handlers safely shutdown the engine upon terminal interrupt commands.

---

## 🛠️ Technology Stack
* **Language:** Python 3.x
* **Core Modules:** `time` (loop delay), `random` (packet distribution), `datetime` (log timestamps)

---

## 🚀 How to Run the Project

1. **Navigate to the file directory:**
   ```bash
   cd Desktop
   ```

2. **Execute the simulator file:**
   ```bash
   python ids_simulator.py
   ```

3. **Stop Monitoring:**
   Press `Ctrl + C` at any point to stop the security monitor administration stream safely.
