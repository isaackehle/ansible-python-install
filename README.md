# Ansible Role - python-install

Ensure that python and python tools are installed on a system.

Available on Ansible Galaxy: [pgkehle.python-install](https://galaxy.ansible.com/pgkehle/python-install)


## Requirements

None

## Role Variables

NA

## Dependencies

None

## Example Playbook

```yaml
- hosts: all
  gather_facts: no     
  roles:
     - { role: pgkehle.python-install, dist_type: "ubuntu" }
```

## License

MIT


