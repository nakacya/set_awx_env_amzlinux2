# set_awx_env_amzlinux2

Ansible AWX Enviroment Setting For Amazon Web Service Amazon Linux 2

Requirement:

instance: t3.small or more

Disk:Over 10GB


How to use

1: Change inventory

   "ansible_host=Your_AWX_host"


2: run to ansible


    ansible -i inventory　set_awx_env_amzlinux2yml
