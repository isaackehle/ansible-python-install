# Ansible Role - install-python

This role will ensure that python is installed.

Available on Ansible Galaxy: [pgkehle.install-python](https://galaxy.ansible.com/pgkehle/install-python)


## Requirements

None

## Role Variables

NA

## Dependencies

None

## Example Playbook

    - hosts: all
      roles:
         - { role: pgkehle.python, dist_type: "ubuntu" }

## License

MIT

## Author Information

Paul Kehle  
@pgkehle ([twitter](https://twitter.com/pgkehle), [github](https://github.com/pgkehle), [linkedin](https://www.linkedin.com/in/pgkehle))
