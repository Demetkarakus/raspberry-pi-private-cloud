# Raspberry Pi Private Cloud Storage System

## Project Overview
This project focuses on designing, deploying and evaluating a low-cost private cloud storage system using Raspberry Pi 4 and Nextcloud.

The system was developed as my final year Computer Science project and demonstrates practical experience in Linux administration, cloud infrastructure, secure file sharing, firewall configuration, troubleshooting and system monitoring.

## Aim
The aim of this project was to build a self-hosted private cloud platform that provides secure file storage, user access control and remote access while evaluating performance, security and usability.

## Technologies Used
- Raspberry Pi 4
- Raspberry Pi OS
- Nextcloud
- Linux
- SSH
- UFW Firewall
- HTTPS / SSL
- Fail2Ban
- Netdata
- WebDAV

## Key Features
- Self-hosted private cloud storage
- Secure file sharing
- User authentication
- Firewall configuration
- HTTPS access
- Trusted domain configuration
- System monitoring
- Performance and usability testing

## System Architecture
<img width="1295" height="863" alt="01_system_architecture_private_cloud" src="https://github.com/user-attachments/assets/540b0d0b-3f4e-48fd-b1e3-218c9f38221f" />

## Implementation Evidence

### Nextcloud Dashboard
The screenshot below shows successful browser-based access to the Nextcloud private cloud dashboard.

<img width="605" height="311" alt="08_nextcloud_dashboard_access" src="https://github.com/user-attachments/assets/9b5e869a-eb18-4185-893a-7ec0dc4c43bb" />


### Firewall Configuration
UFW was configured to control access to the private cloud server and restrict unnecessary network exposure.

<img width="635" height="231" alt="04_ufw_firewall_rules" src="https://github.com/user-attachments/assets/5921fdd5-0bd1-4362-890b-c30a672ec1e8" />


### Trusted Domain Configuration
Nextcloud trusted domains were configured to allow secure access through the local network environment.

<img width="471" height="79" alt="05_trusted_domain_configuration" src="https://github.com/user-attachments/assets/0b5b4126-b4de-4d39-958c-e06419f15415" />


### Live System Monitoring
Netdata was used to observe CPU, memory, network and system performance during private cloud operation.

<img width="1301" height="792" alt="12_netdata_live_monitoring_dashboard" src="https://github.com/user-attachments/assets/fed3ec71-e417-4054-aa2a-4d6a54b8023d" />

## Testing and Evaluation
Testing included:
- Browser-based dashboard access
- File upload and retrieval
- Service status verification
- Firewall rule validation
- Trusted domain configuration
- System resource monitoring
- Performance observation

## Challenges
During implementation, several practical issues were identified and resolved, including:
- Changing local IP addresses
- Trusted domain access issues
- Self-signed HTTPS certificate warnings
- Hotspot/network instability
- Home network upload speed limitations

## What I Learned
This project helped me develop practical skills in:
- Linux system administration
- Cloud infrastructure
- Networking
- Cybersecurity basics
- Troubleshooting
- System monitoring
- Technical documentation

## Project Status
Completed as part of my final year BEng (Hons) Computer Science project at Anglia Ruskin University.
