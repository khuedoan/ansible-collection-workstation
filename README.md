# Workstation Collection for Ansible

## Usage

Include this collection in a `requirements.yml` file using the format:

```yaml
collections:
  - name: https://github.com/khuedoan/ansible-collection-workstation.git
    type: git
    version: master
```

Then install it with:

```sh
ansible-galaxy collection install -r requirements.yml
```

## License

Distributed under the GPLv3 License. See `LICENSE.md` for more information.
