# Lab test
Test Lab
1. Add test server's hostname to file inventory
   cat /etc/ansible/hosts
   [ubuntu]
   test-server
2. Check resolve test server's hostname or add line with server to /etc/hosts
cat /etc/hosts
10.0.0.2 test-server
3. Create folder for this project on another server with ansible and clone files from this project to there
4. Set statis IP for test server
ansible-playbook  network.yml
5. Set nginx
ansible-playbook nginx.yml
6. Set Postgres
ansible-playbook postgres.yml
7. Copy python script 
ansible-playbook cp_script.yml

