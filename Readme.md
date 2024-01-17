## Deploying the Task1 from https://github.com/rashik707/HAZESOFT-T1.git to a VM in cloud.

## Installing Ansible from its official website

## Generating key from personal machine and authorizing that key in VM so that we can connect without requiring authenticatication.

## Checking the connection between personal machine & VM by hitting following command
ansible all -m ping -u root

## Execute the Ansible playbook by using the following command:
ansible-playbook task.yml

## To view the output from browser
http://54.92.194.159:9000/site/index.html
