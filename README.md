ECGALAXY vault4summon role
========

Ansible role which installs [vault4summon](https://github.com/bdhave/vault4summon) and configures it as a Summon provider.

Requirements
------------

None.

Role Variables
--------------

See defaults/main.yml.

Dependencies
------------

* ecgalaxy.common_packages
* optional: ecgalaxy.summon

Example Playbook
----------------

    - hosts: all
      roles:
        - ecgalaxy.vault4summon

License
-------

Copyright the European Union 2022.

Licensed under the EUPL-1.2 or later.

Author Information
------------------

ECGALAXY team.
