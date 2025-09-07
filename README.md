# proxmox-hyperv-virtualization

## Overview
A hybrid virtualization environment combining Proxmox VE and Microsoft Hyper-V to support a mix of Linux and Windows workloads. This project covers cluster design, resource allocation, high availability, GPU passthrough, and cross-hypervisor migration strategies for both production and homelab use.

## Features
- **Cluster Design & HA**: Configure Proxmox VE and Hyper-V clusters for redundancy, load balancing, and live migration.
- **Cross-Hypervisor Migration**: Strategies for migrating VMs between Hyper-V and Proxmox, including P2V/V2V conversions.
- **GPU Passthrough & SR-IOV**: Enable GPU passthrough (e.g., Intel Arc, NVIDIA GPUs) and SR-IOV networking for performance-sensitive workloads.
- **Storage & Backup**: Integrate ZFS, Ceph, or NAS storage and implement snapshotting, replication, and backup policies.
- **Monitoring & Automation**: Set up monitoring (Prometheus/Grafana) and automation scripts for VM lifecycle management and failover.
