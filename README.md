# Network Attached Storage

## Overview

My personal Network Attached Storage project aimed to not only provide hands-on experience for networking, CLI, etc. but was a valuable opportunity for me to explore how setting up servers work, as well as maintaining, updating, protecting, and running various apps and jobs simultaneously on my home network.

### Skills Learned

- Practiced understanding of physical networking.
- Configuring network interfaces with static IP's to ensure reachability.
- Configuring manual DNS to route all network traffic to correct end destination.
- Monitoring all inbound and outbound network traffic with various tools such as Wireshark.
- Practiced access control and permissions to ensure applications and users had access to only what is needed.
- Configuring RAID backups for redundency
- Read and analyze logs to understand issues
- Learned the basics of dockers and containers to run and deploy applications

---

## Technologies Used


| Category   | Technology                      |
| ---------- | ------------------------------- |
| OS         | TrueNAS SCALE                   |
| Storage    | ZFS / RAID                      |
| Networking | VLANs, DNS Rules                |
| Security   | VPN, ACLs                       |
| Services   | SMB, Cloud Sync, Snapshots      |
| Monitoring | Logs, Pihole                    |

---

## Current Apps and Services

 - Immich
 - Jellyfin
 - Nextcloud
 - VaultWarden
 - <a href="https://github.com/Nikolas-Guidone/Pihole">Pihole</a>
 - Nginx Proxy Manager
 - OpenwebUI
 - <a href="https://github.com/Nikolas-Guidone/Dockge">Dockge</a>

 ## Current Hardware

 - Operating System: TrueNAS 25.10.1 - Goldeye
 - Processor: Intel Core i7-4790 CPU @ 3.60GHz
 - Motherboard: Dell 0KWVT8
 - Graphics Card: -
 - Installed RAM: 24GB Total (2x 4GB DDR3 & 2x 8GB DDR3)
 - Storage:
     - 2x Western Digital Red Plus 4 TB HDD
     - 1x Seagate 1TB Desktop HDD
     - 1x Samsung 870 EVO 500GB Internal SSD
 - Network: Ethernet

## Stages of my NAS

| <a href="https://github.com/Nikolas-Guidone/Stage-1-NAS">Stage 1</a> - Physical build and OS install |

## Security Considerations

- No services exposed directly to Internet
- Reverse proxy and custom DNS records
- Vlan and split - horizon DNS
- Custom created certificates managed internally
- HTTP vs HTTPS when exposed (currently not exposed - LAN only)

