# Ansible_Jenkins_roles
---

- This Project is used for installing Jenkins using Ansible-roles , This Works in RedHat Family(i.e. centos and redhat)

---
Here, Files Section is used to provide final Info to the remote hosts for installation.  


---
### USE OF HANDLERS ###
---
- used to start the service after installation  
-  Provide the Initial Admin Password to the console
-  Provide final msg to the user

---
- **my-jenkins.yaml** ---> It is used to run whole roles

--- 
- **TO RUN**  ---> ansible-playbook my-jenkins.yaml

