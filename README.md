# miniconda-arm-travisci

[![Build Status](https://travis-ci.com/githubfoam/miniconda-arm-travisci.svg?branch=master)](https://travis-ci.com/githubfoam/miniconda-arm-travisci)  

~~~~
host bionic amd64
lxd host xenial amd64
docker debian-stretch-slim amr64(arm32v7 raspberry pi) w qemu emulater

sudo docker run arm32v7/debian:stretch-slim-conda conda info
Current conda install:
             platform : linux-armv7l
        conda version : 3.18.3
  conda-build version : 1.17.0
       python version : 2.7.10.final.0
     requests version : 2.8.1
     root environment : /opt/conda  (writable)
  default environment : /opt/conda
     envs directories : /opt/conda/envs
        package cache : /opt/conda/pkgs
         channel URLs : https://repo.continuum.io/pkgs/free/linux-armv7l/
                        https://repo.continuum.io/pkgs/free/noarch/
                        https://repo.continuum.io/pkgs/pro/linux-armv7l/
                        https://repo.continuum.io/pkgs/pro/noarch/
          config file : /root/.condarc
    is foreign system : False

~~~~
~~~~    
<https://repo.continuum.io/miniconda>

Architectures other than amd64?
https://github.com/docker-library/official-images#architectures-other-than-amd64
~~~~
