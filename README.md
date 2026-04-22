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

### 1️⃣ Block Devices — `lsblk`
> Lists all storage devices recognized by the system.

<img width="765" height="248" alt="lsblk png" src="https://github.com/user-attachments/assets/6ff1ef12-e9df-4202-948d-4467f5f7bc77" />

---

### 2️⃣ Disk Space Usage — `df -h`
> Shows filesystem sizes and mount points.

<img width="1103" height="422" alt="df-h png" src="https://github.com/user-attachments/assets/11b2d86d-1784-44ef-87f5-48021fd355fc" />

---

### 3️⃣ Memory Usage — `free -h`
> Displays RAM and swap usage.

<img width="1047" height="141" alt="free -h png" src="https://github.com/user-attachments/assets/86eae5d3-40e9-4063-ad66-868cdd02312c" />

---

### 4️⃣ Network Interfaces — `ip a`
> Shows active network interfaces and IP addresses.

<img width="1221" height="387" alt="ip-a png" src="https://github.com/user-attachments/assets/9e974858-5f59-4913-87a2-d5a608eac3b6" />

---

### 5️⃣ RAID Module — `mdadm --version`
> Confirms mdadm is installed and ready for RAID configuration on the system.

<img width="755" height="100" alt="mdstat png" src="https://github.com/user-attachments/assets/e9ceb93b-e323-4e2a-a2bd-1a64b7795fb3" />

---

## 📁 Files in This Repo
| File | Description |
|------|-------------|
| `commands.md` | All commands used with explanations |
| `raid-notes.md` | RAID concepts and recovery steps |

