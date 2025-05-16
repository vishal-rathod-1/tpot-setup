## 🧰 T-Pot Honeypot - Tool Explanations

T-Pot is a powerful all-in-one honeypot framework developed by Deutsche Telekom that integrates several honeypots, IDS, and log analysis tools.

### 🔍 Included Tools:

| Tool         | Description |
|--------------|-------------|
| **Dionaea**  | A malware capture honeypot designed to collect samples via protocols like SMB, HTTP, FTP, TFTP, MSSQL. |
| **Cowrie**   | A medium interaction SSH and Telnet honeypot that logs brute-force attempts and records attacker sessions. |
| **Conpot**   | A honeypot simulating ICS/SCADA systems, making it attractive to attackers targeting industrial control systems. |
| **Honeytrap**| A flexible low-interaction honeypot framework that listens on unused ports to detect and log traffic. |
| **Suricata** | An open-source IDS/IPS engine for real-time network traffic inspection, alerting, and logging. |
| **Elastic Stack (ELK)** | A log processing and visualization stack: Elasticsearch (storage), Logstash (parsing), and Kibana (dashboard). |
| **Portainer**| A lightweight Docker management GUI used to control honeypot containers. |
| **Cockpit**  | A web-based server manager UI for system-level access and stats monitoring. |

### 🛡️ Why Use T-Pot?

- Centralized honeypot management
- Rich visualizations and logs
- Supports real-world threat emulation
- Easily deployable with Docker containers
