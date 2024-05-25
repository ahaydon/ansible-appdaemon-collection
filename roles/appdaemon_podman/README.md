Ansible Role: AppDaemon
=========

An Ansible role for deploying AppDaemon as a Podman container managed by systemd.

Requirements
------------

None.

Role Variables
--------------

```yaml
appdaemon_podman_name: appdaemon
appdaemon_podman_user: appdaemon
appdaemon_podman_home: /home/appdaemon
appdaemon_podman_version: latest
```

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- name: Deploy AppDaemon
  hosts: servers
  roles:
    - role: appdaemon_podman
      appdaemon_podman_home: /home/appdaemon
```

License
-------

MIT

Author Information
------------------

This role was created by [Adam Haydon](https://github.com/ahaydon)
