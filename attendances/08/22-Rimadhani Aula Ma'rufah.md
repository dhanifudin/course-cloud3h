 OBJECT STORAGE
        The Oracle Cloud Infrastructure Object Storage service is a high-performance and scalable storage platform, offering reliable and cost-effective data resilience. 
The Object Storage service can store an unlimited amount of unstructured data of any type of content, including analytics data and content (such as images and videos). 
Oracle Cloud Infrastructure has various types of Object Storage for managing and storing data, such as:
1. Buckets
        A bucket is a logical container for storing objects. Users or systems create buckets as needed within a region. A bucket is associated with a single compartment (a collection of resources that can 
   only be accessed by a group that has been granted permission by an administrator in the organization) that has policies (Identity and Access Management (IAM) documents are used to determine who has 
   what type of access to our resources) to determine actions what the user can do on the bucket and on all objects in the bucket.
2.  Objects
        All data types, regardless of their content type, are stored as objects. An object consists of the object itself and metadata about that object. Each object is stored in a bucket
3.  Namespace
        The Object Storage namespace acts as a top-level container for all buckets and objects. At the time of account creation, each Oracle Cloud Infrastructure tenant is assigned a unique Object Storage 
    namespace name that is created by the system and cannot be changed. The namespace includes all the compartments within a region. 
4.  Compartment
        Compartments are the primary building blocks used to organize cloud resources. When renting, a root compartment is created to then create a compartment under the root compartment to 
    manage your resources. 
Object Storage Characteristics
Object Storage provides the following features:
1. Strong Consistency
    When there is a read request, Object Storage will make the most recent copy of the data written to the system.
2. Durability
    Object Storage is a regional service. Data is stored redundantly across multiple storage servers. Object Storage actively monitors data integrity using checksums and automatically detects 
  and repairs corrupted data. Object Storage actively monitors and ensures data redundancy. If redundancy loss is detected, Object Storage automatically creates more copies of the data.
3. Custom Metadata
    We can define our own extensive metadata as key-value pairs for any purpose. For example, we can create descriptive tags for objects, retrieve those tags, and sort the data. We can assign custom 
  metadata to objects and buckets using the Oracle Cloud Infrastructure CLI or SDK.
4. Security
      Object Storage ensures the security of data stored using data encryption. Data encryption is a method used to protect the confidentiality of data. The data can be accessed using the decryption key 
    generated when uploading the object to the bucket. It is used in conjunction with an IAM policy that authenticates the user performing the task.
