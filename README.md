Powershell
=========

This role installs powershell on Linux. It is based on the [installation instructions by Microsoft](https://docs.microsoft.com/nl-nl/powershell/scripting/install/installing-powershell-core-on-linux?view=powershell-7).

Requirements
------------

The following platforms are currently supported:

- Debian 8
- Debian 9
- Debian 10

Role Variables
--------------

For normal use, no variables are required. For advanced use, see `defaults/main.yml`.

Example Playbook
----------------

Example usage:

```yaml
- hosts: servers
  roles:
    - { role: powershell }
```

Development
-----------

Checkout the repository and run the following to test the role:

```bash
molecule test
```

See molecule documentation for more information.
