# Komputasi Awan dan Sistem Terdistribusi

## 03 – IaaS (Compute)

Oracle Cloud Infrastructure offers 2 types of instances namely bare metal and virtual machine (VM):
- Bare Metal: are bare metal compute instances that give you access to dedicated physical servers for highest performance and robust isolation.
- Virtual Machine: (VM) is a virtual independent computing environment that runs on bare metal physical hardware. Virtualization makes it possible to run multiple VMs that are isolated from each other. 

## Shapes Type
OCI offers a wide variety of shapes. Shapes is a template that defines the required amount of CPU, memory volume, and other resources allocated to a compute instance.
<br>
1. Standard shapes: designed for general needs that are widely used in applications and use cases in general. 
2. DenseIO shapes: designed for large databases, such as big data and applications that require high storage performance.
3. GPU shapes: designed for hardware acceleration especially GPU requirements including Inter, AMD CPUs and NVIDIA graphics processors.
4. High performance computing (HPC) shapes: designed for high performance computing that requires high frequency of processor cores and HPC in network clusters accessed in parallel.
5. Optimized shapes: designed for high-level computing at processor core frequencies. This shape is also suitable for HPC needs with low latency. This shape also supports cluster networking.

### Flexible Shape
The types of flexible shapes available:
- VM.Standard.E3.Flex (AMD)
- VM.Standard.E4.Flex (AMD)
- VM.Optimized3.Flex (Intel)
- VM.Standard.A1.Flex (Arm processor from Ampere)

## Capacity Type
- On-demand capacity: just pay according to the compute capacity that we use.
- Preemptible capacity: useful when you need resources when the workload increases (autoscaling) for a certain period of time, making it more cost-effective.
- Reserved capacity: reserve capacity that is useful for the future as needed. Unused spare capacity is calculated differently from the resources currently in use.
- Dedicated capacity: running a VM instance on a dedicated server, so that resources are not shared with other clients/customers.