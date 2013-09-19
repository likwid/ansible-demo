ansible-demo
============

### Quick Demonstration of Ansible

Slide deck
https://speakerdeck.com/likwid/ansible-radically-simple-infrastructure-management

In this demo we are going to:

  1. Create a server in Amazon AWS
  2. Provision a server with nginx, Ruby, Unicorn and Sinatra
  3. Deploy Sinatra application
  

### How to run:

vagrant up (make note of the ssh port that gets rebound)
in devops/development inventory file, change the port to the aforementioned vagrant ssh port

from a shell:
ansible-playbook devops/site.yml -i devops/development

This should provision the vagrant box


  
