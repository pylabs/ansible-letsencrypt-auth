letsencrypt_auth
================

Getting letsencrypt certs automatically with nginx frontend

Role Variables
--------------

```yaml
letsencrypt_auth_domain_names:
  - FIRST_DOMAIN_NAME
  - SECOND_DOMAIN_NAME
```

Dependencies
------------

- pylabs.letsencrypt

Example Playbook
----------------

```yaml
  roles:
    - role: pylabs.letsencrypt_auth
  vars:
    letsencrypt_auth_domain_names:
      - www.example.com
      - www.example.org
```

License
-------

MIT

Author Information
------------------

William Wu
