# Ansible Installation

To install ansible please follow below mention commands
```
$ sudo apt update
$ sudo apt install software-properties-common
$ sudo apt-add-repository --yes --update ppa:ansible/ansible
$ sudo apt install ansible

```
# Sonarqube Installation

First thing you have edit ansible.cfg file.Inside ansible.cfg you need define "remote_user" 
and "private_key_file".Follow below mention command and example value

```
$ sudo nano ansible.cfg 
```
Example:-
```
remote_user = "ubuntu"
private_key_file = Openwitclub.pem
```
