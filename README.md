Ansible role: Wordpress CLI
=========

This role installs the WordPress Command Line Interface (WP-CLI) on a target Linux system.

Requirements
------------

None.

Role Variables
--------------

List of variables in ansible-role-wpcli:

```sh
---
wpcli_bin_location: /usr/bin/wp
wpcli_completions_location: /etc/bash_completion.d

```

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
    - devetek.wpcli
```

License
-------

GNU General Public License v3.0 or later

Author Information
------------------

[Nedya Prakasa]. Role created for [dPanel].

[dPanel]: https://cloud.terpusat.com/
[Nedya Prakasa]: https://github.com/prakasa1904
[devetek]: https://github.com/devetek