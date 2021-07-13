Ansible Postgresql
=========

Requirements
------------
no requirements

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:
```yaml
- hosts: servers
  roles:
     - role: ansible-postgres
       postgres_version: 13
       pg_hba_user_options:
       - contype: host
         users: all
         source: 127.0.0.1/32
         databases: all
         method: md5
```

License
-------

MIT

## Devel
for devel use
https://github.com/ansible-community/molecule-libvirt

requirements for testings
KVM host
```
libvirt-python
```
