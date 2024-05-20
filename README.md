# Ansible DevOps Project

This project demonstrates how to deploy a simple web application using Ansible. The setup includes:

- Configuring web and database servers.
- Deploying a Flask application.
- Setting up CI/CD with GitHub Actions.

## Structure

- `ansible.cfg`: Configuration for Ansible.
- `inventory/hosts.ini`: Inventory file with server details.
- `playbooks/`: Ansible playbooks for configuring servers.
- `roles/`: Ansible roles for common tasks, web server, and database.

## How to Use

1. Clone the repository.
2. Update the inventory file with your server details.
3. Run the playbook: `ansible-playbook playbooks/site.yml`

## CI/CD

The project uses GitHub Actions to automate the deployment process.
