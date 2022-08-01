# config-with-ansible

## Description

Configured a remote EC2 server to be able to deploy the TodoList container.
- Installed the necessary packages on the remote server.
- Added users to docker group.
- Used docker compose to launch a multi-container application.

## Getting Started

### Dependencies

* An EC2 Server with a public key.
* Ansible

### Executing program

* Install Ansible.
* Provide the private key to main.yaml file.
* Execute the Ansible playbook.
* The web application starts on port 3000.
```
ansible-playbook main.yaml
```
