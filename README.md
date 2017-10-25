Apigee Server Restart
=========

This role restarts a server. This is typically useful after making changes that take effect after a server restart. 

Requirements
------------

N/A

Role Variables
--------------

| Variable | Default | Description |
|---|---|---|
| start_check_delay: | 15 | Delay in seconds to wait before checking server status |
| server_restart_timeout | 60 | Timeout in seconds that the server should have restarted by  |
    

Dependencies
------------

wait_for and shell modules

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: apigee-server-restart }

License
-------

BSD

Author Information
------------------

Carlos Frias