# azkeyvault-secret-ansible

This Ansible playbook generates a random password and stores it securely in Azure Key Vault.

## Requirements

- Python 3
- Ansible
- [azure.azcollection](https://galaxy.ansible.com/azure/azcollection) Ansible collection
- A virtual environment

## Installation

1. **Create and activate a Python virtual environment:**

```bash
python3 -m venv ~/.venvs/ansible-azure
source ~/.venvs/ansible-azure/bin/activate
# Install the azure collection
ansible-galaxy collection install azure.azcollection