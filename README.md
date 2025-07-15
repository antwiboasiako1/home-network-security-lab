
# 🛡️ Home Network Security Lab – Step-by-Step Project Guide

A hands-on security simulation using pfSense, Snort, Kali Linux, and Wireshark in a virtual lab environment. This project demonstrates intrusion detection and packet analysis for cybersecurity portfolios.

---

## 📶 Step 1: Verify Kali VM Network Configuration

**Description:**  
Check Kali’s IP address to confirm it’s within the same subnet as the pfSense firewall and target VMs.

**Command:**  
```bash
ip a
```

**Screenshot:**  
![Kali IP Address](screenshots/screenshot%201.png)

---

## 🔍 Step 2: Run Nmap Scan from Kali

**Description:**  
Use Nmap to detect open ports on the target (e.g., pfSense). This simulates reconnaissance by an attacker.

**Command:**  
```bash
nmap -sS 192.168.56.1
```

**Screenshot:**  
![Nmap Port Scan](screenshots/screenshot%202.png)

---

## 🧪 Step 3: Start Wireshark Packet Capture

**Description:**  
Begin capturing traffic on `eth0` before simulating attacks to analyze packets.

**Screenshot:**  
![Wireshark Start Capture](screenshots/Screenshot%203.png)

---

## 💥 Step 4: Capture Suspicious Activity with Nmap Aggressive Scan

**Command:**  
```bash
nmap -A 192.168.56.1
```

**Description:**  
Aggressive Nmap scan sends multiple probe types that may be flagged by Snort IDS.

**Screenshot:**  
![Nmap Aggressive Scan + Wireshark](screenshots/Screenshot%204.png)

---

## 🧱 Step 5: Install Snort Package in pfSense

**Description:**  
Access pfSense’s package manager to install Snort for real-time intrusion detection.

**Screenshot:**  
![Snort Installed](screenshots/Screenshot%205.png)

---

## 🧰 Step 6: Configure Snort Interface on pfSense

**Description:**  
Enable Snort on the LAN interface, configure packet logging and unified2 alerts.

**Screenshot:**  
![Snort Interface Config](screenshots/Screenshot%206.png)

---

## 🧾 Step 7: Review Active Snort Interfaces

**Description:**  
Verify Snort is active on the correct interface and monitoring the right traffic.

**Screenshot:**  
![Snort Interfaces Overview](screenshots/Screenshot%207.png)

---

## 📊 Step 8: Monitor Snort Alert Logs

**Description:**  
Inspect Snort logs for real-time detection of the Nmap scan and other potential attacks.

**Screenshot:**  
![Snort Alerts](screenshots/Screenshot%209.png)

---

## 🔄 Step 9: Update Snort Rulesets

**Description:**  
Go to the "Updates" tab in Snort and install the latest community rules to enhance detection.

**Screenshot:**  
![Snort Rules Update](screenshots/Screenshot%2010.png)

---

## 🎯 Final Result: Packets Captured and IDS Detection Confirmed

**Description:**  
Return to Wireshark and validate that Nmap scan packets are captured, and alerts were triggered in Snort.

**Screenshot:**  
![Packet Captures Final](screenshots/Screenshot%208.png)

---

## ✅ Conclusion

This home lab simulates real-world threat detection and response, showcasing your skills in:
- Network scanning
- Packet inspection
- IDS deployment
- Firewall configuration

🔗 Project Repo: [GitHub.com/yourusername/Home-Network-Security-System](https://github.com/yourusername/Home-Network-Security-System)

📩 Connect with me on [LinkedIn](https://www.linkedin.com/in/david-antwi-408907149)
