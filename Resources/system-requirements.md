# Azure Virtual Machine System Requirements

## Virtual Machine Configuration

For reference, we have utilized the Standard_NC6s_v3 Azure virtual machine to create the image.

### Optimal
- **vCPUs:** 6
- **Memory:** 128 GB
- **GPU Memory:** 16 GB 

### Minimum
- **vCPUs:** 6
- **Memory:** 64 GiB 

## Operating System
- **Preferred Operating System:** 20.04.6 LTS (GNU/Linux 5.15.0-1051-azure x86_64)

## Storage
- **Boot Disk Type:** Premium SSD LRS
- **Boot Disk Size:** 1024 GB

## Networking
- **Network Security Group (NSG):** You need to be able to access ports 8080 and 8888, to access Jenkins and Jupyter Notebook respectively.

