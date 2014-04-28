Docker
======

Collection of Dockerfiles.

Image layers
======

    |-- phusion/baseimage
        |-- martinmicunda/mongo
        |-- martinmicunda/jdk7-oracle
        |   |-- martinmicunda/jenkins
        |   |-- martinmicunda/teamcity-server
        |   |-- martinmicunda/teamcity-agent

Installation & Configuration
======

Docker 0.9 and above.

Follow this [blog post](http://www.siliconfidential.com/articles/docker-coreos-osx/) to install Docker and Vagrant on Mac OSX.

> **Note:** Change `DOCKER_HOST` to the following to get it to work: `export DOCKER_HOST=tcp://172.12.8.150:4243`
