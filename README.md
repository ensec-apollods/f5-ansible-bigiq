# Project Name

Ansible example playbook for managing F5 BIG-IQ devices

## Features or Example

First version will re-discover and re-import devices from a F5 BIG-IQ

## Motivation

Since the F5 BIG-IQ cannot schedule a re-discover and re-import job this has to be done with an external script.
For this project [Ansible](https://docs.ansible.com/) was used with the provided [bigiq_device_discovery_module](https://docs.ansible.com/ansible/latest/collections/f5networks/f5_modules/bigiq_device_discovery_module.html).

## Requirements

[Ansible](https://docs.ansible.com/ansible/latest/installation_guide/index.html)

## Getting Started

    git clone https://github.com/ensec-apollods/f5-ansible-bigiq.git
    cd f5-ansible-bigiq
    ansible-playbook -i inventory playbook.yaml

## License

[MIT](http://opensource.org/licenses/mit-license.php)
