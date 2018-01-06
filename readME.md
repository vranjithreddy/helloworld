1. Launched and configured Ec2 instance.
2. Assigned AutoScaling Group and setUp cloudWatch Alarm
3. Using Ansible for Configuration Management
4. Ansible playbook written in YAML contains the tasks to install 'apache module' on host servers
5. main.yml is main file where roles, tasks, templates are defined
6. webserver.yml contains info about hosts and roles of apache webserver are defined
7. helloworld.html contains sample helloworld file

execute 'ansible-playbook webserver.yml -i hosts' to finish the tasks.

it then serves to static web page that is https port
