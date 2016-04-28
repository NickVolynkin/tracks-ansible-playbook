Ansible playbook for installing the [Tracks](http://www.getontracks.org) web application.

It installs and configures:

* Tracks
* MySQL as the database
* Nginx as the webserver

Run this to obtain required roles:

    ansible-galaxy install -r requirements.yml -p roles --force -n
 

