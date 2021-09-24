Infrastructure as a Service (IaaS) - Compute
Oracle Cloud Infrastructure Compute allows you to provision and manage compute hosts, known as instances. You can create as many instances as you need to meet your compute and application requirements.

Oracle Cloud Infrastructure offers 2 types of instances namely bare metal and virtual machine (VM):
Bare Metal: are bare metal compute instances that give you access to dedicated physical servers for highest performance and robust isolation.
Virtual Machine: A Virtual Machine (VM) is a virtual independent computing environment that runs on bare metal physical hardware. Virtualization makes it possible to run multiple VMs that are isolated from each other. VMs are ideal for running applications that do not require the performance and resources (CPU, memory, network bandwidth, storage) of the entire physical machine

Instance Types
When creating a compute instance, you can select the appropriate instance type based on resource characteristics such as the number of CPU cores required, the amount of memory and network resources.

Types of Shapes
OCI offers a wide variety of shapes. Shapes is a template that defines the required amount of CPU, memory volume, and other resources allocated to a compute instance. The following types of shapes are available:

- Standard shapes: designed for general needs that are widely used in application applications and use cases in general.
- DenseIO shapes: designed for large databases, such as big data and applications that require high storage performance.
- GPU shapes: designed for hardware acceleration especially GPU needs including Inter, AMD CPU and NVIDIA graphics processors.
- High performance computing (HPC) shapes: designed for high performance computing that requires high frequency of processor cores and HPC in network clusters accessed in parallel.
- Optimized shapes: designed for high-level computing at processor core frequencies. This shape is also suitable for HPC needs with low latency. This shape also supports cluster networking.

Flexible Shapes
Flexible shapes is a template that can customize the amount of OCPU and memory when launching or changing a VM.
The following types of flexible shapes are available:
• VM.Standard.E3.Flex (AMD)
• VM.Standard.E4.Flex (AMD)
• VM.Optimized3.Flex (Intel)
• VM.Standard.A1.Flex (Arm processor from Ampere)
