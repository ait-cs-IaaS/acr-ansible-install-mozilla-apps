# Ansible-Role: acr-ansible-install-mozilla-apps

AIT-CyberRange: Installs mozilla apps via apt packages


## Requirements

- Debian or Ubuntu 

## Role Variables

```yaml
mozilla_apps:
  - thunderbird
  - firefox
```

## Example Playbook

```yaml
- hosts: all
  roles:
    - role: acr-ansible-install-mozilla-apps
      vars:
        mozilla_apps:
          - thunderbird
          - firefox

```

## License

GPL-3.0

## Author

- Lenhard Reuter