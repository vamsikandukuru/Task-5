# Task 5 – Capture and Analyze Network Traffic Using Wireshark

##  Objective
Capture live network packets using **Wireshark** and analyze traffic for **HTTP**, **Telnet**, and **FTP** protocols.

---

## Tools
- **Wireshark** (Free & Open Source)  
  [Download Wireshark](https://www.wireshark.org/)

---

##  Steps Performed

### 1. Start Wireshark
- Open Wireshark as Administrator.
- Select the active **network interface** (Wi-Fi or Ethernet).
- Click the **blue shark fin** to start capturing packets.

---

### 2. Generate Traffic & Apply Filters

#### **HTTP**
- Action: Accessed a website in a browser to generate HTTP traffic.
- Wireshark Filter:
  ```wireshark
  http
  http.request.method=="POST"
  telnet
  telnet <iP>
  ftp
  ftp <ip>
  
