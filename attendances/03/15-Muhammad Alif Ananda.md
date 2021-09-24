#Summary

Today Summary is about Cloud Computing and Distributed Systems.


Cloud Computing is built from/with distributed computing. Technically, if you have an application which syncs up information across several of your devices you are doing cloud computing and since it is using distributed computing.

there's a Types of Compute. which is :

- Bare Metal: are bare metal compute instances that give you access to dedicated physical servers for highest performance and robust isolation.
- Virtual Machine: (VM) is a virtual independent computing environment that runs on bare metal physical hardware. Virtualization makes it possible to run multiple VMs that are isolated from each other. VMs are ideal for running applications that do not require the performance and resources (CPU, memory, network bandwidth, storage) of the entire physical machine.

When creating a compute instance, you can select the appropriate instance type based on resource characteristics such as the number of CPU cores required, the amount of memory and network resources.

OCI offers a wide variety of shapes. Shapes is a template that defines the required amount of CPU, memory volume, and other resources allocated to a compute instance. The following types of shapes are available:

- Standard shapes: designed for general needs that are widely used in applications and use cases in general. Standard shapes provide balanced resources on core, memory, and network. Standard shapes are available with Intel, AMD, and Arm-based processors.

- DenseIO shapes: designed for large databases, such as big data and applications that require high storage performance. These Shapes get an SSD-based NVMe feature.

- GPU shapes: designed for hardware acceleration especially GPU needs including Inter, AMD CPUs and NVIDIA graphics processors.

- High performance computing (HPC) shapes: designed for high performance computing that requires high frequency of processor cores and HPC in network clusters accessed in parallel.

- Optimized shapes: designed for high-level computing at processor core frequencies. This shape is also suitable for HPC needs with low latency. This shape also supports cluster networking.


We can choose the capacity of each type of host used for the VM. By default the on-demand type capacity is selected, but it is also possible to select other capacity types.

- On-demand capacity: just pay according to the compute capacity that we use.
- Preemptible capacity: useful when you need resources when the workload increases (autoscaling) for a certain period of time, making it more cost-effective.
- Reserved capacity: reserve capacity that is useful for the future as needed. Unused spare capacity is calculated differently from the resources currently in use.
- Dedicated capacity: running a VM instance on a dedicated server, so that resources are not shared with other clients/customers.
