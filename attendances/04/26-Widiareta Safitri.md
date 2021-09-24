# VIRTUAL CLOUD NETWORK (VCN)

## Definition
A virtual private network set up in an Oracle data center. It is very similar to a conventional network, with firewall rules and certain types of communication gateways to choose from. The VCN resides in a single Oracle Cloud Infrastructure region and includes one or more CIDR blocks (IPv4 and IPv6, if enabled)

## Subnets
The subnet contains Virtual Network Interface Cards (VNIC), which are linked to instances. Each subnet consists of a contiguous range of IP addresses (for IPv4 and IPv6, if enabled) that do not overlap with other subnets in the VCN

## VNIC (Virtual Network Interface Cards)
The VNIC is attached to an instance and resides in the subnet to enable connections to the VCN subnet. The VNIC determines how instances connect to endpoints inside and outside the VCN. Each instance has a primary VNIC that is created with the instance and cannot be deleted

## Private IP
Private IPv4 addresses and related information for handling instances (for example, hostnames for DNS). Each VNIC has a primary private IP, and you can add and remove secondary private IPs. The primary private IP address on the instance will not change as long as the instance is in use and cannot be deleted from the instance

## Public IP
Public IPv4 addresses and related information. You can optionally assign a public IP to your instances or other resources that have a private IP. Public IP can be temporary or reserved


