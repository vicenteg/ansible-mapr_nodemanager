Role Name
=========

Install mapr-nodemanager.

Requirements
------------

Role Variables
--------------

```
proxy_env:
  http_proxy: http://1.2.3.4:3128
  https_proxy: https://1.2.3.4:3128
```

Dependencies
------------

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: nodemanager
      roles:
         - mapr-nodemanager

License
-------

MIT

Author Information
------------------

vgonzalez@mapr.com