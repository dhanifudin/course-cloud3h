## Cloud Comuputing Distribution System
> OCI Services Category     :
                                - IN SaaS : ERP and Webmail
                                - IN PaaS : DB,OS,dan Java
                                - IN IaaS : Compute ,Storage,dan Network.
> OCI Core Services         :   
                               
                                - Compute
                                - Storage
                                - Networking
                                - Identity and Access Management (IAM)
                                - Database Cloud Service

Definition Of All :
    1.Compute : is one of the 5 pillars on which OCI is built. Oracle provides compute instances in order to provision and manage Compute hosts.
        Type Of Compute :
                            1) Bare Metal (BM) Instance: In Which you will get direct access to the underlying hardware. It gives a dedicated physical server for Highest performance & strong isolation. It is used for heavy workloads.

                            2) Virtual Machine (VM) Instance: VM instance runs on top of Bare Metal hardware. There is a hypervisor on top of Bare Metal server to virtualize it in smaller VMs. VMs are ideal for running applications that do not require the performance and resources (CPU, memory, network bandwidth, storage) of an entire physical machine.

                            3) Dedicated VM Host: It is the combination of Bare Metal and Virtual Machine. In this multiple VMs are running on Bare Metal and the whole server is dedicated to a single host. Till now Autoscaling & Instance pool is not supported in these instances.

        - Bare Metal is a blank server so users have to handle virtualization, operating system, language runtime, app containers and code.
        - Dedicated Virtual Host and Virtual Machines : Hosts is a single tenant model so no resources will be shared with other users and the     virtualization layer is handled by Oracle.
        - Examples of using VM are: Users want to set most of the operating system, such as OS Patch, security configuration, network, firewall, application configuration and manual or auto scaling to handle traffic needs. 
        
                            - Container Engine : The service is a Container runtime environment that allows users to run Containers and manage Container Images across many nodes.
                            - Oracle Function  : A service that allows users to simply write code.
                            
    4.Storage Model OCI
                            - Storage Services : There are 5 storage services supported by OCI, namely block volume, local NVME, file storage, object storage and archive storage.
    3.Networking        :   - VCN is a network that belongs to your virtual machine.
                            - VCN is a service that provides infrastructure as a service (IaaS).
                            - VCN allows customers to manage their current networks in the cloud. In this situation, we can configure the firewall as well as set the IP address, construct subnets, and route tables.
                            - Some of the components contained in the VCN:
                                    Subnets
                                    Route Table
                                    Security List
                                    Internet Gateway
                                    Nat Gateway
                                    Service Gateway
                                    Dynamic Router Gateway
    5.IAM               : IAM (Identity and Access Management) allows you to manage who has access to the cloud resources you own, as well as the types of access they have.
    6. Database Cloud Services :    - Oracle is the only public cloud that supports VM database systems, offering extremely fast provisioning.
                                    - OCI also supports bare metal database systems, which are extremely fast.
                                    - OCI has a choice Oracle Cluster Databases, also known as Real Application Clusters, or RAC, have been the choice for managing high availability and performance for more than 20 years.
                                    - OCI also offers the Exadata DB system, which offers extreme performance for both Online Transaction Processing (OLTP) and data warehouse applications.
                                    - OCI's latest invention is an autonomous database.





