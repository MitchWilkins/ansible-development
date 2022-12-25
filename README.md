# ansible-development
A IaaC model using Vagrant and Ansible to help create a virtual development environment.

## Vagrant
Helps setup the OS and handles provisioning the VM.

## Ansible
Helps setup the development environment after VM setup. It installs dependancies such as Docker, Nodejs, NPM, Git, and Dotnet.

## Instructions

Once Vagrant and Ansible are installed on your machine, run the following command:
```
vagrant up
```

Then you can use the following to get started with SSH credentials:
```
vagrant ssh
ip a
```
