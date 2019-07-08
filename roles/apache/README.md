# Ansible Role: apache

<!-- TODO: One-liner describing repository -->

## Description

<!-- TODO: Detailed description of repository -->

## Requirements

<!-- TODO: Requirements of the repository -->

Modules used:

* [module](link)

## Installation

<!-- TODO: Installation process to use this repository -->

Install from [Ansible Galaxy](https://galaxy.ansible.com/kirikae/apache)
```bash
ansible-galaxy install kirikae.apache
```

Install from [GitHub](https://github.com/kirikae/ansible-role-apache)
```bash
git clone https://github.com/kirikae/ansible-role-apache.git kirikae.apache
```

Dependencies:
```bash
ansible-galaxy install -r requirements.yml
```

## Usage

<!-- TODO: How to use this repository -->

### Variables

| Variable      | Default     | Comments (type)         |
| :---          | :---        | :---                    |
| `key`         | `value`     | Key and default value.  |

### Example Playbook

Running Ansible [Roles](https://docs.ansible.com/ansible/latest/user_guide/playbooks_reuse_roles.html) can be done in a [playbook](https://docs.ansible.com/ansible/latest/user_guide/playbooks_intro.html).

#### Defaults

```yaml
- hosts: all
  roles:
    - role: kirikae.apache
```

#### Customised

```yaml
- hosts: all
  roles:
    - role: kirikae.apache
      variable: value
      also_a_variable:
        - foo
        - bar
```

## Known Issues

<!-- TODO: List any known issues -->

## Testing

Ansible specific testing is done with [Molecule](https://molecule.readthedocs.io/en/stable/).

## Contribute

If you would like to contribute to further development of this role, Thanks!

[Bugs, Feature Requests, Suggestions](https://github.com/kirikae/ansible-role-apache/issues)
[Pull Requests](https://github.com/kirikae/ansible-role-apache/pulls)

## License

[MIT](https://spdx.org/licenses/MIT.html)

## Author

* Kirikae <kirikae@cs-network.org>