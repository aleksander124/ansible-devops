# Ansible playbook to automate work in devops enviroment

```
├───devops
│   └───roles
│       ├───azure-agent-add             # Role to create configure and add azure agent on virtual machine
│       │   ├───tasks
│       │   └───vars
│       └───azure-machine-config        # Role created to fully configure virtual machine to selfhost azure agents
│           ├───tasks
│           └───vars
└───playbooks                           # Single playbooks to simple jobs
```