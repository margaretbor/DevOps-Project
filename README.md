# DevOps-Project
Vagrant, Ansible, Docker, Git/github and Jenkins. Ready to deploy infrastructure.

These files can be used for provisioning DevOps Environment using:

- Vagrant for infrastructure provisioning

- Ansible for configuration management

- Git for version control

- GitHub as a central repository.

- Jenkins as a continuous integration, delivery and deployment tool. For creating   Jenkins playbook used information from: https://jenkins.io/doc/pipeline/tour/getting-started/


  Host system must have installed:

    Virtualbox (https://www.virtualbox.org/manual/ch01.html)
    Vagrant (https://www.vagrantup.com/intro/getting-started/install.html)
    Ansible (https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)

  To start provisioning:

 - Create a project directory
 - Go into the project directory
 - Clone git repository into this directory
 - Run a command as a regular user: $ vagrant up
 - Wait until vagrant finished creating virtual machines (VM)
 - To check created VMs: $ vagrant status
 - ssh into webserver: $ vagrant ssh web 
 - ssh into database server: $ vagrant ssh db
 - ssh into client server: $ vagrant ssh client
 - ssh into jenkins server: $ vagrant ssh jenkins
  
  User/password for all the VMs: vagrant/vagrant 

In this project used:
https://github.com/kenjis/ci-phpunit-test
https://github.com/abohmeed/swift
   
