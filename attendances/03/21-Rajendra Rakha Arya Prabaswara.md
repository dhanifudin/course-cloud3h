Nama : Rajendra Rakha Arya Prabaswara
NIM  : 1941720080
---

# Cloud Computing and Distributed Systems
## Oracle Cloud Services

There are 2 types of instances in Oracle Cloud:
* **Bare Metal**, Are computational instances that run physically so that their performance is higher.
* **Virtual Machine (VM)**, is a virtual working instance that allows multiple computers
in one resource working simultaneously.

## Type of Instance
### Shapes

That is a template that has specified specifications for the instance to be created, including:
* Standard shapes: designed for standard general requirements and provide optimal specifications for the application
frequently used.
* DenseIO shapes: designed for large databases, such as big data and applications that require high storage performance.
* High Performance Computing (HPC): designed for high-performance computing that requires high specifications.
* Optimized shapes: designed for high-level computing at processor core frequencies to provide HPC with low latency.

### Flexible Shapes

Flexible shapes are templates that can be customized to specifications when launching or changing VMs.
The types of flexible shapes available:
* VM.Standard.E3.Flex (AMD), 64GB per OCPU, 1024 GB Memory
* VM.Standard.E4.Flex (AMD), 64GB per OCPU, 1024 GB Memory
* VM.Optimized3.Flex (Intel), 64GB per OCPU, 256GB Memory
* VM.Standard.A1.Flex (ARM processor from Ampere), 64GB per OCPU, 512 GB Memory

## Capacity

When creating a VM, we can choose the capacity type of the instance, namely:
* On-Demand Capacity: just pay according to the capacity used.
* Preemptible capacity : when there is an increase in workload, this system will be activated.
* Reserved capacity: capacity that is not being used will cost different from the capacity that is being used.
* Dedicated capacity : capacity available for that instance only.