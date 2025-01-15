Vector
=========

This role can install and configure Vector for Clickhouse on Ubuntu

Role Variables
--------------

| vars | Description | Value | Location |
|------|------------|---|---|
| vector_version | Vector version to install | 0.43.1 | defaults/main.yml |


Example Playbook
----------------

```yml
    - name: Install Vector
      hosts: servers
      roles:
        - vector
```

License
-------

MIT

Author Information
------------------

Alexander Rogatnev
rai68@yandex.ru
