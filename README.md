Role Name
=========

Роль для установки filebeat на хостах с ОС: Debian, Ubuntu, CentOS, RHEL.

Requirements
------------

Поддерживаются только ОС семейств debian и EL.

Role Variables
--------------

|Variable name        |	Default	    | Description                                                             |
| :-:                 | :-:         | :-:                                                                     |
|filebeat_version     |	"7.15.2"	| Параметр, который определяет какой версии elasticsearch будет установлен|

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

    -hosts: all
     roles:
       - { role: filebeat-role }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
