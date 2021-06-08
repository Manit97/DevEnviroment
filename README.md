# DevEnviroment Linux/Bash Commands

## After Vagrantfile has been created and the code has been entered:-
- 'config.vm.network "private_network", ip: "192.168.10.100" ' in the Vagrantfile
1) Run 'vagrant up' to get the virtual enviroment started
2) Run 'vagrant status' to check if the vagrant is running
3) Run 'vagrant destroy' if you want to destroy the session
4) Run 'vagrant suspend' if you want to stop it from running and save it automativally
5) Run 'vagrant ssh' to enter the VM and use the Ubuntu System

## After Entering the VM using the previous steps:-
- 'uanme' to check the Machine name to ensure you are in the VM
1) 'sudo apt-get update -y' in VM to update Linux
2) 'sudo apt-get upgrade-y' in VM to upgrade Linux
3) 'sudo apt-get install nginx' in VM to install NGINX (web server)
4) 'exit' to leave the VM and come back to your machine
