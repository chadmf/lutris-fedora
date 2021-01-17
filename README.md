# lutris-fedora
This is a quick ansible role to install lutris on fedora with RPM fusion for nvidia drivers with all of the prerequisites like vulkan. This `SHOULD` get you everything you need to run games in the Battle.net installer according to documentation here: https://github.com/lutris/docs/blob/master/Battle.Net.md

## Prerequisites

Install ansible:

```bash
sudo dnf install ansible -y
```

### Install

```bash
ansible-playbook provision.yml
```

Example:

```bash
ansible-playbook provision.yml -e fedora_version=32
```

TODO:
Add molecule testing

Anyone who would like to contribute please submit a PR Thanks!

