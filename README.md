# ansible-role-backup-target-user-home

Create a drop target for user home directories. For each user home a user with the same name
will be created. Public key authentication is being used for rsync authentication.
See [ansible-backup](https://github.com/andreasbehnke/ansible-backup) for details.
Use in combination with role ansible-role-backup-source-user-home which should be
applied to the users machine.
