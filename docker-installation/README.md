# Ansible Role for installing Docker on Linux servers
=======================================================

Ansible Role that installs [Docker](https://www.docker.com) on Linux.

Pre-requisites:
===============
Run the below commands in the localhost or target host where ever you want to install the docker

Installing the Selinux from the Centos repository:
--------------------------------------------------

sudo yum install -y http://mirror.centos.org/centos/7/extras/x86_64/Packages/**Add_current_container-selinux_package_here**

sudo yum install -y http://mirror.centos.org/centos/7/extras/x86_64/Packages/container-selinux-2.107-3.el7.noarch.rpm

rpm -Va --nofiles --nodigest

Playbook execution for the docker-installation role
---------------------------------------------------

ansible-playbook install-docker.yml
