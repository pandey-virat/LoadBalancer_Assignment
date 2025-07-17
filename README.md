# Azure Load Balancer Assignment

This repository contains the practical implementation of an Azure assignment to configure and test both **Internal** and **External Load Balancers**.

## 📋 Objective

To implement and verify the working of:

- ✅ External Load Balancer (ELB)
- ✅ Internal Load Balancer (ILB)

## 🧪 Implementation Summary

- Created two virtual machines (VM1 & VM2) within the same virtual network.
- Installed and configured **IIS Server** on both VMs.
- Configured an **External Load Balancer**:
  - Created a **public frontend IP**
  - Defined a **health probe** to monitor VM health on port 80
  - Created a **load balancing rule** to distribute HTTP traffic
- Verified the ELB using the public IP.
- Configured an **Internal Load Balancer**:
  - Used a private frontend IP within the subnet
  - Verified connectivity using a third VM inside the same VNet

## 🧾 File Included

- 📄 `LoadBalancer_Assignment.docx` – Full implementation report with step-by-step screenshots

## 🌐 References

- [Azure Load Balancer Overview](https://learn.microsoft.com/en-us/azure/load-balancer/load-balancer-overview)
- [Create a Load Balancer using the Azure Portal](https://learn.microsoft.com/en-us/azure/load-balancer/quickstart-load-balancer-standard-public-portal)

---

