Looking Glass
============
Looking Glass is a set of technologies to create, manage and maintain a company's networks and services. 

Core technologies
-----------------
* Ansible
* CoreOS
* LizardFS

Goals
-----
* (Almost) zero touch service deployment
* Highly available
* Horizontally scalable

Getting Started
===============

Usage
-----
* Install Ansible on your management workstation
* Clone the looking-glass and [looking-glass-secrets](https://github.com/Zorlin/looking-glass-secrets/) repos
* Generate a public/private keypair with a password
* Run 'ssh-agent bash'
* Run 'ssh-add ~/.ssh/id_rsa'
* Run 'ansible-playbook site.yml -i inventory'

Contact Us
==========

IRC
---
You can find us on IRC at #lookingglass on irc.freenode.net. The IRC channel is a good place to get help or discuss development of Looking Glass.
