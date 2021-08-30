Ansible Duo Update Role
=======================

Role to update packages in Linux.

Supported OS Families
---------------------

- Ubuntu (tested)
- Arch Linux (tested)
- Redhat (tested)

Role Variables
--------------

Available variables are listed below, the default values are in [defaults/main.yml](defaults/main.yml):
```
update_reboot_system: whether to reboot system after update, default is no (bool)
```

Dependencies
------------

None

Example Playbook
----------------

Here is an example playbook:
```
- hosts: all

  roles:
  - budimanjojo.update
```

License
-------

MIT License
