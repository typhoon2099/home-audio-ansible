# Ansible Home Audio

Ansible Playbooks and Inventory for configuring my home audio setup.

Clients are Raspberry Pis running Snapclient. The server also acts as a client
connected to the Living Room receiver.

This repo is also my attempt to learn Ansible, so I'm sure at this point there
are a few Ansible no-nos in here, but as I learn more they will be ironed out.

One issue I'm facing at the moment is that I can't pull a Git repo without
installing a Python package, and that requires a Crypography package that needs
to be compiled on the Raspberry Pi, and that requires the Rust toolchain to be
available 🙃. I would like to install Snapclient, Snapserver, and MPD from
source to ensure it is up to date, but this is my sticking point at the moment.
Alternatives include adding a PPA (which may live outside of this repo), or
switching to an Arch distro for the Pis. Both are extra work...
