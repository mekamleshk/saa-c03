# EC2 Instance Types - Overview

You can use different types of EC2 instances that are optimized for different use cases ([AWS EC2 Instance Types](https://aws.amazon.com/ec2/instance-types/))  
AWS has the following naming convention:  
`m5.2xlarge`  
- **m:** instance class  
- **5:** generation (AWS improves them over time)  
- **2xlarge:** size within the instance class  
<br/><br/>

# General Purpose

| Instance Types                                                              |
| --------------------------------------------------------------------------- |
| M5, M5a, M5ad, M5d, M5dn, M5n, M5zn, M6a, M6g, M6gd, M6i, M6id, M6idn, M6in |
| --------------------------------------------------------------------------- |
| M7a, M7g, M7gd, M7i, M7i-flex, M8a, M8g, M8gb, M8gd, M8gn, M8i, M8i-flex    |
| --------------------------------------------------------------------------- |
| Mac1, Mac2, Mac2-m1ultra, Mac2-m2, Mac2-m2pro, Mac-m4, Mac-m4pro            |
| --------------------------------------------------------------------------- |
| T2, T3, T3a, T4g                                                            |


- **Provide a balance of compute, memory, and networking resources.**  
- These instances are ideal for applications that use these resources in equal proportions, such as web servers and code repositories.  
- The **T** instance family is also referred to as burstable performance instances. These instances provide a baseline CPU performance with the ability to burst above the baseline at any time. For more information, see [Burstable performance instances in the Amazon EC2 User Guide](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/burstable-performance-instances.html).

<br/>

# Compute Optimized

| Instance Types                                                                   |
| -------------------------------------------------------------------------------- |
| C5, C5a, C5ad, C5d, C5n, C6a, C6g, C6gn, C6i, C6id, C6in, C7a, C7g, C7gd, C7gn   |
| -------------------------------------------------------------------------------- |
| C7i, C7i-flex, C8a, C8g, C8gb, C8gd, C8gn, C8i, C8i-flex                         |

- Designed for compute-intensive applications that benefit from high-performance processors.  
- These instances are ideal for batch processing workloads, media transcoding, high-performance web servers, high-performance computing (HPC), scientific modeling, dedicated gaming servers, ad server engines, and machine learning inference.  
  
<br/>

# Memory Optimized

| Instance Types                                                           |
| ------------------------------------------------------------------------ |
| R5, R5a, R5ad, R5b, R5d, R5dn, R5n                                       |
| -----------------------------------------------------------------------  |
| R6a, R6g, R6gd, R6i, R6id, R6idn, R6in                                   |
| -----------------------------------------------------------------------  |
| R7a, R7g, R7gd, R7i, R7iz                                                |
| ------------------------------------------------------------------------ |
| R8a, R8g, R8gb, R8gd, R8gn, R8i, R8i-flex                                |
| ------------------------------------------------------------------------ |
| U-3tb1, U-6tb1, U-9tb1, U-12tb1, U-18tb1, U-24tb1                        |
| ------------------------------------------------------------------------ |
| U7i-6tb, U7i-8tb, U7i-12tb, U7in-16tb, U7in-24tb, U7in-32tb, U7inh-32tb  |
| ------------------------------------------------------------------------ |
| X1, X1e, X2gd, X2idn, X2iedn, X2iezn                                     |
| ------------------------------------------------------------------------ |
| X8g, X8aedz, z1d                                                         |
| ------------------------------------------------------------------------ |

- Designed to deliver fast performance for workloads that process large data sets in memory.  
<br/>

# Storage Optimized

| Instance Types                |
| ----------------------------- |
| D2, D3, D3en, H1              |
| ----------------------------- |
| I3, I3en, I4g, I4i, I7i, I7ie |
| ----------------------------- |
| I8g, I8ge, Im4gn, Is4gen      |
| ----------------------------- |

- Designed for workloads that require high, sequential read and write access to very large data sets on local storage.  
- They are optimized to deliver tens of thousands of low-latency, random I/O operations per second (IOPS) to applications.  
<br/>

## Accelerated Computing

| Instance Types                             |
| ------------------------------------------ |
| DL1, DL2q, F1, F2                          |
| ------------------------------------------ |
| G4ad, G4dn, G5, G5g, G6, G6e, G6f          |
| ------------------------------------------ |
| Gr6, Gr6f, Inf1, Inf2, P4d, P4de           |
| ------------------------------------------ |
| P5, P5e, P5en, P6-B200, P6-B300, P6e-GB200 |
| ------------------------------------------ |
| Trn1, Trn1n, Trn2, Trn2u, VT1              |

- Use hardware accelerators, or co-processors, to perform functions, such as floating-point number calculations, graphics processing, or data pattern matching, more efficiently than is possible in software running on CPUs.  
<br/>

# High-Performance Computing

| Instance Types              |
| --------------------------- |
| Hpc6a, Hpc6id, Hpc7a, Hpc7g |

- Purpose-built to offer the best price performance for running HPC workloads at scale on AWS.  
- These instances are ideal for applications that benefit from high-performance processors, such as large, complex simulations and deep learning workloads.  
