# do-ansible-hugo

clone to /etc/ansible
add your Digital Ocean token to keys/

```$cd /etc/ansible```
```$source ./init.sh PROD```
```$ansible-playbook playbooks/play-blog.yaml```

result:
running droplet in Digital Ocean with hugo + go installed


