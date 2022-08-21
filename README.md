DEVSYS-15.Lighthouse
=========

Downdload and install VK Lighthouse

Requirements
------------
```
  - src: git@github.com:AlexeySetevoi/ansible-clickhouse.git
    scm: git
    version: "1.11.0"
    name: my_clickhouse 
```

Role Variables
--------------
```
 install_Lighthouse_dir: '/var/www/html/'
 Lighthouse_url: "https://github.com/VKCOM/lighthouse/archive/refs/heads/master.zip"
```
Dependencies
------------

NO Dependencies

Example Playbook
----------------

```
- name: Install Lighthouse
  hosts: 
    - Lighthouse
  roles:
    - DEVSYS-15.Lighthouse
  tags: 
      - "install Lighthouse"
```
License
-------

BSD

Author Information
------------------
DEVSYS-15

