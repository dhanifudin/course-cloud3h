Nama : Rajendra Rakha Arya Prabaswara

NIM  : 1941720080

---

# Summary Week 8

# Oracle Cloud Infrastructure Object Storage Service

The Object Storage service can store an unlimited amount of unstructured data from
any type of content, including analytic data and content (such as images and videos). This service
used when the application that we use uses the data upload feature. Support elasticity platform
We scale to use the smallest (minimum) capacity to the maximum,
without experiencing a decrease in service performance or reliability.

# Object Storage

Is a regional service and does not depend on a specific compute instance.
We can access data from anywhere within or outside the context of Oracle Cloud Infrastructure,
as long as you have internet connectivity and can access any of the Object Storage endpoints.
Object Storage supports private access of existing Oracle Cloud Infrastructure resources
on the VCN through the gateway service.

# Object Storage Resources

Oracle Cloud Infrastructure has various types of Object Storage to manage
and store data, including:
1. A bucket is a logical container for storing objects. Users or systems create buckets as needed within a region.
2. Objects, all data types, regardless of content type, are stored as objects.
3. Namespace, serves as a top-level container for all buckets and objects. We can control the bucket name, but
the bucket name must be unique in the namespace. Although the namespace is region specific,
the namespace name itself is the same in all regions.
4. Compartments are the main building blocks used to organize cloud resources.
We can control access by creating policies that define what actions can be
the user group performs on the resources in that compartment.
The Object Storage Bucket can only exist in one compartment.

# Object Storage Characteristics

1. Strong Consistency, When there is a read request, Object Storage will make the latest copy of the data written to the system.
2. Durability, Object Storage is a regional service. Data is stored redundantly across multiple servers
storage. Object Storage actively monitors and ensures data redundancy. If redundancy loss is detected,
Object Storage automatically creates more copies of the data.
3. Custom Metadata, we can define our own extensive metadata as key-value pairs for
any purpose. For example, we can create descriptive tags for objects, retrieve those tags, and
sorting data.
4. Security, Object Storage ensures the security of data stored using data encryption.

# How to access Object Storage

We can access Object Storage using several ways, OCI provides accordingly
according to our preferences and according to needs:
1. Console
2. CLI
3. REST API
4. OCI SDK

# Authentication and Authorization

Every service in Oracle Cloud Infrastructure is integrated with IAM for authentication and
authorization, for all interfaces (Console, SDK or CLI, and REST API). IAM also manages
user credentials API signing keys , authentication token and secret key for API compatibility
Amazon S3. We need to set up or create groups, compartments and policies that control
which users can access the service, resources and access type. For example, policy
control who can create users and groups, create buckets, download objects and
manage policies and rules regarding Object Storage.

# Blocking Access to Object Storage Resources from Unauthorized IP Addresses.

We can increase the security of Object Storage policies by restricting access to only
for requests originating from allowed IP addresses. First, we create a network source
(IP address groups can be used in policies to restrict access) to specify IP addresses
allowed, then we add a condition to the policy to restrict access to IP addresses in
network resources.

# Object Storage IP Addresses

Oracle Cloud Infrastructure Object Storage service using CIDR with IP range blocks
134.70.0.0/16 for all regions.
