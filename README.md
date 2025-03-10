# 🛡 Intrusion Detection System (IDS) with Real-Time Dashboard 🚀

## 📌 Overview  
This **Intrusion Detection System (IDS)** is a Python-based security tool that **monitors network traffic** and detects multiple cyberattacks in real time.  
It features a **Flask-based web dashboard** (using **Chart.js**) for **visualizing detected attacks**.  

## ⚡ Features  
✅ **Monitors Network Traffic** using `scapy`  
✅ **Detects Multiple Attacks**:  
   - 🚨 **DoS Attacks**  
   - 🎭 **ARP Spoofing**  
   - 🔍 **Port Scanning**  
   - 🎭 **DNS Spoofing**  
✅ **Logs Detected Attacks** in a file for further analysis  
✅ **Provides a Real-Time Dashboard** using **Flask & Chart.js**  

---

## 📂 Project Structure

SLA/ │── IDS.py                # Main Intrusion Detection Script │── log_file/ │   └── log.txt           # Logs detected attacks │── dashboard/ │   │── app.py            # Flask Backend │   │── templates/ │   │   └── index.html    # Dashboard UI │   │── static/ │   │   ├── script.js     # JavaScript for Charts │   │   ├── style.css     # Styling for Dashboard