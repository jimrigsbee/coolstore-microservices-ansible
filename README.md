# CoolStore Microservices - Ansible Installer
The series of scripts and Ansible playbooks in this repository are used to deploy the Red Hat CoolStore Microservices demo project. This project was born out of the complexity of maintaining a Bash shell script to provision the application. The playbooks utilize the roles and libraries from the *openshift-ansible* project which provide rich Ansible modules for manipulating Kubernetes resources.

## Usage
bin/setup.sh {openshift-version-number}
For example:
```
bin/setup.sh 3.6
```
This clones the proper *openshift-ansible* Git repository to provide the roles and modules needed for the CoolStore Microservices playbooks.
