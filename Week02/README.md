# Week 02 – Enterprise Infrastructure Planning

## ITEP 414 – System Administration and Maintenance

**Program:** Bachelor of Science in Information Technology  
**Project:** Enterprise Infrastructure Planning for a Startup Company  
**Student:** Ralph Rio H. Bautista  
**Week:** 2  
**Company:** ABC Startup Solutions

---

## 📌 Project Overview

This project focuses on designing the initial IT infrastructure of **ABC Startup Solutions**, a newly established software development company with 20 employees operating from a single office floor.

The company currently has no computers, server, network infrastructure, internet infrastructure, or security policies. As the assigned Junior System Administrator, I was tasked with planning the company's IT infrastructure before the purchase and deployment of equipment.

The project includes the development of a company profile, hardware inventory, software inventory, network inventory, enterprise network topology, system administration role analysis, infrastructure recommendations, and a personal reflection.

The goal of this project is to demonstrate how proper infrastructure planning can support business operations, improve security, organize IT resources, and provide a foundation for future expansion.

---

## 🎯 Learning Objectives

Through this project, I was able to:

- Understand the role and responsibilities of a System Administrator.
- Analyze the IT requirements of a small business.
- Identify appropriate hardware, software, and networking equipment.
- Prepare professional IT inventories.
- Design an enterprise network topology.
- Understand basic network segmentation using VLANs.
- Develop technical documentation using Markdown.
- Practice making infrastructure recommendations.
- Improve technical communication and documentation skills.
- Understand the importance of planning before deploying IT infrastructure.

---

# 🏢 Company Scenario

## ABC Startup Solutions

**Nature of Business:**  
Software development and technology services.

**Office Location:**  
Santa Cruz, Laguna, Philippines *(fictional office location)*

**Number of Employees:** 20

### Department Distribution

| Department | Employees |
|------------|-----------|
| Information Technology | 5 |
| Human Resources | 4 |
| Finance | 5 |
| Sales | 6 |
| **Total** | **20** |

ABC Startup Solutions requires a reliable and secure IT infrastructure that allows employees to communicate, access company resources, store files, use business applications, and connect to the internet.

---

# 💻 Hardware Inventory Summary

The hardware infrastructure was planned based on the company's 20 employees and departmental requirements.

| Hardware | Quantity | Purpose |
|----------|----------|---------|
| Desktop Computers | 20 | Primary workstation for employees |
| Laptops | 4 | IT staff and management mobility |
| Server | 1 | Centralized services and internal resources |
| Router | 1 | Network routing and internet connectivity |
| Managed Switch | 1 | Connects wired network devices |
| Network Printer | 2 | Shared printing |
| UPS | 3 | Power protection for critical equipment |
| Wireless Access Point | 2 | Wireless network connectivity |
| NAS Storage | 1 | Centralized file storage and backup |
| External Backup Drive | 2 | Offline backup and disaster recovery |

The hardware selections were designed to provide sufficient capacity for the company's current operations while allowing room for future expansion.

---

# 🖥️ Software Inventory Summary

The software environment includes operating systems, productivity applications, development tools, security software, and system administration utilities.

| Software | Purpose |
|----------|---------|
| Windows 11 Pro | Employee desktop operating system |
| Ubuntu Server | Server operating system |
| Microsoft Office | Productivity and business documentation |
| Visual Studio Code | Software development and programming |
| Git | Version control |
| GitHub Desktop | Git repository management |
| VirtualBox | Virtual machine creation and testing |
| Google Chrome | Web browsing and web-based applications |
| Microsoft Defender | Endpoint security and malware protection |
| AnyDesk | Remote technical support |
| 7-Zip | File compression and extraction |

These software tools support the company's daily operations while providing developers and system administrators with the necessary tools for development, management, troubleshooting, and security.

---

# 🌐 Network Inventory Summary

The planned network infrastructure includes:

| Network Equipment | Quantity | Purpose |
|--------------------|----------|---------|
| ISP Modem / ONT | 1 | Provides internet connection |
| Enterprise Router | 1 | Routes network traffic |
| Firewall | 1 | Protects the internal network |
| Managed Switch | 1 | Connects wired devices |
| Wireless Access Point | 2 | Provides wireless connectivity |
| Patch Panel | 1 | Organizes network cabling |
| CAT6 Ethernet Cables | As required | Wired network connections |
| RJ45 Connectors | As required | Ethernet cable termination |

The network follows a **firewall-protected star topology**, with the managed switch serving as the central connection point for servers, workstations, printers, storage, and wireless access points.

---

# 🗺️ Enterprise Network Diagram

The enterprise network was designed to provide secure and organized connectivity throughout the company.

### Network Flow

```text
Internet
   │
   ▼
ISP Modem / ONT
   │
   ▼
Enterprise Router
   │
   ▼
Firewall
   │
   ▼
24-Port Managed Switch
   │
   ├── Server
   ├── NAS Storage
   ├── Network Printers
   ├── Wireless Access Point 1
   ├── Wireless Access Point 2
   ├── IT Department
   ├── HR Department
   ├── Finance Department
   └── Sales Department
