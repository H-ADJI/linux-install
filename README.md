# Purpose

my ansible playbooks to setup my personal workstations

# Guide

- install git
- install ansible
- launch using :
  - ansible-pull -U https://github.com/H-ADJI/linux-install main.yml
  - ansible-playbook main.yml

## post install

since i didn't find a way to correctly setup users, owners and group i need to run the following command after the ansible setup :
` sudo chown -R khalil:khalil .`
