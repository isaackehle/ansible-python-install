# Ansible Role - install-python

Ensure that python and python tools are installed on a system.

Available on Ansible Galaxy: [pgkehle.install-python](https://galaxy.ansible.com/pgkehle/install-python)


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
     - { role: pgkehle.python, dist_type: "ubuntu" }
```

## License

MIT

## Author Information

Paul Kehle  
@pgkehle ([twitter](https://twitter.com/pgkehle), [github](https://github.com/pgkehle), [linkedin](https://www.linkedin.com/in/pgkehle))
