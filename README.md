<h1 align="center">Edin Haskić</h1>

<p align="center">
  <strong>IT Infrastructure · Systems & Network Administration · Monitoring & Automation</strong>
</p>

<p align="center">
  Linux and Windows services, network infrastructure, virtualization, storage, security, and self-hosted platforms.
</p>

## Profile

I work across systems administration and network infrastructure, with a practical focus on keeping services reliable, networks properly configured, and systems maintainable. My hands-on work includes Linux server operations, network routing and firewall configuration, virtualization and storage, mail infrastructure, monitoring, identity and access services, backup workflows, and operational tooling.

I approach infrastructure with an operations mindset: understand the failure, verify the root cause, test changes before rollout, protect credentials and data, and document repeatable procedures.

## Core Technologies

| Area | Technologies and platforms |
|---|---|
| **Operating systems & services** | Debian, Rocky Linux, Windows, SSH, systemd, Nginx, TLS and certificate management |
| **Networking** | TCP/IP, routing, DNS, VLANs, NAT, firewall policies, WireGuard/VPN; MikroTik, FortiGate, D-Link managed switches, UniFi |
| **Virtualization & containers** | Proxmox VE, Proxmox Backup Server, Hyper-V, VMware Workstation, Docker Compose, K3s |
| **Storage & recovery** | TrueNAS, ZFS, NFS, iSCSI, replication, snapshots, backup and restore workflows |
| **Mail infrastructure** | Modoboa, Postfix, Dovecot, Rspamd, Redis, Roundcube, SPF, DKIM, DMARC, Certbot |
| **Monitoring & security** | Zabbix, Wazuh, Fail2ban, Rspamd, service and mail-queue troubleshooting |
| **Identity & self-hosted services** | Nextcloud AIO, Authentik, Vaultwarden, Mattermost, Wiki.js, NetBox, Smallstep Step CA |
| **Scripting & engineering tools** | PowerShell, Bash, Python, SQL, Git/GitHub, pytest |

## Selected Infrastructure Work

### MailGuard / Modoboa Monitor

**Multi-server mail monitoring and operational tooling** · *In development*

A monitoring application for Modoboa-based mail environments. Development work includes a Python/FastAPI backend, PostgreSQL, a SvelteKit/Svelte frontend, PowerShell installation and update workflows, automated tests, configuration validation, and release-safety checks. The application is developed and tested locally before any production-side changes are considered.

### Modoboa Mail Platform

**Mail services, delivery controls, and troubleshooting**

Configured and troubleshot a Debian-based mail stack involving Modoboa, Postfix, Dovecot, Rspamd, Redis, Nginx, and Roundcube. Work has covered TLS certificates, SPF/DKIM/DMARC, service availability, IMAP authentication, mail queues, filtering history, logs, and Fail2ban.

### Virtualization, Storage & Backup

**Virtual machines, storage services, and recovery workflows**

Hands-on work with Proxmox VE, Proxmox Backup Server, Hyper-V, TrueNAS, ZFS, NFS, and iSCSI. Tasks have included storage expansion, virtual-disk conversion, replication, shared storage, and backup-related configuration and troubleshooting.

### Self-Hosted Services & Identity

**Secure access to internal services**

Deployed and configured services including Nextcloud AIO with TrueNAS-backed NFS storage, Authentik, Vaultwarden, Mattermost, Wiki.js, NetBox, and Smallstep Step CA, with Nginx reverse proxy and TLS-related configuration.

### Network Operations & Monitoring

Worked on MikroTik routing, VLAN trunking, NAT, DNS forwarding, WireGuard routing, FortiGate firewall policies, managed switching, and UniFi wireless access. Monitoring and security work includes Zabbix and Wazuh installation/upgrades, Fail2ban, and service-level troubleshooting.

## Automation & Application Tooling

Alongside infrastructure work, I build tools that support administration and business workflows. Projects have used Python, FastAPI, Flask, PostgreSQL, MariaDB, SQLite, SvelteKit/Svelte, PySide6, and PowerShell. Examples include the HR Portal, a legal-office desktop application, PDF-to-Excel processing, and administrative utilities.

## Current Focus

- Reliable monitoring and operational visibility for self-hosted services
- Repeatable installation, configuration, upgrade, and validation workflows
- Network troubleshooting, access control, and service security
- Backup, storage, and recovery practices
- Clear technical documentation and reproducible project setup

## Portfolio Notes

Some work involves internal or private environments. Public repositories and case studies will contain only material that can be shared safely, with credentials, private network details, logs, and business data removed. Project documentation will distinguish implemented and tested features from work in progress.
