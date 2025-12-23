# Ansible Apache Automation ( Rocky Linux )

This project automates the installation and configuration of Apache HTTP Server on Rocky Linux using Ansible.

## Features
 - Installs Apache (httpd)
 - Starts and enables Apache service
 - Idempotent Ansible Playbook
 - Tested on Rocky Linux 9

## Project Structure
 .
 |-- ansible.cfg 
 |-- inventory
 |-- playbook.yml
 |-- README.yml

## How to Run
1. Clone the repository
2. Update inventory if needed
3. Run the playbook:

ansible-playbook playbook.yml

## Author
Yuvraj Choudhary (RHCE Certified)
