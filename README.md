# AWS EC2 Bootstrap with Ansible

Provision, harden, and validate Ubuntu EC2 instances using Ansible.

## Features
- SSH connectivity
- Package updates
- Java 21 installation
- Apache web server deployment
- Nginx web server deployment
- Basic server hardening
- UFW firewall configuration
- Fail2ban installation
- Automatic security updates
- Automated system verification
- Idempotent playbooks

## Roadmap

### Completed
- [x] Project structure
- [x] Inventory configuration
- [x] SSH connectivity
- [x] Package update playbook
- [x] Java installation playbook
- [x] Apache deployment playbook
- [x] Nginx deployment playbook
- [x] Security hardening playbook
- [x] Automated verification suite
- [x] Modular verification tasks

### Planned
- [ ] Master `site.yml` playbook
- [ ] Apache Virtual Hosts
- [ ] HTTPS with Let's Encrypt
- [ ] MySQL installation and configuration
- [ ] PHP installation
- [ ] WordPress deployment
- [ ] Docker installation
- [ ] Docker Compose deployment
- [ ] Node.js installation
- [ ] Redis installation
- [ ] Automatic backups
- [ ] Log rotation configuration
- [ ] Monitoring tools
- [ ] EC2 bootstrap scripts
- [ ] Terraform integration
- [ ] Dynamic AWS inventory
- [ ] GitHub Actions CI/CD
- [ ] Multi-server deployment
- [ ] Ansible Roles refactoring
