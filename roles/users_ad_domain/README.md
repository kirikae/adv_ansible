# Ansible Role: users_ad_domain

<!-- TODO: One-liner describing repository -->

## Description

<!-- TODO: Detailed description of repository -->

## Requirements

<!-- TODO: Requirements of the repository -->

Modules used:

* [module](link)

## Installation

<!-- TODO: Installation process to use this repository -->

Install from [Ansible Galaxy](https://galaxy.ansible.com/kirikae/users_ad_domain)
```bash
ansible-galaxy install kirikae.users_ad_domain
```

Install from [GitHub](https://github.com/kirikae/ansible-role-users_ad_domain)
```bash
git clone https://github.com/kirikae/ansible-role-users_ad_domain.git kirikae.users_ad_domain
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
    - role: kirikae.users_ad_domain
```

#### Customised

```yaml
- hosts: all
  roles:
    - role: kirikae.users_ad_domain
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

[Bugs, Feature Requests, Suggestions](https://github.com/kirikae/ansible-role-users_ad_domain/issues)
[Pull Requests](https://github.com/kirikae/ansible-role-users_ad_domain/pulls)

## License

[MIT](https://spdx.org/licenses/MIT.html)

## Author

* Kirikae <kirikae@cs-network.org>