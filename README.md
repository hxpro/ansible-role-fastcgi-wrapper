hxpro.fastcgi-wrapper
=========

FastCGI Wrapper

Role Variables
--------------

    fastcgi_wrapper_port: 9002
    fastcgi_wrapper_user: apache
    fastcgi_wrapper_group: apache


Example Playbook
----------------

    - hosts: servers
      roles:
        - { role: hxpro.fastcgi-wrapper, fastcgi_wrapper_port: 9002 }

License
-------

WTFPL

Author Information
------------------

Matěj Koudelka <matej@hxpro.cz>
