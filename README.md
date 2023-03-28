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

> #### Good Practice and Tips
>
> - If you are putting azure agents on a linux virtual machine it is important to make a separate LVM partition to hold agent files for example it could be ```/opt/```
> - It is good to generate one Token to add all agents. you can make this token as global to manage different organizations
> - If you want to add agent to pool your user should have amin permissions on this pool
> - If you createing the token take care of scopes and select only those most needed: ```Manage```
