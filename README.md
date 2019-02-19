# Preparations

1. You should have ansible installed on your local machine. Refer to [Ansible official documentation](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html) to find out how.
2. These playbooks are made for Ubuntu 16.04+ & Debian 8+.


# How to use

1. Edit `*.sample` files to meet your needs and save a copy without the `.sample` extension.
2. Run the following commands in sequence:
    * `ansible-playbook -i ./hosts update_kernel.yml`
    * `ansible-playbook -i ./hosts enable_bbr.yml`
    * `ansible-playbook -i ./hosts install_services.yml`
