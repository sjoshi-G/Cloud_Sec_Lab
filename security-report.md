# Cloud Security Lab Security Report

## System Information
Operating System: CentOS Stream 9
Hostname: cloudseclab

## Security Controls
Firewall Configuration
Firewalld was configured to allow SSH and HTTP traffic while restricting unnecessary services.

## SSH Hardening
Root login was disabled to reduce unauthorized administrative access.

## Nginx Deployment
A custom webpage was hosted using Nginx on port 80.

## Fail2Ban
Fail2Ban was installed and configured to help protect against brute-force attacks.

## Monitoring
System services and authentication logs were reviewed to verify correct operation.

## Results
The server successfully hosted web content while maintaining basic security controls including firewall restrictions, SSH hardening, and intrusion prevention mechanisms.
