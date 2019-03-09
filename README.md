# Centos-devenv
---

This repository holds a Vagrantfile and an ansible playbook
capable of spawning a virtual machine with the following charateristics:

1. Based on CentOS 7
2. the `/vagrant` is shared via Samba (easy to access from Mac OS)
3. has the "Development Tools" installed
4. will load your openssh key automatically for passwordless login
5. network is bridged to allow other people cooperate with you.

Nothing complex, but hopefully useful.
