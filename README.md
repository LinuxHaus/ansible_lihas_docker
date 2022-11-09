# ansible_lihas_coker
Install docker-ce ivia extrepo and cocker-compose via pip+virtualenv

## Requirements

To run solo:
```
ansible-galaxy install -r requirements.yml
ansible-playbook -i localhost, docker.yml
```

## Dependencies

## Example Playbook

```
---
- hosts: '*'
  roles:
    - lihas_docker
...
```
## Tags

## Variables

## Variables example
```
```
