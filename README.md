# ansible_library
collection of ansible playbooks mainly for setting up a kubernetes cluster

## preparation
for the scripts to run, the clients need:
* ubuntu installed
* ssh key access for choosen ansible user

create a hosts file for your setup as given in the hosts_example

## start

    ansible-playbook playbooks/main_set_up_cluster.yml  --extra-vars "host=pi_cluster" -v --ask-become-pass