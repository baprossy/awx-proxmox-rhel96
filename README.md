# AWX Proxmox RHEL 9.6 Deployment

Projet Ansible/AWX pour déployer des VMs RHEL 9.6 sur Proxmox.

## Playbook principal

`playbooks/deploy_rhel96_vm.yml`

## Variables requises

- proxmox_api_host
- proxmox_api_user
- proxmox_api_password
- proxmox_node_name
- vm_hostname
- iso_filename

Voir la documentation complète dans QUICKSTART.md
