# lutris-fedora

![[Lint Code Base](https://github.com/chadhellyea/lutris-fedora/workflows/Lint%20Code%20Base/badge.svg)](https://github.com/chadhellyea/lutris-fedora/actions)

This is a quick ansible role to install lutris on fedora with RPM fusion for nvidia drivers with all of the prerequisites like vulkan. This `SHOULD` get you everything you need to run games in the Battlenet installer according to documentation here: <https://github.com/lutris/docs/blob/master/Battle.Net.md>

## Prerequisites

Install ansible:

```bash
sudo dnf install ansible -y
```

### Install (defaults to Fedora 33)

```bash
ansible-playbook provision.yml
```

### Install and specify Fedora Version

Example:

```bash
ansible-playbook provision.yml -e fedora_version=32
```

TODO:
Add molecule testing

Anyone who would like to contribute please submit a PR Thanks!
