# ansible-helpers
Some ansible helpers, that may or may not be usefull to other people

# Usage

I assume that you have an ssh-enabled server somewhere on the web, and you
can login to it via ssh.

Playbook: initial-setup.yaml will:

* Install a user (by default called provision) that will be used for
  provisioning the server from now on
* Will do some very basic hardening of the server:

  * Disable ssh password logins
  * Enable ufw firewall


Roles:
* amend hosts file
* ``ansible-playbook -i hosts-test -l test initial-setup.yaml -u jbzdak -kK``

