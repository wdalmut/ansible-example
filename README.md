# Example Ansible

```
ansible-playbook -i staging.yaml main.yaml --private-key test-pair.pem
```

## Only tags

```
ansible-playbook -i staging.yaml main.yaml --private-key test-pair.pem --tags install_php
```

## With variables

```
ansible-playbook -i staging.yaml main.yaml --private-key test-pair.pem --tags deploy_dockerapp -e app_version=2.4
```