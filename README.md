Ansible-private-cloud
=====================

Requirements
------------

This playbook requires Ansible 1.4 or higher. It has been tested for Debian 7 system.

Another requirements:
- Users role from [mivok/ansible-users](https://github.com/mivok/ansible-users)
- OpenSSH role from [Ansibles/openssh](https://github.com/Ansibles/openssh)
- NodeJS role from [AnsibleShipyard/ansible-nodejs](https://github.com/AnsibleShipyard/ansible-nodejs)
- CouchDB role from [guillaumededrie/ansible-role-couchdb](https://github.com/guillaumededrie/ansible-role-couchdb)


Installation
------------

Run:
```
$ ansible-galaxy install -r galaxy.yml -p ./roles
```

Execution using Vagrant
-----------------------

Run:
```
$ vagrant run
```


Licence
-------

GNU GPL v3
