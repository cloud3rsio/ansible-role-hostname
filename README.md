cloud3rsio.hostname
=========

Set hostname.

Installation
------------

```bash
$ ansible-galaxy install cloud3rsio.hostname
```

Requirements
------------

Nothing.

Role Variables
--------------

| Key | Default Value | Type |
| ------------- | ------------- | ------------- |
| `hostname` | `localhost` | String |

Dependencies
------------

Nothing.

Example Playbook
----------------

```yaml
- hosts: all
  roles:
    - role: cloud3rsio.hostname
      hostname: hostname.cloud3rs.io
```

License
-------

[MIT](LICENSE)

Author Information
------------------

- youyo
