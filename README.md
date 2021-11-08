# ansible-apps_snoopy

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-apps_snoopy-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/apps_snoopy)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_snoopy.svg)](https://github.com/lotusnoir/ansible-apps_snoopy/releases/latest)
![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_snoopy?color=orange&style=flat)
[![downloads](https://img.shields.io/ansible/role/d/56111)](https://galaxy.ansible.com/lotusnoir/apps_snoopy)
![Ansible Quality Score](https://img.shields.io/ansible/quality/56111)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)


Deploy snoopy using ansible.

## Requirements

none

## Role variables

| Name           | Default Value | Description                        |
| -------------- | ------------- | -----------------------------------|

## Examples

        ---
        - hosts: apps_snoopy
          become: yes
          become_method: sudo
          gather_facts: yes
          roles:
            - role: ansible-apps_snoopy
          environment:
            http_proxy: "{{ http_proxy }}"
            https_proxy: "{{ https_proxy }}"
            no_proxy: "{{ no_proxy }}

## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

