Ansible Elixir role.
=========

[![Build Status](https://travis-ci.org/spitfast/ansible-elixir-role.svg?branch=master)](https://travis-ci.org/spitfast/ansible-elixir-role)

An ansible role for elixir installation.

Requirements
------------

None.

Role Variables
--------------

```yaml
---

elixir_erlang_solution_package: erlang-solutions_1.0_all.deb
```

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
     - { role: spitfast.elixir}
```

License
-------

MIT

Author Information
------------------

[Gordon Shumway](https://github.com/spitfast/)
