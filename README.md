# Scaling Invention

1. Build a webserver

## Local Development


install home brew

`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

Install local dependencies to provision a virtual machine.

`brew install virtualbox vagrant`

## Usage

To build the VM run: 

`vagrant up`

To rerun the provisioning scrit run:

`vagrant up --provision`

To destroy the VM run:

`vagrant destroy -f`
