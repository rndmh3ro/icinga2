docker-icinga2
==============

This repository contains the source for [icinga2](https://www.icinga.org/icinga2/) [docker](https://docker.io) image.

# Image details

1. Based on debian:latest
1. Supervisor, Apache2, MySQL, icinga2, and icinga-web 
1. No SSH.  Use [nsenter](https://github.com/jpetazzo/nsenter)

# Running
```sudo docker run -d -p 80:<EXTERNAL_PORT> -t jordan/icinga2:latest```