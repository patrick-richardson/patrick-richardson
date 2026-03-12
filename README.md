# Patrick Richardson

Infrastructure • Automation • Virtualization • DevOps

Systems Engineer in development focused on infrastructure automation, virtualization, and DevOps practices.

## Current Focus

Building and automating **PatrickHomeLab** — a Proxmox-based home lab used to develop real-world infrastructure engineering skills.

## Lab Environment

### Core Systems

**Forge**  
Proxmox hypervisor hosting the virtual infrastructure.

**Vault**  
Network storage server providing NFS media storage and backup storage.

**Media VM**  
Plex media server running as a virtual machine.

**Monitor-01**  
Prometheus and Grafana monitoring stack.

**Controller-01**  
Ansible automation controller used to manage and automate lab infrastructure.

**VPN-Gateway**  
WireGuard VPN gateway providing secure remote access into the lab environment.

**Proxy-01**  
Reverse proxy server is responsible for internal routing and HTTPS access to lab services.

## Technologies

-Linux  
-Ansible  
-Proxmox  
-Prometheus  
-Grafana  
-Git  
-Infrastructure Automation


## Lab Topology

```
Internet
   │
ISP Router
   │
Eero Gateway
   │
Managed Switch
   │
├── Forge (Physical Server)- Proxmox Hypervisor
│   ├── Media VM - Plex media services
│   ├── Monitor-01 - Prometheus/Grafana monitoring
│   ├── Controller-01 - Ansible automation control node
│   ├── VPN-Gateway - WireGuard remote access
│   └── Proxy-01 - Reverse proxy and HTTPS services
│
└── Vault (Physical Server)- NFS storage and backup server
```

## Current Projects

PatrickHomeLab Infrastructure Automation  
Automating infrastructure management using Ansible.

Future Goals

Infrastructure as Code  
Cloud Engineering  
DevOps Automation
