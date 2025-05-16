## 🚀 T-Pot Honeypot - Setup Walkthrough

Follow these steps to install and deploy T-Pot on a fresh Ubuntu 20.04 server.

---

### ✅ Prerequisites

- OS: Ubuntu Server 20.04 LTS (64-bit)
- RAM: 8 GB minimum
- Disk: 128 GB+ SSD recommended
- Network: Static IP, bridged mode preferred
- Root or sudo privileges

---

### 🧱 Step-by-Step Installation

```bash
# Step 1: Update the system
sudo apt update && sudo apt upgrade -y

# Step 2: Install essential tools
sudo apt install git curl -y

# Step 3: Clone the T-Pot GitHub repository
git clone https://github.com/telekom-security/tpotce
cd tpotce

# Step 4: Run the installer
sudo ./install.sh --type=auto
```

---

### ⚙️ Post-Install

- Reboot the server when prompted.
- Access via web UI at `https://<your-ip>:64297`
- Log in using the credentials you set during installation.

---

### 🌐 Web Interfaces

| Service     | URL Example                          | Description                       |
|-------------|--------------------------------------|-----------------------------------|
| Cockpit     | https://<IP>:64297                   | System stats and access control   |
| Kibana      | https://<IP>:64297/kibana            | Dashboards and logs visualization|
| Portainer   | https://<IP>:64297/portainer         | Container management UI           |

---

### ✅ Tips

- Run on a dedicated VM or physical server.
- Monitor Kibana regularly for threat data.
- Secure the management ports via firewall or VPN.
