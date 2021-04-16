# server-init
```shell
sudo apt install ansible
git clone https://github.com/toshi-click/server-init.git
cd server-init
ansible-galaxy install -r requirements.yml -p roles --force
ansible-playbook -D -i hosts/all.yml -k all.yml  -e ansible_connection=local -l localhost

```
