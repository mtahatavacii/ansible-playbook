# Ansible Setup

This repository contains an Ansible playbook to set up and configure a remote machine.

## Prerequisites

- Ansible installed on the control machine.
- SSH access to the remote machine.

## Installation

1. Install Ansible on the control machine:

   ```shell
   sudo yum install ansible -y
   ansible --version
2. Create the inventory.ini file:
 ```shell
vi inventory.ini

Add the following contents to the inventory.ini file:

```shell
[your_remote_host]
<Your_IP>

