# Cloud Concepts (Question 1-50)


## Question 1 (Describe Cloud Concepts)
<a name="question_1"/>
Question 1: Check which statement is true or false.

Statement | Answer
------------ | -------------
A platform as a service (PaaS) solution that hosts web apps in Azure provides full control of the operating systems that host applications. | True/False
A platform as a service (PaaS) solution that hosts web apps in Azure provides the ability to scale the platform automatically. | True/False
A platform as as service (Paas) solution that hosts web apps in Azure provides professional development services to continuously add features to custom applications. | True/False


<details><summary>See answer</summary>
<p>
  
Statement | Answer | Explanation
------------ | ------------- | -------------
A platform as a service (PaaS) solution that hosts web apps in Azure provides full control of the operating systems that host applications. | False | A PaaS solution does not provide access to the operating system. The Azure Web Apps service provides an environment for you to host your web applications. Behind the scenes, the web apps are hosted on virtual machines running IIS. However, you have no direct access to the virtual machine, the operating system or IIS. 
 A platform as a service (PaaS) solution that hosts web apps in Azure provides the ability to scale the platform automatically. | True  | A PaaS solution that hosts web apps in Azure does provide the ability to scale the platform automatically. This is known as autoscaling. Behind the scenes, the web apps are hosted on virtual machines running IIS. Autoscaling means adding more load balanced virtual machines to host the web apps.
 A platform as as service (Paas) solution that hosts web apps in Azure provides professional development services to continuously add features to custom applications. | True | PaaS provides a framework that developers can build upon to develop or customize cloud-based applications. PaaS development tools can cut the time it takes to code new apps with pre-coded application components built into the platform, such as workflow, directory services, security features, search and so on.
  
  
</p>
</details>

----

## Question 2 (Describe Cloud Concepts)
<a name="question_2"/>
Check which statement is true or false.

Statement | Answer
------------ | -------------
Azure provides flexibility between capital expenditure (CapEx) and operational expenditure (OpEx). | True/False
If you create two Azure virtual machines that use the B2S size, each virtual machine will always generate the same monthly costs | True/False
When an Azure virtual machine is stopped you continue to pay storage costs associated to the virtual machine | True/False

<details><summary>See Answer</summary>
<p>
  
Explanation | Answer | Explanation
------------ | -------------  | -------------  
Azure provides flexibility between capital expenditure (CapEx) and operational expenditure (OpEx). | True | Traditionally, IT expenses have been considered a Capital Expenditure (CapEx). Today, with the move to the cloud and the pay-as-you-go model, organizations have the ability to stretch their budgets and are shifting their IT CapEx costs to Operating Expenditures (OpEx) instead. This flexibility, in accounting terms, is now an option due to the a Service model of purchasing software, cloud storage and other IT related resources.
  If you create two Azure virtual machines that use the B2S size, each virtual machine will always generate the same monthly costs | False | Two virtual machines using the same size could have different disk configurations. Therefore, the monthly costs could be different. 
  When an Azure virtual machine is stopped you continue to pay storage costs associated to the virtual machine  | True | When an Azure virtual machine is stopped, you don't pay for the virtual machine. However, you do still pay for the storage costs associated to the virtual machine.The most common storage costs are for the disks attached to the virtual machines. There are also other storage costs associated with a virtual machine such as storage for diagnostic data and virtual machine backups.
  
  
  
 
  
</p>
</details>


----

## Question 3 (Describe Cloud Concepts)
<a name="question_3"/>
To complete the sentence, select the appropriate option in the answer area.

When you are implementing a Software as a Service (SaaS) solution, you are responsible for:

- configuring high availability
- defining scalability rules.
- installing the SaaS solution.
- configuring the SaaS solution.


<details><summary>See answer</summary>
<p>
  
- configuring the SaaS solution. 
  
When you are implementing a Software as a Service (SaaS) solution, you are responsible for configuring the SaaS solution. Everything else is managed by the cloud provider.
SaaS requires the least amount of management. The cloud provider is responsible for managing everything, and the end user just uses the software.
Software as a service (SaaS) allows users to connect to and use cloud-based apps over the Internet. Common examples are email, calendaring and office tools
(such as Microsoft Office 365).
SaaS provides a complete software solution which you purchase on a pay-as-you-go basis from a cloud service provider. You rent the use of an app for your organization and your users connect to it over the Internet, usually with a web browser. All of the underlying infrastructure, middleware, app software and app data are located in the service provider's data center. The service provider manages the hardware and software and with the appropriate service agreement, will ensure the availability and the security of the app and your data as well.  
 
  
</p>
</details>


----

# Question 4 (Describe Cloud Concepts)

You have an on-premises network that contains several servers. You plan to migrate all the servers to Azure. You need to recommend a solution to ensure that some of the servers are available if a single Azure data center goes offline for an extended period.
What should you include in the recommendation?

Statement | Answer
------------ | -------------
A | fault tolerance
B | elasticity
C | scalability
D | low latency


<details><summary>See Answer</summary>
<p>
  
 Answer | Explanation 
------------ | -------------  
 A. fault tolerance | Fault tolerance is the ability of a system to continue to function in the event of a failure of some of its components. In this question, you could have servers that are replicated across datacenters. Availability zones expand the level of control you have to maintain the availability of the applications and data on your VMs. Availability Zones are unique physicallocations within an Azure region. Each zone is made up of one or more datacenters equipped with independent power, cooling, and networking. To ensure resiliency, there are a minimum of three separate zones in all enabled regions. The physical separation of Availability Zones within a region protects applications and data from datacenter failures.With Availability Zones, Azure offers industry best 99.99% VM uptime SLA. By architecting your solutions to use replicated VMs in zones, you can protect your applications and data from the loss of a datacenter. If one zone is compromised, then replicated apps and data are instantly available in another zone. 
  
https://docs.microsoft.com/en-us/azure/virtual-machines/windows/manage-availability  
  
</p>
</details>

----

# Question 5 (Describe Cloud Concepts)

To complete the sentence, select the appropriate option in the answer area.

An organization that hosts its infrastructure (...) no longer requires a data center.

- in a private cloud
- in a hybrid cloud
- in the public cloud
- on a Hyper-V host

<details><summary>See Answer</summary>
<p>
  
- in the public cloud
  
A private cloud is hosted in your datacenter. Therefore, you cannot close your datacenter if you are using a private cloud.
A public cloud is hosted externally, for example, in Microsoft Azure. An organization that hosts its infrastructure in a public cloud can close its data center.
Public cloud is the most common deployment model. In this case, you have no local hardware to manage or keep up-to-date everything runs on your cloud provider's hardware.
Microsoft Azure is an example of a public cloud provider.
In a private cloud, you create a cloud environment in your own datacenter and provide self-service access to compute resources to users in your organization.
This offers a simulation of a public cloud to your users, but you remain completely responsible for the purchase and maintenance of the hardware and software services you provide.  
 
  
</p>
</details>


----

# Question 6 (Describe Cloud Concepts)

What are two characteristics of the public cloud? Each correct answer presents a complete solution

Statement | Answer
------------ | -------------
A | dedicated hardware
B | unsecured connections
C | limited storage
D | metered pricing
E | self-service management


<details><summary>See Answer</summary>
<p>
  
Statement| Answer | Explanation
------------ | -------------  | ------------
D | metered pricing | With the public cloud, you get pay-as-you-go pricing you pay only for what you use, no CapEx costs.  
E | self-service management | With the public cloud, you have self-service management. You are responsible for the deployment and configuration of the cloud resources such as virtual machines or web sites. The underlying hardware that hosts the cloud resources is managed by the cloud provider.
  

  
</p>
</details>


----

# Question 7 (Describe Cloud Concepts)

When planning to migrate a public website to Azure you must plan to (...)

- deploy a VPN
- pay monthly usages costs
- pay to transfer all the website data to Azure
- reduce the number of connections to the website




<details><summary>See Answer</summary>
<p>
  
- pay monthly usage costs 
 
When planning to migrate a public website to Azure, you must plan to pay monthly usage costs. This is because Azure uses the pay-as-you-go model.
  
</p>
</details>


----

# Question 8 (Describe Cloud Concepts)

Your company plans to migrate all its data and resources to Azure. The company's migration plan states that only Platform as a Service (PaaS) solutions must be used in Azure.
You need to deploy an Azure environment that meets the company migration plan.
Solution: You create an Azure App Service and Azure SQL databases.
Does this meet the goal?

Statement | Answer
------------ | -------------
A. | Yes
B. | No

<details><summary>See Answer</summary>
<p>
  
 Answer | Explanation
------------ | -------------  
 A. Yes | Azure App Service and Azure SQL databases are examples of Azure PaaS solutions. Therefore, this solution does meet the goal. 
  
</p>
</details>

----

# Question 9 (Describe Cloud Concepts)

Your company plans to migrate all its data and resources to Azure.
The company's migration plan states that only Platform as a Service (PaaS) solutions must be used in Azure.
You need to deploy an Azure environment that meets the company migration plan.
Solution: You create an Azure App Service and Azure virtual machines that have Microsoft SQL Server installed.
Does this meet the goal?

Statement | Answer
------------ | -------------
A. | Yes
B. | No

<details><summary>See Answer</summary>
<p>
  
 Answer | Explanation
------------ | -------------  
A. Yes | Azure App Service is a PaaS (Platform as a Service) service. Azure virtual machines are an IaaS (Infrastructure as a Service) service, and a Paas service.Therefore, this solution does meet the goal. Note: Like IaaS, PaaS includes infrastructure servers, storage, and networking but also middleware, development tools, business intelligence (BI) services, database management systems, and more. PaaS is designed to support the complete web application lifecycle: building, testing, deploying, managing, and updating. 
  
  
  
</p>
</details>

----

# Question 10 (Describe Cloud Concepts)

Your company plans to migrate all its data and resources to Azure.
The company's migration plan states that only Platform as a Service (PaaS) solutions must be used in Azure.
You need to deploy an Azure environment that meets the company migration plan.

Solution: You create an Azure App Service and Azure Storage accounts.
Does this meet the goal?

Statement | Answer
------------ | -------------
A. | Yes
B. | No


<details><summary>See Answer</summary>
<p>
  
 Answer | Explanation
------------ | -------------  
B.  No | https://www.examtopics.com/discussions/microsoft/view/8427-exam-az-900-topic-1-question-10-discussion/
  
</p>
</details>


----

# Question 11 (Describe Cloud Concepts)

Your company hosts an accounting application named App1 that is used by all the customers of the company.
App1 has low usage during the first three weeks of each month and very high usage during the last week of each month.
Which benefit of Azure Cloud Services supports cost management for this type of usage pattern?

Statement | Answer
------------ | -------------
A | high availibility
B | high latency
C | elasticity
D | load balancing



<details><summary>See Answer</summary>
<p>
  
 Answer |  Explanation
------------ | -------------  
C. elasticity | Elasticity in this case is the ability to provide additional compute resource when needed and reduce the compute resource when not needed to reduce costs. Autoscaling is an example of elasticity. Elastic computing is the ability to quickly expand or decrease computer processing, memory and storage resources to meet changing demands without worrying about capacity planning and engineering for peak usage. Typically controlled by system monitoring tools, elastic computing matches the amount of resources allocated to the amount of resources actually needed without disrupting operations. With cloud elasticity, a company avoids paying for unused capacity or idle resources and doesn't have to worry about investing in the purchase or maintenance of additional resources and equipment.
  
</p>
</details>


----

# Question 12 (Describe Cloud Concepts)

You plan to migrate a web application to Azure. The web application is accessed by external users.
You need to recommend a cloud deployment solution to minimize the amount of administrative effort used to manage the web application.
What should you include in the recommendation?


Statement | Answer
------------ | -------------
A. | Software as a Service (SaaS)
B. | Platform as a Service (PaaS)
C. | Infrastructure as a Service (IaaS)
D. | Database as a Service (DaaS)


<details><summary>See Answer</summary>
<p>
  
 Answer | Explanation
------------ | -------------  
B. | Azure App Service is a platform-as-a-service (PaaS) offering that lets you create web and mobile apps for any platform or device and connect to data anywhere, in the cloud or on-premises. App Service includes the web and mobile capabilities that were previously delivered separately as Azure Websites and Azure Mobile. 
  
 https://docs.microsoft.com/en-us/azure/security/fundamentals/paas-applications-using-app-services 
  
</p>
</details>


----

# Question 13 (Describe Cloud Concepts)

Which cloud deployment solution is used for Azure virtual machines and Azure SQL databases? To answer, select the appropriate options in the answer area.

Azure | Answer
------------ | -------------  
 Azure Virtual machines | (Iaas)/(PaaS)/(SaaS)
 Azure SQL databases | (IaaS)/(PaaS)/(SaaS)


<details><summary>See Answer</summary>
<p>
  
 Answer |  Explanation 
------------ | -------------  
Azure virtual machines are Infrastructure as a Service (IaaS). | Infrastructure as a Service is the most flexible category of cloud services. It aims to give you complete control over the hardware that runs your application (IT infrastructure servers and virtual machines (VMs), storage, networks, and operating systems). Instead of buying hardware, with IaaS, you rent it. 
Azure SQL databases are Platform as a Service (Paas). | Azure SQL Database is a fully managed Platform as a Service (PaaS) Database Engine that handles most of the database management functions such as upgrading, patching, backups, and monitoring without user involvement. Azure SQL Database is always running on the latest stable version of SQL Server Database Engine and patched OS with 99.99% availability. PaaS capabilities that are built-in into Azure SQL database enable you to focus on the domain specific database administration and optimization activities that are critical for your business. 
  
</p>
</details>


----

# Question 14 (Describe Cloud Concepts)

You have an on-premises network that contains 100 servers.
You need to recommend a solution that provides additional resources to your users. The solution must minimize capital and operational expenditure costs.
What should you include in the recommendation?

Statement | Answer
------------ | -------------
A. | a complete migration to the cloud
B. | an additional data center
C. | a private cloud
D. | a hybrid cloud



<details><summary>See Answer</summary>
<p>
  
Answer | Explanation 
------------ | -------------  
D. a hybrid cloud | A hybrid cloud is a combination of a private cloud and a public cloud.Capital expenditure is the spending of money up-front for infrastructure such as new servers.With a hybrid cloud, you can continue to use the on-premises servers while adding new servers in the public cloud (Azure for example). Adding new servers in Azure minimizes the capital expenditure costs as you are not paying for new servers as you would if you deployed new server on-premises. 
  
</p>
</details>

----

# Question 15 (Describe Cloud Concepts)

Check which statement is true or false.

Statement | Answer
------------ | -------------
To achieve a hybrid cloud model, a company must always migrate from a private cloud model | True/False
A company can extend the capacity of its internal network by using the public cloud | True/False
In a public cloud model, only guest users at your company can acces the resources in the cloud | True/False


<details><summary>See Answer</summary>
<p>
  
  Statement | Answer | Explanation
  ------------ | ------------- | -------------
  To achieve a hybrid cloud model, a company must always migrate from a private cloud model | False | It is not true that a company must always migrate from a private cloud model to implement a hybrid cloud. You could start with a public cloud and then combine that with an on-premise infrastructure to implement a hybrid cloud.
  A company can extend the capacity of its internal network by using the public cloud | True | A company can extend the capacity of its internal network by using the public cloud. This is very common. When you need more capacity, rather than pay out for new on-premises infrastructure, you can configure a cloud environment and connect your on-premises network to the cloud environment by using a VPN.
  In a public cloud model, only guest users at your company can acces the resources in the cloud | False |  It is not true that only guest users can access cloud resources. You can give anyone with an account in Azure Active Directory access to the cloud resources. There are many authentication scenarios but a common one is to replicate your on-premises Active Directory accounts to Azure Active Directory and provide access to the Azure Active Directory accounts. Another commonly used authentication method is 'Federation' where authentication for access to cloud resources is passed to another authentication provider such as an on-premises Active Directory.
  
 https://azure.microsoft.com/en-gb/overview/what-is-hybrid-cloud-computing/ 
  

  
</p>
</details>


----

# Question 16 (Describe Cloud Concepts)

You plan to migrate several servers from an on-premises network to Azure.
What is an advantage of using a public cloud service for the servers over an on-premises network?

Statement | Answer
------------ | -------------
A. | The public cloud is owned by the public, NOT a private corporation
B. | The public cloud is a crowd-sourcing solution that provides corporations with the ability to enhance the cloud
C. | All public cloud resources can be freely accessed by every member of the public
D. | The public cloud is a shared entity whereby multiple corporations each use a portion of the resources in the cloud

<details><summary>See Answer</summary>
<p>
  
Answer | Explanation
------------ | -------------  
D. The public cloud is a shared entity whereby multiple corporations each use a portion of the resources in the cloud | The public cloud is a shared entity whereby multiple corporations each use a portion of the resources in the cloud. The hardware resources (servers, infrastructure etc.) are managed by the cloud provider. Multiple companies create resources such as virtual machines and virtual networks on the hardware resources. 
  
</p>
</details>

----

# Question 17 (Describe Cloud Concepts)
Azure Site Recovery provides (...) for virtual machines

- fault tolerance
- disaster recovery
- elasticiy
- high availibility



<details><summary>See Answer</summary>
<p>
  
- fault tolerance
  
Azure Site Recovery helps ensure business continuity by keeping business apps and workloads running during outages. Site Recovery replicates workloads running on physical and virtual machines (VMs) from a primary site to a secondary location. 
  
https://docs.microsoft.com/en-us/azure/site-recovery/site-recovery-overview  
 
  
</p>
</details>


----

# Question 18 (Describe Cloud Concepts)

In which type of cloud model are all the hardware resources owned by a third-party and shared between multiple tenants?

Statement | Answer
------------ | -------------
A. | private
B. | hybrid
C. | public

<details><summary>See Answer</summary>
<p>
  
 Answer | Explanation
------------ | -------------  
C | Microsoft Azure, Amazon Web Services and Google Cloud are three examples of public cloud services. Microsoft, Amazon and Google own the hardware. The tenants are the customers who use the public cloud services. 
  
</p>
</details>


----

# Question 19 (Describe Cloud Concepts)


An Azure web app that queries on an on-premises Microsoft SQL server in an example of a (..) cloud

- hybrid
- multi-vendor
- private
- public


<details><summary>See Answer</summary>
<p>
  
- hybrid
 
https://azure.microsoft.com/en-gb/overview/what-is-hybrid-cloud-computing/  
  
</p>
</details>


----

# Question 20 (Describe Cloud Concepts)

You have 1,000 virtual machines hosted on the Hyper-V hosts in a data center.
You plan to migrate all the virtual machines to an Azure pay-as-you-go subscription.
You need to identify which expenditure model to use for the planned Azure solution.
Which expenditure model should you identify?


Statement | Answer
------------ | -------------
A. | operational
B. | elastic
C. | capital
D. | scalable


<details><summary>See Answer</summary>
<p>
  
Answer | Operational
------------ | -------------  
A. operational | One of the major changes that you will face when you move from on-premises cloud to the public cloud is the switch from capital expenditure (buying hardware) to operating expenditure (paying for service as you use it). This switch also requires more careful management of your costs. The benefit of the cloud is that you can fundamentally and positively affect the cost of a service you use by merely shutting down or resizing it when it's not needed. 
 
  
</p>
</details>



----

# Question 21

Match the Azure Cloud Services benefit to the correct description.

Answer Options | Answer Area | Answer
------------ | ------------- | -------------
Disaster recovery | A cloud service that remains available after a failure occurs | -
Fault tolerance | A cloud service that can be recovered after a failure occurs | -
Low latency | A cloud service that performs quickly when demand increases | -
Dynamic stability | A cloud service that can be accessed quickly from the internet | -

<details><summary>See Answer</summary>
<p>
  
Answer Area | Answer | Explanation
------------- | ------------- | -------------
A cloud service that remains available after a failure occurs | Fault tolerance | Fault tolerance is the ability of a service to remain available after a failure of one of the components of the service. For example, a service running on multiple servers can withstand the failure of one of the servers.
A cloud service that can be recovered after a failure occurs | Disaster recovery | Disaster recovery is the recovery of a service after a failure. For example, restoring a virtual machine from backup after a virtual machine failure.
A cloud service that performs quickly when demand increases | Dynamic stability | Dynamic scalability is the ability for compute resources to be added to a service when the service is under heavy load. For example, in a virtual machine scale set, additional instances of the virtual machine are added when the existing virtual machines are under heavy load.
A cloud service that can be accessed quickly from the internet | Low latency | Latency is the time a service to respond to requests. For example, the time it takes for a web page to be returned from a web server. Low latency means low response time which means a quicker response.
 
 
  
</p>
</details>


----

# Question 22 (Describe Cloud Concepts)

Check which statement is true or false

Statement | Answer
------------ | -------------
To implement a hybrid cloud model, a company must have an internal network | True/False
A company can extend the computing resources of its internal network by using a hybrid cloud | True/False
In a public cloud model, only quest users at your company can acces the resources in the cloud | True/False

<details><summary>See Answer</summary>
<p>
  
Statement | Answer | Explanation
------------ | -------------  | -------------  
To implement a hybrid cloud model, a company must have an internal network | False | It is not true that a company must always migrate from an internal network to implement a hybrid cloud. You could start with a public cloud and then combine that with an on-premise infrastructure to implement a hybrid cloud. 
A company can extend the computing resources of its internal network by using a hybrid cloud | True | A company can extend the computing resources of its internal network by using the public cloud. This is very common. When you need more resources, rather than pay out for new on-premises infrastructure, you can configure a cloud environment and connect your on-premises network to the cloud environment by using a VPN. 
In a public cloud model, only quest users at your company can acces the resources in the cloud | False | It is not true that only guest users can access cloud resources. You can give anyone with an account in Azure Active Directory access to the cloud resources. There are many authentication scenarios but a common one is to replicate your on-premises Active Directory accounts to Azure Active Directory and provide access to the Azure Active Directory accounts. Another commonly used authentication method is 'Federation' where authentication for access to cloud resources is passed to another authentication provider such as an on-premises Active Directory. 
  
</p>
</details>


----

# Question 23 (Describe Cloud Concepts)

Check which statement is true or false

Statement | Answer
------------ | -------------
A Platform as a Service (PaaS) solution provides full control of operating systems that host applications | True/False
A Platform as a Service (PaaS) solution provides additional memory to apps by changing pricing tiers | True/False
A Platform as a Service (PaaS) solution can automatically scale the number of instances | True/False

<details><summary>See Answer</summary>
<p>
  
Statement | Answer | Explanation
------------ | ------------- |  -------------
A Platform as a Service (PaaS) solution provides full control of operating systems that host applications | False 
A Platform as a Service (PaaS) solution provides additional memory to apps by changing pricing tiers | False
A Platform as a Service (PaaS) solution can automatically scale the number of instances | True
 
https://azure.microsoft.com/en-us/overview/what-is-paas/
  
</p>
</details>

----

# Question 24 (Describe Cloud Concepts)

Your company has an on-premises network that contains multiple servers.
The company plans to reduce the following administrative responsibilities of network administrators:
- Backing up application data
- Replacing failed server hardware
- Managing physical server security
- Updating server operating systems
- Managing permissions to shared documents

The company plans to migrate several servers to Azure virtual machines.
You need to identify which administrative responsibilities will be eliminated after the planned migration.
Which two responsibilities should you identify? Each correct answer presents a complete solution.
NOTE: Each correct selection is worth one point.

Statement | Answer
------------ | -------------
A. | Replacing failed server hardware
B. | Backing up application data
C. | Managing physical server security
D. | Updating server operating systems
E. | Managing permissions to shared documents

<details><summary>See Answer</summary>
<p>
  
Statement | Answer
------------ | -------------  
A. | Replacing failed server hardware
C. | Managing physical server security
  
Azure virtual machines run on Hyper-V physical servers. The physical servers are owned and managed by Microsoft. As an Azure customer, you have no access to the physical servers. Microsoft manage the replacement of failed server hardware and the security of the physical servers so you don't need to.
  
Incorrect Answers:
B: Microsoft have no control over the applications you run on the virtual machines. Therefore, it is your responsibility to ensure that application data is backed up.
D: Microsoft do not manage the operating systems you run on the virtual machines. Therefore, it is your responsibility to ensure that the operating systems are updated.
E: Microsoft have no control over the shared folders you host on the virtual machines. Therefore, it is your responsibility to ensure that folder permissions are configured appropriately.
  
</p>
</details>

----

# Question 25 (Describe Cloud Concepts)

Check which statement is true or false

Statement | Answer
------------ | -------------
Azure Pay-As-You-Go pricing is an example of CapEx | True/False
Paying electricity for your datacenter is an example of OpEx | True/False
Deploying your own datacenter is an example of CapEx | True/False



<details><summary>See Answer</summary>
<p>
  
One of the major changes that you will face when you move from on-premises cloud to the public cloud is the switch from capital expenditure (buying hardware) to operating expenditure (paying for service as you use it).  
  
Statement | Answer | Explanation 
------------ | -------------  | ------------- 
Azure Pay-As-You-Go pricing is an example of CapEx | False | With the pay-as-go model, you pay for services as you use them. This is Opex (Operational Expenditure), not CapEx (Captial Expenditure). CapEx is where you pay for something upfront. For example, buying a new physical server. 
Paying electricity for your datacenter is an example of OpEx | False | Paying for electricity for your own datacenter will be classed as CapEx, not OpEx. 
Deploying your own datacenter is an example of CapEx | True | Deploying your own datacenter is an example of CapEx. This is because you need to purchase all the infrastructure upfront before you can use it. 
 
  
</p>
</details>


----

# Question 26 (Describe Cloud Concepts)

You plan to provision Infrastructure as a Service (IaaS) resources in Azure.
Which resource is an example of IaaS?

Statement | Answer
------------ | -------------
A. | an Azure web app
B. | an Azure virtual machine
C. | an Azure logic app
D. | an Azure SQL database

<details><summary>See Answer</summary>
<p>
  
 Answer | Explanation
------------ | -------------  
B. an Azure virtual machine | An Azure virtual machine is an example of Infrastructure as a Service (IaaS). Azure web app, Azure logic app and Azure SQL database are all examples of Platform as a Service (Paas). 
  
  
  
</p>
</details>


----

# Question 27 (Describe Cloud Concepts)

To which cloud models can you deploy physical servers?


Statement | Answer
------------ | -------------
A. | private cloud and hybrid cloud only
B. | private cloud only
C. | private cloud, hybrid cloud and public cloud
D. | hybrid cloud only


<details><summary>See Answer</summary>
<p>
  
Answer | Explanation
------------ | -------------  
A. private cloud and hybrid cloud only | A private cloud is on-premises so you can deploy physical servers. A hybrid cloud is a mix of on-premise and public cloud resources. You can deploy physical servers on-premises. 
  
https://azure.microsoft.com/en-gb/overview/what-is-hybrid-cloud-computing/
  
</p>
</details>



----

# Question 28 (Describe Cloud Concepts)

Match the correct statements in the blank fields

Statement | (blank) | Answer
------------ | ------------- | ------------- 
Hybrid Cloud | | No required capital expenditure
Private Cloud | | Provides complete control over security
Public Cloud | | Provides a choice to use on-premises or cloud-based resources



<details><summary>See Answer</summary>
<p>
  
Cloud Model | Answer | Explanation
------------- | ------------ |  --------
Public Cloud | No required capital expenditure | With a public cloud, there is no capital expenditure on server hardware etc. You only pay for cloud resources that you use as you use them.
Private Cloud | Provides complete control over security | A private cloud exists on premises, so you have complete control over security.
Hybrid Cloud | Provides a choice to use on-premises or cloud-based resources | A hybrid cloud is a mix of public cloud resources and on-premises resources. Therefore, you have a choice to use either.
 
  
</p>
</details>


----

# Question 29 (Describe Cloud Concepts)

Check which statement is true or false.

Statement | Answer
------------ | -------------
A company can extend a private cloud by adding its own physical servers to the public cloud | True/False
To build a hybrid cloud, you must deploy resources to the public cloud | True/False
A private cloud must be disconnected from the internet | True/False

<details><summary>See Answer</summary>
<p>
  
Statement | Answer | Explanation
------------ | -------------  | -------------  
A company can extend a private cloud by adding its own physical servers to the public cloud | False | You cannot add physical servers to the public cloud. You can only deploy virtual servers in the public cloud. You can extend a private cloud by deploying virtual servers in a public cloud. This would create a hybrid cloud. 
To build a hybrid cloud, you must deploy resources to the public cloud  | True | A hybrid cloud is a combination of a private cloud and public cloud. Therefore, to create a hybrid cloud, you must deploy resources to a public cloud. 
A private cloud must be disconnected from the internet | False | It is not true that a private cloud must be disconnected from the Internet. Private clouds can be and most commonly are connected to the Internet. Private cloud means that the physical servers are managed by you. It does not mean that it is disconnected from the Internet. 
  
</p>
</details>

----

# Question 30 (Describe Cloud Concepts)

You have 50 virtual machines hosted on-premises and 50 virtual machines hosted in Azure. The on-premises virtual machines and the Azure virtual machines connect to each other.
Which type of cloud model is this?

Statement | Answer
------------ | -------------
A. | hybrid
B. | private
C. | public

<details><summary>See Answer</summary>
<p>
  
Statement | Answer | Explanation
------------ | -------------  | -------------  
 A. | hybrid |  https://azure.microsoft.com/en-gb/overview/what-is-hybrid-cloud-computing/ 
  
</p>
</details>

----

# Question 31 (Describe Cloud Concepts)

Check which statement is true or false.

Statement | Answer
------------ | -------------
A Platform as a Service (PaaS) solution that hosts web apps in Azure provides full control of the operating systems that hosts applications | True/False
A Platform as a Service (PaaS) solution that hosts web apps in Azure can be provided with additional memory by changing the pricing tier | True/False
A Platform as a Service (PaaS) solution can be configured to automatically scale the number of instances based on demand | True/False


<details><summary>See Answer</summary>
<p>
  
Statement | Answer | Explanation
------------ | -------------  | -------------  
A Platform as a Service (PaaS) solution that hosts web apps in Azure provides full control of the operating systems that hosts applications | False | A PaaS solution does not provide access to the operating system. The Azure Web Apps service provides an environment for you to host your web applications. Behind the scenes, the web apps are hosted on virtual machines running IIS. However, you have no direct access to the virtual machine, the operating system or IIS. 
A Platform as a Service (PaaS) solution that hosts web apps in Azure can be provided with additional memory by changing the pricing tier | True | .... 
A Platform as a Service (PaaS) solution can be configured to automatically scale the number of instances based on demand | True | A PaaS solution that hosts web apps in Azure does provide the ability to scale the platform automatically. This is known as autoscaling. Behind the scenes, the web apps are hosted on virtual machines running IIS. Autoscaling means adding more load balanced virtual machines to host the web apps. 
  
</p>
</details>


----

# Question 32 (Describe Cloud Concepts)

Your company plans to migrate all its data and resources to Azure.
The company's migration plan states that only Platform as a Service (PaaS) solutions must be used in Azure.
You need to deploy an Azure environment that meets the company migration plan.
Solution: You create Azure virtual machines, Azure SQL databases, and Azure Storage accounts.
Does this meet the goal?


Statement | Answer
------------ | -------------
A. | Yes
B. | No

<details><summary>See Answer</summary>
<p>
  
 Answer | Explanation
------------ | -------------  
B. No | Platform as a service (PaaS) is a complete development and deployment environment in the cloud. PaaS includes infrastructure, servers, storage, and networking but also middleware, development tools, business intelligence (BI) services, database management systems, and more. PaaS is designed to support the complete web application lifecycle: building, testing, deploying, managing, and updating. However, virtual machines are examples of Infrastructure as a service (IaaS). IaaS is an instant computing infrastructure, provisioned and managed over the internet. 
  
</p>
</details>


----

# Question 33 (Describe Cloud Concepts)

Your company plans to deploy several custom applications to Azure. The applications will provide invoicing services to the customers of the company. Each application will have several prerequisite applications and services installed. You need to recommend a cloud deployment solution for all the applications.
What should you recommend?


Statement | Answer
------------ | -------------
A. | Software as a Service (SaaS)
B. | Platform as a Service (Paas)
C. | Infrastructure as a Service (IaaS)



<details><summary>See Answer</summary>
<p>
  
 Answer | Explanation
------------ | -------------  
C. Infrastructure as a Service (IaaS) | Infrastructure as a service (IaaS) is an instant computing infrastructure, provisioned and managed over the internet. The IaaS service provider manages the infrastructure, while you purchase, install, configure, and manage your own software 
  
</p>
</details>


----

# Question 34 (Describe Cloud Concepts)

Check which statement is true or false.

Statement | Answer
------------ | -------------
Building a data center infrastructure is an example of operational expenditure (OpEx) costs | True/False
Monthly salaries for technical personnel are an example of operational expenditure (OpEx) costs | True/False
Leasing software is an example of operation expenditure (OpEx) costs | True/False


<details><summary>See Answer</summary>
<p>
  
Answer | Explanation 
------------ | -------------  
False | Building a data center infrastructure is capital expenditure, not operation expenditure. 
True | OpEx is ongoing costs (costs of operations) such as staff salaries. 
True | OpEx is ongoing costs (costs of operations) such as leasing software. If you purchased software as a one-off purchase, that would be CapEx, but leasing software is ongoing so it's OpEx.
 
  
</p>
</details>


----

# Question 35 (Describe Cloud Concepts)

Azure Cosmos DB is an example of an (...) offering.

- Platform as a Service (PaaS)
- Infrastructure as a Service (IaaS)
- Serverless
- Software as a Service (SaaS)

<details><summary>See Answer</summary>
<p>
  
Azure Cosmos DB is an example of a platform as a service (PaaS) cloud database provider.
 
  
</p>
</details>



----

# Question 36 (Describe Cloud Concepts)

Check which statement is true or false

Statement | Answer
------------ | -------------
With Software as a Service (SaaS), you must apply software updates | True/False
With Infrastructure as a Service (IaaS), you must install the software that you want to use | True/False
Azure Backup is an example of platform as a service (PaaS) | True/False


<details><summary>See Answer</summary>
<p>
  
Statement | Answer | Explanation
------------ | ------------ | -------------  
With Software as a Service (SaaS), you must apply software updates | False | With Software as a Service (SaaS), you must apply software updates 
With Infrastructure as a Service (IaaS), you must install the software that you want to use | True | With Infrastructure as a Service (IaaS), you must install the software that you want to use 
Azure Backup is an example of platform as a service (PaaS) | True | Azure Backup is an example of platform as a service (PaaS) 
 
  
</p>
</details>


----

# Question 37 (Describe Cloud Concepts)

Check which statement is true or false.

Statement | Answer
------------ | -------------
You can create a resource group inside a resource group | True/False
An Azure virtual machine can be in multiple resource groups | True/False
A resource group can contain resources from multiple Azure regions | True/False

<details><summary>See Answer</summary>
<p>
  
Statement | Answer | Explanation
------------ | -------------   | ------------- 
You can create a resource group inside a resource group | False | ...
An Azure virtual machine can be in multiple resource groups | False | Each resource can exist in only one resource group. 
A resource group can contain resources from multiple Azure regions | True | Resources from multiple different regions can be placed in a resource group. The resource group only contains metadata about the resources it contains. 
  
</p>
</details>

----

# Question 38 (Describe Cloud Concepts)

Check which statement is true or false.


Statement | Answer
------------ | -------------
Microsoft SQL Server 2019 installed on an Azure virtual machine is an example of Platform as a Service (PaaS) | True/False
Azure SQL Database in an example of platform as a service (Paas) | True/False
Azure Cosmos DB is an example of software as a service (SaaS) | True/False


<details><summary>See Answer</summary>
<p>
  
Statement | Answer
------------ | -------------  
Microsoft SQL Server 2019 installed on an Azure virtual machine is an example of Platform as a Service (PaaS) | False
Azure SQL Database in an example of platform as a service (Paas) | True
Azure Cosmos DB is an example of software as a service (SaaS) | False
 
https://docs.microsoft.com/en-us/azure/azure-sql/azure-sql-iaas-vs-paas-what-is-overview  
  
https://docs.microsoft.com/en-us/azure/cosmos-db/account-databases-containers-items 
  
https://www.red-gate.com/simple-talk/cloud/azure/overview-of-azure-cosmos-db  
  
</p>
</details>

----

# Question 39 (Describe Cloud Concepts)

A Micrsoft SQL Server database that is hosted in the cloud and has software updats managed by Azure is an example of 

- disaster recovery as a service (DRaaS)
- Infrastructure as a Service (IaaS)
- Platform as a Service (PaaS)
- Software as a Service (SaaS)


<details><summary>See Answer</summary>
<p>
  
- Platform as a Service (PaaS)
  
 https://docs.microsoft.com/en-us/azure/azure-sql/azure-sql-iaas-vs-paas-what-is-overview
 
  
</p>
</details>

----

# Question 40 (Describe Cloud Concepts)

Your company plans to migrate all its data and resources to Azure.
The company's migration plan states that only Platform as a Service (PaaS) solutions must be used in Azure.
You need to deploy an Azure environment that meets the company's migration plan.
What should you create?

Statement | Answer
------------ | -------------
A. | Azure virtual machines, Azure SQL databases, and Azure Storage accounts.
B. | an Azure App Service and Azure virtual machines that have Microsoft SQL Server installed.
C. | an Azure App Service and Azure SQL databases.
D. | Azure storage account and web server in Azure virtual machines.

<details><summary>See Answer</summary>
<p>
  
 Answer | Explanation 
------------ | -------------  
C. an Azure App Service and Azure SQL databases. | Azure App Service and Azure SQL databases are examples of Azure PaaS solutions. Therefore, this solution does meet the goal. 
  
</p>
</details>


----

# Question 41 (Describe Cloud Concepts)

What does a customer provide in a software as a service (SaaS) model?

Statement | Answer
------------ | -------------
A. | application data
B. | data storage
C. | compute resources
D. | application software

<details><summary>See Answer</summary>
<p>
  
Answer | Explanation
------------ | -------------  
A.  application data | SaaS provides a complete software solution which you purchase on a pay-as-you-go basis from a cloud service provider. You rent the use of an app for your organization and your users connect to it over the Internet, usually with a web browser. All of the underlying infrastructure, middleware, app software and app data are located in the service provider's data center. The service provider manages the hardware and software and with the appropriate service agreement, will ensure the availability and the security of the app and your data as well. 
  
</p>
</details>

----

# Question 42 (Describe Cloud Concepts)

Check which statement is true or false

Statement | Answer
------------ | -------------
Azure Files is an example of Infrastructure as a Service (IaaS) | True/False
A DNS server that runs on an Azure virtual machine is an example of Platform as a Service  (PaaS) | True/False
Microsoft Intune is an example of Software as a Service (SaaS) | True/False


<details><summary>See Answer</summary>
<p>
  
Statement | Answer
------------ | -------------
Azure Files is an example of Infrastructure as a Service (IaaS) | True
A DNS server that runs on an Azure virtual machine is an example of Platform as a Service (PaaS) | True
Microsoft Intune is an example of Software as a Service (SaaS) | True
 
  
https://azure.microsoft.com/en-gb/overview/what-is-iaas/
  
https://azure.microsoft.com/en-gb/overview/what-is-paas/
  
https://azure.microsoft.com/en-gb/overview/what-is-saas/  
  
</p>
</details>


----

# Question 43 (Describe Cloud Concepts)

Check which answer is true or fasel.

Statement | Answer
------------ | -------------
Cloud computing provides elastic scalabillity | True/False
Customers can minimize capital expenditure (CapEx) by using a public cloud | True/False
Cloud computing leverages virtualization to provide services to multiple customers simultaneously | True/False

<details><summary>See Answer</summary>
<p>
  
Statement | Answer
------------ | -------------
Cloud computing provides elastic scalabillity | True
Customers can minimize capital expenditure (CapEx) by using a public cloud | True
Cloud computing leverages virtualization to provide services to multiple customers simultaneously | True
 
  
</p>
</details>


----

# Question 44 (Describe Cloud Concepts)


When you need to delegate permission to several Azure virtual machines simultaneously, you must deploy the Azure virtual machines (...)

- to the same Azure region.
- by using the same Azure Resource Manager template.
- to the same resource group.
- to the same availability zone.



<details><summary>See Answer</summary>
<p>
  
- to the same resource group
  
A resource group is a logical container for Azure resources. Resource groups make the management of Azure resources easier.
With a resource group, you can allow a user to manage all resources in the resource group, such as virtual machines, websites, and subnets. The permissions you apply to the resource group apply to all resources contained in the resource group.

https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/overview#resource-groups https://docs.microsoft.com/en-us/azure/role-based-access-control/overview
 
  
</p>
</details>





----

# Question 45 (Describe Cloud Concepts)

You plan to deploy several Azure virtual machines.
You need to ensure that the services running on the virtual machines are available if a single data center fails.
Solution: You deploy the virtual machines to two or more availability zones.
Does this meet the goal?

Statement | Answer
------------ | -------------
A. | Yes
B. | No


<details><summary>See Answer</summary>
<p>
  
Answer | Explanation 
------------ | -------------  
A. Yes | Availability zones expand the level of control you have to maintain the availability of the applications and data on your VMs. An Availability Zone is a physically separate zone, within an Azure region. There are three Availability Zones per supported Azure region. Each Availability Zone has a distinct power source, network, and cooling. By architecting your solutions to use replicated VMs in zones, you can protect your apps and data from the loss of a datacenter. If one zone is compromised, then replicated apps and data are instantly available in another zone.
  
</p>
</details>


----

# Question 46 (Describe Cloud Concepts)

This question requires that you evaluate the underlined text to determine if it is correct.
One of the benefits of Azure SQL Data Warehouse is that high availability is built into the platform.


Statement | Answer
------------ | -------------
A. | No change is needed
B. | automatic scaling
C. | data compression
D. | versioning


<details><summary>See Answer</summary>
<p>
  
Azure Data Warehouse (now known as Azure Synapse Analytics) is a PaaS offering from Microsoft. As with all PaaS services from Microsoft, SQL Data
Warehouse offers an availability SLA of 99.9%. Microsoft can offer 99.9% availability because it has high availability features built into the platform.

https://docs.microsoft.com/en-us/azure/sql-data-warehouse/sql-data-warehouse-overview-faq
  
</p>
</details>

----

# Question 47 (Describe Cloud Concepts)

You plan to deploy several Azure virtual machines.
You need to ensure that the services running on the virtual machines are available if a single data center fails.
Solution: You deploy the virtual machines to two or more regions.
Does this meet the goal?

Statement | Answer
------------ | -------------
A. | Yes
B. | No

<details><summary>See Answer</summary>
<p>
  
Answer | Explanation
------------ | -------------  
A.  Yes | By deploying the virtual machines to two or more regions, you are deploying the virtual machines to multiple datacenters. This will ensure that the services running on the virtual machines are available if a single data center fails. Azure operates in multiple datacenters around the world. These datacenters are grouped in to geographic regions, giving you flexibility in choosing where to build your applications. You create Azure resources in defined geographic regions like 'West US', 'North Europe', or 'Southeast Asia'. You can review the list of regions and their locations. Within each region, multiple datacenters exist to provide for redundancy and availability. 
  
</p>
</details>

----

# Question 48 (Describe Cloud Concepts)

Check which statement is true or false.

Statement | Answer
------------ | -------------
Azure resources can only acces other resources in the same resource group | True/False
If you delete a resource group, all the resources in the resource group will be deleted | True/False
A resource group can contain resources from multiple Azure regions | True/False

<details><summary>See Answer</summary>
<p>
  
Statement | Answer | Explanation
------------ | ------------- | -------------
Azure resources can only acces other resources in the same resource group | False | A resource can interact with resources in other resource groups.
If you delete a resource group, all the resources in the resource group will be deleted | True | Deleting the resource group will remove the resource group as well as all the resources in that resource group. This can be useful for the management of resources. For example, a virtual machine has several components (the VM itself, virtual disks, network adapter etc.). By placing the VM in its own resource group, you can delete the VM along with all its associated components by deleting the resource group. Another example is when creating a test environment. You could place the entire test environment (Network components, virtual machines etc.) in one resource group. You can then delete the entire test environment by deleting the resource group.
A resource group can contain resources from multiple Azure regions | True | Resources from multiple different regions can be placed in a resource group. The resource group only contains metadata about the resources it contains.
  
https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-group-overview
  
https://www.codeisahighway.com/effective-ways-to-delete-resources-in-a-resource-group-on-azure/
  
</p>
</details>


----

# Question 49 (Describe Cloud Concepts)

You plan to store 20 TB of data in Azure. The data will be accessed infrequently and visualized by using Microsoft Power BI.
You need to recommend a storage solution for the data.
Which two solutions should you recommend? Each correct answer presents a complete solution.

Statement | Answer
------------ | -------------
A. | Azure Data Lake
B. | Azure Cosmos DB
C. | Azure SQL Data Warehouse
D. | Azure SQL Database
E. | Azure Database for PostgreSQL

<details><summary>See Answer</summary>
<p>
  
Statement | Answer
------------ | -------------  
 A. | Azure Data Lake
 C. | Azure SQL Data Warehouse 
  
You can use Power BI to analyze and visualize data stored in Azure Data Lake and Azure SQL Data Warehouse.
Azure Data Lake includes all of the capabilities required to make it easy for developers, data scientists and analysts to store data of any size and shape and at any speed, and do all types of processing and analytics across platforms and languages. It removes the complexities of ingesting and storing all your data while making it faster to get up and running with batch, streaming and interactive analytics. It also integrates seamlessly with operational stores and data warehouses so that you can extend current data applications.  
  
  
https://docs.microsoft.com/en-us/azure/data-lake-store/data-lake-store-power-bi
  
https://azure.microsoft.com/en-gb/solutions/data-lake/
  
https://docs.microsoft.com/en-us/azure/data-lake-store/data-lake-store-power-bi
  
</p>
</details>

----

# Question 50 (Describe Cloud Concepts)

You have an Azure environment that contains 10 web apps. To which URL should you connect to manage all the Azure resources? To answer, select the appropriate options in the answer area.

https:// ( A ) . ( B ) . com

A | B
------------ | -------------
admin | azure
portal | azurewebsites
www | microsoft

<details><summary>See Answer</summary>
<p>
  
A | B
------------ | -------------  
 portal | azure
  
The Azure portal is a web-based management interface where you can view and manage all your Azure resources in one unified hub, including web apps, databases, virtual machines, virtual networks, storage and Visual Studio team projects.
The URL of the Azure portal is https://portal.azure.com.  
  
</p>
</details>
