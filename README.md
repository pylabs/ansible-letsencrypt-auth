letsencrypt auth
================

Getting letsencrypt certs automatically with nginx frontend

Role Variables
--------------

```yaml
letsencrypt_auth_domain_name: YOUR_DOMAIN_NAME
```

Dependencies
------------

- pylabs.letsencrypt

Example Playbook
----------------

```yaml
  roles:
    - role: pylabs.letsencrypt-auth
  vars:
    letsencrypt_auth_domain_name: www.example.com
```

License
-------

MIT

Author Information
------------------

William Wu
