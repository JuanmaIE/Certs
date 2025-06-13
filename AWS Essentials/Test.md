### What is cloud computing?

Backing up files that are stored on desktop and mobile devices to prevent data loss

Deploying applications connected to on-premises infrastructure

Running code without needing to manage or provision servers

- On-demand delivery of IT resources and applications through the internet with pay-as-you-go pricing

The correct response option is **On-demand delivery of IT resources and applications through the internet with pay-as-you-go pricing**.

The other response options are incorrect because:

- It is possible to back up files to the cloud, but this response option does not describe cloud computing as a whole.
- Deploying applications connected to on-premises infrastructure is a sample use case for a hybrid cloud deployment. Remember that cloud computing also has cloud and on-premises (or private cloud) deployment models.
- AWS Lambda is an AWS service that lets you run code without needing to manage or provision servers. This description does not describe cloud computing as a whole. AWS Lambda is explained in greater detail later in the course.

### What is another name for on-premises deployment?

- Private cloud deployment

Cloud-based application

Hybrid deployment

AWS Cloud

The correct response option is **Private cloud deployment**.

The other response options are incorrect because:

- Cloud-based applications are fully deployed in the cloud and do not have any parts that run on premises.
- A hybrid deployment connects infrastructure and applications between cloud-based resources and existing resources that are not in the cloud, such as on-premises resources. However, a hybrid deployment is not equivalent to an on-premises deployment because it involves resources that are located in the cloud.
- The AWS Cloud offers three cloud deployment models: cloud, hybrid, and on-premises. This response option is incorrect because the AWS Cloud is not equivalent to only an on-premises deployment.

### How does the scale of cloud computing help you to save costs?

You do not have to invest in technology resources before using them.

- The aggregated cloud usage from a large number of customers results in lower pay-as-you-go prices.

Accessing services on-demand helps to prevent excess or limited capacity.

You can quickly deploy applications to customers and provide them with low latency.

The correct response option is **The aggregated cloud usage from a large number of customers results in lower pay-as-you-go prices**.

This answer describes how customers can benefit from massive economies of scale in cloud computing.

The other response options are incorrect because:

- Not having to invest in technology resources before using them relates to _Trade upfront expense for variable expense_.
- Accessing services on-demand to prevent excess or limited capacity relates to _Stop guessing capacity_.
- Quickly deploying applications to customers and providing them with low latency relates to _Go global in minutes_.

---

### Which Amazon EC2 instance type is suitable for data warehousing applications?

Memory optimized

- Storage optimized

General purpose

Compute optimized

### Which Amazon EC2 instance type balances compute, memory, and networking resources?

Memory optimized

Storage optimized

- General purpose

Compute optimized

### Which Amazon EC2 instance type is ideal for high-performance databases?

- Memory optimized

Storage optimized

General purpose

Compute optimized

### Which Amazon EC2 instance type offers high-performance processors?

Memory optimized

Storage optimized

General purpose

- Compute optimized

---

### Which Amazon EC2 pricing option provides a discount when you specify a number of EC2 instances to run a specific OS, instance family and size, and tenancy in one Region?

Convertible Reserved Instances

EC2 Instance Savings Plans

Spot Instances

- Standard Reserved Instances

Correct!  Standard Reserved Instances require you to specify: 

- instance family and size
- platform description
- tenancy
- Region

Your specified amount of EC2 instances are covered over a 1-year or 3-year term.

### Which Amazon EC2 pricing option provides a discount when you make an hourly spend commitment to an instance family and Region for a 1-year or 3-year term?

On-demand

- EC2 Instance Savings Plans

Spot Instances

Reserved Instances

---

### Which AWS service is the best choice for publishing messages to subscribers?

Amazon Simple Queue Service (Amazon SQS)

Amazon EC2 Auto Scaling

- Amazon Simple Notification Service (Amazon SNS)

Elastic Load Balancing

The correct response option is **Amazon Simple Notification Service (Amazon SNS)**.

Amazon SNS is a publish/subscribe service. Using Amazon SNS topics, a publisher publishes messages to subscribers.

The other response options are incorrect because:

- Amazon Simple Queue Service (Amazon SQS) is a message queuing service. It does not use the message subscription and topic model that is involved with Amazon SNS.
- Amazon EC2 Auto Scaling enables you to automatically add or remove Amazon EC2 instances in response to changing application demand.
- Elastic Load Balancing is the AWS service that automatically distributes incoming application traffic across multiple resources, such as Amazon EC2 instances.

**Learn more:**

- [Amazon SNS](https://aws.amazon.com/sns)

---

### You want to use an Amazon EC2 instance for a batch processing workload. What would be the best Amazon EC2 instance type to use?

General purpose

Memory optimized

- Compute optimized

Storage optimized

The correct response option is **Compute optimized**.

The other response options are incorrect because:

- General purpose instances provide a balance of compute, memory, and networking resources. This instance family would not be the best choice for the application in this scenario. Compute optimized instances are more well suited for batch processing workloads than general purpose instances.
- Memory optimized instances are more ideal for workloads that process large datasets in memory, such as high-performance databases.
- Storage optimized instances are designed for workloads that require high, sequential read and write access to large datasets on local storage. The question does not specify the size of data that will be processed. Batch processing involves processing data in groups. A compute optimized instance is ideal for this type of workload, which would benefit from a high-performance processor.

**Learn more:**

- [Amazon EC2 instance types](https://aws.amazon.com/ec2/instance-types/)

### What are the contract length options for Amazon EC2 Reserved Instances? (Select TWO.)

- 1 year <>
    
- 2 years
    
- 3 years <>
    
- 4 years
    
- 5 years

The two correct response options are:

- **1 year**
- **3 years**

Reserved Instances require a commitment of either 1 year or 3 years. The 3-year option offers a larger discount.

  

**Learn more:**

- [Amazon EC2 Reserved Instances](https://aws.amazon.com/ec2/pricing/reserved-instances/)

### You have a workload that will run for a total of 6 months and can withstand interruptions. What would be the most cost-efficient Amazon EC2 purchasing option?

Reserved Instance

- Spot Instance

Dedicated Instance

On-Demand Instance

The correct response option is **Spot Instance**.

The other response options are incorrect because:

- Reserved Instances require a contract length of either 1 year or 3 years. The workload in this scenario will only be running for 6 months.
- Dedicated Instances run in a virtual private cloud (VPC) on hardware that is dedicated to a single customer. They have a higher cost than the other response options, which run on shared hardware.
- On-Demand Instances fulfill the requirements of running for only 6 months. However, a Spot Instance would be the best choice because it does not require a minimum contract length, is able to withstand interruptions, and costs less than an On-Demand Instance.

**Learn more:**

- [Amazon EC2 pricing](https://aws.amazon.com/ec2/pricing/)

### Which process is an example of Elastic Load Balancing?

- Ensuring that no single Amazon EC2 instance has to carry the full workload on its own

Removing unneeded Amazon EC2 instances when demand is low

Adding a second Amazon EC2 instance during an online store’s popular sale

Automatically adjusting the number of Amazon EC2 instances to meet demand

The correct response option is **Ensuring that no single Amazon EC2 instance has to carry the full workload on its own**.

Elastic Load Balancing is the AWS service that automatically distributes incoming application traffic across multiple resources, such as Amazon EC2 instances. This helps to ensure that no single resource becomes overutilized.

The other response options are all examples of Auto Scaling.

  

**Learn more:**

- [Elastic Load Balancing(opens in a new tab)](https://aws.amazon.com/elasticloadbalancing)
- [Amazon EC2 Auto Scaling(opens in a new tab)](https://aws.amazon.com/ec2/autoscaling)

### You want to deploy and manage containerized applications. Which service should you use?

AWS Lambda

Amazon Simple Notification Service (Amazon SNS)

Amazon Simple Queue Service (Amazon SQS)

- Amazon Elastic Kubernetes Service (Amazon EKS)

The correct response option is **Amazon Elastic Kubernetes Service (Amazon EKS)**.

Amazon EKS is a fully managed Kubernetes service. Kubernetes is open-source software that enables you to deploy and manage containerized applications at scale.

The other response options are incorrect because:

- AWS Lambda is a service that lets you run code without provisioning or managing servers.
- Amazon Simple Queue Service (Amazon SQS) is a service that enables you to send, store, and receive messages between software components through a queue.
- Amazon Simple Notification Service (Amazon SNS) is a publish/subscribe service. Using Amazon SNS topics, a publisher publishes messages to subscribers.

**Learn more:**

- [Amazon EKS](https://aws.amazon.com/eks)

---

### Which statement best describes an Availability Zone?

A geographical area that contains AWS resources

- A single data center or group of data centers within a Region

A data center that an AWS service uses to perform service-specific operations

A service that you can use to run AWS infrastructure within your own on-premises data center in a hybrid approach

The correct response option is **A single data center or group of data centers within a Region**.

The other response options are incorrect because:

- A Region is a geographical area that contains AWS resources.
- An edge location is a data center that an AWS service uses to perform service-specific operations. Edge locations are examined in the next section of this module.
- AWS Outposts is a service that you can use to run AWS infrastructure, services, and tools in your own on-premises data center in a hybrid approach. AWS Outposts is explored later in this module.

**Learn more:**

- [AWS global infrastructure(opens in a new tab)](https://aws.amazon.com/about-aws/global-infrastructure)
- [Regions and Availability Zones](https://aws.amazon.com/about-aws/global-infrastructure/regions_az)

---


### Which statement is TRUE for the AWS global infrastructure?

A Region consists of a single Availability Zone.

An Availability Zone consists of two or more Regions.

- A Region consists of three or more Availability Zones.

An Availability Zone consists of a single Region.

The correct response option is **A Region consists of three or more Availability Zones**.

For example, the South America (São Paulo) Region is sa-east-1. It includes three Availability Zones: sa-east-1**a**, sa-east-1**b**, and sa-east-1**c**.

  

**Learn more:**

- [AWS global infrastructure(opens in a new tab)](https://aws.amazon.com/about-aws/global-infrastructure)
- [Regions and Availability Zones](https://aws.amazon.com/about-aws/global-infrastructure/regions_az)

### Which factors should be considered when selecting a Region? (Select TWO.)

- Compliance with data governance and legal requirements <>
    
- Proximity to your customers <>
    
- Access to 24/7 technical support
    
- Ability to assign custom permissions to different users
    
- Access to the AWS Command Line Interface (AWS CLI)

The correct two response options are:

- **Compliance with data governance and legal requirements**
- **Proximity to your customers**

Two other factors to consider when selecting a Region are pricing and the services that are available in a Region.

The other response options are incorrect because:

- The level of support that you choose is not determined by Region. AWS Support plans are explored later in this course.
- Assigning custom permissions to different users is a feature that is possible in all AWS Regions.
- The AWS Command Line Interface (AWS CLI) is available in all AWS Regions.

**Learn more:**

- [Choosing Regions and Availability Zones](https://docs.aws.amazon.com/AmazonElastiCache/latest/mem-ug/RegionsAndAZs.html)

### Which statement best describes Amazon CloudFront?

A service that enables you to run infrastructure in a hybrid cloud approach

A serverless compute engine for containers

A service that enables you to send and receive messages between software components through a queue

- A global content delivery service

The correct response option is **A global content delivery service**.

Amazon CloudFront is a content delivery service. It uses a network of edge locations to cache content and deliver content to customers all over the world. When content is cached, it is stored locally as a copy. This content might be video files, photos, webpages, and so on.

The other response options are incorrect because:

- AWS Outposts is a service that enables you to run infrastructure in a hybrid cloud approach.
- AWS Fargate is a serverless compute engine for containers.
- Amazon Simple Queue Service (Amazon SQS) is a service that enables you to send, store, and receive messages between software components through a queue.

**Learn more:**

- [Amazon CloudFront](https://aws.amazon.com/cloudfront)

### Which site does Amazon CloudFront use to cache copies of content for faster delivery to users at any location?

Region

Availability Zone

- Edge location

Origin

The correct response option is **Edge location**.

The other response options are incorrect because:

- A Region is a separate geographical location with multiple locations that are isolated from each other.
- An Availability Zone is a fully isolated portion of the AWS global infrastructure.
- An origin is the server from which CloudFront gets your files. Examples of CloudFront origins include Amazon Simple Storage Service (Amazon S3) buckets and web servers. **Note**: Amazon S3 is explored later in this course.

**Learn more:**

- [Amazon CloudFront infrastructure](https://aws.amazon.com/cloudfront/features/?nc=sn&loc=2#Amazon_CloudFront_Infrastructure)

### Which action can you perform with AWS Outposts?

Automate actions for AWS services and applications through scripts.

Access wizards and automated workflows to perform tasks in AWS services.

Develop AWS applications in supported programming languages.

- Extend AWS infrastructure and services to different locations including your on-premises data center.

The correct response option is **Extend AWS infrastructure and services to different locations, including your on-premises data center**.

The other response options are incorrect because:

- The AWS Command Line Interface (AWS CLI) is used to automate actions for AWS services and applications through scripts.
- The AWS Management Console includes wizards and workflows that you can use to complete tasks in AWS services.
- Software development kits (SDKs) enable you to develop AWS applications in supported programming languages.

**Learn more:**

- [AWS Outposts](https://aws.amazon.com/outposts/)

---

### Which statement best describes an AWS account’s default network access control list?

It is stateless and denies all inbound and outbound traffic.

It is stateful and allows all inbound and outbound traffic.

- It is stateless and allows all inbound and outbound traffic.

It is stateful and denies all inbound and outbound traffic.

The correct response option is **It is stateless and allows all inbound and outbound traffic**.

Network access control lists (ACLs) perform **stateless** packet filtering. They remember nothing and check packets that cross the subnet border each way: inbound and outbound.

Each AWS account includes a default network ACL. When configuring your VPC, you can use your account’s default network ACL or create custom network ACLs.

By default, your account’s default network ACL allows all inbound and outbound traffic, but you can modify it by adding your own rules. For custom network ACLs, all inbound and outbound traffic is denied until you add rules to specify which traffic should be allowed. Additionally, all network ACLs have an explicit deny rule. This rule ensures that if a packet doesn’t match any of the other rules on the list, the packet is denied.

  

**Learn more:**

- [Network ACLs](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-network-acls.html)

---

### Which statement best describes DNS resolution?

Launching resources in a virtual network that you define

Storing local copies of content at edge locations around the world

Connecting a VPC to the internet

- Translating a domain name to an IP address

The correct response option is **Translating a domain name to an IP address**.

For example, if you want to visit AnyCompany’s website, you enter the domain name into your PC and this request is sent to a DNS server. Next, the DNS server asks the web server for the IP address that corresponds to AnyCompany’s website. The web server responds by providing the IP address for AnyCompany’s website, 192.0.2.0.

  

**Learn more:**

- [Amazon Route 53](https://aws.amazon.com/route53/)

---

### Your company has an application that uses Amazon EC2 instances to run the customer-facing website and Amazon RDS database instances to store customers’ personal information. How should the developer configure the VPC according to best practices?

Place the Amazon EC2 instances in a private subnet and the Amazon RDS database instances in a public subnet.

- Place the Amazon EC2 instances in a public subnet and the Amazon RDS database instances in a private subnet.

Place the Amazon EC2 instances and the Amazon RDS database instances in a public subnet.

Place the Amazon EC2 instances and the Amazon RDS database instances in a private subnet.

The correct response option is **Place the Amazon EC2 instances in a public subnet and the Amazon RDS databases instances in a private subnet**.

A **subnet** is a section of a VPC in which you can group resources based on security or operational needs. Subnets can be public or private.

Public subnets contain resources that need to be accessible by the public, such as an online store’s website.

Private subnets contain resources that should be accessible only through your private network, such as a database that contains customers’ personal information and order histories.

  

**Learn more:**

- [Amazon VPC(opens in a new tab)](https://aws.amazon.com/vpc)
- [VPCs and subnets](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Subnets.html)

### Which component can be used to establish a private dedicated connection between your company’s data center and AWS?

Private subnet

DNS

- AWS Direct Connect

Virtual private gateway

The correct response option is **AWS Direct Connect**.

The other response options are incorrect because:

- A private subnet is a section of a VPC in which you can group resources that should be accessed only through your private network. Although it is private, it is not used for establishing a connection between a data center and AWS.
- DNS stands for Domain Name System, which is a directory used for matching domain names to IP addresses.
- A virtual private gateway enables you to create a VPN connection between your VPC and a private network, such as your company’s data center. Although this connection is private and encrypted, it travels through the public internet, not through a dedicated connection.

**Learn more:**

- [AWS Direct Connect](https://aws.amazon.com/directconnect)

### Which statement best describes security groups?

- They are stateful and deny all inbound traffic by default.

They are stateful and allow all inbound traffic by default.

They are stateless and deny all inbound traffic by default.

They are stateless and allow all inbound traffic by default.

The correct response option is **Security groups are stateful and deny all inbound traffic by default**.

  

Security groups are stateful. This means that they use previous traffic patterns and flows when evaluating new requests for an instance.

  

By default, security groups deny all inbound traffic, but you can add custom rules to fit your operational and security needs.

  

**Learn more:**

- [Security groups for your VPC](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_SecurityGroups.html)

### Which component is used to connect a VPC to the internet?

Public subnet

Edge location

Security group

- Internet gateway

The correct response option is **I****nternet gateway.**

  
 The other response options are incorrect because:

- A public subnet is a section of a VPC that contains public-facing resources.
- An edge location is a site that Amazon CloudFront uses to store cached copies of your content for faster delivery to customers.
- A security group is a virtual firewall that controls inbound and outbound traffic for an Amazon EC2 instance.

**Learn more:**

- [Internet gateways](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Internet_Gateway.html)

### Which service is used to manage the DNS records for domain names?

Amazon Virtual Private Cloud

AWS Direct Connect

Amazon CloudFront

- Amazon Route 53

The correct response option is **Amazon Route 53**.

Amazon Route 53 is a DNS web service. It gives developers and businesses a reliable way to route end users to internet applications that host in AWS.

  

Another feature of Route 53 is the ability to manage the DNS records for domain names. You can transfer DNS records for existing domain names managed by other domain registrars. You can also register new domain names directly in Route 53.

  

The other response options are incorrect because:

- Amazon Virtual Private Cloud (Amazon VPC) is a service that enables you to provision an isolated section of the AWS Cloud. In this isolated section, you can launch resources in a virtual network that you define.
- AWS Direct Connect is a service that enables you to establish a dedicated private connection between your data center and VPC.  
- Amazon CloudFront is a content delivery service. It uses a network of edge locations to cache content and deliver content to customers all over the world.

**Learn more:**

- [Amazon Route 53](https://aws.amazon.com/route53)

---

### Which of the following are characteristics of the Amazon EBS service? (Select TWO.)

- Best for data that requires retention <>
    
- Best for temporary data that is not kept long term
    
- Separate drives from the host computer of an EC2 instance <>
    
- Physically attached to the host computer of an EC2 instance
    
- Data is deleted when an EC2 instance is stopped

---

### You want to store data that is infrequently accessed but must be immediately available when needed. Which Amazon S3 storage class should you use?

S3 Intelligent-Tiering

S3 Glacier Deep Archive

- S3 Standard-IA

S3 Glacier Flexible Retrieval

The correct response option is **S3 Standard-IA**.

The S3 Standard-IA storage class is ideal for data that is infrequently accessed but requires high availability when needed. Both S3 Standard and S3 Standard-IA store data in a minimum of three Availability Zones. S3 Standard-IA provides the same level of availability as S3 Standard but at a lower storage price.

The other response options are incorrect because:

- In the S3 Intelligent-Tiering storage class, Amazon S3 monitors objects’ access patterns. If you haven’t accessed an object for 30 consecutive days, Amazon S3 automatically moves it to the infrequent access tier, S3 Standard-IA. If you access an object in the infrequent access tier, S3 automatically moves it to the frequent access tier, S3 Standard.
- S3 Glacier Flexible Retrieval and S3 Glacier Deep Archive are low-cost storage classes that are ideal for data archiving. They would not be the best choice for this scenario, which requires high availability. You can retrieve objects stored in the S3 Glacier Flexible Retrieval storage class within a few minutes to a few hours. By comparison, you can retrieve objects stored in the S3 Glacier Deep Archive storage class within 12 hours.

---

### What are the scenarios in which you should use Amazon Relational Database Service (Amazon RDS)? (Select TWO.)

- Running a serverless database
    
- Using SQL to organize data <>
    
- Storing data in a key-value database
    
- Scaling up to 10 trillion requests per day
    
- Storing data in an Amazon Aurora database <>

The two correct response options are:

- Using SQL to organize data
- Storing data in an Amazon Aurora database

The other three response options are scenarios in which you should use Amazon DynamoDB.