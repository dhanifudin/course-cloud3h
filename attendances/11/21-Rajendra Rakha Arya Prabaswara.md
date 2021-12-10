Nama : Rajendra Rakha Arya Prabaswara

NIM  : 1941720080

---

# Week 11

## What is Docker Compose ?

That is a tool for defining, launching, and managing services, where the service is defined as one or more docker containers. Services and systems are defined in YAML files. What docker compose can do is build docker images, run applications as services, run full system services, manage services, scale up/down and view container logs.


## Type Of Docker Network  

### What is Bridge ?

Is the default docker network type and when docker runs it will configure a virtual bridge called docker0. Each container will be allocated a virtual Ethernet eth0. Interface ethh0 will be assigned an IP address from the bridge range. Docker will look for an available IP and will configure eth0. When the container connects to the internet, the bridge will automatically forward packets between interfaces as long as they are connected and allowed to communicate with the host machine.

### What is Host ?

This network puts the container on the network host stack. All interfaces are accessible via containers. Using the host network is the same as the original network so it can perform the best network performance, even faster than containers that use bridges. The container will share the network from the host that goes directly to the internet. When using this network, the container will be accessible via the IP host. This network tends to be insecure because it is directly exposed to the internet.


## Expose and Mapping ports

This is a common scenario when you want a container to be accessed from outside of Docker. An image can also expose ports, i.e. the container will listen on the exposed port. For example, the Tomcat server application will listen on port 8080, so later all containers running on the same host will communicate with Tomcat on port 8080.

## Persistent Storage (Volume)

Aims to keep the data even if the container is deleted. Persistent storage can also share data between containers or docker hosts. For example, when a transaction data container is deleted, the data will still exist even though the container has been deleted.

## Docker Volume Driver

There are different types of volumes to integrate with other types of storage :

1. Docker volume driver for Azure file storage, which is the driver for docker that Azure uses.

2. IPFS (InterPlanetary File System) is an open source volume plugin that allows filesystems to become volumes.

3. Keywhiz, a system used to manage and distribute confidential data such as TLS certificates, GPG keys, API tokens, and database credentials.

