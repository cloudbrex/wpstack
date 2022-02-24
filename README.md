<<<<<<< HEAD
# ansible-wordpress-ubuntu
=======
# Ansible Ubuntu Wordpress

This Ansible playbook sets up an Ubuntu 20.04 box for super-fast Wordpress hosting.

It includes:

 - Configuring Ubuntu with auto updates
 - Nginx, with page caching to local ram storage
 - phpfpm for PHP
 - MariaDB for a database
 - Redis for object caching
 - Certbot & LetsEncrypt for SSL.

Additionally, it'll:

 - Install a list of Wordpress plugins
 - Install a list of themes, including activating one if you want it to
 - Import a database export from another site

## Pre-requisites

- An Ubuntu 20.04 box
- Ansible

## Installation

1. Run playbooks locally

2. Install the dependent roles and collections: `ansible-galaxy install -r requirements.yml`

3. Run it: `ansible-playbook -become -i inventory setup.yml -b`# ansible-wordpress-ubuntu
>>>>>>> 1608fd5... first commit
