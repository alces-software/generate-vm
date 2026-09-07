## Setup
download any of the os choices generic cloud image, place it in the images folder and rename it to it's name in the OS Choices.qcow2 such as alma10_generic_cloud.qcow2 would become alma10.qcow2.

## Usage

Run:
`./generate-vm --name myvm --user dev --size 64G --os alma10 --ssh "your public ssh key" `

## OS Choices:
- alma10
- alma9
- alma8
- arch
- debian13
- debian12
- debian11
- rocky10
- rocky9
- rocky8

## Commands:

--stop: stops specified vm. example: `./generate-vm --stop --name examplevm`
--destroy: destroys specified vm. example: `./generate-vm --destroy --name examplevm`
--cleanup: cleans up leftover files from specified vm. example: `./generate-vm --cleanup --name examplevm`
--recreate: destroys, cleans up and then recreates specified vm. example: `./generate-vm --recreate --name examplevm`
--help: shows commands. example: `./generate-vm --help`
