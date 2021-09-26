VIRTUAL CLOUD NETWORK (VCN)
A virtual private network set up in an Oracle data center. It is very similar to a conventional network, with firewall rules and certain types of communication gateways to choose from. The VCN resides in a single Oracle Cloud Infrastructure region and includes one or more CIDR blocks (IPv4 and IPv6, if enabled)

SUBNETS
The subdivision specified in the VCN (for example, 10.0.0.0/24, 10.0.1.0/24, or 2001:DB8::/64). The subnet contains Virtual Network Interface Cards (VNIC), which are linked to instances. Each subnet consists of a contiguous range of IP addresses (for IPv4 and IPv6, if enabled) that do not overlap with other subnets in the VCN

VNIC (Virtual Network Interface Cards)
The VNIC is attached to an instance and resides in the subnet to enable connections to the VCN subnet. The VNIC determines how instances connect to endpoints inside and outside the VCN.

PRIVATE IP
Private IPv4 addresses and related information for handling instances (for example, hostnames for DNS). Each VNIC has a primary private IP, and you can add and remove secondary private IPs.

PUBLIC IP
Public IPv4 addresses and related information. You can optionally assign a public IP to your instances or other resources that have a private IP.

DYNAMIC ROUTING GATEWAY (DRG)
A virtual router (optional) that you can add to your VCN. It provides a private network traffic path between your VCN and the local network. You can use it with other Network components and routers on your local network to establish a connection via Site-to-Site VPN or OCI FastConnect.

Service Gateway
A virtual router (optional) that you can add to your VCN. It provides a path for private network traffic between your VCN and services supported on the Oracle Services Network

LOCAL PEERING GATEWAY (LPG)
A virtual router (optional) that you can add to your VCN. This allows associating one VCN with another VCN in the same region. Peering means VCNs communicate using private IP addresses, without internet traffic or only over local networks in the cloud.

REMOTE PEERING CONNECTION (RPC)
Components you can add to a DRG. This allows associating one VCN with another VCN in a different region.

ROUTE TABLES
Virtual route tables for your VCN. They have rules for routing traffic from subnets to destinations outside the VCN via gateways or specially configured instances.

SECURITY RULES
Virtual firewall rules for your VCN. This is for the inbound and outbound rules that define the type of traffic (protocols and ports) that are allowed in and out of the instance. You can choose whether the given rule is stateful or stateless.

DHCP OPTIONS
Configuration information that is automatically passed to instances at boot.
