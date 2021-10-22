rnp-tools-ansibleroles-sethostname
=========

Ansible Role - Set Hostname

![Overwiew](https://gitlab.com/rachuna-net.pl/tools/ansibleroles/rnp-tools-ansibleroles-sethostname/-/raw/develop/docs/setHostname.png)

Role Variables
--------------

Defaults role values:
```
input_role_hostname_fqdn:    "{{ inventory_hostname }}"
```

Role vars
```
```

Example Playbook
----------------

```
- hosts: localhost
  remote_user: root
  become: yes
  tasks:
  - include_role:
      name: rnp-tools-ansible-roles-sethostname
    vars:
      input_role_hostname_fqdn:    "{{ inventory_hostname }}"
```

License
-------

BSD 3-Clause

Author Information
------------------

### Maciej Rachuna
SysOps/DevOps