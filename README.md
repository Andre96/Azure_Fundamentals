# Azure_Fundamentals

![Azure Fundamentals Logo](Images/Azure-AZ-900_image.png)

This Document has the purpose to create a collection of questions about Azure Fundamentals usable to understand how deeply you understood it.


# Usage

This document can be used to create a speech about the different Fundamentals areas of Azure. This process, hopefully, will lead to a self evaluation about the preparation for the **Exam AZ-900: Microsoft Azure Fundamentals**.
In this document will be presented different sections pertaining to the different areas of the Exam.
If you are determined to pass the exam, you should be able to describe Azure architectural components and Azure services, such as:

- Compute
- Networking
- Storage

You should also be able to describe features and tools to secure, govern, and administer Azure.
You should have skills and experience working with an area of IT, such as:

- Infrastructure management
- Database management
- Software development

In this document you will find the **Questions** used to recreate a speech about the Azure Fundamentals components, you should try it yourself, whenever you're stuck, is possible to check the answare that I propose. Let's start the journey!

# Here we start with the questions!
> **_NOTE_**: The questions will be divided in different sections depending on the subject.

> **_NOTE_**: The weight of each area in the exam is showed in the following table

| AZ-900 Domain Area                        | Weight   |
| ---------------------------------------- | -------- |
| Describe cloud concepts                  | 25-30%   |
| Describe Azure architecture and services | 35-40%   |
| Describe Azure management and governance | 30-35%   |


# Introduction
Let's warm up a bit...

<details>
  <summary><b>What is Azure?</b></summary>
  Azure, often referred to as Microsoft Azure, is a cloud computing platform provided by Microsoft. It offers a wide range of services, including computing power, storage, networking, databases, analytics, artificial intelligence (AI), and Internet of Things (IoT), among others. Azure enables individuals and organizations to build, deploy, and manage applications and services through Microsoft's global network of data centers.
</details>

# Cloud concepts

Now we are redy to start, here will be asked questions about cloud concepts.


## Cloud computing
<details>
  <summary><b>What is Cloud Computing?</b></summary>
  Cloud computing is the delivery of computing services over the internet. Computing services include common IT infrastructure such as virtual machines, storage, databases, and networking. Cloud services also expand the traditional IT offerings to include things like Internet of Things (IoT), machine learning (ML), and artificial intelligence (AI).
</details>

<details>
  <summary><b>What is the shared responsibility model?</b></summary>
  The Shared Responsibility Model in cloud computing, including Azure, defines the division of responsibilities between the cloud service provider (CSP) and the customer. It outlines which aspects of security and management are handled by the cloud provider and which are the responsibility of the customer. This model is crucial for ensuring a secure and well-managed cloud environment.
  
![Shared resposibility model](Images/shared-responsibility-model.svg)
You’ll always be responsible for:

- The information and data stored in the cloud
- Devices that are allowed to connect to your cloud (cell phones, computers, and so on)
- The accounts and identities of the people, services, and devices within your organization

The cloud provider is always responsible for:

- The physical datacenter
- The physical network
- The physical hosts

Your service model will determine responsibility for things like:

- Operating systems
- Network controls
- Applications
- Identity and infrastructure
</details>

<details>
  <summary><b>Define Cloud models</b></summary>
  The cloud models define the deployment type of cloud resources. The three main cloud models are: 
  - private 
  - public
  - hybrid
  
### Private cloud
A private cloud is, in some ways, the natural evolution from a corporate datacenter. It’s a cloud (delivering IT services over the internet) that’s used by a single entity. Private cloud provides much greater control for the company and its IT department. However, it also comes with greater cost and fewer of the benefits of a public cloud deployment. Finally, a private cloud may be hosted from your on site datacenter. It may also be hosted in a dedicated datacenter offsite, potentially even by a third party that has dedicated that datacenter to your company.

### Public Cloud
A public cloud is built, controlled, and maintained by a third-party cloud provider. With a public cloud, anyone that wants to purchase cloud services can access and use resources. The general public availability is a key difference between public and private clouds.

### Hybrid Cloud
A hybrid cloud is a computing environment that uses both public and private clouds in an inter-connected environment. A hybrid cloud environment can be used to allow a private cloud to surge for increased, temporary demand by deploying public cloud resources. Hybrid cloud can be used to provide an extra layer of security. For example, users can flexibly choose which services to keep in public cloud and which to deploy to their private cloud infrastructure.

### Multi-Cloud
A fourth, and increasingly likely scenario is a multi-cloud scenario. In a multi-cloud scenario, you use multiple public cloud providers. Maybe you use different features from different cloud providers. Or maybe you started your cloud journey with one provider and are in the process of migrating to a different provider. Regardless, in a multi-cloud environment you deal with two (or more) public cloud providers and manage resources and security in both environments.

</details>

<details>
  <summary><b>How is the Cloud environment managed?</b></summary>
  ### Azure Arc
  Azure Arc is a set of technologies that helps manage your cloud environment. Azure Arc can help manage your cloud environment, whether it's a public cloud solely on Azure, a private cloud in your datacenter, a hybrid configuration, or even a multi-cloud environment running on multiple cloud providers at once.
</details>

<details>
  <summary><b>Describe the consumption-based model</b></summary>
  Operational Expenditure(OpEx) is spending money on services or products over time. Renting a convention center, leasing a company vehicle, or signing up for cloud services are all examples of OpEx.

Cloud computing falls under OpEx because cloud computing operates on a consumption-based model. With cloud computing, you don’t pay for the physical infrastructure, the electricity, the security, or anything else associated with maintaining a datacenter. Instead, you pay for the IT resources you use. If you don’t use any IT resources this month, you don’t pay for any IT resources.
This consumption-based model has many benefits, including:

- No upfront costs.
- No need to purchase and manage costly infrastructure that users might not use to its fullest potential.
- The ability to pay for more resources when they're needed.
- The ability to stop paying for resources that are no longer needed.

Cloud computing is the delivery of computing services over the internet by using a pay-as-you-go pricing model. You typically pay only for the cloud services you use.
Instead of maintaining CPUs and storage in your datacenter, you rent them for the time that you need them. The cloud provider takes care of maintaining the underlying infrastructure for you. The cloud enables you to quickly solve your toughest business challenges and bring cutting-edge solutions to your users.
</details>

## The benefit of using cloud services

<details>
  <summary><b>What are the key benefit concepts of cloud services?</b></summary>
  The key benefit concepts are: 
  
  - Availability 
  - Scalability
  - Reliability
  - Predictability
  - Pecurity
  - Governance
  - Manageability 

### Availability
When you’re deploying an application, a service, or any IT resources, it’s important the resources are available when needed. High availability focuses on ensuring maximum availability, regardless of disruptions or events that may occur.

When you’re architecting your solution, you’ll need to account for service availability guarantees. Azure is a highly available cloud environment with uptime guarantees depending on the service. These guarantees are part of the service-level agreements (SLAs).
> **_NOTE_**: SLA is a formal agreement between the cloud platform and a customer, it garantee the customer a fixed level of services, like the up time percentage e.g. 99% or 99.9%

### Scalability
Another major benefit of cloud computing is the scalability of cloud resources. Scalability refers to the ability to adjust resources to meet demand. If you suddenly experience peak traffic and your systems are overwhelmed, the ability to scale means you can add more resources to better handle the increased demand.

The other benefit of scalability is that you aren't overpaying for services. Because the cloud is a consumption-based model, you only pay for what you use. If demand drops off, you can reduce your resources and thereby reduce your costs.

Scaling generally comes in two varieties: **vertical and horizontal**. **Vertical scaling** is focused on increasing or decreasing the capabilities of resources. **Horizontal scaling** is adding or subtracting the number of resources.
<details>
  <summary><b>Vertical sacling</b></summary>
  With vertical scaling, if you were developing an app and you needed more processing power, you could vertically scale up to add more CPUs or RAM to the virtual machine. Conversely, if you realized you had over-specified the needs, you could vertically scale down by lowering the CPU or RAM specifications.
</details>
<details>
  <summary><b>Horizontal scaling</b></summary>
  With horizontal scaling, if you suddenly experienced a steep jump in demand, your deployed resources could be scaled out (either automatically or manually). For example, you could add additional virtual machines or containers, scaling out. In the same manner, if there was a significant drop in demand, deployed resources could be scaled in (either automatically or manually), scaling in.
</details>

### Reliability
Reliability is the ability of a system to recover from failures and continue to function. It's also one of the pillars of the Microsoft Azure Well-Architected Framework.

The cloud, by virtue of its decentralized design, naturally supports a reliable and resilient infrastructure. With a decentralized design, the cloud enables you to have resources deployed in regions around the world. With this global scale, even if one region has a catastrophic event other regions are still up and running. You can design your applications to automatically take advantage of this increased reliability. In some cases, your cloud environment itself will automatically shift to a different region for you, with no action needed on your part. You’ll learn more about how Azure leverages global scale to provide reliability later in this series.

### Predictability
Predictability in the cloud lets you move forward with confidence. Predictability can be focused on performance predictability or cost predictability. Both performance and cost predictability are heavily influenced by the Microsoft Azure Well-Architected Framework. Deploy a solution that’s built around this framework and you have a solution whose cost and performance are predictable.

### Governance
Whether you’re deploying infrastructure as a service or software as a service, cloud features support governance and compliance. Things like set templates help ensure that all your deployed resources meet corporate standards and government regulatory requirements. Plus, you can update all your deployed resources to new standards as standards change. Cloud-based auditing helps flag any resource that’s out of compliance with your corporate standards and provides mitigation strategies. Depending on your operating model, software patches and updates may also automatically be applied, which helps with both governance and security.

### Security
On the security side, you can find a cloud solution that matches your security needs. If you want maximum control of security, infrastructure as a service provides you with physical resources but lets you manage the operating systems and installed software, including patches and maintenance. If you want patches and maintenance taken care of automatically, platform as a service or software as a service deployments may be the best cloud strategies for you.

And because the cloud is intended as an over-the-internet delivery of IT resources, cloud providers are typically well suited to handle things like distributed denial of service (DDoS) attacks, making your network more robust and secure.

## Manageability
A major benefit of cloud computing is the manageability options. There are two types of manageability for cloud computing that you’ll learn about in this series, and both are excellent benefits.

### Management of the cloud
Management of the cloud speaks to managing your cloud resources. In the cloud, you can:

- Automatically scale resource deployment based on need.
- Deploy resources based on a preconfigured template, removing the need for manual configuration.
- Monitor the health of resources and automatically replace failing resources.
- Receive automatic alerts based on configured metrics, so you’re aware of performance in real time.
 
### Management in the cloud
Management in the cloud speaks to how you’re able to manage your cloud environment and resources. You can manage these:

- Through a web portal.
- Using a command line interface.
- Using APIs.
- Using PowerShell.
</details>

## Cloud service type

<details>
  <summary><b>Describe Infrastructure as a Service</b></summary>
  Infrastructure as a service (IaaS) is the most flexible category of cloud services, as it provides you the maximum amount of control for your cloud resources. In an IaaS model, the cloud provider is responsible for maintaining the hardware, network connectivity (to the internet), and physical security. You’re responsible for everything else: operating system installation, configuration, and maintenance; network configuration; database and storage configuration; and so on. With IaaS, you’re essentially renting the hardware in a cloud datacenter, but what you do with that hardware is up to you.

  ### Scenario:
  Some common scenarios where IaaS might make sense include:

  - Lift-and-shift migration: You’re standing up cloud resources similar to your on-prem datacenter, and then simply moving the things running on-prem to running on the IaaS infrastructure.
  - Testing and development: You have established configurations for development and test environments that you need to rapidly replicate. You can stand up or shut down the different environments rapidly with an IaaS structure, while maintaining complete control.
  
</details>

<details>
  <summary><b>Describe Platform as a Service</b></summary>
  Platform as a service (PaaS) is a middle ground between renting space in a datacenter (infrastructure as a service) and paying for a complete and deployed solution (software as a service). In a PaaS environment, the cloud provider maintains the physical infrastructure, physical security, and connection to the internet. They also maintain the operating systems, middleware, development tools, and business intelligence services that make up a cloud solution. In a PaaS scenario, you don't have to worry about the licensing or patching for operating systems and databases.

PaaS is well suited to provide a complete development environment without the headache of maintaining all the development infrastructure.

  ### Scenario
  Some common scenarios where PaaS might make sense include:

  - Development framework: PaaS provides a framework that developers can build upon to develop or customize cloud-based applications. Similar to the way you create an Excel macro, PaaS lets developers create applications using built-in software components. Cloud features such as scalability, high-availability, and multi-tenant capability are included, reducing the amount of coding that developers must do.
  - Analytics or business intelligence: Tools provided as a service with PaaS allow organizations to analyze and mine their data, finding insights and patterns and predicting outcomes to improve forecasting, product design decisions, investment returns, and other business decisions.
</details>

<details>
  <summary><b>Describe Software as a Service</b></summary>
  Software as a service (SaaS) is the most complete cloud service model from a product perspective. With SaaS, you’re essentially renting or using a fully developed application. Email, financial software, messaging applications, and connectivity software are all common examples of a SaaS implementation.

While the SaaS model may be the least flexible, it’s also the easiest to get up and running. It requires the least amount of technical knowledge or expertise to fully employ.

  ### Scenario
  Some common scenarios for SaaS are:

  - Email and messaging.
  - Business productivity applications.
  - Finance and expense tracking.
</details>

# Azure architecture and services
Good job till now, keep it up! Let's change topic! 
Mantain this Image as reference for all this topic
![hierarchy]()
## Core architectural components of Azure

<details>
  <summary><b>Why do you need an Azure Account?</b></summary>
  When you're working with your own applications and business needs, you need to create an Azure account, and a subscription will be created for you. After you've created an Azure account, you're free to create additional subscriptions. For example, your company might use a single Azure account for your business and separate subscriptions for development, marketing, and sales departments. After you've created an Azure subscription, you can start creating Azure resources within each subscription.
</details>

<details>
  <summary><b>Describe Azure physical infrastructure</b></summary>
  The physical infrastructure for Azure starts with datacenters. Conceptually, the datacenters are the same as large corporate datacenters. They’re facilities with resources arranged in racks, with dedicated power, cooling, and networking infrastructure.

As a global cloud provider, Azure has datacenters around the world. However, these individual datacenters aren’t directly accessible. Datacenters are grouped into **Azure Regions** or **Azure Availability Zones** that are designed to help you achieve resiliency and reliability for your business-critical workloads.

### Azure Regions
A region is a geographical area on the planet that contains at least one, but potentially multiple datacenters that are nearby and networked together with a low-latency network. Azure intelligently assigns and controls the resources within each region to ensure workloads are appropriately balanced.

When you deploy a resource in Azure, you'll often need to choose the region where you want your resource deployed.

### Availability Zones
Availability zones are physically separate datacenters within an Azure region. Each availability zone is made up of one or more datacenters equipped with independent power, cooling, and networking. An availability zone is set up to be an isolation boundary. If one zone goes down, the other continues working. Availability zones are connected through high-speed, private fiber-optic networks.
>**__Note__**: To ensure resiliency, a minimum of three separate availability zones are present in all availability zone-enabled regions. However, not all Azure Regions currently support availability zones.
</details>

<details>
  <summary><b>Why and how Availability zones are used?</b></summary>
  You want to ensure your services and data are redundant so you can protect your information in case of failure. When you host your infrastructure, setting up your own redundancy requires that you create duplicate hardware environments. Azure can help make your app highly available through availability zones.

You can use availability zones to run mission-critical applications and build high-availability into your application architecture by co-locating your compute, storage, networking, and data resources within an availability zone and replicating in other availability zones. Keep in mind that there could be a cost to duplicating your services and transferring data between availability zones.

Availability zones are primarily for VMs, managed disks, load balancers, and SQL databases. Azure services that support availability zones fall into three categories:

- Zonal services: You pin the resource to a specific zone (for example, VMs, managed disks, IP addresses).
- Zone-redundant services: The platform replicates automatically across zones (for example, zone-redundant storage, SQL Database).
- Non-regional services: Services are always available from Azure geographies and are resilient to zone-wide outages as well as region-wide outages.

Even with the additional resiliency that availability zones provide, it’s possible that an event could be so large that it impacts multiple availability zones in a single region. To provide even further resilience, Azure has **Region Pairs**.

### Region Pairs
Most Azure regions are paired with another region within the same geography (such as US, Europe, or Asia) at least 300 miles away. This approach allows for the replication of resources across a geography that helps reduce the likelihood of interruptions because of events such as natural disasters, civil unrest, power outages, or physical network outages that affect an entire region. For example, if a region in a pair was affected by a natural disaster, services would automatically fail over to the other region in its region pair.

**Additional advantages of region pairs**
- If an extensive Azure outage occurs, one region out of every pair is prioritized to make sure at least one is restored as quickly as possible for applications hosted in that region pair.
- Planned Azure updates are rolled out to paired regions one region at a time to minimize downtime and risk of application outage.
- Data continues to reside within the same geography as its pair (except for Brazil South) for tax- and law-enforcement jurisdiction purposes.
</details>

<details>
  <summary><b>Question</b></summary>
  answer
</details>

<details>
  <summary><b>Question</b></summary>
  answer
</details>

<details>
  <summary><b>Question</b></summary>
  answer
</details>

<details>
  <summary><b>Question</b></summary>
  answer
</details>

<details>
  <summary><b>Question</b></summary>
  answer
</details>

<details>
  <summary><b>Question</b></summary>
  answer
</details>

<details>
  <summary><b>Question</b></summary>
  answer
</details>

<details>
  <summary><b>Question</b></summary>
  answer
</details>

<details>
  <summary><b>Question</b></summary>
  answer
</details>
