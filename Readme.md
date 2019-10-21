# Ansible Scripts

## Installation

* Create virtualenv and install ansible

`mkvirtualenv ansible`  
`pip install ansible`

## Setup hosts

* see hosts-file

## Run a playbook

* Switch to correct virtualenv

`workon ansible`

* Run playbook with hosts file and verbose output
   
`ansible-playbook apt_upgrade.yml -i ./hosts -v`

