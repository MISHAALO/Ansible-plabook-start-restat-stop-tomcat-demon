cp -r inventories/* /etc/ansible/

cp -r roles/* /etc/ansible/roles 

ansible-playbook main.yml -e "HOST=host" -e "state=started" 
