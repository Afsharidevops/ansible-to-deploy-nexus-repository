## Deploy Nexus Repositoy with Ansible (Debian and Ubuntu)

## Intro

Setup Nexus with optional Let's Encrypt SSL

## Feature overview

*   [x] **Easy to Deploy Nesus**
*   [x] **Easy get SSL for Nexus**

## Getting Started

So how do you get this template to work for your project? It is easier than you think.

### Requirements

* Install Ansible.
* Install git package.
* Clone this project.

### Install

Use git to clone this repository into your computer.

```
git clone https://github.com/Afsharidevops/ansible-to-deploy-nexus-repository.git
cd ansible-to-deploy-nexus-repository/
```

### Hosts File

replace your server ip address with 0.0.0.0 on hosts file.
```
vim hosts
```

### Vars File

change content for your repository or add your Requirement packages to install: Packages, Enable SSL, Domain name, ...  
```
vim vars
```
### Run ansible

```
cd ansible-to-deploy-nexus-repository/
ansible-playbook -i hosts deploy_nexus.yaml
```
