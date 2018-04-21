This is an [Ansible](http://www.ansible.com/home) role for an
installation of [Docker](https://www.docker.com/).

# What it Does

Installs Docker and configures the `docker` service.  Allows you to set Docker's root directory.

# Usage

Use the role in a playbook like this:

```yaml
- hosts: all
  roles:
    - role: docker
	  docker_root_dir: /somewhere/for/docker

```
