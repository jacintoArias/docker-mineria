[![Docker Automated buil](https://img.shields.io/docker/automated/jrottenberg/ffmpeg.svg)](https://hub.docker.com/r/jacintoarias/docker-mineria/)

# docker-mineria

This repository contains the docker image for the data mining course.

This image can be directly obtained from dockerhub at:

https://hub.docker.com/r/jacintoarias/mineria/


## Launching with docker-compose

A docker-compose file is included as an example on how to launch the jupyter
notebook. It just exposes the notebook on port 8888 and binds the working
directory as a volume on the home directory of the notebook server.
