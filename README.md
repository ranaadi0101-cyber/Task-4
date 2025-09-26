# Task 4 - Linux Firewall Configuration using UFW

## 🔧 Tool Used
- UFW (Uncomplicated Firewall) on Kali Linux

## 🎯 Objective
Configure and test firewall rules on Linux using UFW to block and allow specific traffic.

## ✅ Steps Performed

1. Installed and enabled UFW firewall.
2. Listed current firewall rules (ufw status numbered).
3. Blocked inbound traffic on port 23 (Telnet) to secure the system.
4. Allowed inbound traffic on port 22 (SSH) to maintain remote access.
5. Verified rules were correctly applied.

## 🧪 Commands Used

```bash
sudo apt update
sudo apt install ufw -y
sudo ufw enable
sudo ufw status numbered
sudo ufw deny 23
sudo ufw allow 22
sudo ufw status numbered
