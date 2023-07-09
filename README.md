# Ansible Setup

This repository contains an Ansible playbook to set up and configure a remote machine.

## Prerequisites

- Ansible installed on the control machine.
- SSH access to the remote machine.

## Installation

   1. Install Ansible on the control machine:
   
      ```shell
      yum install ansible -y
      ansible --version
   2. Create the inventory.ini file:
   3. Configure SSH access without a password:
         ```shell
         ssh-keygen
         ssh-copy-id root@<Your_IP>

## Usage
1. Clone this repository.
2. Run the Ansible playbook:
   ```shell
   ansible-playbook -i inventory.ini playbook.yml
