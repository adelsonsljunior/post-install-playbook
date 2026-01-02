# post-install-playbook

Prepare o ambiente
~~~sh
sudo apt install git ansible -y
~~~

Clone o repositório
~~~sh
git clone github.com/adelsonsljunior/post-install-playbook
~~~

Aplique o Playbook
~~~sh
ansible-playbook playbooks/zorin.yaml --ask-become-pass
~~~
