# Pricing and Support

# [AWS Free Tier](#aws-free-tier)

**The [AWS Free Tier](https://aws.amazon.com/free/) enables you to begin using certain services without having to worry about incurring costs for the specified period.**

Three types of offers are available: 
- Always Free
- 12 Months Free
- Trials

---

### [Always free](#always-free)

These offers do not expire and are available to all AWS customers.

Examples:
-  AWS Lambda allows 1 million free requests and up to 3.2 million seconds of compute time per month. 
- Amazon DynamoDB allows 25 GB of free storage per month.

---

### [12 Months Free](#12-months-free)

These offers are free for 12 months following your initial sign-up date to AWS.

Examples:
- specific amounts of Amazon S3 Standard Storage, 
- thresholds for monthly hours of Amazon EC2 compute time, 
- amounts of Amazon CloudFront data transfer out.

---

### [Trials](#trials)

Short-term free trial offers start from the date you activate a particular service.

Examples:
- Amazon Inspector offers a 90-day free trial. 
- Amazon Lightsail offers 750 free hours of usage over a 30-day period.

---

# [How AWS Pricing Works](#how-aws-pricing-works)

AWS offers a range of cloud computing services with pay-as-you-go pricing. 

**Categories:**
1. **Pay for what you use.** For each service, you pay for exactly the amount of resources that you actually use, without requiring long-term contracts or complex licensing. 
2. **Pay less when you reserve.** Some services offer reservation options that provide a significant discount compared to On-Demand Instance pricing.
3. **Pay less with volume-based discounts when you use more.** Some services offer tiered pricing, so the per-unit cost is incrementally lower with increased usage.

---

# [AWS Pricing Calculator](#aws-pricing-calculator)

**[The AWS Pricing Calculator](https://calculator.aws/#/) lets you explore AWS services and create an estimate for the cost of your use cases on AWS.**

You can organize your AWS estimates by groups that you define. A group can reflect how your company is organized, such as providing estimates by cost center.

---

# [AWS Pricing Examples](#aws-pricing-examples)

## [AWS Lambda Pricing](#aws-lambda-pricing)

- You are charged based on the number of requests for your functions and the time that it takes for them to run.
- **1 million free requests** and up to **3.2 million seconds** of compute time per month.

You can save on AWS Lambda costs by signing up for a Compute Savings Plan. **A Compute Savings Plan offers lower compute costs in exchange for committing to a consistent amount of usage over a 1-year or 3-year term.** This is an example of **paying less when you reserve**. 

---

## [AWS EC2 Pricing](#aws-ec2-pricing)

- You pay for only the compute time that you use while your instances are running.
- For some workloads, you can significantly reduce Amazon EC2 costs by using Spot Instances. *For example, suppose that you are running a batch processing job that is able to withstand interruptions.*
- You can find additional cost savings for Amazon EC2 by considering Savings Plans and Reserved Instances.

---

## [AWS S3 Pricing](#aws-s3-pricing)

Consider the following cost components.

### [1. Storage](#1-storage)

You pay for only the storage that you use. You are charged based on:
- the objects' sizes
- storage classes
- how long you have stored each object during the month.

### [2. Request and data retrievals](#2-request-and-data-retrievals)

You pay for requests made to your Amazon S3 objects and buckets.

### [3. Data transfer](#3-data-transfer)

There is **no cost** to transfer data between different Amazon S3 buckets or from Amazon S3 to other services within the same AWS Region.

You **pay for data that you transfer into and out of Amazon S3**, with a few exceptions.

There is **no cost for data transferred into Amazon S3 from the internet or out to Amazon CloudFront**. 

There is also **no cost for data transferred out to an Amazon EC2 instance in the same AWS Region as the Amazon S3 bucket**.

### [4. Management and replication](#4-management-and-replication)

You pay for the storage management features that you have enabled on your account’s Amazon S3 buckets. These features include Amazon S3 inventory, analytics, and object tagging.

---

For each Region, charges are based on the following factors:
- The number of requests to add or copy objects into a bucket
- The number of requests to retrieve objects from a bucket
- The amount of storage space used.

---

# [Notes](#notes)

- S3 us free for 12 months for up to five gigs of storage.
- Amazon Lightsail is a service that enables you to run virtual private servers.
- **Pay less when you reserve** *Example*: suppose that your company is using Amazon EC2 instances for a workload that needs to run continuously. You might choose to run this workload on Amazon EC2 Instance Savings Plans, because the plan allows you to save up to 72% over the equivalent On-Demand Instance capacity.
- **Pay less with volume-based discounts when you use more** *Example*:  The more Amazon S3 storage space you use, the less you pay for it per GB.


---

# References

- [AWS S3 Pricing](https://aws.amazon.com/s3/pricing/)
- [AWS EC2 Pricing](https://aws.amazon.com/ec2/pricing/)
- [AWS Lambda Pricing](https://aws.amazon.com/lambda/pricing/)