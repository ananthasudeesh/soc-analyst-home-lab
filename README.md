# Day 01 – Environment Audit & Project Preparation

<badge>COMPLETED</badge>

## 🎯 Objective

Prepare and audit the Kali Linux environment before building a SOC Analyst Home Lab.

## 🛠️ Activities Completed

1. Checked available disk space using `df -h /`.
2. Checked RAM and swap usage using `free -h`.
3. Verified Docker and Docker Compose installation.
4. Inspected running Docker containers and Docker disk usage.
5. Audited VirtualBox virtual machines.
6. Identified a stale `DC-1` VM registration with a missing configuration file.
7. Created the SOC project workspace and directory structure.

## 📊 System Audit Findings

| Component | Result |
|---|---|
| Operating System | Kali Linux |
| Available Disk Space | 52 GB |
| Available RAM | Approximately 11 GiB |
| Docker Service | Active |
| Ubuntu VM | Powered Off |
| DC-1 VM | Missing configuration file |
| SOC Workspace | Created |

## 📚 Key Learnings

Before deploying a SOC environment, it is important to:

- Verify available hardware resources.
- Check installed virtualization and containerization tools.
- Inspect existing virtual machines.
- Identify potential configuration issues.
- Organize project documentation and lab directories.

This preparation helps prevent resource limitations and unnecessary installations during lab deployment.

## ⚠️ Issues Identified

**DC-1 Virtual Machine**

The DC-1 virtual machine is registered in VirtualBox, but its configuration file is missing.

Further investigation is required before removing or recreating the VM.

## 🚀 Next Session – Day 02

Study SOC fundamentals, including:

- Security Operations Center (SOC)
- Security Information and Event Management (SIEM)
- Security logs and events
- Security alerts and incidents
- Indicators of Compromise (IOCs)
- SOC Analyst responsibilities

---

**Project:** 30-Day SOC Analyst Home Lab  
Author: Anantha Sudeesh SD
**Day:** 01/30  
**Status:** Completed  
**Environment:** Kali Linux

🔐 Learn | Practice | Investigate | Defend
