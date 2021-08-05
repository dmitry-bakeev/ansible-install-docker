# Ansible-install-docker

## This ansible playbook makes it easy to install docker and docker-compose on ubuntu server

You need a remote server with a root user for which the ssh key is added

How to run

~~~bash
ansible-playbook -e server_ip=<your-server-ip> -e ssh_private_key_file=<path-to-your-ssh-private-key> setup-docker.yml
~~~
