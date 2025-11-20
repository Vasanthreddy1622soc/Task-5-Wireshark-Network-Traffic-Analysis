# Wireshark Network Traffic Analysis

## 📌 Project Overview
This project demonstrates live network traffic capture and protocol analysis using **Wireshark**. The objective is to identify and analyze commonly used protocols such as **DNS, TCP, and ICMP**, understand packet structure, and gain practical packet inspection skills.

---

## 🎯 Task Objective
- Capture live network packets
- Analyze and filter traffic by different protocols
- Identify packet-level details like IP addresses, ports, queries, flags, etc.
- Export the capture as a `.pcapng` file
- Provide a report summarizing findings

---

## 🛠 Tools Used
| Tool | Purpose |
|------|---------|
| Wireshark | Packet capturing and protocol analysis |
| Windows 10/11 | Active Wi-Fi network capture |
| Npcap | Network packet sniffing support |

---

## 🔍 Protocols Identified
| Protocol | Description | Evidence Observed |
|----------|-------------|------------------|
| **DNS** | Resolves domain names (e.g., google.com) to IP addresses | Queries to public DNS servers |
| **TCP** | Reliable transport protocol for applications (HTTPS/web apps) | ACK flags, seq/ack numbers |
| **ICMP / UDP QUIC** | Connectivity tests and fast encrypted communication | Echo requests/data payload |

---

## 📂 Files Included in This Repo
| File Name | Purpose |
|----------|---------|
| `task5_wireshark_capture.pcapng` | Exported packet capture file |
| `Wireshark_Report.pdf` *(or .md)* | Detailed analysis of captured protocols |
| Screenshots | Visual evidence of packet inspection |

---

## 📷 Screenshots Included
- DNS packet details
- TCP traffic over port 443 (HTTPS)
- UDP/ICMP payload inspection

---

## 🚀 Skills Demonstrated
✔ Network traffic analysis  
✔ Understanding of protocol behavior  
✔ Practical SOC skill development  
✔ Packet-level investigation techniques  

---

## 🏁 Conclusion
This task successfully showcases:
- Identification of multiple internet protocols  
- Ability to inspect packet headers and payload  
- Understanding of how browsing generates network traffic  

---

## 📧 Author
**Vasanth Reddy**  
Cybersecurity Learner | Blue Team Enthusiast

---



