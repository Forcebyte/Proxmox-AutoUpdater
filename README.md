# Proxmox-AutoUpdater

### Brief / Overview
This repo is a random YAML file used to update repositories in homelab

### Requirements
- SSH Key access to Proxmox server (Preferrably root)
- Jenkins Server to run job on a timed basis

### Why not Ansible Tower DNS Module?
This is mostly for personal preference - I wanted more experience with Jenkins' Ansible extensions so I went with that. This will also work off of Ansible Tower if required (all I use Ansible for is propagating off of an inventory file)
