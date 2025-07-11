# pve-tools
Open-E JovianDSS tools run in the Proxmox VE Shell to automate the addition of cloned NFS storage from a JovianDSS snapshot and the automated restore of VMs and containers.

## Installation
Copy & Paste in the Proxmox VE shell:
```bash
wget https://raw.githubusercontent.com/open-e/pve-tools/main/pve-tools \
    -O /usr/local/sbin/pve-tools; \
    chmod +x /usr/local/sbin/pve-tools; \
    pve-tools
```

## Run it:
```bash
pve-tools
```
