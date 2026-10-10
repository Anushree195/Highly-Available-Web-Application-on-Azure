# Project notes

This project was documented from the available project description after the original deployment files and screenshots were lost.

## Details supported by the project description

- Two Azure VMs in an Availability Set
- One VNet and Resource Group
- Azure public Load Balancer with frontend IP, backend pool, and health probe
- IIS installed on both VMs, with custom HTML pages
- VM public IPs removed so user traffic goes through the Load Balancer
- Network rules configured for the intended traffic path
- Custom Azure RBAC role for the Operations team
- Website requests tested through the Load Balancer; traffic was reported to reach both servers

## Details not recovered

The following were not available and are intentionally not invented:
- Exact VNet/subnet address ranges
- VM names, sizes, operating system versions, and region
- Load Balancer SKU and exact rule/probe settings
- Exact network security rule values
- Portal screenshots, deployment logs, or exported configuration
- Infrastructure-as-code files

If these details are recovered later, update this document and the architecture diagram.
