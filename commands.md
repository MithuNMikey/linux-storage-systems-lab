# Commands Reference

## System Monitoring
```bash
top               # Live CPU/memory usage
df -h             # Disk space usage
free -h           # RAM usage
lsblk             # List block devices
```

## Network Diagnostics
```bash
ping google.com       # Test connectivity
ip a                  # Show network interfaces
netstat -tuln         # Active ports/connections
```

## RAID with mdadm
```bash
# Create RAID 1
sudo mdadm --create /dev/md0 --level=1 --raid-devices=2 /dev/sdb /dev/sdc

# Check RAID status
cat /proc/mdstat

# Monitor RAID
sudo mdadm --detail /dev/md0
```

## Log Analysis
```bash
dmesg | tail -20          # Recent kernel messages
journalctl -xe            # Detailed system logs
cat /proc/mdstat          # RAID status
```
