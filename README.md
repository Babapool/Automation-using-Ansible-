# Automation using Ansible
![ansible](https://github.com/mrsarthak001/Automation-using-Ansible-/blob/master/doc/ansible.gif)

## What is Ansible?

Ansible is an Open-Source IT Automation Engine that is used to automate application deployment, infrastructure automation, cloud provisioning, and many IT services. Ansible improves the scalability, consistency & reliability of the IT environment.

Ansible is easy-to deploy as it is agentless and doesn't require any security infrastructure. Ansible uses the concept of a playbook and uses a language. YAML (Yet Another Markup Language) for its configuration management. Its advantage is that playbooks are so simple that even the support guys can debug it.

## Basic terms in ansible

### Controller node:

Any machine with Ansible installed. You can run Ansible commands and playbooks by invoking the ansible or ansible-playbook command from any control node. You can use any computer that has a Python installation as a control node - laptops, shared desktops, and servers can all run Ansible. However, you cannot use a Windows machine as a control node. You can have multiple control nodes.

### Managed Node: 

The network devices (and/or servers) you manage with Ansible. Managed nodes are also sometimes called “hosts”. Ansible is not installed on managed nodes.

### Inventory: 

A list of managed nodes. An inventory file is also sometimes called a “hostile”. Your inventory can specify information like the IP address for each managed node. An inventory can also organize managed nodes, creating and nesting groups for easier scaling.

### Playbooks: 

Ordered lists of tasks, saved so you can run those tasks in that order repeatedly. Playbooks can include variables as well as tasks. Playbooks are written in YAML and are easy to read, write, share, and understand.

---

The contribution guidelines are present [here](docs/CONTRIBUTING.md)

---

The project is licensed under [MIT License](LICENSE) 
