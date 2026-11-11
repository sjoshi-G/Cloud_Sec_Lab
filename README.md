# Cloud Security Lab using CentOS Stream 9
## Overview
This project demonstrates the deployment and hardening of a Linux server using CentOS Stream 9.

The lab focuses on implementing security controls commonly used in cloud and enterprise environments.

## Technologies Used
CentOS Stream 9
Nginx
Firewalld
OpenSSH
Fail2Ban

## Security Controls Implemented

### Host Configuration
Changed system hostname to cloudseclab
Verified operating system and kernel version

### Network Security
Configured Firewalld
Allowed only required services
SSH (22)
HTTP (80)

### Web Services
Installed and configured Nginx
Hosted a custom webpage

### SSH Hardening
Disabled root login
Validated SSH configuration

### Brute Force Protection
Installed Fail2Ban
Enabled SSH monitoring

### Verification
Confirmed active ports using ss -tulnp
Reviewed authentication logs

### Screenshots
Screenshots demonstrating each phase are available in the screenshots directory.

### Skills Demonstrated
Linux Administration
Cloud Security
Network Security
System Hardening
Log Analysis
Firewall Configuration
Web Server Administration
