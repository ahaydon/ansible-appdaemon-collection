# Ansible Collection for AppDaemon

This collection includes roles to deploy AppDaemon with Podman and systemd.

## Installation

The collection can be installed with `ansible-galaxy`:

```sh
ansible-galaxy collection install git+https://github.com/ahaydon/ansible-appdaemon-collection.git
```

## Usage

```yaml
- role: ahaydon.appdaemon.appdaemon_podman
  appdaemon_podman_home: /home/appdaemon
```

## License

This Ansible collection is [MIT licensed](LICENSE)
