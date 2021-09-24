# Cloud Computing - 3

Instance: 
- Standard shapes: for general needs. Balanced memory, core and network resources
- DenseIo shapes: for large databases such as big data. Using NVMe SSD
- GPU shapes: for GPU acceleration
- High performances computing (HPC) shapes: for those who need high processor core acceleration and HPC in parallel accessed networks
- Optimized shapes: for those who need high-level computing

We can choose capacity each host for VM
- On-demand capacity: just pay according to the compute capacity you use
- Preemptible capacity: useful when needing resources when the workload increases
- Reserved capacity: reserve capacity for the future
- Dedicated capacity: resources are not shared with others

Component when create VM
- Availability domain: geographic location of oracle data
- Virtual cloud network: network configuration (subnet, gateway, etc)
- Key pair (Linux) : security for SSH to instance
- Tags: helps to process instances with tags so they are easy to find
- Password (Windows): security for instance access
- Image: virtual hard drive templates that define OS and other software
- Shape: templates determine the amount of CPU, memory, and other resource allocations
