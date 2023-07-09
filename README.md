# gobackup-ansible

A simple Ansible playbook to deploy Gobackup.

## How to use it

**1-** Add your gobackup config file under configs directory.

**2-** Add your hosts to *inventory* file or use your own inventory file.

**3-** Change variables in *vars.yaml* file.

**4-** Run the playbook with:
```
ansible-playbook -i inventory main.yaml
```
