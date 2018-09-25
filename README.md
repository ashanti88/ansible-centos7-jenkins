This Ansible role is created to install Jenkins on an CentOS 7 server. It installs nginx to setup an reverse proxy on port 80. It also installs the following tools commonly used in combination with Jenkins and PHP development:

- GIT
- php-fpm
- Docker
- Composer

The password to login is shown in the last step. 

# How to run

Edit the data in `hosts` and run:

`ansible-playbook jenkins.yml -i hosts`

# Using vagrant

`vagrant up`

or

`vagrant up --provision`
