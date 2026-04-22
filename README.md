# 🖥️ Linux & Storage Systems Lab

**Tools:** Linux (Ubuntu/WSL), mdadm, Bash CLI  
**Focus:** System administration, RAID configuration, disk management

---

## 📌 Overview
Hands-on lab project simulating real-world Linux system administration tasks including
storage management, RAID configuration, and system monitoring all using WSL (Ubuntu).

---

## ✅ What I Did

### 🔧 Environment Setup
- Installed and configured Ubuntu on WSL (Windows Subsystem for Linux)
- Navigated the Linux filesystem and practised CLI-based workflows

### 📊 System Monitoring
- Monitored CPU and memory usage using `top`
- Checked disk space with `df -h` and memory with `free -h`
- Listed block devices and partitions using `lsblk`

### 🌐 Network Diagnostics
- Ran connectivity tests using `ping`
- Inspected network interfaces with `ip a`
- Viewed active connections using `netstat`

### 💾 RAID Configuration (mdadm)
- Configured **RAID 0** (striping) for performance
- Configured **RAID 1** (mirroring) for redundancy
- Simulated disk failure and studied recovery procedures

### 📋 Log Analysis
- Analysed kernel messages using `dmesg`
- Queried system logs with `journalctl`
- Monitored RAID status via `/proc/mdstat`

---

## 🧠 Key Concepts Learned
- Difference between RAID levels (0, 1, 5, 10) and their trade-offs
- How Linux handles block devices and storage abstraction
- Importance of log monitoring in diagnosing system/disk failures

---

## 📷 Screenshots
<img width="765" height="248" alt="lsblk png" src="https://github.com/user-attachments/assets/6ff1ef12-e9df-4202-948d-4467f5f7bc77" />
<img width="1103" height="422" alt="df-h png" src="https://github.com/user-attachments/assets/11b2d86d-1784-44ef-87f5-48021fd355fc" />
<img width="1047" height="141" alt="free -h png" src="https://github.com/user-attachments/assets/86eae5d3-40e9-4063-ad66-868cdd02312c" />


---

## 📁 Files in This Repo
| File | Description |
|------|-------------|
| `commands.md` | All commands used with explanations |
| `raid-notes.md` | RAID concepts and recovery steps |

