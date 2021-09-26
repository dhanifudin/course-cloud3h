# Virtual Cloud Network

## Virtual Cloud Network
A virtual private network set up in an Oracle data center. Very similar to conventional networks, with firewall rules and certain types of communication gateways to choose from.

## Subnets
Each subnet consists of a contiguous range of IP addresses (for IPv4 and IPv6, if enabled) that do not overlap with other subnets in the VCN.

## VNIC
The VNIC determines how instances connect to endpoints inside and outside the VCN. Each instance has a primary VNIC that is created with the instance and cannot be deleted.

## Private IP
Private IPv4 addresses and related information for handling instances (for example, hostnames for DNS). The primary private IP address on the instance will not change as long as the instance is in use and cannot be removed from the instance.

## Public IP
Public IPv4 addresses and related information. Public IPs can be temporary or reserved.

## Dynamic Routing Gateway (DRG)
It provides a private network traffic path between your VCN and the local network.

## Service Gateway
It provides a path for private network traffic between your VCN and services supported on the Oracle Services Network.

## Local Peering Gateway (LPG)
This allows associating one VCN with another VCN in the same region. Peering means VCNs communicate using private IP addresses, without internet traffic or only over local networks in the cloud.

## Remote Peering Connection (RPC)
Components you can add to a DRG. This allows associating one VCN with another VCN in a different region.

## Route Tables
Virtual route tables for your VCN. They have rules for routing traffic from subnets to destinations outside the VCN via gateways or specially configured instances.

## Security Rules
Virtual firewall rules for your VCN. This is for the inbound and outbound rules that define the type of traffic (protocols and ports) that are allowed in and out of the instance.

## DHCP Options
Configuration information that is automatically passed to instances at boot.
