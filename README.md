# Azure Linux VM Lab

## Overview

This lab was created to practice basic Microsoft Azure infrastructure deployment and networking concepts.

In this project I:
- Created a Virtual Network (Vnet_lab1)
- Configured a subnet
- Deployed a Ubuntu Linux VM
- Configured Network Security Group (NSG) rules
- Connected to the VM using SSH

---

# Technologies Used

- Microsoft Azure
- Ubuntu Linux
- Azure Virtual Networks
- Network Security Groups
- SSH

---

# Network Configuration

| Resource | Configuration |
|---|---|
| VNet | 10.0.0.0/16 |
| subnet | 10.0.1.0/24 |
| VM Name | linux.vmLab1 |
| VM Size | Standard D2s |

---

# SSH Connection

Connected to the VM using:

```bash
ssh dean-infra_lab@52.188.187.160
```

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

<img width="1248" height="1069" alt="vm setup" src="https://github.com/user-attachments/assets/289e6fc3-0a2f-4619-b2a9-d9a92a40a5be" />
<img width="1179" height="1094" alt="Vnet setup" src="https://github.com/user-attachments/assets/e5fbb8d4-9f99-4833-a2fe-5a84609d3ad3" />
<img width="1297" height="705" alt="nsg setup" src="https://github.com/user-attachments/assets/ff374de7-1438-4b71-89c6-abb135faa894" />
<img width="1295" height="1222" alt="linux terminal" src="https://github.com/user-attachments/assets/4a3f0d8b-dc33-4515-9f6e-17ace5248308" />

---

# Author

dean-infra
