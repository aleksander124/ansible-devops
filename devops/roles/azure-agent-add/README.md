> #### Good Practice and Tips
>
> - If you are putting azure agents on a linux virtual machine it is important to make a separate LVM partition to hold agent files for example it could be ```/opt/```
> - It is good to generate one Token to add all agents. you can make this token as global to manage different organizations
> - If you want to add agent to pool your user should have amin permissions on this pool
> - If you createing the token take care of scopes and select only those most needed: ```Agent Pools - Read & manage``` ```Read Audit Log```