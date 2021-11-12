Summary of Week 11 :

Docker Network Bridge:
-Is the default network type from Docker
-When the Docker service daemon is running, it will configure a virtual bridge called docker0.
-If we don't specify the network used, docker run –net=<Network> then the Docker daemon will connect to the container using a network bridge.
-Each container created, will be allocated an Ethernet virtual device and mapped as eth0 on the container.
-In the interface container eth0 will be assigned an IP address from the bridge address range.
-Docker will look for an available IP address on the bridge and will configure the interface eth0 container with that IP address.
-When a container wants to connect to the internet it will use a bridge. The bridge will automatically forward packets between other network interfaces as long as they are connected and allow the container to communicate with the host machine.

Docker Network Hosts:
-Docker network of this type is to put the container in the stack of the host network.
-All predefined network interfaces can be accessed via containers.
-When we run the container we use the –net=host parameter, so the container will use the network host.
-When using a host network it will be as fast as a normal network because there is no use of bridges or translations
-When you need to get the best network performance using a host.
-Containers running on the network host stack will get much faster than containers running on network bridges, no traversing on docker0 bridges and iptables port mappings.
-Containers share their network of hosts that are directly exposed to the outside world.
-When using the command –net=host, our container will be accessible via the host's IP address.
-We need to be careful when using network hosts because it is dangerous.

Docker Network None:
-Network None aims to not configure networking.
-No driver is used on this type of Network.
-When we don't want the container to be accessible. The command used by adding the parameter –net=none