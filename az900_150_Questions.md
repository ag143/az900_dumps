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

# Question 51 (Describe Cloud Concepts)

You need to identify the type of failure for which an Azure Availability Zone can be used to protect access to Azure services.
What should you identify?

Statement | Answer
------------ | -------------
A. | a physical server failure
B. | an Azure region failure
C. | a storage failure
D. | an Azure data center failure



<details><summary>See Answer</summary>
<p>
  
 Answer | Explanation
------------ | -------------  
D. an Azure data center failure | Availability zones expand the level of control you have to maintain the availability of the applications and data on your VMs. An Availability Zone is a physically separate zone, within an Azure region. There are three Availability Zones per supported Azure region. Each Availability Zone has a distinct power source, network, and cooling. By architecting your solutions to use replicated VMs in zones, you can protect your apps and data from the loss of a datacenter. If one zone is compromised, then replicated apps and data are instantly available in another zone. 
  
  
</p>
</details>

----

# Question 52 (Describe Cloud Concepts)

You plan to extend your company's network to Azure. The network contains a VPN appliance that uses an IP address of 131.107.200.1.
You need to create an Azure resource that defines the VPN appliance in Azure.
Which Azure resource should you create? To answer, select the appropriate resource in the answer area.

Statement | Answer
------------ | -------------
A. | NAT gateways
B. | Application gateways
C. | Local Network gateways
D. | Virtual Network gateways
E. | On-premises Data Gateways
F. | Azure Data Box Gateway
G. | Azure Stack Edge/Data Box Gateway
H. | Web Application Firewall policies


<details><summary>See Answer</summary>
<p>
  
 Answer | Explanation 
------------ | -------------  
C.  Local Network gateways | A Local Network Gateway is an object in Azure that represents your on-premise VPN device. A Virtual Network Gateway is the VPN object at the Azure end of the VPN. A connection is what connects the Local Network Gateway and the Virtual Network Gateway to bring up the VPN. The local network gateway typically refers to your on-premises location. You give the site a name by which Azure can refer to it, then specify the IP address of the on-premises VPN device to which you will create a connection. You also specify the IP address prefixes that will be routed through the VPN gateway to the VPN device. The address prefixes you specify are the prefixes located on your on-premises network. If your on-premises network changes or you need to change the public IP address for the VPN device, you can easily update the values later.
  
https://docs.microsoft.com/en-us/azure/vpn-gateway/tutorial-site-to-site-portal
  
</p>
</details>

----

# Question 53 (Describe Cloud Concepts)

You plan to deploy several Azure virtual machines.
You need to ensure that the services running on the virtual machines are available if a single data center fails.
Solution: You deploy the virtual machines to two or more resource groups.
Does this meet the goal?

Statement | Answer
------------ | -------------
A. | Yes
B. | No


<details><summary>See Answer</summary>
<p>
  
 Answer | Explanation
------------ | -------------  
B. No | A resource group is a logical container for Azure resources. When you create a resource group, you specify which location to create the resource group in. However, when you create a virtual machine and place it in the resource group, the virtual machine can still be in a different location (different datacenter). Therefore, creating multiple resource groups, even if they are in separate datacenters does not ensure that the services running on the virtual machines are available if a single data center fails.
  
</p>
</details>



----

# Question 54 (Describe Cloud Concepts)

You plan to deploy several Azure virtual machines.
You need to ensure that the services running on the virtual machines are available if a single data center fails.
Solution: You deploy the virtual machines to a scale set.
Does this meet the goal?


Statement | Answer
------------ | -------------
A. | Yes
B. | No


<details><summary>See Answer</summary>
<p>
  
 Answer | Explanation
------------ | -------------  
B. No | This answer does not specify that the scale set will be configured across multiple data centers so this solution does not meet the goal. Azure virtual machine scale sets let you create and manage a group of load balanced VMs. The number of VM instances can automatically increase or decrease in response to demand or a defined schedule. Scale sets provide high availability to your applications, and allow you to centrally manage, configure, and update many VMs. Virtual machines in a scale set can be deployed across multiple update domains and fault domains to maximize availability and resilience to outages due to data center outages, and planned or unplanned maintenance events. 
  
</p>
</details>

----

# Question 55 (Describe Cloud Concepts)

Check which statement is true or false.

Statement | Answer
------------ | -------------
An Azure subscription can be associated to multiple Azure Active Directory (Azure AD) tenants | True/False
You can change the Azure Active Directory (Azure AD tenant) to which an Azure subscription is associated | True/False
When an Azure subscription expires, the associated Azure Active Directory (Azure AD) tenant is deleted automatically | True/False

<details><summary>See Answer</summary>
<p>
  
Statement | Answer | Explanation
------------ | ------------- | -------------
An Azure subscription can be associated to multiple Azure Active Directory (Azure AD) tenants | False | An Azure AD tenant can have multiple subscriptions but an Azure subscription can only be associated with one Azure AD tenant. 
  You can change the Azure Active Directory (Azure AD tenant) to which an Azure subscription is associated | True |  If your subscription expires, you lose access to all the other resources associated with the subscription. However, the Azure AD directory remains in Azure. You can associate and manage the directory using a different Azure subscription. 
  When an Azure subscription expires, the associated Azure Active Directory (Azure AD) tenant is deleted automatically | False | If your subscription expires, you lose access to all the other resources associated with the subscription. However, the Azure AD directory remains in Azure. You can associate and manage the directory using a different Azure subscription.
  
  
https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-how-subscriptions-associated-directory
  
</p>
</details>


----

# Question 56 (Describe Cloud Concepts)

Peter is working in an organization that hosts its non-critical servers in Azure. He has asked to recommend a support plan that gives billing and subscription management support, Azure Advisor access, and Azure health status and notifications at the lowest possible cost. Which of the following support plan should Peter suggest in this case to meet the requirement?

Choice | Answer
------------ | -------------
A. | Basic
B. | Standard
C. | Developer
D. | Premier

<details><summary>See Answer</summary>
<p>
  
Choice | Answer
------------ | -------------  
 A. | Basic
  
</p>
</details>

----

# Question 57 (Describe Cloud Concepts)

Jane is working in an organization that plans on storing 40 TB of data in Azure that they can query using either serverless on-demand or provisioned resources at a scale.

Also, it is required that the stored data must be integrated and visualized using Microsoft Power BI, for analytics.
Which of the following Azure service should Jane suggest in this case?

Choice | Answer
------------ | -------------
A. | Azure CycleCloud
B. | Azure Sphere
C. | Azure Database Migration Service
D. | Azure Synapse Analytics

<details><summary>See Answer</summary>
<p>
  
  
Choice | Answer
------------ | -------------  
 D. | Azure Synapse Analytics
  
  
https://azure.microsoft.com/en-us/services/synapse-analytics/  
  
</p>
</details>

----

# Question 58 (Describe Cloud Concepts)

(...) is the ability of a system to remain up and running even in case one if its components is non functional like an outage on a single Azure data center.

- Agility
- Scalability
- Fault tolerance
- Elasticity


<details><summary>See Answer</summary>
<p>
  
- Fault tolerance 
 
  
</p>
</details>

----

# Question 59 (Describe Cloud Concepts)

(...) is used to explain the personal data that Microsoft processes, how Microsoft processes it, and for what purposes

- Microsoft Online Subscription Agreement
- Microsoft Cloud Agreement (MCA)
- Microsoft Privacy Statement 
- Micrsoft Online Services Level Agreement


<details><summary>See Answer</summary>
<p>
  
- Microsoft Privacy Statement 
 
 
  
</p>
</details>


----

# Question 60 (Describe core Azure services)

An organization plans to migrate its docker containers to Azure. You have been asked to suggest a solution that offers a set of version control tools to help developers manage the application code. Which amongst the following will you include in your recommendation?

Choice | Answer
------------ | -------------
A. | Azure Monitor
B. | Azure Repos
C. | Azure Pipelines
D. | Azure Activity Log

<details><summary>See Answer</summary>
<p>
  
Choice | Answer
------------ | -------------  
 B. | Azure Repos
  
 https://azure.microsoft.com/en-us/services/devops/repos/ 
  
</p>
</details>


----

# Question 61 (Describe Cloud Concepts)

A company plans to migrate its application servers hosted on-premises to Azure. Which of the following is the key advantage of using the public cloud for its servers?

Choice | Answer
------------ | -------------
A. | Public cloud is a shared entity operated by a third-party cloud service provider that various corporations can use.
B. | Public cloud is used exclusively by a single business or organization.
C. | Public cloud is owned by the public and not a private organization or corporation.
D. | Public cloud is a free shared entity that is crowdfunded by the public and is accessible by everyone.

<details><summary>See Answer</summary>
<p>
  
Choice | Answer
------------ | -------------  
A. | Public cloud is a shared entity operated by a third-party cloud service provider that various corporations can use. 
  
</p>
</details>


----

# Question 62 (Describe core Azure services)

Let us suppose a company needs to create around 50 customized Virtual Machines every week. Out of which 20 are Windows-based Virtual machines and the remaining 30 are Ubuntu Machines. Which of the given options would assist in reducing the administrative effort needed to deploy the machines?

Choice | Answer
------------ | -------------
A. | Azure DevTest Labs
B. | Microsoft Managed Desktop
C. | Azure virtual machine scale sets
D. | Azure Reserved Virtual Machines (VM) Instances

<details><summary>See Answer</summary>
<p>
  
Choice | Answer
------------ | -------------  
 A. | Azure DevTest Labs
  
Azure DevTest Labs provides developers and testers a self-service sandbox environment to quickly create Dev/Test environments while minimizing waste and controlling costs. Check out this video to see all the benefits you can get from Azure DevTest Labs.
  
 https://azure.microsoft.com/en-us/services/devtest-lab/ 
  
</p>
</details>


----

# Question 63 (Describe Cloud Concepts)

You have plans to deploy several Azure virtual machines. You are required to ensure that the services running on the virtual machines are available, even if a single data center fails.

Solution: You suggest deploy the virtual machines to two or more scale sets.

Does the suggested solution meet the desired goal?

Choice | Answer
------------ | -------------
A. | Yes, the solutions meets the desired goal
B. | No, the solution does not meet the desired goal

<details><summary>See Answer</summary>
<p>
  
Choice | Answer
------------ | -------------  
 B. | No, the solution does not meet the desired goal
  
Azure virtual machine scale sets let you create and manage a group of load balanced VMs. The number of VM instances can automatically increase or decrease in response to demand or a defined schedule. Scale sets provide high availability to your applications, and allow you to centrally manage, configure, and update a large number of VMs. With virtual machine scale sets, you can build large-scale services for areas such as compute, big data, and container workloads. 
  
</p>
</details>


----

# Question 64 (Describe Cloud Concepts)

Let us suppose a company wants to try out some services that are being offered by Azure in Public Preview.
In this case, should the company deploy resources which are part of Public Preview in their production environment?

Choice | Answer
------------ | -------------
A. | Yes
B. | No

<details><summary>See Answer</summary>
<p>
  
Choice | Answer
------------ | -------------  
 B. | No
  
Azure Active Directory preview programs
Azure Active Directory provides updates and new features in the form of preview programs. Microsoft rolls out previews in phases to give Microsoft and customers the opportunity to evaluate and understand the new feature before it becomes part of the standard service of Azure AD. The phases are as follows:

- Private preview
  During this phase we invite a few customers to take part in early access to new concepts and features. This phase does not include formal support.
- Public preview
  During this phase we allow any customer with the proper Azure AD license to evaluate the new feature. Microsoft Customer Support Services will supply support services during     this phase, but normal service level agreements do not apply. For new features exposed in the Azure AD Portal, customer can expect to see information banners in the user         interface that draw attention to the new experience available during the preview. By clicking on the information banner customers then opt-in to the preview experience.
- Generally available (GA)
  After the public preview is completed, the feature is open for any licensed customer to use and is supported via all Microsoft support channels. Be aware when a new feature       impacts existing functionality, it might change the way you or your users use the functionality.
  Every Azure Active Directory preview program has different opt-in requirements and dependencies.
  
</p>
</details>


----

# Question 65 (Describe general security and network security features)

You are working in a company that plans to migrate their application to Azure. This application will be responsible to host the banking records for its users. You have been asked to suggest a security information event management (SIEM) and security orchestration automated response (SOAR) solution.
Which of the following Azure service will meet the requirement?


Choice | Answer
------------ | -------------
A. | Azure CycleCloud
B. | Azure Sphere
C. | Azure Security Center
D. | Azure Sentinel

<details><summary>See Answer</summary>
<p>
  
Choice | Answer
------------ | -------------  
 D. | Azure Sentinel
  
  
Microsoft Azure Sentinel is a scalable, cloud-native, Security Information Event Management (SIEM) and Security Orchestration Automated Response (SOAR) solution. Azure Sentinel delivers intelligent security analytics and threat intelligence across the enterprise, providing a single solution for alert detection, threat visibility, proactive hunting, and threat response.

Azure Sentinel is your birds-eye view across the enterprise alleviating the stress of increasingly sophisticated attacks, increasing volumes of alerts, and long resolution time frames.

- Collect data 
  at cloud scale across all users, devices, applications, and infrastructure, both on-premises and in multiple clouds. 

- Detect previously undetected threats, 
  and minimize false positives using Microsoft's analytics and unparalleled threat intelligence. 

- Investigate threats 
  with artificial intelligence, and hunt for suspicious activities at scale, tapping into years of cyber security work at Microsoft. 

- Respond to incidents rapidly 
  with built-in orchestration and automation of common tasks.
  
</p>
</details>


----

# Question 66 (Describe core Azure services)

Which of the following Azure Service would you suggest when you are planning to create an application with an event-based architecture that has the feature to ingest events from Blob storage and create custom topics?

Choice | Answer
------------ | -------------
A. | Azure Machine Learning Studio
B. | Azure Functions
C. | Azure Event Grid
D. | Azure Logic Apps

<details><summary>See Answer</summary>
<p>
  
Choice | Answer
------------ | -------------  
 C. | Azure Event Grid
 
Azure Event Grid allows you to easily build applications with event-based architectures. First, select the Azure resource you would like to subscribe to, and then give the event handler or WebHook endpoint to send the event to. Event Grid has built-in support for events coming from Azure services, like storage blobs and resource groups. Event Grid also has support for your own events, using custom topics.

You can use filters to route specific events to different endpoints, multicast to multiple endpoints, and make sure your events are reliably delivered.

Azure Event Grid is deployed to maximize availability by natively spreading across multiple fault domains in every region, and across availability zones (in regions that support them). For a list of regions that are supported by Event Grid, see Products available by region.
  
</p>
</details>

----

# Question 67 (Describe identity, governance, privacy, and compliance features)

________________ is used to explain the personal data that Microsoft processes, how Microsoft processes it, and for what purposes.

Choice| Answer
------------ | ------------- 
A. | Microsoft Online Subscription Agreement
B. | Microsoft Cloud Agreement (MCA)
C. | Microsoft Online Services Level Agreement
D. | Microsoft Privacy Statement

<details><summary>See Answer</summary>
<p>
  
Choice| Answer
------------ | -------------  
D. | Microsoft Privacy Statement
  
</p>
</details>

----

# Question 68 (Describe core Azure services)

You organization is planning to build a customized solution for uploading weather data to Azure using several million sensors. Which of the given service should the company use to connect, monitor, and control the sensors without managing the infrastructure?

Choice | Answer
------------ | -------------
A. | Azure Files
B. | Azure App Service
C. | Azure Virtual Machine
D. | Azure IoT Hub

<details><summary>See Answer</summary>
<p>
  
Choice| Answer
------------ | -------------  
 D. | Azure IoT Hub
  
IoT Hub is a managed service hosted in the cloud that acts as a central message hub for communications in both directions between an IoT application and its attached devices. You can connect millions of devices and their backend solutions reliably and securely. Almost any device can be connected to an IoT Hub.

Several messaging patterns are supported, including device-to-cloud telemetry, uploading files from devices, and request-reply methods to control your devices from the cloud. IoT Hub also supports monitoring to help you track creating devices, connecting devices, and device failures.

With IoT Hub's capabilities, you can build scalable, full-featured IoT solutions such as managing industrial equipment used in manufacturing, tracking valuable assets in healthcare, and monitoring office building usage. 
  
</p>
</details>

----

# Question 69 (Describe Cloud Concepts)

An organization plans to migrate its application named QuickApp1 to Azure.
As per the observed pattern QuickApp1 has a low usage during the second and fourth weeks and high usage during the first and third weeks of the month
Which amongst the following benefit of Azure Cloud Services will support cost management for this kind of usage pattern?

Choice | Answer
------------ | -------------
A. | Load Balancing
B. | Elasticity
C. | High availibility
D. | Fault tolerance

<details><summary>See Answer</summary>
<p>
  
Choice| Answer
------------ | -------------  
 B. | Elasticity
  
Azure elasticity as a service is referred to a cloud service that enables in automatically scaling Azure hosted resources in par with the demand and configured parameters. It provides Azure Administrators with the ability to auto scale Azure infrastructure and resources as and when needed. Typically, it is delivered through an Azure Monitoring and Automation Software that monitors the systems for certain conditions and automatically scales / downscales infrastructure as needed.
  
  
  
</p>
</details>

----

# Question 70 (Describe Cloud Concepts)

A company plans to migrate all of its servers and data to Azure. John has been asked to suggest a solution that allows to only use Software-as-a-Service Azure products that will support the planned migration. John suggests to deploy Azure virtual machines and Azure SQL Database. Does the solution suggested by John meet the requirement?


Choice | Answer
------------ | -------------
A | Yes, it meets the requirement
B | No, it does not meet the requirement

<details><summary>See Answer</summary>
<p>
  
Choice| Answer
------------ | -------------  
 B | No, it does not meet the requirement
  
 Virtual Machines are Infrastructure as a Service (IaaS)
 Azure SQL Database is Platform as a Service (Paas)
  
</p>
</details>



----

# Question 71 (Describe core Azure services)

Which of the following Azure Service would you suggest when you are planning to create an application with an event-based architecture that has the feature to ingest events from Blob storage and create custom topics?

Choice | Answer
------------ | -------------
A. | Azure Functions
B. | Azure Machine Learning Studio
C. | Azure Logic Apps
D. | Azure Event Grid

<details><summary>See Answer</summary>
<p>
  
Choice| Answer
------------ | -------------  
 D. | Azure Event Grid
  
</p>
</details>

----

# Question 72 (Describe core solutions and management tools on Azure)

Jacob is working in an organization. He has been asked to migrate its SQL Database to Azure by ensuring that other users in the organization do not accidentally delete or modify critical resources.
Which of the following Azure feature should Jacob use to meet the requirement?

Choice | Answer
------------ | -------------
A. | Azure Resource Manager Locks
B. | Azure role-based acces control
C. | Azure Policy
D. | Azure Active Directory

<details><summary>See Answer</summary>
<p>
  
Choice| Answer
------------ | -------------  
 A. | Azure Resource Manager Locks
  
 Lock resources to prevent unexpected changes 
  
 As an administrator, you can lock a subscription, resource group, or resource to prevent other users in your organization from accidentally deleting or modifying critical resources. The lock overrides any permissions the user might have.

You can set the lock level to CanNotDelete or ReadOnly. In the portal, the locks are called Delete and Read-only respectively.

CanNotDelete means authorized users can still read and modify a resource, but they can't delete the resource.
ReadOnly means authorized users can read a resource, but they can't delete or update the resource. Applying this lock is similar to restricting all authorized users to the permissions granted by the Reader role.
Unlike role-based access control, you use management locks to apply a restriction across all users and roles.
  
</p>
</details>


----

# Question 73 (Describe core solutions and management tools on Azure)

Let us suppose you work for ABC Ltd. which has several business units. Each business unit requires 20 different Azure resources for daily operation. All the business units require the same type of Azure resources. Now, you are required to suggest a solution to automate the creation of Azure resources.

Which of the following options would you suggest in this case?

Choice | Answer
------------ | -------------
A. | Virtual machine scale sets
B. | The Azure API Management service
C. | Management groups
D. | Azure Resource Manager templates

<details><summary>See Answer</summary>
<p>
  
Choice| Answer
------------ | -------------  
 D. | Azure Resource Manager templates
  
  
With the move to the cloud, many teams have adopted agile development methods. These teams iterate quickly. They need to repeatedly deploy their solutions to the cloud, and know their infrastructure is in a reliable state. As infrastructure has become part of the iterative process, the division between operations and development has disappeared. Teams need to manage infrastructure and application code through a unified process.

To meet these challenges, you can automate deployments and use the practice of infrastructure as code. In code, you define the infrastructure that needs to be deployed. The infrastructure code becomes part of your project. Just like application code, you store the infrastructure code in a source repository and version it. Any one on your team can run the code and deploy similar environments.

To implement infrastructure as code for your Azure solutions, use Azure Resource Manager templates (ARM templates). The template is a JavaScript Object Notation (JSON) file that defines the infrastructure and configuration for your project. The template uses declarative syntax, which lets you state what you intend to deploy without having to write the sequence of programming commands to create it. In the template, you specify the resources to deploy and the properties for those resources.

We've introduced a new language named Bicep that's used to develop ARM template JSON. Bicep files and JSON templates offer the same capabilities. You can convert templates between the two languages. Bicep provides a syntax that's easier to use for creating templates. For more information, see What is Bicep?.
  
</p>
</details>


----

# Question 74 (Describe core Azure services)

You are deploying an application on Azure. You want to ensure high availability and data protection in the event of a regional disaster. What Azure technology will help most in this task?

Choice | Answer
------------ | -------------
A. | Locally Redundant Storage
B. | Availibility Set
C. | Zone-redundant sotrage
D. | Geo-zone-redundant storage



<details><summary>See Answer</summary>
<p>
  
Choice| Answer
------------ | -------------  
 D. | Geo-zone-redundant storage
  
For protection against regional disasters, Microsoft recommends using geo-zone-redundant storage (GZRS), which uses ZRS in the primary region and also geo-replicates your data to a secondary region.  
  
</p>
</details>


----

# Question 75 (Describe core solutions and management tools on Azure)

You have an Azure virtual network named VNet in a resource group named Bob-RG.
You assign an Azure policy specifying virtual networks are not an allowed resource type in Bob-RG.
What happens to VNet once this policy is applied?

Choice | Answer
------------ | -------------
A. | Bob-RG is deleted automatically
B. | VNet is deleted automatically
C. | VNet continues to function normally, but no new subnets can be added.
D. | VNet is moved to a new resource group

<details><summary>See Answer</summary>
<p>
  
Choice| Answer
------------ | -------------  
 C. | VNet continues to function normally, but no new subnets can be added.
  
 Azure policies that determine the allowed types of resources can only prevent non-compliant resources from being created. Existing non-compliant resources are not affected. However, the policy is flagged as non-compliant so that the administrator can determine action (if any).
  
</p>
</details>


----

# Question 76 (Describe Cloud Concepts)

Which of the following are characteristic of private clouds?

Choice | Answer
------------ | -------------
A. | Improved security
B. | Limited flexibility
C. | High scalability
D. | Lower costs

<details><summary>See Answer</summary>
<p>
  
Choice| Answer
------------ | -------------  
 A. | Improved security
 C. | High scalability
  
 - Improved security,
   because resources are not shared with others, private clouds provide higher levels of control and security.
  
  - High scalability,
   private clouds still afford the scalability and efficiency of a public cloud. Resources are purchased and available to meet your business needs.
  
</p>
</details>


----

# Question 77 (Describe core Azure services)

You need to create a network drive in Azure Storage. The drive needs to be accessible from several computers that run Windows 8.1.
What storage solution should you create?

Choice | Answer
------------ | -------------
A. | A Queue service in a storage account
B. | A Blobl service in a storage account
C. | A File service in a storage account
D. | A Virtual Machine Data Disk


<details><summary>See Answer</summary>
<p>
  
Choice| Answer
------------ | -------------  
  C. | A File service in a storage account
  
 Azure Files offers fully managed file shares in the cloud that are accessible via the industry standard Server Message Block (SMB) protocol. Azure file shares can be mounted concurrently by cloud or on-premises deployments of Windows, Linux, and macOS.
 
  
</p>
</details>


----

# Question 78 (Describe Cloud Concepts)

Which of the following statements about Azure availability zones are true? (Choose the best 2 answers).


Choice | Answer
------------ | -------------
A. | An Availability Zone in an Azure region combines a fault domain and an update domain
B. | Availability zones are used to ensure that the VM resources are isolated from each other when they are deployed within an Azure datacenter.
C. | Only virtual machines that run Windows Server can be created in availability zones.
D. | Availability zones are used to replicate data and applications to multiple data centers within an Azure region. Zone-redundant services replicate your applications and data across Availability Zones.

<details><summary>See Answer</summary>
<p>
  
Choice| Answer | Explanation
------------ | -------------  | -------------
 A. | An Availability Zone in an Azure region combines a fault domain and an update domain | By using this combination, high availability can be achieved.
 D. | Availability zones are used to replicate data and applications to multiple data centers within an Azure region. Zone-redundant services replicate your applications and data across Availability Zones. | Multiple datacenters protect your applications and data across availability zones to protect from single points of failure.
  
  
</p>
</details>


----

# Question 79 (Describe core Azure services)

You are the system administrator for T-Bones Restaurant Group, Inc. You currently have an on-premises data center that consists of 50 Windows servers running IIS and SQL Server.
IT management has dictated that all systems should be moved to Azure in the coming year. They also state that only platform-as-a-service (PaaS) solutions should be implemented.
Which of the following meet these requirements?

Choice | Answer
------------ | -------------
A. | Azure App Service
B. | Azure Virtual Network
C. | Azure SQL Database
D. | Azure Virtual Machines

<details><summary>See Answer</summary>
<p>
  
Choice | Answer | Explanation
------------ | -------------  | -------------
  A. | Azure App Service | Azure App Service is a platform-as-a-service (PaaS) offering for web services and is a common solution for the migration of IIS.
C. | Azure SQL Database | Azure SQL Database is a platform-as-a-service (PaaS) offering for relational database management and is a common solution for the migration of SQL.

 https://azure.microsoft.com/en-us/services/app-service/
  
 https://azure.microsoft.com/en-us/products/azure-sql/database/
  
</p>
</details>

----

# Question 80 (Describe core Azure services)

Your company wants to make use of Azure for deployment of various solutions. They want to ensure suspicious attacks and threats to resources in their Azure account are prevented. Which of the following helps prevent such attacks by using built-in sensors in Azure?

Choice | Answer
------------ | -------------
A. | Azure Privileged Identity Management
B. | Azure DDoS Protection
C. | Azure Advanced Threat Protection
D. | Azure AD Identity Protection

<details><summary>See Answer</summary>
<p>
  
Choice| Answer | Explanation
------------ | -------------   | -------------  
 C. | Azure Advanced Threat Protection | The Microsoft documentation states the below feature on the Azure Advanced Threat Protection service:Azure ATP monitors and analyzes user activities and information across your network, such as permissions and group membership, creating a behavioral baseline for each user. Azure ATP then identifies anomalies with adaptive built-in intelligence, giving you insights into suspicious activities and events, revealing the advanced threats, compromised users, and insider threats facing your organization. Azure ATP’s proprietary sensors monitor organizational domain controllers, providing a comprehensive view for all user activities from every device.
  
 https://docs.microsoft.com/en-us/azure-advanced-threat-protection/what-is-atp 
  
</p>
</details>


----

# Question 81 (Describe Cloud Concepts)

Which of the following statements about SaaS cloud services is correct?

Choice | Answer
------------ | -------------
A. | The cloud service provider is responsible for all application upgrades.
B. | The client is responsible for purchasing all client software.
C. | The client has complete control over the application.
D. | Applications must be accessed from a secure network (aka VPN)

<details><summary>See Answer</summary>
<p>
  
Choice | Answer
------------ | -------------  
  A. | The cloud service provider is responsible for all application upgrades.
  
 The cloud service provider performs all underlying hardware, OS, and middleware updates.
 
  
</p>
</details>


----

# Question 82 (Describe core solutions and management tools on Azure)

You are the systems administrator for Highlander Cutlery, Inc.
Your company has an on-premises network that contains multiple servers.
As part of a headcount reduction, the company plans to reduce the following administrative responsibilities of network administrators:

- Backing up application data
- Replacing failed server hardware
- Managing physical server security
- Updating server operating systems
- Managing permissions to shared documents

The company plans to migrate several servers to Azure virtual machines.
Which administrative responsibilities will be reduced after the planned migration?


Choice | Answer
------------ | -------------
A. | Updating server operating systems
B. | Managing permissions to shared documents
C. | Backing up application data
D. | Managing physical server security
E. | Replacing failed server hardware

<details><summary>See Answer</summary>
<p>
  
Choice| Answer | Explanation
------------ | -------------  | -------------  
 D. | Managing physical server security | One advantage of the IaaS cloud model is that a cloud service provider can often provide better security for your applications and data than what you can achieve in-house.
E. | Replacing failed server hardware  | IaaS sidesteps the upfront expense of setting up and managing an on-site data center, making it an economical option for start-ups and businesses testing new ideas.
 
  
</p>
</details>


----

# Question 83 (Describe core Azure services)

You need to create an Azure storage solution that will store messages created by an Azure web role. The messages will then be processed by an Azure worker role.
What type of storage solution should you create?



Choice | Answer
------------ | -------------
A. | A Queue service in a storage account
B. | A Blob service in a storage account
C. | A File service in a storage account
D. | Azure Files offers fully managed file shares in the cloud that are accessible via the industry standard Server Message Block (SMB) protocol. Azure file shares can be mounted concurrently by cloud or on-premises deployments of Windows, Linux, and macOS.


<details><summary>See Answer</summary>
<p>
  
Choice| Answer | Explanation
------------ | ------------- | ------------ 
A. | A Queue service in a storage account |  Azure Queue storage is a service for storing large numbers of messages that can be accessed from anywhere in the world via authenticated calls using HTTP or HTTPS. https://docs.microsoft.com/en-us/azure/storage/queues/storage-queues-introduction
 
  
</p>
</details>



----

# Question 84 (Describe core Azure services)

Which Azure service can provide big data analysis for machine learning?

Choice | Answer
------------ | -------------
A. | Azure WebJobs
B. | Azure Databricks
C. | Azure App Service
D. | Application Insights

<details><summary>See Answer</summary>
<p>
  
Choice| Answer | Explanation
------------ | -------------  | -------------
 B. | Azure Databricks | Azure Databricks is an Apache Spark-based analytics platform optimized for the Microsoft Azure cloud services platform. Databricks enables collaboration between data scientists, data engineers, and business analysts.
  
 https://docs.microsoft.com/en-us/azure/azure-databricks/what-is-azure-databricks
  
</p>
</details>


----

# Question 85 (Describe core Azure services)

Which of the following components are required to establish communication between on-premises resources and resources in Azure?

Choice | Answer
------------ | -------------
A. | VNet peer
B. | Virtual Network
C. | Virtual network gateway
D. | Route tables


<details><summary>See Answer</summary>
<p>
  
Choice | Answer | Explanation
------------ | -------------  | ------------- 
 B. | Virtual Network | Azure Virtual Network enables many types of Azure resources, such as Azure Virtual Machines (VM), to securely communicate with each other, the internet, and on-premises networks. https://docs.microsoft.com/en-us/azure/virtual-network/virtual-networks-overview
  C. | Virtual network gateway | A virtual network gateway defines the Azure network side of a site-to-site virtual private network. https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-about-vpngateways
  
  
  
</p>
</details>


----

# Question 86 (Describe Cloud Concepts)

You are deploying an application on Azure. You want to ensure high availability and data protection in the event of a regional disaster. What Azure technology will help most in this task?


Choice | Answer
------------ | -------------
A. | Geo-zone-redunant storage
B. | Avaibility Set
C. | Zone-redundant storage
D. | Locally-redundant storage

<details><summary>See Answer</summary>
<p>
  
Choice| Answer | Explanation 
------------ | -------------  | ------------- 
 A. | Geo-zone-redunant storage | For protection against regional disasters, Microsoft recommends using geo-zone-redundant storage (GZRS), which uses ZRS in the primary region and also geo-replicates your data to a secondary region. Reference: Geo-zone-redundant storage.
  
</p>
</details>

----

# Question 87 (Describe core Azure services)

Which of the following components can be used to load balance traffic to web applications, such as Azure App Service web apps using layer 7 of the OSI model?

Choice | Answer
------------ | -------------
A. | Virtual Network
B. | Virtual Network Gateway
C. | Application Gateway
D. | Route table
E. | Load Balancer


<details><summary>See Answer</summary>
<p>
  
Choice| Answer | Explanation
------------ | -------------  | -------------  
 C. | Application Gateway | Azure Application Gateway is a web traffic load balancer that enables you to manage traffic to your web applications. Traditional load balancers operate at the transport layer (OSI layer 4 — TCP and UDP) and route traffic based on source IP address and port to a destination IP address and port.
  
 https://docs.microsoft.com/en-us/azure/application-gateway/overview 
  
</p>
</details>


----

# Question 88 (Describe core Azure services)

Your company wants to make use of Azure for deployment of various solutions. They want to ensure suspicious attacks and threats to resources in their Azure account are prevented. Which of the following helps prevent such attacks by using built-in sensors in Azure?

Choice | Answer
------------ | -------------
A. | Azure DDos protection
B. | Azure Advanced Threat Protection
C. | Azure Privilegd Identity Management
D. | Azure Priviliged  Identity Management
E. | Azure Identity Protection


<details><summary>See Answer</summary>
<p>
  
Choice| Answer | Explanation
------------ | -------------  |  -------------
 B. | Azure Advanced Threat Protection | The Microsoft documentation states the below feature on the Azure Advanced Threat Protection service: Azure ATP monitors and analyzes user activities and information across your network, such as permissions and group membership, creating a behavioral baseline for each user. Azure ATP then identifies anomalies with adaptive built-in intelligence, giving you insights into suspicious activities and events, revealing the advanced threats, compromised users, and insider threats facing your organization. Azure ATP’s proprietary sensors monitor organizational domain controllers, providing a comprehensive view for all user activities from every device.

https://docs.microsoft.com/en-us/azure-advanced-threat-protection/what-is-atp
  
</p>
</details>


----

# Question 89 (Describe core solutions and management tools on Azure)

Which of the following tools can be used on a workstation running Ubuntu Linux with a GNOME desktop?

Choice | Answer
------------ | -------------
 A. | AzCopy v9 
 B. | Azure PowerShell
 C. | Azure Cloud Shell
 D. | Azure CLI
 

<details><summary>See Answer</summary>
<p>
  
Choice| Answer | Explanation
------------ | -------------  | -------------  
 B. | Azure PowerShell | PowerShell Core is now an open-source project on GitHub and can be installed on Windows, macOS, and Linux.
 C. | Azure Cloud Shell | Azure Cloud Shell is an interactive, browser-accessible shell for managing Azure resources. It provides the flexibility of choosing the shell experience that best suits the way you work. Linux users can opt for a Bash experience, while Windows users can opt for PowerShell.
 D. | Azure CLI | The Azure command line interface (CLI) is Microsoft's cross-platform command line experience for managing Azure resources. It can be installed on macOS, Linux, or Windows.
  
  
</p>
</details>


----

# Question 90 (Describe core Azure services)

Which of the following is true regarding HDInsight?


Choice | Answer
------------ | -------------
A. | It is a managed relational cloud database service.
B. | It is an open-source framework for the distributed processing and analysis of big datasets in clusters.
C. | It is an on-demand analytics job service that simplifies big data. Instead of deploying, configuring, and tuning hardware, you write queries to transform your data and extract valuable insights.

<details><summary>See Answer</summary>
<p>
  
Choice| Answer | Explanation
------------ | -------------  | --------
 B. | It is an open-source framework for the distributed processing and analysis of big datasets in clusters. | Azure HDInsight is a managed, full-spectrum, open-source analytics service for enterprises. HDInsight is a cloud service that makes it easy, fast, and cost-effective to process massive amounts of data. HDInsight also supports a broad range of scenarios, like extract, transform, and load (ETL); data warehousing; machine learning; and IoT.
  
</p>
</details>


----

# Question 91 (Describe identity, governance, privacy, and compliance features)

For any Single Instance virtual machine using premium SSD or Ultra Disk for all Operating System Disks and Data Disks, what is the SLA guarantee for virtual machine connectivity?

Choice | Answer
------------ | -------------
A. | There is no SLA guarantee
B. | 99.95%
C. | 99.99%
D. | 99.9%

<details><summary>See Answer</summary>
<p>
  
Choice | Answer | Explanation
------------ | -------------  | -------------  
 D. | 99.9% | For any Single Instance Virtual Machine using Premium SSD or Ultra Disk for all Operating System Disks and Data Disks, Azure guarantees you will have Virtual Machine Connectivity of at least 99.9%.
  
  https://azure.microsoft.com/en-us/support/legal/sla/virtual-machines/v1_9/
  
  https://azure.microsoft.com/en-us/support/legal/sla/summary/
  
</p>
</details>


----

# Question 92 (Describe Azure cost management and Service Level Agreements)

You have an Azure subscription that contains the following unused resources:

Name	| Type	 | Configuration
------------ | ------------- | ------
nic0	| Network Interface	| 10.0.0.6
pip1	| Public IP	| Static
lb1	| Load Balancer |	Standard, 5 rules configured
VNet2 |	Virtual Network |	10.1.0.0/16
VM3 |	Virtual Machine	| Stopped (Deallocated)

Based on this information, which of the following unused resources should you remove to lower cost?


<details><summary>See Answer</summary>
<p>
  
Name	| Type	 | Configuration | Explanation
------------ | ------------- | ------------- | -------------
  pip1	| Public IP	| Static | In ARM deployment model, there is no charge for dynamic public IP addresses when the associated virtual machine is “stopped-deallocated”. However, you’re charged for a static public IP address irrespective of the associated resource (unless it is part of the first five static ones in the region). This resource should be removed.
  lb1	| Load Balancer |	Standard, 5 rules configured | The pricing for Standard Load Balancer is based on the number of rules configured (load balancer rules and NAT rules) and data processed.However, there is no hourly charge for the Standard Load Balancer itself when no rules are configured. Since this load balancer contains rules, it should be removed to save money.
  
  

  
</p>
</details>

----

# Question 93 (Describe Azure cost management and Service Level Agreements)

Where can you open a new Azure support request?


Choice | Answer
------------ | -------------
A. | support.microsoft.com
B. | Knowledge Center
C. | Security Center
D. | Azure Portal

<details><summary>See Answer</summary>
<p>
  
Choice| Answer | Explanation
------------ | -------------  | ------------- 
 D. | Azure Portal | A support request can only be opened via the Azure Portal.
  
</p>
</details>

----

# Question 94 (Describe core Azure services)

Azure virtual machines can be moved between which of the following Azure resources?

Choice | Answer
------------ | -------------
A. | Resource Groups
B. | Availibility Zones
C. | Subscriptions
D. | Regions

<details><summary>See Answer</summary>
<p>
  
Choice | Answer | Explanation
------------ | -------------  | ------------- 
A. | Resource Groups | Azure virtual machines can be moved between resource groups with either Azure PowerShell or the Azure portal.
B. | Availibility Zones |   Using Azure Site Recovery, you can migrate Azure VMs to other Availability Zones.
C. | Subscriptions | Azure virtual machines can be moved between subscriptions with either Azure PowerShell or the Azure portal.
D. | Regions |  Using Azure Site Recovery, you can migrate Azure VMs to other regions.
  
 https://docs.microsoft.com/en-us/azure/virtual-machines/windows/move-vm
  
 https://docs.microsoft.com/en-us/azure/site-recovery/azure-to-azure-tutorial-migrate
  

 
</p>
</details>



----

# Question 95 (Describe Azure cost management and Service Level Agreements)

Which of the following Azure support plans offer 24x7 access to Microsoft engineers via telephone and email?


Choice | Answer
------------ | -------------
A. | Basic
B. | Developer
C. | Premier
D. | Standard
E. | Professional Direct

<details><summary>See Answer</summary>
<p>
  
Choice| Answer | Explanation
------------ | -------------  | ------------- 
C. | Premier | The Premier support plan offers 24x7 access to Microsoft Support Engineers via telephone and email.
D. | Standard | The Standard support plan offers 24x7 access to Microsoft Support Engineers via telephone and email.
E. | Professional Direct | The Professional Direct support plan offers 24x7 access to Microsoft Support Engineers via telephone and email.
 
https://azure.microsoft.com/en-us/support/plans/  
  
</p>
</details>

----

# Question 96 (Describe Azure cost management and Service Level Agreements)

You attempt to create several managed disks in your Azure environment.
In the Portal, you receive a message that you must increase your Azure subscription limits.
What should you do to increase the limits?


Choice | Answer
------------ | -------------
A. | Modify an Azure policy
B. | Use Azure PowerShell to create the new managed disks.
C. | Upgrade your support plan.
D. | Create a new support request.

<details><summary>See Answer</summary>
<p>
  
Choice| Answer | Explanation
------------ | -------------  | ---------
 D. | Create a new support request. | If you want to raise the limit or quota above the default limit, open an online customer support request at no charge.
  
</p>
</details>


----

# Question 97 (Describe Azure cost management and Service Level Agreements)

When utilizing at least two Azure virtual machines with at least two availability zones, what is the guaranteed service level agreement that can be expected?

Choice | Answer
------------ | -------------
A. | 99.99%
B. | 99.999%
C. | 99.0%
D. | 99.95%

<details><summary>See Answer</summary>
<p>
  
Choice| Answer | Explanation
------------ | -------------  | ------------- 
 A. | 99.99% | When deploying at least two Azure virtual machines across two or more Availability Zones in the same Azure region, a 99.99% SLA is guaranteed.
  
https://azure.microsoft.com/en-us/support/legal/sla/virtual-machines/v1_9/
  
</p>
</details>

----

# Question 98 (Describe Azure cost management and Service Level Agreements)

Which of the following is the formula used to calculate uptime?

Choice | Answer
------------ | -------------
A. | (Maximum Available Minutes - Downtime) / Maximum Available Minutes X 1440
B. | Maximum Available Minutes / (Maximum Available Minutes - Downtime) X 100
C. | (Maximum Available Minutes / Downtime) X 100
D. | (Maximum Available Minutes - Downtime) / Maximum Available Minutes X 100

<details><summary>See Answer</summary>
<p>
  
Choice| Answer
------------ | -------------  
 D. | (Maximum Available Minutes - Downtime) / Maximum Available Minutes X 100
  
  https://azure.microsoft.com/en-us/support/legal/sla/virtual-machines/v1_9/
  
</p>
</details>

----

# Question 99 (Describe identity, governance, privacy, and compliance features)

What should you use to evaluate whether your company's Azure environment meets regulatory requirements?

Choice | Answer
------------ | -------------
A. | Knowledge Center
B. | Azure Advisor
C. | Azure Security Center
D. | Compliance Manager


<details><summary>See Answer</summary>
<p>
  
Choice| Answer | Explanation
------------ | -------------  | ------------- 
  C. | Azure Security Center | Azure Security Center now has a regulatory compliance dashboard https://azure.microsoft.com/de-de/blog/regulatory-compliance-dashboard-in-azure-security-center-now-available/
  D. | Compliance Manager | Compliance Manager enables you to track, assign, and verify your organization's regulatory compliance activities related to Microsoft Professional Services and Microsoft cloud services, such as Microsoft Office 365, Microsoft Dynamics 365, and Microsoft Azure.

 
  
</p>
</details>

----

# Question 100 (Describe core solutions and management tools on Azure)

Which of the following can be used to limit network connections to Azure virtual machines or subnets?


Choice | Answer
------------ | -------------
A. | Service endpoint
B. | Virtual network gateway
C. | Network security group (NSG)
D. | Route table

<details><summary>See Answer</summary>
<p>
  
Choice| Answer | Explanation 
------------ | -------------  
  C. | Network security group (NSG) | You can filter network traffic to and from resources in a virtual network using network security groups. You can control how Azure routes traffic from subnets. 
  
  
 https://docs.microsoft.com/en-us/azure/virtual-network/virtual-network-vnet-plan-design-arm#security
 
  
</p>
</details>
# Question 101

Which of the following defines performance targets, like uptime, for an Azure product or service?

Choice | Answer
------------ | -------------
A. | Service Level Agreements
B. | Support Plans
C. | Usage Meters

<details><summary>See Answer</summary>
<p>
  
Choice | Answer
------------ | -------------
A. | Service Level Agreements
  
Answer is Service Level Agreement (SLA). The SLA defines performance targets for an Azure product or service  
 
  
</p>
</details>

----

# Question 102

Which of the following is a logical unit of Azure services that links to an Azure account?

Choice | Answer
------------ | -------------
A. | Azure Subscription
B. | Management Group
C. | Resource Group

<details><summary>See Answer</summary>
<p>
  
Choice| Answer
------------ | -------------  
 A. | Azure Subscription
  
Answer is Azure subscription. Azure subscription is a logical unit of Azure services that links to an Azure account.  
</p>
</details>


----

# Question 103

Which Azure support plan is best for business-critical workloads?

Choice | Answer
------------ | -------------
A. | Azure Developer
B. | Azure Professional Direct
C. | Azure Standard

<details><summary>See Answer</summary>
<p>
  
Choice| Answer
------------ | -------------  
B. | Azure Professional Direct
  
  Answer is Azure Professional Direct is the best way to ensure your solutions are running nearly all the time
 
  
</p>
</details>


----

# Question 104

An Azure Reservations offers discounted prices if you?

Choice | Answer
------------ | -------------
A. | Pay in advance.
B. | Provision a certain number of resources.
C. | Use spending limits.

<details><summary>See Answer</summary>
<p>
  
Choice| Answer
------------ | -------------  
  A. | Pay in advance.
  
  Answer is Pay in advance. Azure Reservations offers discounted prices if you pay in advance. To get a discount, you reserve products and resources by paying in advance. You can prepay for one or three year's use of certain Azure resources
 
  
</p>
</details>


----

# Question 105

You have two services with different SLAs. The composite SLA is determined by?

Choice | Answer
------------ | -------------
A. | Adding the SLAs percentages together.
B. | Multiplying the SLAs percentages together.
C. | Taking the lowest SLA percentage.

<details><summary>See Answer</summary>
<p>
  
Choice| Answer
------------ | -------------  
B. | Multiplying the SLAs percentages together.
  
 Answer is Multiply the SLAs together. To determine a composite SLA you multiply the individual SLAs together.
 
  
</p>
</details>


----

# Question 106

Releasing a feature to all Azure customers is called?

Choice | Answer
------------ | -------------
A. | General Availibility
B. | General Preview
C. | Public Preview

<details><summary>See Answer</summary>
<p>
  
Choice| Answer
------------ | -------------  
 A. | General Availibility
  
 Answer is General Availability (GA). GA is a feature released to all Azure customers
  
</p>
</details>


----

# Question 107

Which of the following can be used to estimate cost savings when migrating to Azure?

Choice | Answer
------------ | -------------
A. | Pricing calculator.
B. | Total Cost of Ownership calculator.
C. | Usage meter.

<details><summary>See Answer</summary>
<p>
  
Choice| Answer
------------ | -------------  
 B. | Total Cost of Ownership calculator.
  
  Which of the following can be used to estimate cost savings when migrating to Azure?
  
</p>
</details>


----

# Question 108

Azure Advisor provides recommendations for _________

Choice | Answer
------------ | -------------
A. | Cost only.
B. | High availibility, security, performance, operational excellence, and cost.
C. | High availibility, performance, and cost.

<details><summary>See Answer</summary>
<p>
  
Choice| Answer
------------ | -------------  
 B. | High availibility, security, performance, operational excellence, and cost.
  
  Azure Advisor provides recommendations on many different capabilities for your solutions.
  
</p>
</details>


----

# Question 109

To use Azure datacenters that are made available with power, cooling, and networking capabilities independent from other datacenters in a region, choose a region that supports _________?

Choice | Answer
------------ | -------------
A. | Geography distrubtion
B. | Service-Level Agreements (SLAs)
C. | Availibiliy Zones


<details><summary>See Answer</summary>
<p>
  
Choice | Answer
------------ | -------------  
 C. | Availibiliy Zones
  
  Answer is Availability Zones are datacenters set up to be an isolation boundary from others in the region, with their own power, cooling, and networking. If one zone in a region goes down, other Availability Zones in the region continue to work.
  
</p>
</details>


----

# Question 110

Application availability refers to what?

Choice | Answer
------------ | -------------
A. | The service level agreement of the associated resource.
B. | Application support for an availibility zone.
C. | The overal time that a system is functional and working.

<details><summary>See Answer</summary>
<p>
  
Choice| Answer
------------ | -------------  
 C. | The overal time that a system is functional and working.
  
</p>
</details>


----

# Question 111
Your company plans to migrate all its data and resources to Azure.The company's migration plan states that only Platform as a Service (PaaS) solutions must be used in Azure.You need to deploy an Azure environment that meets the company migration plan.

Solution: You create an Azure App Service and Azure Storage accounts.

Does this meet the goal?

Choice | Answer
------------ | -------------
A. | Yes
B. | No


<details><summary>See Answer</summary>
<p>
  
Choice| Answer
------------ | -------------  
 B. | No
  
  Azure App Service is a PaaS (Platform as a Service) service. However, Azure Storage accounts are an IaaS (Infrastructure as a Service) service. Therefore, this solution does not meet the goal.
  
</p>
</details>

----

# Question 112

Check which statement is true or false.

Statement | Answer
------------ | -------------
You can create a resource group inside of an other resource group | True/False
An Azure virutal machine can be in multiple resource groups | True/False
A resource group can contain resources from multiple Azure regions | True/False


<details><summary>See Answer</summary>
<p>
  
Statement | Answer | Explanation
------------ | -------------  | -------------  
  You can create a resource group inside of an other resource group | False | ..
An Azure virutal machine can be in multiple resource groups | True | Each resource can exist in only one resource group
A resource group can contain resources from multiple Azure regions | True | Resources from multiple different regions can be places in a resource group. The resource group only contains metadata about the resources it contains.
 
  
</p>
</details>


----

# Question 113

Check which statement is true or false.

Statement | Answer
------------ | -------------
 You can use Availibility Zones in Azure to protect Azure virtual machines from a datacenter failure. | True/False
 You can use Availibility Zones in Azure to protect Azure virtual machines form a region failure | True/False
 You can use Availibiliy Zones in Azure to protect managed disk from a datacenter failure | True/False


<details><summary>See Answer</summary>
<p>
  
Statement | Answer
------------ | -------------  
 You can use Availibility Zones in Azure to protect Azure virtual machines from a datacenter failure. | True
 You can use Availibility Zones in Azure to protect Azure virtual machines form a region failure | False
 You can use Availibiliy Zones in Azure to protect managed disk from a datacenter failure | True
  
  Availibilty zones expand the level of control you have to maintain the availability of the applications and data on your VMs. Availability Zones are unique physical locations within an Azure region. Each zone is made up of one or more datacenters equipped with independent power, cooling and networking. To ensure resiliency, there are a minium of three seperate zones in all enabled regions. The physical seperation of Availabilty Zones within a region protects applications and data from datacenter failures.
 
  
</p>
</details>

----

# Question 114

Check which statement is true or false.

Statement | Answer
------------ | -------------
An Azure subscription can have multiple account administrators | True/False
An Azure subscription can be managed by using a Microsoft account only | True/False
An Azure resource group can contain multiple Azure subscriptions | True/False

<details><summary>See Answer</summary>
<p>
  
Statement | Answer | Explanation
------------ | -------------   | -------------  
  An Azure subscription can have multiple account administrators | True | You can assign addiotnal account administratos in the Azure Portal
An Azure subscription can be managed by using a Microsoft account only | False | You need an Azure Active Directory account to manage a subscription, not a Microsoft account. An account is created in the Azure Active Directory when you create the subscription. Further accounts can be created in the Azure Active Directory to manage the subscription.
An Azure resource group can contain multiple Azure subscriptions | False | No. Resource groups are logical containers for Azure resources. However, resource groups do not contain subscriptions. Subscriptions contain resource groups.
 
  
</p>
</details>


----

# Question 115

Check which statement is true or false.

Statement | Answer
------------ | -------------
An Azure subscription can be associated to multiple Azure Active Directory (Azure AD) tenants. | True/False
You can change the Azure Active Directory (Azure AD) tenant to which an Azure subscription is associated | True/False
When an Azure subscription expires, the associated Azure Active Directory (Azure AD) tenant is deleted automatically. | True/False

<details><summary>See Answer</summary>
<p>
  
Statement | Answer | Explanation
------------ | -------------  | -------------  
 An Azure subscription can be associated to multiple Azure Active Directory (Azure AD) tenants. | False | An Azure AD tenant can have multiple subscriptions but an Azure subscription but an Azure subscription can only be associated with one Azure AD tenant
You can change the Azure Active Directory (Azure AD) tenant to which an Azure subscription is associated | True
When an Azure subscription expires, the associated Azure Active Directory (Azure AD) tenant is deleted automatically. | False | If your subscription expires, you lose acces to all the other resources associated with the subscription. However, the Azure AD directory remains in Azure. You can associate and manage the directory using a different Azure subscription.
 
  
</p>
</details>


----

# Question 116 

Chech which statement is true or false.

Statement | Answer
------------ | -------------
A single Microsoft account can use to manage multiple Azure subscriptions. | True/False
Two Azure subscriptions can be merged into a single subscription | True/False
A company can use resources from multiple subscriptions | True/False


<details><summary>See Answer</summary>
<p>
  
Statement | Answer | Explanation
------------ | -------------  | ------------- 
 A single Microsoft account can use to manage multiple Azure subscriptions. | True | You can use the same account to manage multiple subscriptions. You can create an additional subscription to avoid hitting subscription limits, to create seperate environments for security, or to isolate data for compliance reasons.
Two Azure subscriptions can be merged into a single subscription | False | You cannot merge two subscriptions into a single subscription. However you can move some Azure resources from one subscription to another. You can also transfer ownership of a subscription and change the billing type for a subscription.
A company can use resources from multiple subscriptions | True | A company can have multiple subscriptions and store resources in the different subscriptions. However, a resource instance can exist in only one subscription.
  
</p>
</details>

----

# Question 117 (Azure Pricing and Support)

Which of the following statements regarding an Azure Free account are true?

Statement | Answer
------------ | -------------
Several services are always free. | True/False
A Subset of Azure services free for 12 months | True/False
Free tier virtual machines always available for Dev/Test | True/False
$200 USD free credit (170 euro) to explore any Azure service for 30 days. | True/False

<details><summary>See Answer</summary>
<p>
  
Statement | Answer | Explanation
------------ | ------------- | -------------
  Several services are always free. | True | Correct: 25 Azure products are free of charge to use with an Azure free account
A Subset of Azure services free for 12 months | True | Correct: A subset of Azure services is free for 12 months. 
Free tier virtual machines always available for Dev/Test | False | Free tier virtual machines are a feature of a competing cloud service provider (which shall remain nameless).
$200 USD free credit (170 euro) to explore any Azure service for 30 days. | True | $200 USD free credit (170 euro) to explore any Azure service for 30 days.
 
  
</p>
</details>


----

# Question 118 (Azure Pricing and Support)

What tool provides cost information and would help to identify underutilized and idle Azure resources in order to help reduce overall spending?

Choice | Answer
------------ | -------------
A. | Azure Monitor
B. | Azure Advisor
C. | Azure Fundamentals
D. | Application Insights

<details><summary>See Answer</summary>
<p>
  
Choice | Answer | Explanation
------------ | -------------  
 B. | Azure Advisor | Advisor helps you optimize and reduce your overall Azure spending by identifying idle and underutilized resources.
  
  https://docs.microsoft.com/en-us/azure/advisor/advisor-cost-recommendations
  
  
</p>
</details>

----

# Question 119 (Azure Pricing and Support)

You are planning on purchasing Azure AD Premium for your Azure subscription. What is the SLA for this product?

Choice | Answer
------------ | -------------
A. | 99.95%
B. | Azure AD Premium is not covered at a 99.95% SLA
C. | 99.99%
D. | 99.9%


<details><summary>See Answer</summary>
<p>
  
Choice| Answer | Explanation
------------ | -------------  | -------------
 C. | 99.99% |  Per the Azure documentation: We guarantee 99.99% availability of the Azure Active Directory Basic and Premium services. The services are considered available in the following scenarios: Users are able to login to the Azure Active Directory service.
Azure Active Directory successfully emits the authentication and authorization tokens required for users to log in to applications connected to the service.
  
</p>
</details>



----

# Question 120

Which of the following Azure support plans offer Severity "A" and "B" cases to be opened?

Choice | Answer
------------ | -------------
A. | Premier
B. | Basic
C. | Developer
D. | Professional Direct
E. | Standard

<details><summary>See Answer</summary>
<p>
  
Choice | Answer | Explanation
------------ | -------------  | ------------- 
 A. | Premier | This support plan offers cases to be assigned a severity of "A", "B", and "C". The response times are as follows: "A": < 1 hour "B": < 2 hour "C": < 4 business hours 
 D. | Professional Direct | This support plan offers cases to be assigned a severity of "A", "B", and "C". The response times are as follows: "A": < 1 hour "B": < 2 hour "C": < 4 business hours 
  E. | Standard  | This support plan offers cases to be assigned a severity of "A", "B", and "C". The response times are as follows: "A": < 1 hour "B": < 4 hour "C": < 8 business hours                   
  
</p>
</details>

----

# Question 121

Why would you use a Content Delivery Network? Choose 2

Choice | Answer
------------ | -------------
A | A CDN ensures maximum uptimes for an application that is hosted in more than one datacenter.
B | For incoming traffic, to make routing decisions based on additional attributes of an HTTP request, such a URI path or host headers.
C | To better handle instantaneous high loads, such as the start of a product launch event.
D | To ensure requests made from users are securely handled and served.
E | To provide better performance and improved user experience for end users.

<details><summary>See Answer</summary>
<p>
  
Choice| Answer
------------ | -------------  
 C | To better handle instantaneous high loads, such as the start of a product launch event. 
 E | To provide better performance and improved user experience for end users.
 
  
A CDN keeps a recent copy of your web application and can deliver this much faster to users close to an endpoint. CDNs can handle a LOT more data than a typical web server, which makes it ideal to handle traffic spikes as well. CDNs don't generally handle individual traffic routing rules nor security.
  
</p>
</details>


----

# Question 122
Which of the following is a function of an Azure VPN Gateway?
Choice | Answer
------------ | -------------
A. | To make sure the connection from a Virtual Network to the Internet is secure.
B. | To manage the IP addresses for an Azure Subscription and to ensure only secure traffic is allowed.
C. | To handle any suspicious activity trying to access your Azure subscription.
D. | To balance data coming into your Azure services from an external private network.
E. | To send encrypted traffic between an Azure Virtual Network and an on-premises location over the public Internet.


<details><summary>See Answer</summary>
<p>
  
Choice| Answer
------------ | -------------  
 E. | To send encrypted traffic between an Azure Virtual Network and an on-premises location over the public Internet.
  
 A VPN Gateway is an important part of a hybrid Azure infrastructure. It allows encrypted traffic to flow between on-premises services and Azure services.
 
  
</p>
</details>


----

# Question 123

How do resources on Azure use a virtual network?

Choice | Answer
------------ | -------------
A. | Any resource that communicates with the public Internet has to be on a Virtual Network.
B. | Azure virtual network enables Azure resources to securely communicate with each other, the internet, and on-premises networks.
C. | All resources must be connected to a Virtual Network to use the Azure platform.
D. | Resources on a free account don't have to be on a Virtual Network to use Azure.

<details><summary>See Answer</summary>
<p>
  
Choice| Answer
------------ | -------------  
 B. | Azure virtual network enables Azure resources to securely communicate with each other, the internet, and on-premises networks.
  
 Azure virtual network enables Azure resources to securely communicate with each other, the internet, and on-premises networks. Key scenarios that you can accomplish a virtual network include: communication of Azure resources with the internet, communication between Azure resources, communication with on-premises resources, filtering network traffic, routing network traffic, and integration with Azure services. Reference: Why use an Azure Virtual network? 
  
</p>
</details>


----

# Question 124

Which benefits does adding a load balancer provide? Choose 3

Choice | Answer
------------ | -------------
A. | A load balancer ensures that the load is evenly distributed between 2-5 Virtual Machines.
B. | To ensure only healthy servers process requests.
C. | A load balancer can log traffic that passes through it.
D. | When a Virtual disk is running out of space on a Virtual Machine the incoming data can be directed to another Virtual Machine to manage the load.
E. | When there is too much incoming network traffic for a single VM to handle, a load balancer can distribute the load to many VMs.


<details><summary>See Answer</summary>
<p>
  
Choice| Answer
------------ | -------------  
 B. | To ensure only healthy servers process requests.
 C. | A load balancer can log traffic that passes through it. 
 E. | When there is too much incoming network traffic for a single VM to handle, a load balancer can distribute the load to many VMs.
 
A load balancer sits in front of two or more Virtual Machines to manage, and balance, the load to the Virtual Machines. This can be based on amount of incoming traffic or specific properties in the traffic. A load balancer has nothing to do with Virtual disks, and the max number of VMs to manage goes up to 1000. A load balancer ensures only healthy instances receive traffic and will stop sending traffic to any server that does not pass health checks. All ELB types can log traffic that passes through them 
</p>
</details>


----

# Question 125

What is an address space on a Virtual Network?

Choice | Answer
------------ | -------------
A. | An address space is a range of IP addresses that can be assigned to resources attached to the Virtual Network.
B. | A definition of what types of resources can connect to either a private or public network hosted on Azure.
C. | A reserved number of public IP addresses that you can use to connect a Virtual Network to the public Internet.
D. | A portion of the complete address space for a given Azure subscription can be assigned to a Virtual Network.


<details><summary>See Answer</summary>
<p>
  
Choice| Answer
------------ | -------------  
 A. | An address space is a range of IP addresses that can be assigned to resources attached to the Virtual Network.
  
 
An address space on a Virtual Network is a number of IP addresses that are unique only on the specific Virtual Network. These IP addresses are assigned to resources connected to the VNet, which allows the resources to interact and communicate. There is no limit to the number or VNets you can have, nor to the number of address spaces.
  
</p>
</details>


----

# Question 126

In which scenario would you use an Application Gateway?

Choice | Answer
------------ | -------------
A. | For incoming traffic, to make routing decisions based on additional attributes of an HTTP request, such as URI path or host headers.
B. | To manage the IP addresses for an Azure Subscription and to ensure only secure traffic is allowed.
C. | To send encrypted traffic between an Azure Virtual Network and an on-premises location over the public Internet.
D. | To make sure the connection from a Virtual Network to the Internet is secure.
E. | If traffic with specific properties needs to be processed by a particular VM.



<details><summary>See Answer</summary>
<p>
  
Choice| Answer
------------ | -------------  
 A. | For incoming traffic, to make routing decisions based on additional attributes of an HTTP request, such as URI path or host headers.
 E. | If traffic with specific properties needs to be processed by a particular VM.
 
 An application gateway is similar to a load balancer, but can redirect traffic based on attributes in the HTTP request, the request coming in from the internet. You can have a VM handling video, one handling images and so on. Application Gateways do not handle traffic security, nor manage any Virtual Networks.
  
</p>
</details>

----

# Question 127

What is the best scenario for using Azure ExpressRoute?

Choice | Answer
------------ | -------------
A. | Connecting your multi-cloud infrastructure between providers for added speed and security.
B. | ExpressRoute can only be used to and from Azure, and not to other cloud providers.
C. | Connecting your on-premises datacenter with Azure, where the connection needs to be secure and cost-effective.
D. | Connecting your on-premises datacenter with Azure, where the connection needs to be secure and fast.


<details><summary>See Answer</summary>
<p>
  
Choice| Answer
------------ | -------------  
 D. | Connecting your on-premises datacenter with Azure, where the connection needs to be secure and fast.
 
 ExpressRoute data never goes over the public Internet, and you can choose your own connection speed directly to Azure. Just be aware of the price tag… 
  
</p>
</details>

----

# Question 128

Your company plans to move several servers to Azure. The company's compliance policy states that a server named FinServer must be on a seperate network segment. You are evaluating which Azure Services can be used to meet the compliance policy requirements.

Choice | Answer
------------ | -------------
A. | A VPN for FinServer and a virtual network gateway for each other server
B. | A resource group for FinServer and another resource group for all the other servers
C. | A virtual network for FinServer and another virtual network for all the other server
D. | One resource group for all the servers and a resource lock for FinServer

<details><summary>See Answer</summary>
<p>
  
Choice| Answer
------------ | -------------  
 C. | A virtual network for FinServer and another virtual network for all the other server
  
 Azure virtual networks are similar to LANS on your on-premises network. The idea behind an Azure virtual network is that you create a network. based on a single private IP adress space, on which you can place all your Azure virtual machines. The private IP adress spaces available are in the class A (10.0.0.0/8), Class B (172.16.0.0/12), and Class C (192.168.0.0/16) ranges. Best practice: Create network acces controls between subnets. Routing between subnets happens automatically, and you don't need to manually configure routing tables. By default, there are no network acces controls between the subnets that you create on an Azure Virtual network. Detail: Use a network security group to protect against unsolicited traffic into Azure subnets. Network Security Groups are simple stateful packet inspection devices that use the 5-tuple approach (source IP, source port, destination port, and layer 4 protocol) to create allow/deny rules for network traffic. You allow or deny traffic to and from a single IP adress, to and from multiple IP addresses, or to and from entire subnets. When you use network security groups for network acces control between subnets, you can put the resources that belong to the same security zone or role in their own subnets. 
  
</p>
</details>


Az900
------

1. True or false: You need to purchase an Azure account before you can use any Azure resources.

False

True
2. What is meant by cloud computing?

Delivery of computing services over the internet.

Setting up your own datacenter.

Using the internet
3. Which of the following is not a feature of Cloud computing?

Faster innovation

A limited pool of services

Speech recognition and other cognitive services


1. Which of the following choices isn't a cloud computing category?

Networking-as-a-Service (NaaS)

Platform-as-a-Service (PaaS)

Infrastructure-as-a-Service (IaaS)

Software-as-a-Service (SaaS)
2. Which of the following statements is true?

With Operating Expenses (OpEx), you are responsible for purchasing and maintaining your computing resources.

With Operating Expenses (OpEx), you are only responsible for the computing resources that you use.

With Capital Expenses (CapEx), you are only responsible for the computing resources that you use.
3. Which of the following options isn't a type of cloud computing?

Distributed cloud

Hybrid cloud

Private cloud

Public cloud
4. Which of the following choices isn't a benefit of using cloud services?

Scalability

Disaster recovery

High availability

Geographic isolation

1. Which of the following can be used to manage governance across multiple Azure subscriptions?

Azure initiatives

Management groups

Resource groups
2. Which of the following is a logical unit of Azure services that links to an Azure account?

Azure subscription

Management group

Resource group

Public cloud
3. Which of the following features does not apply to resource groups?

Resources can be in only one resource group.

Role-based access control can be applied to the resource group.

Resource groups can be nested.
4. Which of the following statements is a valid statement about an Azure subscription?

Using Azure doesn't require a subscription.

An Azure subscription is a logical unit of Azure services.


1. Which Azure compute resource can be deployed to manage a set of identical virtual machines?

Virtual machine scale sets

Virtual machine availability sets

Virtual machine availability zones
2. Which of the following services should be used when the primary concern is to perform work in response to an event (often via a REST command) that needs a response in a few seconds?

Azure Functions

Azure App Service

Azure Container Instances
3. Your company has a team of remote workers that need to use Windows-based software to develop your company's applications, but your team members are using various operating systems like macOS, Linux, and Windows. Which Azure compute service would help resolve this scenario?

Azure App Service

Azure Virtual Desktop

Azure Container Instances

1. Tailwind Traders wants to create a secure communication tunnel between its branch offices. Which of the following technologies can't be used?

Point-to-site virtual private network

Implicit FTP over SSL

Azure ExpressRoute

Site-to-site virtual private network
2. Tailwind Traders wants to use Azure ExpressRoute to connect its on-premises network to the Microsoft cloud. Which of the following choices isn't an ExpressRoute model that Tailwind Traders can use?

Any-to-any connection

Site-to-site virtual private network

Point-to-point Ethernet connection

CloudExchange colocation
3. Which of the following options can you use to link virtual networks?

Network address translation

Multi-chassis link aggregation

Dynamic Host Configuration Protocol

Virtual network peering
4. Which of the following options isn't a benefit of ExpressRoute?

Redundant connectivity

Consistent network throughput

Encrypted network communication

Access to Microsoft cloud services


1. What is the first step that you would take in order to share an image file as a blob in Azure Storage?

Create an Azure Storage container to store the image.

Create an Azure Storage account.

Upload the image file and create a container.

Use a Shared Access Signature (SAS) token to restrict access to the image.
2. Which Azure Storage option is better for storing data for backup and restore, disaster recovery, and archiving?

Azure Files Storage

Azure Disk Storage

Azure Blob Storage

1. Your development team is interested in writing Graph-based applications that take advantage of the Gremlin API. Which option would be ideal for that scenario?

Azure Cosmos DB

Azure SQL Database

Azure Databricks

Azure Database for PostgreSQL
2. Tailwind Traders uses the LAMP stack for several of its websites. Which option would be ideal for migration?

Azure Cosmos DB

Azure Database for MySQL

Azure Database for PostgreSQL
3. Tailwind Traders has millions of log entries that it wants to analyze. Which option would be ideal for analysis?

Azure Cosmos DB

Azure SQL Database

Azure Database for PostgreSQL

Azure Synapse Analytics

1. A company wants to build a new voting kiosk for sales to governments around the world. Which IoT technologies should the company choose to ensure the highest degree of security?

IoT Hub

IoT Central

Azure Sphere
2. A company wants to quickly manage its individual IoT devices by using a web-based user interface. Which IoT technology should it choose?

IoT Hub

IoT Central

Azure Sphere
3. You want to send messages from the IoT device to the cloud and vice versa. Which IoT technology can send and receive messages?

IoT Hub

IoT Central

Azure Sphere


1. You need to predict future behavior based on previous actions. Which product option should you select as a candidate?

Azure Machine Learning

Azure Bot Service

Azure Cognitive Services
2. You need to create a human-computer interface that uses natural language to answer customer questions. Which product option should you select as a candidate?

Azure Machine Learning

Azure Cognitive Services

Azure Bot Service
3. You need to identify the content of product images to automatically create alt tags for images formatted properly. Which product option is the best candidate?

Azure Machine Learning

Azure Cognitive Services

Azure Bot Service

1. You need to process messages from a queue, parse them by using some existing imperative logic written in Java, and then send them to a third-party API. Which serverless option should you choose?

Azure Functions

Azure Logic Apps
2. You want to orchestrate a workflow by using APIs from several well-known services. Which is the best option for this scenario?

Azure Functions

Azure Logic Apps
3. Your team has limited experience with writing custom code, but it sees tremendous value in automating several important business processes. Which of the following options is your team's best option?

Azure Functions

Azure Logic Apps

1. Which of the following choices would not be used to automate a CI/CD process?

Azure Pipelines

GitHub Actions

Azure Boards
2. Which service could help you manage the VMs that your developers and testers need to ensure that your new app works across various operating systems?

Azure DevTest Labs

Azure Test Labs

Azure Repos
3. Which service lacks features to assign individual developers tasks to work on?

Azure Boards

GitHub

Azure Pipelines

1. As an administrator, you need to retrieve the IP address from a particular VM by using Bash. Which of the following tools should you use?

ARM templates

Azure PowerShell

The Azure portal

The Azure CLI
2. You're a developer who needs to set up your first VM to host a process that runs nightly. Which of the following tools is your best choice?

ARM templates

Azure PowerShell

The Azure portal

The Azure CLI
3. What is the best infrastructure-as-code option for quickly and reliably setting up your entire cloud infrastructure declaratively?

ARM templates

Azure PowerShell

The Azure portal

The Azure CLI

1. You want to be alerted when new recommendations to improve your cloud environment are available. Which service will do this?

Azure Advisor

Azure Monitor

Azure Service Health
2. Which service provides official outage root cause analyses (RCAs) for Azure incidents?

Azure Advisor

Azure Monitor

Azure Service Health
3. Which service is a platform that powers Application Insights, monitoring for VMs, containers, and Kubernetes?

Azure Advisor

Azure Monitor

Azure Service Health

Consider the following scenario.

Tailwind Traders is moving its online payment system from its datacenter to the cloud. The payment system consists of virtual machines (VMs) and SQL Server databases.

Here are a few security requirements that the company identifies as it plans the migration:

It wants to ensure a good security posture across all of its systems, both on Azure and on-premises.
In the datacenter, access to VMs requires a TLS certificate. The company needs a place to safely store and manage its certificates.
Here are some additional requirements that relate to regulatory compliance:

Tailwind Traders must store certain customer data on-premises, in its datacenter.
For certain workloads, the company must be the only customer running VMs on the physical hardware.
The company must only run approved business applications on each VM.
See the following diagram that shows the proposed architecture.

A diagram showing the proposed architecture. Virtual machines run both on Azure and in the datacenter.

On Azure, Tailwind Traders will use both standard VMs and VMs that run on dedicated physical hardware. In the datacenter, the company will run VMs that can connect to databases within its internal network.

Choose the best response for each question. Then select Check your answers.

Check your knowledge
1. How can Tailwind Traders enforce having only certain applications run on its VMs?

Connect your VMs to Azure Sentinel.

Create an application control rule in Azure Security Center.

Periodically run a script that lists the running processes on each VM. The IT manager can then shut down any applications that shouldn't be running.
2. What's the easiest way for Tailwind Traders to combine security data from all of its monitoring tools into a single report that it can take action on?

Collect security data in Azure Sentinel.

Build a custom tool that collects security data, and displays a report through a web application.

Look through each security log daily and email a summary to your team.
3. Which is the best way for Tailwind Traders to safely store its certificates so that they're accessible to cloud VMs?

Place the certificates on a network share.

Store them on a VM that's protected by a password.

Store the certificates in Azure Key Vault.
4. How can Tailwind Traders ensure that certain VM workloads are physically isolated from workloads being run by other Azure customers?

Configure the network to ensure that VMs on the same physical host are isolated.

This is not possible. These workloads need to be run on-premises.

Run the VMs on Azure Dedicated Host.


Consider the following scenario. Then choose the best response for each question that follows and select Check your answers.

Tailwind Traders is moving its online payment system to Azure. The processing of online orders begins through a website, which Tailwind Traders manages through Azure App Service. (App Service is a way to host web applications on Azure.)

The web application that runs the website passes order information to virtual machines (VMs), which further process each order. These VMs exist on an Azure virtual network, but they need to access the internet to retrieve software packages and system updates.

Here's a diagram that shows the basic architecture of the company's payment system:

An architecture diagram that shows network traffic flowing into Azure. Azure App Service receives passes public network traffic to virtual machines running on a virtual network.

The security team wants to ensure that only valid network traffic reaches the company's Azure resources. As an extra layer of defense, the team also wants to ensure that the VMs can reach only trusted hosts on specific ports.

Check your knowledge
1. An attacker can bring down your website by sending a large volume of network traffic to your servers. Which Azure service can help Tailwind Traders protect its App Service instance from this kind of attack?

Azure Firewall

Network security groups

Azure DDoS Protection
2. What's the best way for Tailwind Traders to limit all outbound traffic from VMs to known hosts?

Configure Azure DDoS Protection to limit network access to trusted ports and hosts.

Create application rules in Azure Firewall.

Ensure that all running applications communicate with only trusted ports and hosts.
3. How can Tailwind Traders most easily implement a deny by default policy so that VMs can't connect to each other?

Allocate each VM on its own virtual network.

Create a network security group rule that prevents access from another VM on the same network.

Configure Azure DDoS Protection to limit network access within the virtual network.

Consider the following scenario. Then choose the best response for each question that follows and select Check your answers.

At Tailwind Traders, recall that retail employees are issued tablet devices from which they can track orders and plan their work schedules.

Tailwind Traders also allows delivery drivers to use their own mobile devices to access scheduling and logistics applications.

A stolen password might allow unauthorized access to company and customer data. Tailwind Traders wants to extend its investments in Active Directory to secure all of its applications, when accessed both from the intranet and from public networks.

The company is looking into how Azure Active Directory (Azure AD), single sign-on (SSO), multifactor authentication, and Conditional Access can help it achieve those goals.

Check your knowledge
1. How can the IT department ensure that employees at the company's retail stores can access company applications only from approved tablet devices?

SSO

Conditional Access

Multifactor authentication
2. How can the IT department use biometric properties, such as facial recognition, to enable delivery drivers to prove their identities?

SSO

Conditional Access

Multifactor authentication
3. How can the IT department reduce the number of times users must authenticate to access multiple applications?

SSO

Conditional Access

Multifactor authentication

Consider the following scenario.

Tailwind Traders has created environments for development and testing for its e-commerce system.

Here's a diagram that shows the basic compute, database, and networking components found in each environment.

A diagram of the development and test environments. Each environment contains virtual machines, a database, and a virtual network. The development environment includes three virtual machines. The test environment contains six virtual machines.

These environments provide a way for the team to build and test new application features. If you've gone through the Plan and manage your Azure costs module, then you've already seen this layout.

Although the development and test teams report to different departments, both environments exist under the same Azure subscription.

The IT manager wants to implement governance controls to help ensure that only authorized users can access these systems. Having these controls in place will also help them track and manage operating costs.

Choose the best response for each question. Then select Check your answers.

Check your knowledge
1. How can Tailwind Traders allow some users to control the virtual machines in each environment but prevent them from modifying networking and other resources in the same resource group or Azure subscription?

Create a role assignment through Azure role-based access control (Azure RBAC).

Create a policy in Azure Policy that audits resource usage.

Split the environment into separate resource groups.
2. Which is the best way for Tailwind Traders to ensure that the team deploys only cost-effective virtual machine SKU sizes?

Create a policy in Azure Policy that specifies the allowed SKU sizes.

Periodically inspect the deployment manually to see which SKU sizes are used.

Create an Azure RBAC role that defines the allowed virtual machine SKU sizes.
3. Which is likely the best way for Tailwind Traders to identify which billing department each Azure resource belongs to?

Track resource usage in a spreadsheet.

Split the deployment into separate Azure subscriptions, where each subscription belongs to its own billing department.

Apply a tag to each resource that includes the associated billing department.

Consider the following scenario.

At Tailwind Traders, the legal and IT departments want to better understand how Microsoft handles personal data. They also want to better understand how Azure services can help them meet their compliance goals.

Their needs go beyond just Azure. For example, applications in their retail stores use Cortana to help store employees quickly locate items.

Choose the best response for each question. Then select Check your answers.

Check your knowledge
1. Where can the team access details about the personal data Microsoft processes and how the company processes it, including for Cortana?

Microsoft Privacy Statement

The Azure compliance documentation

Microsoft compliance offerings
2. Where can the legal team access information around how the Microsoft cloud helps them secure sensitive data and comply with applicable laws and regulations?

Microsoft Privacy Statement

Trust Center

Online Services Terms
3. Where can the IT department find reference blueprints that it can apply directly to its Azure subscriptions?

Online Services Terms

Azure compliance documentation

Microsoft Privacy Statement

Consider the following scenario, then choose the best response for each question that follows, and select Check your answers.

Before they migrate their existing e-commerce system from their datacenter to production environments on Azure, the Tailwind Traders team wants to first set up environments for development and testing.

Here's a diagram that shows the basic compute, database, and networking components found in each environment:

A diagram of the development and test environments. Each environment contains virtual machines, a database, and a virtual network. The development environment includes three virtual machines. The test environment contains six virtual machines.

An e-commerce system might require a website, the products database, a payment system, and so on. Because developers can't always run the entire service from their local development environment, the Dev environment is the first place where everything the app needs comes together.

After the development team verifies changes to the Dev environment, they promote changes to the Test environment. The Test environment is where the testing team verifies new app features and also verifies that no regressions, or breaks to existing features, happen as new features are added.

The team will map each component in their existing infrastructure to the appropriate Azure service.

Check your knowledge
1. Which is the best first step the team should take to compare the cost of running these environments on Azure versus in their datacenter?

They're just test environments. Spin them up and check the bill at the end of the month.

Assume that running in the cloud costs about the same as running in the datacenter.

Run the Total Cost of Ownership Calculator.
2. What's the best way to ensure that the development team doesn't provision too many virtual machines at the same time?

Do nothing. Let the development team use what they need.

Apply spending limits to the development team's Azure subscription.

Verbally give the development lead a budget and hold them accountable for overages.
3. Which is the most efficient way for the testing team to save costs on virtual machines on weekends, when testers are not at work?

Delete the virtual machines before the weekend and create a new set the following week.

Deallocate virtual machines when they're not in use.

Just let everything run. Azure bills you only for the CPU time that you use.
4. Resources in the Dev and Test environments are each paid for by different departments. What's the best way to categorize costs by department?

Apply a tag to each virtual machine that identifies the appropriate billing department.

Split the cost evenly between departments.

Keep a spreadsheet that lists each team's resources.

Consider the following scenario. Then choose the best response for each question that follows, and select Check your answers.

Recall that the Tailwind Traders' Special Orders application includes two virtual machines, Azure Load Balancer, and Azure SQL Database:

A diagram showing two virtual machines connected to Azure Load Balancer and Azure SQL Database.

Here's the service-level agreement (SLA) for each service:

Service	SLA
Azure Virtual Machines	99.9 percent
Azure SQL Database	99.99 percent
Azure Load Balancer	99.99 percent
To compute the composite SLA for a set of services, you multiply the SLA of each individual service. Recall that the existing composite SLA is:

99.9
%
×
99.9
%
×
99.99
%
×
99.99
%
=
99.78
%
The team wants to add a mapping feature so that it can calculate routes between nearby suppliers and each retail store. For that, the team will use Azure Maps.

The team also needs more processing power to keep up with demand. For that, it will add a third virtual machine to the pool.

Here's a diagram that shows their proposed plan:

A diagram showing three virtual machines connected to Azure Load Balancer, Azure SQL Database, and Azure Maps.

Recall that you can access SLAs from Service Level Agreements.

Tailwind Traders is also considering using an augmented reality service in the Special Orders app to help customers visualize their customizations. This Azure service is currently in the public preview phase.

Check your knowledge
1. What's the SLA for Azure Maps in terms of guaranteed uptime?

99 percent

99.9 percent

99.99 percent
2. What's the new composite SLA? Remember, the new SLA includes a third virtual machine and Azure Maps.

99.58 percent

99.78 percent

99.99 percent
3. Adding a third virtual machine reduces the composite SLA. How can Tailwind Traders offset this reduction?

Increase the size of each virtual machine.

Deploy extra instances of the same virtual machines across the different availability zones in the same Azure region.

Do nothing. Using Azure Load Balancer increases the SLA for virtual machines.
4. What approach might the company take in adding the augmented reality (AR) preview service to its architecture?

The Special Orders app is already in production. The company shouldn't look into the AR service until the service reaches general availability (GA).

The Special Orders app is mainly for use by retail employees. The company can integrate the AR service now because potential downtime or failures aren't an important factor.

The development team can create a prototype version of the app that includes the AR service that it tests out with select retail employees.

