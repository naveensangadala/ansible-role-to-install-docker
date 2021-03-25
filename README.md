Ansible-Role-to-Install-Docker
==============================

Ansible role to install docker on Linux servers 

Pre-requisites:
--------------

execute the below commands where ever you install docker either it on localhost or target host:

sudo yum install -y http://mirror.centos.org/centos/7/extras/x86_64/Packages/**Add_current_container-selinux_package_here**

sudo yum install -y http://mirror.centos.org/centos/7/extras/x86_64/Packages/container-selinux-2.107-3.el7.noarch.rpm

rpm -Va --nofiles --nodigest

Execute the below ansible role to install docker 
-------------------------------------------------

ansible-playbook install-docker.yml
