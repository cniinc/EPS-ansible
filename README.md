# EPS (Effortless Photo Stack) Ansible Automation

Ansible playbooks for managing Operation EPS (Effortless Photo Stack) - a coordinated PhotoPrism/Immich photo management system.

## Features
- Automated processing window coordination
- PhotoPrism/Immich timing management
- System monitoring and status checks

## Quick Start
1. Update `inventory/production.yml` with your server details
2. Configure variables in `group_vars/all.yml`
3. Run: `ansible-playbook playbooks/eps-coordination.yml -e "action=status"`

## Playbooks
- `eps-coordination.yml` - Main timing coordination
- `eps-setup.yml` - Initial system setup
- `maintenance.yml` - System maintenance

## Semaphore Integration
This repository is designed for use with Semaphore UI for scheduling and execution.