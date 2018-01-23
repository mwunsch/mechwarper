# Mechwarper

Studies in configuration management and provisioning. The purpose of
this repository is to house scripts for administering my personal
systems and to better understand the _Infrastructure as Code_ process.

Mechwarper is made up of
never-complete [Ansible](https://www.ansible.com) playbooks.

Two different playbooks exist, one for administering a
single [FreeBSD](https://www.freebsd.org) server hosted
on [DigitalOcean](https://m.do.co/c/19d9dc066fc3).

    $ ansible-playbook -i hosts freebsd/site.yml

Another for bootstrapping a
local [macOS High Sierra](https://www.apple.com/macos/high-sierra/)
machine to become a preferred development environment.

    $ ansible-playbook local/local.yml
