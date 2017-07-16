# Introduction

We start building our cloud with virtual machines. You could use bare-metal machines as well, the configuration would be the same. Given that most readers (myself included) will be using virtual infrastructure, from now on I'll be referring strictly to VMs.

## Ingredients

3 x Virtual Machines, each with:
* CentOS/Fedora Atomic
* At least 1GB RAM
* At least 20GB disk space (but it'll be tight)
* Connectivity to each other within the same subnet, and on a low-latency link (i.e., no WAN links)

## Preparation

1. Install Virtual machines

* Hosts must be within the same subnet, and connected on a low-latency link (i.e., no WAN links)

2. Setup super-user access for your admin user, as a member of the "docker" group