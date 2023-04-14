Role Name
=========

A small role to manage the /etc/motd file of the target system. The role will update the file on each Ansible run, including a timestamp of the run.
The role is a fork of https://github.com/totaldebug/ansible-role-motd

Requirements
------------

None

Role Variables
--------------

`motd_template`: Specifies which template file to use. Default: `motd.js`
`motd_modification`: Should the motd be modified. Default: `true`
`motd_info`: List of additional information to append to the motd file.



Dependencies
------------

None

