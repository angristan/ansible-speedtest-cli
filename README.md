# Ansible role for speedtest

This is a simple role for Debian-based machines that will install the [official speedtest CLI](https://www.speedtest.net/apps/cli) (not the one from PIP).

## Sample playbook

```yaml
---

- hosts: myhost
  roles:
    - {role: speedtest, tags: speedtest}
```
