# VCN (Virtual Cloud Network)

## 1. VCN Definition
A virtual private network set up in an Oracle data center. It is very similar to a conventional network, with firewall rules and certain types of communication gateways to choose from. The VCN resides in a single Oracle Cloud Infrastructure region and includes one or more CIDR or Classless Inter-Domain Routing blocks (IPv4 and IPv6, if enabled)

## 2. Subnets
A subnet is a subdivision defined in the VCN (for example, 10.0.0.0/24, 10.0.1.0/24, or 2001:DB8::/64). The subnet contains Virtual Network Interface Cards (VNIC), which are linked to instances. Each subnet consists of a contiguous range of IP addresses (for IPv4 and IPv6, if enabled) that do not overlap with other subnets in the VCN.

## 3. VNIC (Virtual Network Interface Cards)
The VNIC is attached to an instance and resides in the subnet to enable connections to the VCN subnet. The VNIC determines how instances connect to endpoints inside and outside the VCN. Each instance has a primary VNIC that is created with the instance and cannot be deleted.

## 4. Private IP
Private IPv4 addresses and related information for handling instances (for example, hostnames for DNS). Each VNIC has a primary private IP, and you can add and remove secondary private IPs. The primary private IP address on the instance will not change as long as the instance is in use and cannot be removed from the instance.

## 5. Public IP
Public IPv4 addresses and related information. You can optionally assign a public IP to your instances or other resources that have a private IP. Public IPs can be temporary or reserved.

## 6. Dynamic Routing Gateway (DRG)
A virtual router (optional) that you can add to your VCN. It provides a private network traffic path between your VCN and the local network. You can use it with other Network components and routers on your local network to establish a connection via Site-to-Site VPN or OCI FastConnect. It can also provide a private network traffic path between your VCN and other VCNs in different regions.

## 7. Service Gateway
A virtual router (optional) that you can add to your VCN. It provides a path for private network traffic between your VCN and services supported on the Oracle Services Network (examples: Oracle Cloud Infrastructure Object Storage and Autonomous Database). For example, a System DB on a private subnet in your VCN can back up data to Object Storage without requiring a public IP address or access to the internet.

## 8. Local Peering Gateway
A virtual router (optional) that you can add to your VCN. This allows associating one VCN with another VCN in the same region. Peering means VCNs communicate using private IP addresses, without internet traffic or only over local networks in the cloud. Certain VCNs must have separate LPG for each peering they make.

## 9. Remote Peering Connection
Components you can add to a DRG. This allows associating one VCN with another VCN in a different region.

## 10. Route Tables
Virtual route tables for your VCN. They have rules for routing traffic from subnets to destinations outside the VCN via gateways or specially configured instances. Your VCN comes with an empty default route table, and you can add your own custom route table.

## 11. Security Rules
Virtual firewall rules for your VCN. This is for the inbound and outbound rules that define the type of traffic (protocols and ports) that are allowed in and out of the instance. You can choose whether the given rule is stateful or stateless. For example, you can allow incoming SSH traffic from anywhere to a set of instances by setting up a stateful ingress rule with source CIDR 0.0.0.0/0, and destination TCP port 22. To enforce security rules, you can use network security groups or security lists. A network security group consists of a set of security rules that apply only to resources in that group.

