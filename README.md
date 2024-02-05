To run this project follow the below steps.
1. Clone the repo
2. Run the Vagrantfile by using the cmd "vagrant up" and to stop the VMs run "vagrant halt".
3. Run "vagrant ssh ansible-control" to access the VM. In case if it ask for username or password "vagrant" 
3. To connect with all the machine run keygen cmd and copy the ssh file to all VM.
4. Install ansible to the ansible-control VM by running cmd "apt install ansible -y"
5. Go to Ansible-files and run "ansible-playbook -i dev -K playbook.yml".