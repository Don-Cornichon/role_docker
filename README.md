Role Name
=========

Install Docker-CE

Requirements
------------

Centos 7 usable

Role Variables
--------------

docker_state: "present" for installation and "absent" for desinstallation
Dependencies
------------


Example Playbook
----------------

	- name: Ensure that docker is well installed
          hosts: app
          roles:
            - { role: role_docker, docker_state: "present" }
            - { role: role_docker, docker_state: "absent" }

License
-------

BSD

Author Information
------------------
C'est Nous.
