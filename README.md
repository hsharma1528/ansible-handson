# ansible-handson
Ansible playbooks for setting up loadbalancer, webserver and database server
use vagrantfile to spinup your lab environment.
Playbooks:
  control.yml uses control role roles\control 
  database.yml uses mysql role roles\mysql
  loadbalancer.yml uses nginx role roles\nginx
  webserver.yml uses apache2 role\apache2
demo_app is demo application which will be deployed
group_vars used for defining varaiables

  
