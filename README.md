### README: ansible-postgresql94-bdr

Features:
- supported distributions: Redhat/CentOS version 5, 6 or 7.
- supported PostgreSQL versions: 9.4
- allows specify hosts and demo database which would be created after install.
- ability to determine a set of postgresql.conf parameters and absense postgresql.conf template. Template is not used due to the fact that the postgresql.conf differs from version to version on a set of parameters.
- ability to specify another cluster directory.

Known issues:

Todo:

How-to use:
- download repo with git clone;
- cd into role directory;
- change "hosts:" and other variables in defaults/main.yml;
- start ansible-playbook with role.yml and your inventory file.
```
ansible-playbook -i /etc/ansible/staging role.yml
```
