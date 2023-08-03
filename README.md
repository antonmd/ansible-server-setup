## Usage:

This is a repo for initial setup your linux server using Ansible. An Ansible playbook include the follow tasks:
1. Update and upgrade packages
2. Create a new sudo user with public key, which have access to ssh and can run sudo command without password
3. Disable ssh authorization with password
4. Close ssh for root login
5. Change ssh port

You can setup your username, path to the public key and ssh port in vars.yml file.