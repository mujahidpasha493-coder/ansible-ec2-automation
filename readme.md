Automate AWS EC2 Server Configuration Using Ansible

Project Overview

This project automates Apache2 web server configuration on an AWS EC2 Ubuntu instance using Ansible.

Tools Used

- AWS EC2
- Ubuntu
- Ansible
- Apache2
- YAML

Implementation

1. Created an Ansible control node and a managed EC2 node.
2. Configured SSH connectivity and an Ansible inventory.
3. Verified connectivity using the Ansible ping module.
4. Installed and started Apache2 using Ansible.
5. Used an Ansible playbook to deploy a custom webpage.

Result

Successfully automated Apache2 configuration and deployed a custom webpage.

Website content: "Deployed Using Ansible - AWS EC2"

Ad-hoc Commands vs Playbooks

- Ad-hoc commands: Run individual tasks directly on managed hosts.
- Playbooks: Define repeatable, multi-step automation tasks in YAML.
