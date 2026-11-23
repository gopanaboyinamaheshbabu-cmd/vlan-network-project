| Device | Interface | IP Address | VLAN |
|--------|-----------|------------|------|
| R1 | Gi0/0.10 | 192.168.10.1/24 | 10 (Sales) |
| R1 | Gi0/0.20 | 192.168.20.1/24 | 20 (IT) |
| PC0, PC1 | Fa0 | DHCP 192.168.10.11+ | 10 (Sales) |
| PC2, PC3 | Fa0 | DHCP 192.168.20.11+ | 20 (IT) |
| Switch | Fa0/1-2 | access ports | 10 |
| Switch | Fa0/3-4 | access ports | 20 |
| Switch | Gi0/1 | trunk to R1 | 10, 20 |
