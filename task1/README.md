### creating user
```bash
ansible-playbook -i inventory create/playbook.yml --extra-vars "new_username=aral123"
```
### deleting
```bash
ansible-playbook -i inventory delete/playbook.yml --extra-vars "delete_username=aral"
```
