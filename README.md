Role Name
=========

Sets up PM2 as a systemd service

Requirements
------------

Requires access to the root account.

Role Variables
--------------

appdir: The app directory
appname: The app name
userweb: The service account which will run the app


Dependencies
------------

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
    roles:
      - {
          role: oscbco.systemd_pm2_service,
          userweb: "app-web",
          appname: "app",
          appdir: "/srv/app"
        }

License
-------

MIT

Author Information
------------------
website: oscbco.me