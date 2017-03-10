# Hadoop Cluster Automation

Ansible playbooks to automate the provisioning and configuration of Cloudera/Hadoop clusters on Centos 7.

## Features
- **Prerequisites**: Java, Kernel tuning, SELinux configuration.
- **Roles**: NameNode, DataNode, ResourceManager, NodeManager.
- **Security**: Kerberos client configuration.

## Usage
```bash
ansible-playbook -i inventory/prod site.yml
```

## Tech Stack
- Ansible
- Shell
- CentOS
