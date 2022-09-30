Ansible roles for configure httpd LB with webserver
Using ansible roles for configure Haproxy and update it's configuration file on each time managed node in host file.

myloadbalancer - this folder is a role contain main file in task folder called as playbook to installing and configure Ha proxy lb with its dependencies This will run from Ansible Controller Node to its target node

haproxy.cfg - This is the file contain in templates of configuration of haproxy. Ansible CN has contain copy of this file and written some extra code inside this using JINJA(It is the Ansible Framework that is provide extra power to ansible)

mywebserver - this folder is a role contain webpage file which show to browser of different servers and main file in task will install webserver to target node and deploy webpage as well start service

setup.yml this is  file called as our main playbook which deploy our task

ansible.cfg file to configure ansible setup credentials
inventory file for host groups 

For any queries feel free to Contact me:
Email: sachin312746@gmail.com
Linkedin: www.linkedin.com/in/sachin-kumar10