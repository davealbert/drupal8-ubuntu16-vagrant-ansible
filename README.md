Drupal 8 | Vagrant | Ansible | Ubuntu 16.04 - Dev Enviornment
===


This is a Vagrantfile with an Ansible provisioner to create a Drupal 8 Development enviornment.

It's a little rough around the edges style wise, but seems to work consistantly.


Tested On:
---
Drupal:   8 
Vagrant:  1.8.6
Ansible:  2.2.0.0 
Ubuntu:   16.04


Getting Started:
---
 - vagrant up
 - visit http://drupaltest.dev/


Settings:
---

/etc/hosts
   drupaltest.dev  192.168.33.10

url: http://drupaltest.dev/


TODO:
---

  - Change Ansible playbook to use roles
  - Clean up some less than optimal code in Ansible 
  - Adjust the role so it will work with remote providers (DO,AWS)

