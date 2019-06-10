# Ansible ELK Playbook for Ubuntu 18.04.2 LTS (Bionic Beaver)
#This playbook is for setting up version 5.x of the ELK Stack on a remote server 
# Instructions

install java 11 before for Ubuntu 18.04.2 LTS (Bionic Beaver)

sudo add-apt-repository ppa:linuxuprising/java

sudo apt update

sudo apt install oracle-java11-installer

sudo apt install oracle-java11-set-default

java -version

----------------------------------------

# into the directory, and run:

sudo ansible-playbook -i hosts site.yml


# to connect to kibana

 http://localhost:5601

https://github.com/charles1964/jupiter.git
