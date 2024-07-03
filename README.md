# writefreely Ansible Role

![writefreely logo](assets/logo.png)

writefreely is a self-hosted open source platform for building a writing space on the web connected to the fediverse.
This role helps you to set up writefreely:

- with everything run in [Docker](https://www.docker.com/) containers
- powered by [algernon/writefreely](https://hub.docker.com/r/algernon/writefreely) container image

This role *implicitly* depends on:

- [`com.devture.ansible.role.systemd_docker_base`](https://github.com/devture/com.devture.ansible.role.systemd_docker_base)

## Installing

To configure and install writefreely on your own server(s), you should use a playbook like [Mother of all self-hosting](https://github.com/mother-of-all-self-hosting/mash-playbook) or write your own.

# Configuring this role for your playbook

```
writefreely_enabled: true
writefreely_hostname: 'example.org'

```
