# docker-ubuntu-LTS
Latest ubuntu LTS 16.04

Dockerfile for ubuntu:16.04 LTS baseimage with a couple of extra packages.

The image is built on top of the latest LTS ubuntu:16.04 image and installs the following extra packages:

 - nano
 - wget
 - sudo
 - net-tools
 - ca-certificates
 - unzip
 
Additionally apt is configured  to SKIP  recommended and suggested packages.
