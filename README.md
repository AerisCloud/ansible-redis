Redis
======

This role installs and configures Redis on your server.

Configuration
--------------

* `redis_port`: Accept connections on the specified port, default is `6379`.

Tests
-----

You can easily test this role with [ansible-role-test](https://github.com/AerisCloud/ansible-role-test).

```bash
ansible-role-test . --skip-tags="firewall"
```

See also
---------

* [Redis](http://redis.io/)
