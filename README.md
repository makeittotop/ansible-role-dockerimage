Role Name
=========

Ansible role to deploy a simple flask application in a docker container

Role Variables
--------------

app_name: name of the docker container
image_name: image you wish to install
app_port: port to expose to host


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: ,  app_name: foo, app_port: 80 }

License
-------

MIT

Author Information
------------------

Abhishek Pareek
hello@abhishekpareek.io
https://www.abhishekpareek.me
# ansible-role-dockerimage
