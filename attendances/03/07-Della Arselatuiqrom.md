Summary of Week 3 Cloud Computing :

Iaas :

Oracle Cloud Infrastructure offers 2 types of instances namely bare metal and virtual machine (VM):
- Bare Metal: are bare metal compute instances that give you access to dedicated physical servers for ultimate performance and robust isolation.
- Virtual Machines: (VMs) are virtual independent computing environments running on bare metal physical hardware. Virtualization makes it possible to run multiple VMs that are isolated from each other.

Instance Type:

- Types of Shapes:
1. Standard Shapes : Standard shapes provide balanced resources on core, memory, and network. Standard shapes are available with Intel, AMD, and Arm-based processors.

2. DenseIO shapes: designed for large databases, such as big data and applications that require high storage performance. These Shapes get an SSD-based NVMe feature.

3. GPU Shapes: designed for hardware acceleration, especially GPU needs including Inter, AMD CPUs and NVIDIA graphics processors.

4. High performance computing (HPC) shapes: designed for high performance computing that requires high frequency of processor cores and HPC in network clusters accessed in parallel.

5. Optimized shapes: designed for high-level computing at processor core frequencies. This shape is also suitable for HPC needs with low latency. This shape also supports cluster networking.

-Flexible Shapes:
Flexible shapes is a template that can customize the amount of OCPU and memory when launching or changing a VM. When you create a VM using a flexible shape, the choice of the number of OCPUs and the required memory volume can be adjusted.

Type Capacity :
1. On-demand capacity: just pay according to the compute capacity that we use.

2. Preemptible capacity: useful when you need resources when the workload increases (autoscaling) for a certain period of time, so it is more cost effective.

3. Reserved capacity: reserve capacity that is useful for the future as needed. Unused spare capacity is calculated differently from the resources currently in use.

4. Dedicated capacity: running a VM instance on a dedicated server, so that resources are not shared with other clients/customers.