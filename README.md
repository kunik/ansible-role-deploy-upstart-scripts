Ansible deploy-environment
==========================

This role generates upstart scripts and restarts application.

For more information about deployment setup see this [overview](https://github.com/kunik/ansible-role-deploy-metadata/blob/master/USAGE.md)

Requirements
------------

No

Role Variables
--------------

```
deploy_upstart_scripts:
  respawn_limit: '5 10'
  command: 'node_modules/.bin/coffee index.coffee'
  param_name: PORT
  param_values:
    - 8080
```

Dependencies
------------

No

License
-------

BSD
