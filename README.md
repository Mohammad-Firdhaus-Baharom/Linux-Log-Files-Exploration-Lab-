# Linux Log Files Exploration Lab  

## Objective  
This lab explores Linux log files located in `/var/log/` to improve system troubleshooting, security monitoring, and performance analysis.  

## Skills Learned  
- Navigating the Linux file system to locate log files.  
- Understanding the purpose of various system logs.  
- Using terminal commands to list and analyze log files.  
- Interpreting authentication, kernel, system, and package installation logs.  

## Tools Used  
- **Linux Commands:**  
  - `cd` – Navigate directories.  
  - `ls` – List files in a directory.  
  - `nano` – View log files.  
  - `cat`, `less`, `grep` – Search and filter log content.  
- **Log Files in `/var/log/` Directory:**  
  - `auth.log` – Authentication-related events.  
  - `kern.log` – Kernel-related events.  
  - `syslog` – General system messages.  
  - `dpkg.log` – Package installation records.  
  - `apache2/access.log` – Web server access logs.  
  - `apache2/error.log` – Web server error logs.  
  - `apt/history.log` – APT package manager history.  
  - `mysql/error.log` – MySQL database error logs.  

## Steps  
1. **Launch the Ubuntu Linux Virtual Machine.**  
2. **Open a Terminal:** Press `Ctrl + Alt + T`.  
3. **Navigate to Log Directory:**  
   ```bash
   cd /var/log/
