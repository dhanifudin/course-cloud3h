Resume week 3 by Ahmad Mahfudin Alwi

# Oracle Cloud Infrastructure instance types

<ol>

<li>Bare Metal</li>

Bare metal are bare metal compute instances that give you access to dedicated physical servers for highest performance and robust isolation.

<li>Virtual Machine (VM)</li>

VM is a virtual independent computing environment that runs on bare metal physical hardware. Virtualization makes it possible to run multiple VMs that are isolated from each other.

</ol>

# Shapes

Shapes is a template that defines the required amount of CPU, memory volume, and other resources allocated to a compute instance.

<ol>

<li>Standard shapes</li>

designed for general needs that are widely used in applications and use cases in general.

<li>DenseIO shapes</li>

designed for large databases, such as big data and applications that require high storage performance.

<li>GPU shapes</li>

designed for hardware acceleration especially GPU needs including Intel, AMD CPUs and NVIDIA graphics processors.

<li>High performance computing (HPC) shapes</li>

designed for high-performance computing that requires high frequency of processor cores and HPC in network clusters accessed in parallel.

<li>Optimized shapes</li>

designed for high-level computing at processor core frequencies. This shape is also suitable for HPC needs with low latency. This shape also supports cluster networking.

</ol>

## Flexible Shapes

Flexible shapes is a template that can customize the amount of OCPU and memory when launching or changing a VM. An OCPU is equivalent to one physical core with simultaneous multithreading (hyper-threading), where each OCPU refers to two hardware executing threads (also known as virtual CPUs or vCPUs). When you create a VM using a flexible shape, the choice of the number of OCPUs and the required memory volume can be adjusted. The following types of flexible shapes are available:

<ol>

<li> VM.Standard.E3.Flex (AMD) </li>
<li> VM.Standard.E4.Flex (AMD)
<li> VM.Optimized3.Flex (Intel)
<li> VM.Standard.A1.Flex (Arm processor from Ampere)

</ol>

We also learned in today’s lesson that when creating a VM instance we can specify the CPU processor, the software image, how much computing power whither that would be adding more RAM or GPU.
