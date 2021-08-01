# ansible-role-docker

Ansible role to install Docker and docker-compose.


## Requirements

The `jq` program must be installed on the host. See the [jq web page](https://stedolan.github.io/jq/) to install.


## Example Playbook

```sh
- hosts: servers
  roles:
    - role: andreswebs.docker
```


## Authors

**Andre Silva** [@andreswebs](https://github.com/andreswebs)


## License

This project is licensed under the [Unlicense](UNLICENSE.md).
