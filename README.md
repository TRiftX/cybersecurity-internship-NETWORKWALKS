# Cybersecurity Internship - Network Walks

## 🚀 Task 1: Lab Setup (Kali Linux on VirtualBox)

### Objective
Configure a secure virtualization environment using Oracle VM VirtualBox and install Kali Linux to serve as the primary penetration testing and network analysis workstation.

---

## 🛠️ Environment Specifications
* Host Operating System: Windows 
* Hypervisor: Oracle VM VirtualBox (v7.x)
* Guest Operating System: Kali Linux (64-bit Rolling)
* Allocated Resources:
  * RAM: 3 GB (3072 MB)
  * CPU Cores: 2 Cores
  * Storage: 80.09 GB (Virtual Disk Image)
  * Network Adapter: NAT (Network Address Translation)

---

## 📝 Step-by-Step Implementation

1. Virtual Machine Provisioning:
   * Downloaded the pre-built VirtualBox 64-bit Kali Linux image from the official documentation.
   * Imported the appliance into Oracle VM VirtualBox Manager and allocated 3 GB RAM and 2 CPU cores.
2. First Boot & Authentication:
   * Powered on the virtual machine and logged into the Kali desktop environment using default credentials (`kali` / `kali`).
3. Network Interface Verification:
   * Opened a terminal instance within the guest OS and ran configuration utilities to verify active network adapters and IP assignment (`eth0` interface via NAT).

---

## 📷 Lab Evidence / Screenshots

### 1. VirtualBox Manager
![VirtualBox](./screenshots/virtualbox.jpg)

### 2. Lab Setup View
![Lab Setup](./screenshots/lab%20setup.jpg)

### 3. Kali VirtualBox Settings & Terminal
![Kali Settings](./screenshots/kali%20virtualbox%20setting.jpg)