ansible-playground
==================

playing out with ansible (docker and aws)

ssh-add ~/.ssh xxxxxxxx.pem

ansible -m ping -i hosts -u ubuntu webservers
ansible-playbook -i hosts -u ubuntu deploy.yml
