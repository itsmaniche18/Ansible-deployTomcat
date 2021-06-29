# Ansible

Pass module as choice parameter,release | props as string parameter.

Run Ansible with
/usr/bin/ansible-playbook -i /root/server/hosts /root/server/deploy.yml --extra-vars='release=$release module=$module props=$props' 
