Docker
======

Collection of Dockerfiles.

Image layers
======

    |-- ubuntu:precise
	    |-- komljen/ubuntu
	        |-- komljen/redis
	        |-- komljen/apache
	        |   |-- komljen/php-apache
	        |       |-- komljen/wordpress
	        |-- komljen/nodejs
	        |   |-- komljen/ghost
	        |   |-- komljen/hipache
	        |-- komljen/postgres
	        |-- komljen/mysql
	        |-- komljen/mongo
	        |-- komljen/jdk6-oracle
	        |   |-- komljen/tomcat
	        |   |-- komljen/jenkins
	        |   |-- komljen/maven3
	        |       |-- komljen/jmeter-2.9-abh

Installation & Configuration
======

Docker 0.9 and above.

Follow this [blog post](http://www.siliconfidential.com/articles/docker-coreos-osx/) to install Docker and Vagrant on Mac OSX.

> **Note:** Change `DOCKER_HOST` to the following to get it to work: `export DOCKER_HOST=tcp://172.12.8.150:4243`
