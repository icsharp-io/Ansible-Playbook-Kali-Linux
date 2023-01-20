# Ansible Playbook Kali Linux

Quick and dirty Ansible Playbook for provisioning Kali Linux on a fresh Debian 11 (my typical Azure use case(s))

Install Ansible

```
sudo apt-get update && sudo apt-get install ansible -y
```
Run playbook
```
ansible-playbook kali.yml
```

TODO: add TerraForm for provisioning virtual machine (Debian), virtual network, subnet, nsg, load balancer with in/out bound nat rule.
