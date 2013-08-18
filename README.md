Deployment of fresh Ubuntu / Linux Mint development
==================================================

Ansible playbook that will install and configure a
fresh install of Ubuntu with all the required packages
I consider necessary to be productive developing in
python and java

To run the script;
	* Download and install ansible
	* ansible-playbook -i hosts --connection=local dev_deploy.yml
