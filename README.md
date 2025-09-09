# ansible-role-docker

Ansible role to install Docker and Docker Compose.

See the official installation docs:

- <https://docs.docker.com/engine/install/debian/>
- <https://docs.docker.com/engine/install/ubuntu/>

## Example Playbook

```yaml
- hosts: docker-servers
  roles:
    - role: andreswebs.docker
```

## Authors

**Andre Silva** [@andreswebs](https://github.com/andreswebs)

## License

This project is licensed under the [Unlicense](UNLICENSE).
