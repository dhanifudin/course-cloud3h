Resume week 4 by Ahmad Mahfudin Alwi

In this 4th meeting we are taught how to create a database server on a Virtual Machine.

### Summary of theoretical material

## Virtual Cloud Network (VCN)

Networking Components
Network services use virtual versions of components from conventional networks
that you may already be familiar with, which are as follows:

<ol>

<li> VIRTUAL CLOUD NETWORK (VCN)</li>

A virtual private network that you set up in an Oracle data center. It is very similar to a conventional network, with firewall rules and certain types of communication gateways that you can choose to use.

<li> SUBNETS </li>

The subdivision you specify in the VCN (for example, 10.0.0.0/24, 10.0.1.0/24, or 2001:DB8::/64). The subnet contains Virtual Network Interface Cards (VNIC), which are linked to instances. Each subnet consists of a range of contiguous IP addresses (for IPv4 and IPv6, if enabled) that do not overlap with other subnets in the VCN.

<li> VNIC (Virtual Network Interface Cards) </li>

The VNIC is attached to an instance and resides in the subnet to enable connections to the VCN subnet. The VNIC determines how instances connect to endpoints inside and outside the VCN. Each instance has a primary VNIC that is created with the instance and cannot be deleted.

<li> PRIVATE IP </li>

Private IPv4 addresses and related information for handling instances (for example, hostnames for DNS). Each VNIC has a primary private IP, and you can add and remove secondary private IPs. The primary private IP address on the instance will not change as long as the instance is in use and cannot be removed from the instance.

<li> PUBLIC IP </li>

Public IPv4 addresses and related information. You can optionally assign a public IP to your instances or other resources that have a private IP.

<li> IPV6 </li>

IPv6 address and related information. IPv6 addressing is supported for all commercial and government areas.

<li> DYNAMIC ROUTING GATEWAY (DRG) </li>

A virtual router (optional) that you can add to your VCN. It provides a private network traffic path between your VCN and the local network. 

<li> INTERNET GATEWAY </li>

A virtual router (optional) that you can add to your VCN to provide direct internet access.

<li> NETWORK ADDRESS TRANSLATION (NAT) GATEWAY </li>

A virtual router (optional) that you can add to your VCN. It gives cloud resources without a public IP address.

<li> SERVICE GATEWAY </li>

Oracle Cloud Service Gateway provides a customer’s on-premises network with private access to Oracle Cloud services. Once connected to your VCN, Service Gateway allows secure, private connectivity to Oracle Cloud services like compute instances, cloud storage, containers, and databases.

<li> LOCAL PEERING GATEWAY (LPG) </li>

A virtual router (optional) that you can add to your VCN. It provides a path for private network traffic between your VCN and services supported on the Oracle Services Network. 

<li> REMOTE PEERING CONNECTION (RPC) </li>

Components you can add to a DRG. This allows associating one VCN with another VCN in a different region.

<li> ROUTE TABLES </li>

Virtual route tables for your VCN. They have rules for routing traffic from subnets to destinations outside the VCN via gateways or specially configured instances.

<li> SECURITY RULES </li>

Virtual firewall rules for your VCN. This is for the inbound and outbound rules that define the type of traffic (protocols and ports) that are allowed in and out of the instance. You can choose whether the given rule is stateful or stateless.

<li> DHCP OPTIONS </li>

Configuration information that is automatically passed to instances at boot.

</ol>
