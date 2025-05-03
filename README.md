<!--
SPDX-FileCopyrightText: 2023 Slavi Pantaleev
SPDX-FileCopyrightText: 2025 XHawk87

SPDX-License-Identifier: AGPL-3.0-or-later
-->

# Minecraft Ansible role

[![REUSE status](https://api.reuse.software/badge/github.com/XHawk87/ansible-role-minecraft)](https://api.reuse.software/info/github.com/XHawk87/ansible-role-minecraft)

This is an [Ansible](https://www.ansible.com/) role which installs [Minecraft](https://docker-minecraft-server.readthedocs.io/) to run as a [Docker](https://www.docker.com/) container wrapped in a systemd service.

Note that by running this playbook you implicitly agree to the [Mojang EULA for Minecraft](https://www.minecraft.net/en-us/eula).

This role *implicitly* depends on:

- [`com.devture.ansible.role.playbook_help`](https://github.com/devture/com.devture.ansible.role.playbook_help)
- [`com.devture.ansible.role.systemd_docker_base`](https://github.com/devture/com.devture.ansible.role.systemd_docker_base)

Check [defaults/main.yml](defaults/main.yml) for the full list of supported options.
