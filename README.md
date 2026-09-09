## Setup
Use the `./generate-vm --fetch` command to download the VM images required.

## Usage

Run:
`./generate-vm --name myvm --user dev --size 64G --os alma10 --ssh "your public ssh key" `
or Run:
`./generate-vm --wizard` for a guided virtual machine creation

## OS Choices:
- alma10
- alma9
- alma8
- arch
- centos10
- centos9
- debian13
- debian12
- debian11
- rocky10
- rocky9
- rocky8
- ubuntu26
- ubuntu25
- ubuntu24

## Commands:
--wizard: guides a user through the creation of a virtual machine
--stop: stops specified vm. example: `./generate-vm --stop --name examplevm`
--destroy: destroys specified vm. example: `./generate-vm --destroy --name examplevm`
--cleanup: cleans up leftover files from specified vm. example: `./generate-vm --cleanup --name examplevm`
--recreate: destroys, cleans up and then recreates specified vm. example: `./generate-vm --recreate --name examplevm`
--help: shows commands. example: `./generate-vm --help`
