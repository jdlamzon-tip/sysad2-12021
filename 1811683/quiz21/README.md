# Quiz 2.1: Ansible

## 1. How to create an Ansible Configuration.

	- To verify that Ansible is installed: `ansible --version`.

	- If you dont have Ansible, install Ansible according on what type of package of your Linux.

	- After installing Ansible, you can create an Ansible configuration file by `ansible.cfg`.


## 2. How to create an Ansible Inventory.

	- Check the directory of the configuration and the name of the inventory file in your ansible configuration file.

	- Create an inventory file by `vim (inventory name)`.

	- Name the hostname of your machines by this `[hostname]`.

	- Check the IP addresses of your machines and put it inside the inventory file.

	- Save the inventory file pressing ESC and type `:wq!`.


## 3. How to create an Ad-hoc Ansible Command with setup and shell module.

	- Using the command `ansible (hostname) -m setup (module or file)`, it will do the setup for the hostname/s included in the program.

	- Using the command `ansible (hostname) -m shell -a (linux commands)`, it will run a bash scripts.
