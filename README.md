# docker-osp-galera

Galera on Docker for OpenStack using RDO on CentOS.

Currently is one node only to keep it simple. This is just to test stuff, don't use it.


## Usage

Launch with

    docker run -d -p 3306:3306 --name mariadb adrahon/docker-osp-galera
