# rpicluster
Configurations for setting up a cluster of Raspberry Pi 3's running Raspbian (version: November 2016).

rpi0: sudo apt-get install isc-dhcp-server

all: sudo apt-get install nfs-common

rpi0: sudo apt-get install nfs-kernel-server

slaves: sudo apt-get install autofs

all: curl -sSL https://get.docker.com | sh
