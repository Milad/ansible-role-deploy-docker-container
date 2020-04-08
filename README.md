ansible-role-deploy-docker-container
=========
Pulls an image from a docker registry, deploys it to a container then prunes images.

Requirements
------------

Ansible user needs to be in docker group, so it can execute docker commands without sudo.

Role Variables
--------------

Check the file [defaults/main.yml](./defaults/main.yml) for details.

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

MIT

Author Information
------------------

Milad Kawas. @miladkawas
