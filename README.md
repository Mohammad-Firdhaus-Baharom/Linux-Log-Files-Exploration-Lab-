# System Log Analysis Lab

## Objective
The objective of this lab is to develop the skills necessary for locating, accessing, and interpreting system logs on a Linux-based system. By reviewing key log files, the lab enhances your ability to monitor system health, diagnose issues, and identify security threats on Ubuntu systems.

## Skills Learned
- Locating and navigating Linux log files, including /var/log/ and key system logs.
- Reviewing and analyzing various types of system logs such as syslog, auth.log, kern.log, and more.
- Detecting potential security issues related to system messages, authentication, and package installations.
- Using terminal commands (e.g., last, dmesg, journalctl, logger) to explore system logs.
- Utilizing GUI tools (e.g., GNOME System Log Viewer, KDE System Log Viewer) for analyzing logs.
- Identifying security-related events, such as unauthorized login attempts and suspicious network activity.

## Tools Used
### Terminal commands:
- `cd`, `ls`, `nano` (to navigate and open log files)
- `sudo`, `last`, `lastb`, `dmesg`, `journalctl`, `logger` (for log analysis)

### Log Files:
- `/var/log/syslog`
- `/var/log/auth.log`
- `/var/log/kern.log`
- `/var/log/apt/history.log`
- `/var/log/apache2/access.log`

### GUI Tools:
- GNOME System Log Viewer
- KDE System Log Viewer (ksystemlog)

## Steps

### Locating Log Files:
1. Navigate to `/var/log/` directory using the command `cd /var/log/` and list the contents with `ls`.
2. Review and document the purpose of each log file in this directory.

### Reviewing System Messages:
1. Use `sudo nano /var/log/syslog` to explore system messages.
2. Identify security-related events such as suspicious activity or system errors.
3. Optionally, use `logger` to add custom events to the syslog.

### Reviewing Authentication-related Events:
1. Open `/var/log/auth.log` using `sudo nano /var/log/auth.log`.
2. Check for login attempts, failed logins, and other authentication issues.
3. Use `last`, `lastb`, and `sudo lastb` to explore login history and failed attempts.

### Reviewing Kernel-related Events:
1. Use `sudo nano /var/log/kern.log` to check kernel-related logs.
2. Explore system events like hardware interactions and driver issues.
3. Use `dmesg`, `journalctl`, and variations of these commands to further analyze kernel messages.

### Reviewing Package Installation Logs:
1. Open `/var/log/apt/history.log` and `/var/log/dpkg.log` to inspect package installation history.
2. Analyze package-related events for security concerns, such as unauthorized software installation.

### Reviewing Web Server Logs:
1. Access `/var/log/apache2/access.log` and `/var/log/apache2/error.log` to analyze web server logs.
2. Identify security-related events such as failed connections or misconfigurations.

### Reviewing Logs Using Ubuntu GUI:
1. Launch the GNOME System Log Viewer and explore categorized logs (e.g., Important, Applications, System, Security, Hardware).
2. Install and use the KDE System Log Viewer (ksystemlog) for additional log analysis features.
