# docker-ubuntu-LTS
Latest ubuntu LTS 16.04

Dockerfile to build a ubuntu:16.04 LTS baseimage with a couple of extra packages.

The image is built on top of the latest LTS ubuntu:16.04 image and installs the following extra packages:

nano
wget
sudo
net-tools
ca-certificates
unzip
The packages are selected based on the criteria that they are commonly used and that they do not influence the size of the resulting image too much.

Additionally apt is configured to NOT install recommended and suggested packages.
