# Example Ansible

```
ansible-playbook -i staging.yaml main.yaml --private-key test-pair.pem
```

## Only tags

```
ansible-playbook -i staging.yaml main.yaml --private-key test-pair.pem --tags install_php
```