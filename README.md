# docker_centos7php56u

## Summary

This Dockerfile builds the baseline Docker image used by many PHP Project.

It consist of the latest CentOS 7 operating system with PHP 5.6 from the IUS Community repository.


## Installation and Usage

    docker pull ernestova/docker_centos7php56u
    docker run -d -p 80:80 ernestova/docker_centos7php56u
  
## Build

To build the Docker image, run the following command:

    git clone https://github.com/ernestova/docker-centos7php56u.git
    cd docker_centos7php56u
    docker build -t centos7php56u .
    
### Maintainers

  * [Ernesto Vargas](ernesto_vargas@yahoo.com)
  
  
