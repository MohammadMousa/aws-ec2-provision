# AWS EC2 Provisioning

Provision, configure, harden, and validate Ubuntu EC2 infrastructure using **Terraform and Ansible**.

The project separates infrastructure provisioning from server configuration:

* **Terraform** — provisions AWS infrastructure.
* **Ansible** — configures, hardens, and validates EC2 instances.

## Features

### Infrastructure

* AWS EC2 provisioning with Terraform
* Configurable instance and infrastructure parameters
* Infrastructure outputs for downstream configuration

### Server Configuration

* SSH connectivity
* Package updates
* Java 21 installation
* Apache web server deployment
* Nginx web server deployment
* Mail service using Postfix
* Basic server hardening
* UFW firewall configuration
* Fail2ban installation
* Automatic security updates
* Automated system verification
* Idempotent Ansible playbooks
* Modular Ansible roles

## Project Structure

```text
aws-ec2-provision/
├── terraform/
└── ansible/
    ├── ansible.cfg
    ├── inventory/
    ├── group_vars/
    ├── host_vars/
    ├── roles/
    ├── tasks/
    └── playbooks/
```

## Roadmap

### Completed
* [x] Project structure
* [x] Ansible inventory configuration
* [x] SSH connectivity
* [x] Package update configuration
* [x] Java 21 installation
* [x] Apache deployment
* [x] Nginx deployment
* [x] Mail service with Postfix
* [x] Security hardening
* [x] UFW firewall configuration
* [x] Fail2ban configuration
* [x] Automatic security updates
* [x] Automated verification suite
* [x] Modular verification tasks
* [x] Ansible roles structure
* [x] HTTPS with Let's Encrypt
* [x] Master `site.yml` playbook
* [x] Ansible lint integration
* [x] CI pipeline (ansible-lint on push)

### In Progress
* [ ] Terraform AWS infrastructure provisioning
* [ ] Terraform → Ansible integration
* [ ] Full CI/CD with ephemeral test instance

### Planned
* [ ] Apache Virtual Hosts
* [ ] MySQL installation and configuration
* [ ] PHP installation
* [ ] WordPress deployment
* [ ] Docker installation
* [ ] Docker Compose deployment
* [ ] Node.js installation
* [ ] Redis installation
* [ ] Automatic backups
* [ ] Log rotation configuration
* [ ] Monitoring tools
* [ ] EC2 bootstrap scripts
* [ ] Dynamic AWS inventory
* [ ] GitHub Actions CI/CD
* [ ] Multi-server deployment
* [ ] Expanded Ansible role coverage

```
```

