# ansible-phpipam

Instructions:

1. copy `ansible_variables.sample.yaml` to `ansible_variables.yaml` and put a *REAL* password
1. edit [inventory.ini](inventory.ini) and add the connection string for your server(s)
1. type:
    * `ansible-galaxy collection install community.mysql` # only once, in your host server
    * `ansible-playbook install_phpipam_php74_offline_v2.yaml`
1. go to http://IP_OF_YOUR_SERVER
1. click on `automatic install`
1. for the mysql user, put `root`
1. for the mysql password, put the one you have on `ansible_variables.yaml`
1. done
