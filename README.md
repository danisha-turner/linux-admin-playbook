# linux-admin-playbook
Ansible playbooks for Linux system administration tasks (CentOS/RHEL).
# Linux Admin Playbooks

This repository contains Ansible playbooks used to automate common Linux system administration tasks
in CentOS Stream 9 and RHEL 9 environments.

## Scope
- Package installation and updates
- User and group management
- Firewall configuration (firewalld)
- Service management (systemd)
- 
## Playbooks
- `playbooks/packages.yml` – Installs baseline administration packages
- `playbooks/users.yml` – Creates local users/groups and configures sudo access safely
- `playbooks/firewalld.yml` – Ensures firewalld is running and opens common services (ssh/http/https)
- 
## Environment
- OS: CentOS Stream 9 / RHEL 9
- Automation: Ansible
- Inventory: Static inventory (lab environment)

## Notes
- Playbooks are designed for lab and learning purposes.
- No secrets or credentials are stored in this repository.
