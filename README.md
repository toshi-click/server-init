# server-init
```shell
ansible-galaxy install -r requirements.yml -p roles --force
ansible-playbook -D -i hosts/all.yml -k all.yml -l localhost

```
