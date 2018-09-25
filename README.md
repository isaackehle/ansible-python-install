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

## Author Information

Paul Kehle  
@pgkehle ([twitter](https://twitter.com/pgkehle), [github](https://github.com/pgkehle), [linkedin](https://www.linkedin.com/in/pgkehle))

## For local development testing

```bash
rsync -av --delete ~/code/ansible-python-install/* ~/.ansible/roles/pgkehle.python-install
```
