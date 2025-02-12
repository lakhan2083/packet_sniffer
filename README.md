# 🕵️‍♂️ Packet_Sniffer – Live Packet Capture & Analysis

## 📌 About the Project
This **Python-based Network Sniffer** captures live network packets, extracts essential details, and displays them in a **structured tabular format** for easy analysis. Built using **Scapy** and **Tabulate**, this tool helps in monitoring and analyzing network traffic by capturing packets and extracting information such as **MAC & IP addresses, TTL, and Protocols (TCP, UDP, HTTP).**

Developed as part of the **Code Alpha Cybersecurity Internship Program**, this project enhances network security visibility and real-time monitoring capabilities. 🚀

## 🚀 Features
✅ **Live packet capture** for real-time monitoring  
✅ **Filters & analyzes TCP, UDP, and HTTP traffic**  
✅ **Extracts key network details** (MAC, IP, TTL, Protocol)  
✅ **Neat tabular output for structured data representation**  

## 🔧 Tech Stack
- **Python 3**  
- **Scapy** (For packet sniffing)  
- **Tabulate** (For structured tabular output)  

## 🛠️ Installation & Setup
### **1. Install Dependencies**
Make sure you have Python installed, then install the required libraries:
```bash
pip install scapy tabulate
```

### **2. Run the Sniffer**
To start capturing network packets, run the script with administrator/root privileges:
```bash
sudo python network_sniffer.py
```

⚠️ **Note:** Running this script requires administrative privileges (root access) since it involves network packet sniffing.

## 📊 Sample Output
```
╒═════════════════════╤═════════════════════╤════════════════════╤════════════════════╕
│ Field               │ Value               │ Field              │ Value               │
╞═════════════════════╪═════════════════════╪════════════════════╪════════════════════╡
│ Destination MAC     │ 00:1A:2B:3C:4D:5E   │ Source MAC         │ 00:1A:2B:3C:4D:5F   │
├─────────────────────┼─────────────────────┼────────────────────┼────────────────────┤
│ Ethernet Protocol   │ 0x800               │ IP Version         │ 4                   │
├─────────────────────┼─────────────────────┼────────────────────┼────────────────────┤
│ TTL                │ 64                   │ Protocol           │ TCP                 │
├─────────────────────┼─────────────────────┼────────────────────┼────────────────────┤
│ Source IP          │ 192.168.1.100        │ Destination IP     │ 192.168.1.101       │
╘═════════════════════╧═════════════════════╧════════════════════╧════════════════════╛
```

## 🎯 Use Cases
🔹 **Cybersecurity & Ethical Hacking** – Monitor suspicious network activity  
🔹 **Network Troubleshooting** – Identify connectivity issues  
🔹 **Educational Purposes** – Learn how network packets work  

## 🤝 Contributing
Feel free to **fork** this repository, **submit issues**, or **make pull requests** to improve the project!

## 📜 License
This project is **open-source** and available under the **MIT License**.

## 🙌 Acknowledgments
Special thanks to **Code Alpha** for providing the opportunity to work on this project! 🎉

---
**🔗 Connect & Discuss**
Let’s collaborate on more cybersecurity projects! 🚀 Drop your thoughts in the comments or connect with me on **LinkedIn**!

#CyberSecurity #Python #Networking #PacketSniffing #Scapy #CodeAlpha #Internship #NetworkMonitoring
