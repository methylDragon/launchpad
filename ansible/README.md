# Ansible

A "Scripting language for infrastructure. Configuration as code."
Ansible lets you declare step-by-step tasks for infrastructure setup.

## Setup

[Installation Guide](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#installation-guide)

```shell
$ python3 -m pip install --user ansible
$ ansible --version
```

## Run Playbook

```shell
$ ansible-playbook hello_world/hello.yaml
```

## Bonus

Ansible uses cowsay to print its statements.
You can configure what ASCII art is used!

```shell
export ANSIBLE_COW_SELECTION=methylhalf
```