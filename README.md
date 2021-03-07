# Personal Ansible Playbooks

Cannot be run directly from Windows, but can be run from WSL.

Example run command:

    ansible-playbook /mnt/e/Code/ansible-personal/playbooks/setup-docker.yaml -i "<hostname>," --ask-become-pass
    
By passing a single hostname with a tailing comma, Ansible treats it as a
single item list and works.

The "Become" passwork is the passwork used on the remote machine to run sudo
commands.
