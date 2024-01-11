# Azure_Fundamentals

![Azure Fundamentals Logo](Images/Azure-AZ-900_image.png)

This Document has the purpose to create a collection of questions about Azure Fundamentals usable to understand how deeply you understood it.
_________________

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

## Availability
When you’re deploying an application, a service, or any IT resources, it’s important the resources are available when needed. High availability focuses on ensuring maximum availability, regardless of disruptions or events that may occur.

When you’re architecting your solution, you’ll need to account for service availability guarantees. Azure is a highly available cloud environment with uptime guarantees depending on the service. These guarantees are part of the service-level agreements (SLAs).
> **_NOTE_**: SLA is a formal agreement between the cloud platform and a customer, it garantee the customer a fixed level of services, like the up time percentage e.g. 99% or 99.9%

## Scalability
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

## Reliability
Reliability is the ability of a system to recover from failures and continue to function. It's also one of the pillars of the Microsoft Azure Well-Architected Framework.

The cloud, by virtue of its decentralized design, naturally supports a reliable and resilient infrastructure. With a decentralized design, the cloud enables you to have resources deployed in regions around the world. With this global scale, even if one region has a catastrophic event other regions are still up and running. You can design your applications to automatically take advantage of this increased reliability. In some cases, your cloud environment itself will automatically shift to a different region for you, with no action needed on your part. You’ll learn more about how Azure leverages global scale to provide reliability later in this series.

## Predictability
Predictability in the cloud lets you move forward with confidence. Predictability can be focused on performance predictability or cost predictability. Both performance and cost predictability are heavily influenced by the Microsoft Azure Well-Architected Framework. Deploy a solution that’s built around this framework and you have a solution whose cost and performance are predictable.

## Governance
Whether you’re deploying infrastructure as a service or software as a service, cloud features support governance and compliance. Things like set templates help ensure that all your deployed resources meet corporate standards and government regulatory requirements. Plus, you can update all your deployed resources to new standards as standards change. Cloud-based auditing helps flag any resource that’s out of compliance with your corporate standards and provides mitigation strategies. Depending on your operating model, software patches and updates may also automatically be applied, which helps with both governance and security.

## Security
On the security side, you can find a cloud solution that matches your security needs. If you want maximum control of security, infrastructure as a service provides you with physical resources but lets you manage the operating systems and installed software, including patches and maintenance. If you want patches and maintenance taken care of automatically, platform as a service or software as a service deployments may be the best cloud strategies for you.

And because the cloud is intended as an over-the-internet delivery of IT resources, cloud providers are typically well suited to handle things like distributed denial of service (DDoS) attacks, making your network more robust and secure.
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
