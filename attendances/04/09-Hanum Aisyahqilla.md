<h1>Virtual Cloud Network(VCN)</h1>
<h4>Hanum Aisyahqilla Algadrie / 1941720082</h4>
_________________________________________________________________________

<h3>Definition</h3>
<p>A virtual private network set up in an Oracle data center. It is very similar to a conventional network, with firewall rules and certain types of communication gateways to choose from. The VCN resides in a single Oracle Cloud Infrastructure region and includes one or more CIDR blocks (IPv4 and IPv6, if enabled)</p>

_________________________________________________________________________

<h3>Subnets</h3>
<p>Each subnet consists of a contiguous range of IP addresses (for IPv4 and IPv6, if enabled) that do not overlap with other subnets in the VCN.</p>
_________________________________________________________________________

<h3>VNIC (Virtual Network Interface Cards)</h3>
<p>The VNIC is attached to an instance and resides in the subnet to enable connections to the VCN subnet. The VNIC determines how instances connect to endpoints inside and outside the VCN.</p>
_________________________________________________________________________

<h3>Private IP</h3>
<p>Private IPv4 addresses and related information for handling instances (for example, hostnames for DNS). The primary private IP address on the instance will not change as long as the instance is in use and cannot be removed from the instance.</p>

_________________________________________________________________________

<h3>Public IP</h3>
<p>Public IPv4 addresses and related information. Public IPs can be temporary or reserved.</p>
 
_________________________________________________________________________