# Template Ansible Project
This is a sample setup for an Ansible project which is in line with the way of working and tools described in:

* https://github.com/Thulium-Drake/ansible-utils
* https://github.com/Thulium-Drake/ansible-role-ansible_controller

I mainly keep it on Github to kickstart a new project :-) but if you have any feedback, feel free to open an issue!

## Ansible Sign
This project is signed with Ansible-sign, please use ```ansible-sign project gpg-verify``` to verify it's integrity.

The configuration for ansible-sign is included in MANIFEST.in, and you can re-sign any downstream projects with ```ansible-sign project gpg-sign <YOUR_PROJECT_DIR>```
