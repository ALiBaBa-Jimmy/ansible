# users
=========

Set up user accounts, sudoers and ssh public keys.

Requirements
------------

sudo access.

Role Variables
--------------

User public keys are defined in defaults/main.yml, user suppose to override
`users` and `sudoers` only from `group_vars` and/or `host_vars`.
