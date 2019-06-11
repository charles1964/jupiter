Ansible netdara Playbook for Ubuntu 18.04.2 LTS (Bionic Beaver)
  
#This playbook is for setting up version 5.x of the LAMP Stack on a remote server

Instructions

into the directory, and run:

sudo ansible-playbook -i hosts site.yml
---------------------------------------------
to connect to test apache2

http://localhost

----------------------------------------------
to connect to test php

http://localhost/index.php

----------------------------------------------
to connect to test mariadb

sudo mariadb
[sudo] Mot de passe de charles : 
Welcome to the MariaDB monitor.  Commands end with ; or \g.
Your MariaDB connection id is 60
Server version: 10.1.40-MariaDB-0ubuntu0.18.04.1 Ubuntu 18.04

Copyright (c) 2000, 2018, Oracle, MariaDB Corporation Ab and others.

Type 'help;' or '\h' for help. Type '\c' to clear the current input statement.

MariaDB [(none)]> 
---------------------------------------------

https://github.com/charles1964/jupiter.git
