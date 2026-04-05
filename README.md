# azure-network-security-lab-Mohamed-Moihdeen
## Overview
This project demonstates a secure cloud network setup on Micrososft Azure, including: 
- VNet with **public and private subnets**
- **Network Security Groups (NSGs)** enforcing traffic rules

  The goal is to showcase **Network Segmentation**, **firewall rule enforcement**, and **basic security validation** in a cloud enviroment.

  -------------------------------------------------------------------------------------------------------------------

  ## Architecture
  ![Network Architecture] (network-architecture-topology.png, network-architecture.png)

  **Components:**
  - **VNet:** 'vnet-project-cyberlab' (10.0.0.0/16)
  - **Public Subnet:** 'frontend-subnet' (10.0.1.0/24)
  - **Private Subnet:** 'backend-subnet' (10.0.2.0/24)
  - **NSG:** 'NSG-cyberlab' applied to 'frontend-subnet'

-----------------------------------------------------------------------------------------------------------------------
