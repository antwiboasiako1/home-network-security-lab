
# 🛡️ Home Network Security Lab – Step-by-Step Project Guide

A hands-on security simulation using pfSense, Snort, Kali Linux, and Wireshark in a virtual lab environment. This project demonstrates intrusion detection and packet analysis for cybersecurity portfolios.

---

## 📶 Step 1: Verify Kali VM Network Configuration

**Command:**  
```bash
ip a
```

**Screenshot:**  
![Kali IP](screenshots/screenshot 1.png)

---

## 🔍 Step 2: Run Nmap Scan from Kali  
```bash
nmap -sS 192.168.56.1
```

![Nmap Port Scan](screenshots/screenshot 2.png)

---

## 🧪 Step 3: Start Wireshark Packet Capture  
![Wireshark Start](screenshots/Screenshot 3.png)

---

## 💥 Step 4: Aggressive Nmap Scan with Wireshark  
```bash
nmap -A 192.168.56.1
```

![Aggressive Scan](screenshots/Screenshot 4.png)

---

## 🧱 Step 5: Install Snort on pfSense  
![Snort Install](screenshots/Screenshot 5.png)

---

## 🧰 Step 6: Configure Snort Interface  
![Snort Config](screenshots/Screenshot 6.png)

---

## 📊 Step 7: Review Snort Interfaces  
![Snort Interfaces](screenshots/Screenshot 7.png)

---

## 🧪 Step 8: Final Packet Capture  
![Packet Capture](screenshots/Screenshot 8.png)

---

## 🚨 Step 9: Snort Alert Logs  
![Snort Alerts](screenshots/Screenshot 9.png)

---

## 🔄 Step 10: Snort Ruleset Update  
![Ruleset Update](screenshots/Screenshot 10.png)

---

## ✅ Step 11: Summary Dashboard  
![Summary](screenshots/Screenshot 11.png)

---

## ✅ Conclusion

This lab showcases:
- 🔍 Network scanning
- 🧱 Firewall configuration
- 🧪 Packet inspection
- 🚨 IDS alerting

📩 Connect: [LinkedIn – David Antwi](https://www.linkedin.com/in/david-antwi-408907149)  
📁 Repo: [GitHub](https://github.com/yourusername/Home-Network-Security-System)
