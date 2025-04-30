# nginx_on_rhel_by_ansible_using_roles
Basic repo for configuring an nginx server on RHEL using the ansible roles

Make sure to edit the variables and the IPs for your use case.

After pulling the repo, just run:

ansible-playbook -i hosts webserver.yaml
