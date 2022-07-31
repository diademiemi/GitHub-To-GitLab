# Ansible Playbook to sync GitHub to GitLab
This is a misuse of Ansible using it to download all GitHub repositories in users/organisations you have access to and upload them to a GitLab server.  
The playbook creates a `mapping.yml` file which is used to link GitHub repos to a GitLab namespace, name and visilibity.  

Repositories are created automatically.  

Check `defaults/` for variables.  


## TODO create documentation for variables