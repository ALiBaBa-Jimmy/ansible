# ZephonCloud ansible-playbook

## Dependency

You need to be able to ssh to target host as `root` user, or `admin` user with
*NOPASSWD* sudo access.

## Example Usage

```
ansible-playbook site.yml -i inventory/hosts -l cuda8 --list-host
ansible-playbook site.yml -i inventory/hosts -l cuda8 -v
```

