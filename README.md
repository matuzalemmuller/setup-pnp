## Description

Ansible playbook to customize my Pinebook Pro running Debian 12 XFCE. Based on [`setup-workstation`](https://github.com/matuzalemmuller/setup-workstation).

**_Use it at your own risk. Not open for pull requests or issues._**

```
./wrapper-script.sh

# or install ansible requirements and run
ansible-playbook playbook/setup-pnp.yml --ask-become-pass

# to run a specific tag (may need to set first time install)
ansible-playbook playbook/setup-pnp.yml --ask-become-pass -t <tag>
```
