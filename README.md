Role Name
=========

Installs PowerShell and Invoke-Obfuscation on Linux.

Requirements
------------

None

Role Variables
--------------

io_git_location: '/opt'

Dependencies
------------

leesoh.git

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - leesoh.invoke-obfuscation
```

License
-------

BSD-3

Author Information
------------------

GitHub: https://github.com/danielbohannon/Invoke-Obfuscation