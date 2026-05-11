# Azure Linux VM Lab

## Overview

This lab was created to practice basic Microsoft Azure infrastructure deployment and networking concepts.

In this project I:
- Created a Virtual Network (VNet)
- Configured a subnet
- Deployed an Ubuntu Linux VM
- Configured Network Security Group (NSG) rules
- Connected to the VM using SSH
- Troubleshot connectivity issues

---

# Technologies Used

- Microsoft Azure
- Ubuntu Linux
- Azure Virtual Networks
- Network Security Groups
- SSH
- GitHub

---

# Network Configuration

| Resource | Configuration |
|---|---|
| VNet | 10.0.0.0/16 |
| Subnet | 10.0.1.0/24 |
| VM Name | HuskVM |
| VM Size | Standard B2s |

---

# SSH Connection

Connected to the VM using:

```bash
ssh username@public-ip
```

---

# Issues Encountered

## SSH Timeout

Initially experienced SSH connection timeout errors.

### Cause
Used the incorrect IP address while attempting SSH access.

### Resolution
Verified the VM public IP address in Azure and successfully connected.

---

# Lessons Learned

- Difference between public and private IP addresses
- Basic Azure networking structure
- Importance of NSG rules
- Azure reserved subnet addresses
- Basic Linux VM deployment process

---

# Future Improvements

- Add VNet peering
- Configure Azure Bastion
- Use SSH keys instead of passwords
- Deploy resources using Terraform

---

# Screenshots

> Screenshots will be added her e

---

# Author

dean-infra
