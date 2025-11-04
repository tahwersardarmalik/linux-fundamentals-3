# Linux Fundamentals 3 — Notes 🐧

## 🔐 File Permissions
- `r` = read
- `w` = write
- `x` = execute
- Use `ls -l` to view file permissions
- Change permissions → `chmod`
  - Example: `chmod 755 file`

## 👥 Users & Groups
- Check current user → `whoami`
- Show all users → `cat /etc/passwd`
- Show groups → `groups`

## ⚙️ Processes & Jobs
- List processes → `ps`
- Live process viewer → `top`
- Background jobs → `jobs`
- Bring job to foreground → `fg`
- Kill a process → `kill PID`

## 📡 SSH Basics
- Remote login → `ssh user@ip`
- Secure remote access to systems

## 📁 Logs & Troubleshooting
- Logs stored in `/var/log/`
- Check system logs:
  - `sudo tail -f /var/log/syslog`
  - `journalctl`

## 🧠 Key Learning
Linux is all about:
✔ Understanding permissions  
✔ Managing users & processes  
✔ Viewing logs  
✔ Secure remote access  
