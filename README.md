# 🌐 Network Monitoring Lab

A Docker-based Network Operations Center (NOC) lab using **Prometheus** and **Grafana** to monitor simulated hosts.  
The lab visualizes metrics such as CPU load, disk space, and network latency, with alerting rules for performance thresholds.

---

### 🧰 Features
- Prometheus for metrics collection  
- Grafana dashboards for visualization  
- Simulated network nodes via Docker containers  
- Custom alert rules (CPU > 80%, disk usage > 90%, etc.)

---

### 💡 Skills Demonstrated
- Docker containerization and networking  
- System and network monitoring setup  
- Dashboard design and alert configuration  
- Understanding of NOC workflows and KPIs

---

### 📊 Example Dashboards
- **System Health Overview** – Displays CPU, memory, and disk usage across nodes  
- **Network Latency Tracker** – Monitors ping times and packet loss  
- **Alert Center** – Lists triggered alerts by severity level

---

### 🧾 Project Summary
This project demonstrates the ability to build and maintain a network monitoring stack from scratch using modern open-source tools.  
It highlights operational awareness and proactive incident detection skills relevant to NOC and IT Operations roles.

---

## 🧱 Virtualization Environment

This lab is fully virtualized to simulate a real-world IT environment.

**Platform:** VirtualBox (or VMware Workstation / Hyper-V)  
**Topology:**
- 🖥️ Windows Server (Domain Controller / File Server)
- 💻 Windows 10 Client(s)
- 🧰 Security Tools VM (Kali Linux, Wazuh, Security Onion, etc.)
- 🌐 pfSense (firewall + router)

**Networking:**  
- Internal NAT network for internet access  
- Host-only network for isolated lab traffic  
- Static IP addressing for critical systems  

This setup demonstrates understanding of:
- Virtual networking & isolation
- Resource allocation (CPU, memory, storage)
- Snapshot management
- System provisioning and configuration in a virtual environment

---
