# Week 03 – Enterprise Server Deployment and Operating System Installation

## ITEP 414 – System Administration and Maintenance

**Program:** Bachelor of Science in Information Technology  
**Course:** ITEP 414 – System Administration and Maintenance  
**Project:** Enterprise Server Deployment and Operating System Installation  
**Week:** 3  
**Project Type:** Individual Portfolio Project  
**Student:** Ralph Rio H. Bautista  
**Company Scenario:** ABC Startup Solutions

---

# 📌 Project Overview

This project focuses on deploying and configuring an Ubuntu Server virtual machine for **ABC Startup Solutions**, a startup software development company.

As a Junior System Administrator, I was tasked with installing a Linux server that can later be used for services such as file sharing, remote administration, database hosting, web hosting, and other internal services.

The project involved creating an Ubuntu Server virtual machine, configuring the operating system, enabling SSH, verifying network connectivity and system services, updating the server, researching BIOS and UEFI, creating an Ubuntu boot process flowchart, and comparing Windows Server, Ubuntu Server, and Rocky Linux.

The project also included installing Windows Server Evaluation in a separate virtual machine as part of the bring-home activity.

The main goal of this project was to develop practical skills in server deployment, virtualization, Linux administration, operating system management, troubleshooting, and technical documentation.

---

# 🎯 Learning Objectives

After completing this project, I was able to:

- Understand the purpose of an operating system in an enterprise environment.
- Install Ubuntu Server in a virtual machine.
- Configure basic server settings.
- Configure a hostname and user account.
- Configure disk storage using guided partitioning.
- Install and verify OpenSSH Server.
- Verify network connectivity.
- Update an Ubuntu Server system.
- Understand the differences between BIOS and UEFI.
- Understand the stages of the Linux boot process.
- Explain the purpose of GRUB and systemd.
- Compare Ubuntu Server, Windows Server, and Rocky Linux.
- Practice virtualization using VirtualBox.
- Document server installation procedures.
- Troubleshoot basic server configuration problems.
- Improve technical documentation and system administration skills.

---

# 🖥️ Virtual Machine Specifications

The Ubuntu Server virtual machine was configured according to the requirements provided for the project.

| Component | Configuration |
|-----------|---------------|
| Virtual Machine Name | Ubuntu-Server-Week03 |
| Operating System | Ubuntu Server LTS |
| RAM | 4 GB |
| CPU | 2 Virtual Processors |
| Storage | 40 GB |
| Disk Type | VDI |
| Network Mode | NAT |
| Installation Media | Ubuntu Server LTS ISO |
| Hostname | server01 |
| SSH | OpenSSH Server |
| File System | ext4 |
| Partitioning | Guided – Use Entire Disk |

### Virtualization Software

**Oracle VM VirtualBox** was used to create and manage the virtual machine.

---

# 🐧 Installation Summary

The Ubuntu Server installation was completed using the Ubuntu Server LTS ISO inside a virtual machine.

The following installation settings were configured:

1. Selected English as the installation language.
2. Configured the keyboard layout.
3. Configured the network using DHCP.
4. Assigned the hostname:

```text
server01
