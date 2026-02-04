# Homelab

Reproducible homelab powered by Docker, Dokploy, and Ansible.

## Goals
- One-command rebuild
- Minimal manual configuration
- Git as source of truth
- Safe public exposure of select services

## Stack
- Ubuntu Server LTS
- Docker
- Dokploy
- Ansible
- Caddy (reverse proxy)

## Rebuild
```bash
ansible-playbook ansible/site.yml
```
