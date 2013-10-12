mysql_secure_installation_silent
================================

This is non-interactive version of mysql_secure_installation script. 

It does not ask any questions (assumes most secure options), generates random password (by calling uuidgen, which I assume to present in modern distros) and saves it to /root/.my.cnf 

This script is based on mysql_secure_installation script included with MySQL itself. 

You can review the changes by calling 
  diff mysql_secure_installation_silent /usr/bin/mysql_secure_installation


