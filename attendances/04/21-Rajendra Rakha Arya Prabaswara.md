Nama : Rajendra Rakha Arya Prabaswara
NIM  : 1941720080
---

# Virtual Cloud Network (VCN)

## Learning objectives

-Knowing the OCI Service Network
- Activate *port* 80 via VCN
- Able to install Apache and Web Server

## Commonly used Common Web Server Ports

- 80 = HTTP
- 443 = HTTPS
- 22 = SSH

## Apache MwmAnf Steps and Enabling Port 80

- Create VM Instance with **Ubuntu**
- Access VM Instance with **SSH**, by entering **Public Username, IP Address, and SSH Private Key**
- Install Web Server (Apache)
- Check Web Server Status with `systemctl`, if it is not active, activate it with `systemctl`.
- Go back to the OCI Website, the created *instance* section, go to the VCN page and add a new 

**Ingress Rule** with:

- Source Type: CIDR
- CIDR Source: 0.0.0.0/0
- IP Protocol: TCP
- Destination Port: 80 (HTTP)
- Open Port 80 in VM Instance via SSH by following the method [here](https://www.cyberciti.biz/faq/how-to-open-firewall-port-on-ubuntu-linux-12-04-14- 04-lt/)
- Restart the VM Instance and log back in
- Access the Web server with the command `curl -I 127.0.0.1`. If there is a *response* from the *header* HTML, then it works.
- Try to access publicly *public port* on VM Instance