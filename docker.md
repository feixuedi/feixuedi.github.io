# Docker, Kubernates and Openshift

## 1. Docker 

### 1.1 what is docker?

    sudo docker run -i -t ubuntu /bin/bash

A rootfs run on the oprating system kernel(for linux)

#### 1.1.1 namespace

* Pid
* Mount
* Network
* User
* UTS
* IPC

#### 1.1.2 cgroup

* cpu
* memery
* io
* ......

### 1.2 dockerfile, image and container

    # version 1.0
    from ubuntu:latest
    run apt-get update
    run apt-get install -y vim

    sudo docker build -t="ubuntu-with-vim" .

### 1.3 union-mount and copy-on-write

![union mount and copy on write](/pictures/docker-01.png)

### 1.4 why use docker?(vs vm)

## 2. Kubernetes

### 2.1 history

1. from cloud foundry: paas
2. swarm fig(compose) and machine
3. CoreOs and openshift
4. kubernetes and openshift

### 2.2 architecture

![kubernetes](/pictures/kubernetes-01.png)

## 3. openshift

### 3.1 platform as a service

[community website](https://www.okd.io/)

