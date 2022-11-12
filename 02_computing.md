# Compute at AWS Cloud

# [Amazon EC2](#amazon-ec2)

**[Amazon Elastic Compute Cloud (Amazon EC2)](https://aws.amazon.com/ec2/)** provides secure, resizable compute capacity in the cloud as Amazon EC2 instances. 

When you spin up an EC2 instance, you aren't necessarily taking an entire host to yourself. Instead, you are sharing the host with multiple other instances, otherwise known as **virtual machines**. And a hypervisor running on the host machine is responsible for sharing the underlying physical resources between the virtual machines. This idea of sharing underlying hardware is called **multitenancy**.

EC2 instances are resizable. You might start with a small instance, but at some point you can give that instance more memory and more CPU. This is what we call **vertically scaling** an instance. 

---

## [How Amazon EC2 works](#how-amazon-ec2-works)

1. Launch an instance - select a template with basic configuration, instance type, security and network settings.
2. Connect to the instance (e.g. ssh)
3. Use instance - install software, add storage...

Some **benefits** of using Amazon EC2 include:

* You can provision and launch an Amazon EC2 instance within minutes.
* You can stop using it when you have finished running a workload.
* You pay only for the compute time you use when an instance is running, not when it is stopped or terminated.
* You can save costs by paying only for server capacity that you need or want.

---

## [Amazon EC2 instance types](#amazon-ec2-instance-types)

1. **General purpose instances provide a balance of compute, memory, and networking resources.** 

If you have an application in which the resource needs for compute, memory, and networking are roughly equivalent, you might consider running it on a general purpose instance because the application does not require optimization in any single resource area.

2. **Compute optimized instances are ideal for compute-bound applications that benefit from high-performance processors.** 

Ideal for compute-intensive tasks like gaming servers, high performance computing or HPC, and even scientific modeling.

3. **Memory optimized instances are designed to deliver fast performance for workloads that process large datasets in memory.**

4. **Accelerated computing instances use hardware accelerators, or coprocessors, to perform some functions more efficiently than is possible in software running on CPUs.**

Examples of these functions include floating-point number calculations, graphics processing, and data pattern matching. Accelerated computing instances are ideal for workloads such as graphics applications, game streaming, and application streaming.

5. **Storage optimized instances are designed for workloads that require high, sequential read and write access to large datasets on local storage.** 

---

## [Amazon EC2 Pricing](#amazon-ec2-pricing)

1. **On-Demand Instances are ideal for short-term, irregular workloads that cannot be interrupted.**

*Use cases:* developing and testing applications and running applications that have unpredictable usage patterns. Not recommended for workloads that last a year or longer.

2. **Amazon EC2 Savings Plans enable you to reduce your compute costs by committing to a consistent amount of compute usage for a 1-year or 3-year term.**

This term commitment results in savings of up to **72%** over On-Demand costs.

3. **Reserved Instances are a billing discount applied to the use of On-Demand Instances in your account.**

You can purchase **Standard Reserved** and **Convertible Reserved** Instances for a 1-year or 3-year term, and **Scheduled Reserved** Instances for a 1-year term. 

4. **Spot Instances are ideal for workloads with flexible start and end times, or that can withstand interruptions.**

Spot Instances use unused Amazon EC2 computing capacity and offer you cost savings at up to **90% off** of On-Demand prices.

5. **Dedicated Hosts are physical servers with Amazon EC2 instance capacity that is fully dedicated to your use.** 

You can use your existing *per-socket, per-core, or per-VM* software licenses to help maintain license compliance. 

You can purchase **On-Demand Dedicated Hosts** and **Dedicated Hosts Reservations.** 

---

### Notes
- In computing, the term *input/output operations per second (IOPS)* is a metric that measures the performance of a storage device. *Storage optimized* instances are designed to deliver tens of thousands of low-latency, random IOPS to applications. 
- **AWS Cost Explorer is a tool that enables you to visualize, understand, and manage your AWS costs and usage over time.**
-  If you are considering your options for Savings Plans, AWS Cost Explorer can analyze your Amazon EC2 usage over the past 7, 30, or 60 days. 
- Of all the Amazon EC2 Pricing options that were covered, **Dedicated Hosts are the most expensive.**

---

# References

