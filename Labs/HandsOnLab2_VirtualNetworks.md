# Lab 2: Configuring Virtual Networks in Azure

## Objective:
Create and configure a Virtual Network (VNet), Subnets, and secure traffic using NSGs.

### Steps:
1. **Create a Virtual Network**: Name it `az305-vnet-lab`.
2. **Add Two Subnets**: Frontend and Backend.
3. **Create NSGs**: One for each subnet.
   - Allow inbound traffic for Frontend (HTTP/HTTPS).
   - Restrict traffic to Backend (allow only internal VNet traffic).
4. **Create a VM in Each Subnet**.

## Verification:
- Verify traffic flow between VMs in different subnets.
---
