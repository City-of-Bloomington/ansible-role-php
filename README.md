# PHP
Ansible Role for maintaing PHP on linux servers

## Dependencies
- City-of-Bloomington.linux
- City-of-Bloomington.apache

Example Playbook
----------------

```yml
- hosts: linux-php
  become: yes
  roles:
    - City-of-Bloomington.php
```

Copying and License
-------
This material is copyright 2016 City of Bloomington, Indiana
It is open and licensed under the GNU General Public License (GLP) v3.0 whose full text may be found at:
https://www.gnu.org/licenses/gpl.txt
