# Homelab Resources

Welcome to my homelab repository! This is where I share the configuration and setup details for my 4-node Proxmox cluster with TrueNAS NFS shared storage. My lab is a playground for experimenting with various services, containers, virtual machines, and more.

## Overview

My homelab setup includes a range of services, containers, and virtual machines. Here's a glimpse of what you'll find:

### Network
1. Vlan seperation for home,lab,storage,kids networks
2. 10Gb core network
3. Unifi UDMP/APs

### LXC Containers

1. **Cloudflare**: Containerized setup for Cloudflare services to enhance security and performance.
2. **Pi-hole**: A network-wide ad blocker that improves your browsing experience.
3. **Ansible-Semaphore**: Web-based Ansible playbook management tool for easy automation.

### Virtual Machines

1. **Proxmox Backup Server**: A dedicated VM for handling backups within the Proxmox environment.
2. **Test Environments**: Multiple Windows, macOS, and Linux machines for experimenting and testing.
3. **Kubernetes Cluster**: A 6-node Kubernetes cluster with 3 worker nodes and 3 control nodes.
4. **CasaOS**: Exploring smart home automation with CasaOS.
5. **Windows Active Directory/DHCP/DNS**: Configured in failover for network services.
6. **Docker/Docker-Compose Host**: A versatile Debian-based host for Docker and Docker Compose.

## Setup Details

[WORK IN PROGRESS]For detailed instructions on setting up and configuring each component, please explore the respective directories and files in this repository.

## Contributions

I welcome contributions, suggestions, and improvements to this homelab resource repository. If you have ideas for enhancing any of the configurations or want to add new services, feel free to submit a pull request.
