# Lab 1: Deploying an Azure Virtual Machine

## Objective:
Deploy a Windows or Linux Virtual Machine (VM) using the Azure portal and configure networking and storage.

### Steps:
1. **Login to Azure Portal**.
2. **Create a new Resource Group**: `az305-vm-lab-rg`.
3. **Deploy a VM**:
   - OS: Windows Server 2019
   - Size: Standard D2s_v3
   - Disk: Premium SSD.
4. **Configure Networking**:
   - Create a new VNet.
   - Add NSG to control inbound traffic (allow RDP for Windows or SSH for Linux).
5. **Review and Deploy**.

## Verification:
- Connect to the VM via RDP/SSH.
- Verify storage and network configurations.
---
