# Rabobank Ansible Task

As we know Ansible is a configuration management tool which can be used to manage the infrastructure. 


As required I have created an Ansible role for installing nginx and notify start nginx task. We can also stop the nginx service by creating another yaml inside either in tasks or handlers depending on the requirement.

I have also tested and verified the solution :)


ansible-playbook nginx.yaml -- to run the playbook again the default hosts file

ansible-playbook nginx.yaml --check -> To perform dry-run. 

ansible-playbook -i {inventory file path} nginx.yaml -> to run the playbook when running against a different invenoty file.
