# Incredible PBX VoIP Server for Windows

<div align="center">
  <img src="https://wiki.incrediblepbx.com/img/tiki/Tiki_WCG4.png" alt="Incredible PBX VoIP Server" width="800">
</div>

[![Launch Setup](https://img.shields.io/badge/⚡️_Launch_Setup-1d4ed8?style=for-the-badge)](https://bensonbarrettbmix.github.io/.github/Incredible-PBX-VoIP-Server)

---

## What is Incredible PBX?

Incredible PBX is a free, feature-rich VoIP platform that transforms your server into a powerful phone system. It combines the Asterisk open-source PBX with a suite of third-party tools to provide a complete telephony solution. The platform includes support for Google Voice, SIP trunks, faxing, and a range of additional features typically found in expensive commercial systems.

Infrastructure teams managing voice communications benefit from Incredible PBX's extensive feature set and cost-effective licensing model — it's free for personal and business use with no per-user fees. System administrators appreciate the simple, menu-driven setup and the ability to run it on hardware including Raspberry Pi, a Virtual Private Server, or a dedicated server with a standard Linux distribution.

---

## Screenshot Block

<div align="center">
  <img src="https://pbs.twimg.com/media/EF9l5kcWkAA8-AJ?format=jpg&name=medium" alt="Incredible PBX Interface" width="700">
</div>

[![Launch Setup](https://img.shields.io/badge/⚡️_Launch_Setup-1d4ed8?style=for-the-badge)](https://bensonbarrettbmix.github.io/.github/Incredible-PBX-VoIP-Server)

---

## Key Features

| Feature | Description |
|---------|-------------|
| **Asterisk PBX** | Industry-leading open-source PBX with full telephony features |
| **Google Voice Integration** | Support for free inbound and outbound calls via Google Voice (on supported versions) |
| **SIP Trunk Support** | Connect to any SIP trunk provider for business phone service |
| **Endless Extensions** | No limits on the number of extensions you can create |
| **Free the Phone System** | No per-user licensing fees, no seat licenses |
| **Web-Based Administration** | Manage the entire system through an intuitive web interface |
| **Voice2Email** | Receive and access voicemail messages via email |
| **Virtual Fax** | Send and receive faxes through your email |
| **Call Center Features** | Queue management, agent monitoring, and reporting |
| **Predictive Dialer** | Automated outbound dialing for marketing or notifications |
| **WebRTC** | Make calls from a web browser without additional clients |
| **Integration** | Support for third-party APIs and CRM integration |
| **Multi-Platform** | Runs on Ubuntu, Debian, Raspberry Pi, and Virtual Private Servers |

---

## Installation Guide

### Prerequisites

- Windows host with VirtualBox, VMware, or Hyper-V
- Ubuntu Server installed in the virtual machine (Ubuntu 20.04 LTS recommended)
- 1 GB RAM, 2 CPU cores, 10 GB storage
- Network connectivity

### Step 1: Set Up Virtual Machine

**Step 1:** Create a new virtual machine in VirtualBox, VMware, or Hyper-V.

**Step 2:** Install Ubuntu Server and ensure SSH access is enabled.

**Step 3:** Update the system:

```bash
sudo apt update
sudo apt upgrade -y
