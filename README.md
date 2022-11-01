This is a Node/Mongo development enviroment as a beginner project.

Description: I created a basic development enviroment that uses Vagrant to deploy and Ansible to configure/provision two local virtual machines that will host a node api and a mongo database respectively. The node api contains routes and functions for a student database and the database will house that student information.

Dependencies:
1. Requires Vagrant and VirtualBox/VMWare to create and manage virtual machines.
2. Requires Ansible to configure the virtual machines. Mac and Linux natively, however Windows Users will require a different method to install Ansible, for example WSL. 

How to install and run the project:
1. Fork this repository
2. Clone the forked repository
3. Start the create the virtual machines using "vagrant up" in your terminal
4. Go to nology.training/cicd to view the webpage