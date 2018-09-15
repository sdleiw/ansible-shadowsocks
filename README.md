Shadowsocks
========

extends [repo](https://github.com/jlund/ansible-shadowsocks) for multi-ports

Role Variables
--------------

Gathered facts are used to determine the default IPv4 address that the server should bind to. Make sure that gather_facts is not set to "no" in your playbook.

**Variables that can be set by the user (or another role)**

> shadowsocks_local_port: The local port that Shadowsocks should listen on. Set to "1080" by default.

> shadowsocks_timeout: Timeout (in seconds). Set to "600" by default.

> shadowsocks_encryption_method: The encryption method that will be used to secure the connection. A list of options can be found in the [Shadowsocks documentation](https://github.com/clowwindy/shadowsocks). The default for this role is "aes-256-cfb".
