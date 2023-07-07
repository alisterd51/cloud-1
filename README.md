# Cloud-1

```bash
# create roles/common/files/.env file

# update /etc/hosts
# update production (for example: replace node1 by anclarma.fr)

# if we need a sudo password: --ask-become-pass
# if we need other user: --user=ubuntu

ansible webservers -i production -m ping

ansible-playbook -i production site.yml
```
