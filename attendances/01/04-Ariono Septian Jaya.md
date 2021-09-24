## Cloud Computing
Cloud computing is the on-demand access to computing resources hosted 
in remote data centers managed by cloud services through the Internet-applications,
servers (physical servers and virtual servers), data storage, development tools, 
network functions, etc. providers (or CSP) . CSP provides these resources on a monthly 
subscription fee or charges them based on usage.

Compared with traditional local IT, depending on the cloud service you choose, 
cloud computing helps to do the following:
Reduce IT costs: Cloud allows you to share some or most of the cost and work of purchasing,
installing, configuring, and managing your own local infrastructure.
Improve agility and time to value: With the cloud, your organization can 
start using enterprise applications in minutes, instead of waiting weeks or months 
for IT to respond to requests, purchase and configure supporting hardware, and install software.
The cloud also allows you to authorize certain users (especially developers and data scientists)
to help them use the software and supporting infrastructure for themselves.

Scaling more easily and cost-effectively: 
Cloud provides flexibility-you don't need to buy excess capacity that is idle during slow periods, 
you can expand and shrink capacity based on peaks and valleys of traffic. You can also use your 
cloud provider's global network to spread your application to locations closer to users around 
the world.

## CLOUD COMPUTING SERVICES :
1.IaaS (Infrastructure-as-a-Service), PaaS (Platform-as-a-Service) , and SaaS (Software-as-a-Service)
are the three most common models of cloud services, and it’s not uncommon for an organization to use 
all three. However, there is often confusion among the three and what’s included with each:

a.SaaS (Software-as-a-Service)
SaaS (also known as cloud-based software or cloud application) is application software hosted in the cloud, which you can access and use through a web browser, 
a dedicated desktop client, or an API integrated with a desktop or mobile operating system . In most cases, SaaS users pay monthly or annual fees; some may provide 
"pay as you go" pricing based on your actual usage.
In addition to the cost savings, time to value, and scalability advantages of the cloud, SaaS also provides the following features:
-Automatic upgrades: With SaaS, you can take advantage of new features as soon as the provider adds them, without the need to coordinate internal deployment upgrades.
-Protection from data loss: Because your application data is in the cloud, using the application, if your device crashes or is damaged, you will not lose data.

SaaS is the primary delivery model for most commercial software today—there are hundreds of thousands of SaaS solutions available, from the most focused industry 
and departmental applications, to powerful enterprise software database and AI (artificial intelligence) software.

b.PaaS (Platform-as-a-Service)
PaaS provides software developers with on-demand platform—hardware, complete software stack, infrastructure, and even development tools—for running, 
developing, and managing applications without the cost, complexity, and inflexibility of maintaining that platform on-premises.
With PaaS, the cloud provider hosts everything—servers, networks, storage, operating system software, middleware, databases—at their data center. 
Developers simply pick from a menu to ‘spin up’ servers and environments they need to run, build, test, deploy, maintain, update, and scale applications.
Today, PaaS is often built around containers, a virtualized compute model one step removed from virtual servers. Containers virtualize the operating system, 
enabling developers to package the application with only the operating system services it needs to run on any platform, without modification and without need for middleware.
Red Hat OpenShift is a popular PaaS built around Docker containers and Kubernetes, an open source container orchestration solution that automates deployment, 
scaling, load balancing, and more for container-based applications.

c.IaaS (Infrastructure-as-a-Service)
IaaS provides on-demand access to fundamental computing resources–physical and virtual servers, networking, and storage—over the internet on a pay-as-you-go basis. 
IaaS enables end users to scale and shrink resources on an as-needed basis, reducing the need for high, up-front capital expenditures or unnecessary on-premises or ‘owned’ 
infrastructure and for overbuying resources to accommodate periodic spikes in usage.  
In contrast to SaaS and PaaS (and even newer PaaS computing models such as containers and serverless), IaaS provides the users with the lowest-level control of computing 
resources in the cloud.
IaaS was the most popular cloud computing model when it emerged in the early 2010s. While it remains the cloud model for many types of workloads, use of SaaS and PaaS is 
growing at a much faster rate.

d.Serverless computing 
Serverless computing (also called simply serverless) is a cloud computing model that offloads all the backend infrastructure management tasks–provisioning, 
scaling, scheduling, patching—to the cloud provider, freeing developers to focus all their time and effort on the code and business logic specific to their applications.
What's more, serverless runs application code on a per-request basis only and scales the supporting infrastructure up and down automatically in response to the number of requests. 
With serverless, customers pay only for the resources being used when the application is running—they never pay for idle capacity. 
FaaS, or Function-as-a-Service, is often confused with serverless computing when, in fact, it's a subset of serverless. FaaS allows developers to execute portions of 
application code (called functions) in response to specific events. Everything besides the code—physical hardware, virtual machine operating system, and web server software 
management—is provisioned automatically by the cloud service provider in real-time as the code executes and is spun back down once the execution completes. Billing starts when execution 
starts and stops when execution stops.

## Types of cloud computing
Public cloud
Public cloud is a type of cloud computing in which a cloud service provider makes computing resources—anything from SaaS applications, to individual virtual machines (VMs), 
to bare metal computing hardware, to complete enterprise-grade infrastructures and development platforms—available to users over the public internet. These resources might be 
accessible for free, or access might be sold according to subscription-based or pay-per-usage pricing models.
The public cloud provider owns, manages, and assumes all responsibility for the data centers, hardware, and infrastructure on which its customers’ workloads run, and it typically 
provides high-bandwidth network connectivity to ensure high performance and rapid access to applications and data. 
Public cloud is a multi-tenant environment—the cloud provider's data center infrastructure is shared by all public cloud customers. In the leading public clouds—Amazon Web Services (AWS), 
Google Cloud, IBM Cloud, Microsoft Azure, and Oracle Cloud—those customers can number in the millions.
The global market for public cloud computing has grown rapidly over the past few years, and analysts forecast that this trend will continue; industry analyst Gartner predicts that 
worldwide public cloud revenues will exceed USD 330 billion by the end of 2022 (link resides outside IBM).
Many enterprises are moving portions of their computing infrastructure to the public cloud because public cloud services are elastic and readily scalable, flexibly adjusting to meet 
changing workload demands. Others are attracted by the promise of greater efficiency and fewer wasted resources since customers pay only for what they use. Still others seek to reduce 
spending on hardware and on-premises infrastructures.


Private cloud
Private cloud is a cloud environment in which all cloud infrastructure and computing resources are dedicated to, and accessible by, one customer only. Private cloud 
combines many of the benefits of cloud computing—including elasticity, scalability, and ease of service delivery—with the access control, security, and resource customization 
of on-premises infrastructure.
A private cloud is typically hosted on-premises in the customer's data center. But a private cloud can also be hosted on an independent cloud provider’s infrastructure or built 
on rented infrastructure housed in an offsite data center.
Many companies choose private cloud over public cloud because private cloud is an easier way (or the only way) to meet their regulatory compliance requirements. Others choose private 
cloud because their workloads deal with confidential documents, intellectual property, personally identifiable information (PII), medical records, financial data, or other sensitive data.
By building private cloud architecture according to cloud native principles, an organization gives itself the flexibility to easily move workloads to public cloud or run them within a 
hybrid cloud (see below) environment whenever they’re ready.

## Cloud Security
Traditionally, security concerns have been the primary obstacle for organizations considering cloud services, particularly public cloud services. In response to demand, 
however, the security offered by cloud service providers is steadily outstripping on-premises security solutions.
According to security software provider McAfee, today, 52% of companies experience better security in the cloud than on-premises (link resides outside IBM). And Gartner has 
predicted that by this year (2020), infrastructure as a service (IaaS) cloud workloads will experience 60% fewer security incidents than those in traditional data centers (PDF, 2.3 MB) 
(link resides outside IBM).
Nevertheless, maintaining cloud security demands different procedures and employee skillsets than in legacy IT environments. Some cloud security best practices include the following:
Shared responsibility for security: Generally, the cloud provider is responsible for securing cloud infrastructure and the customer is responsible for protecting its data within the 
cloud—but it's also important to clearly define data ownership between private and public third parties.
Data encryption: Data should be encrypted while at rest, in transit, and in use. Customers need to maintain full control over security keys and hardware security module.
User identity and access management: Customer and IT teams need full understanding of and visibility into network, device, application, and data access.
Collaborative management: Proper communication and clear, understandable processes between IT, operations, and security teams will ensure seamless cloud integrations that are secure and 
sustainable.
Security and compliance monitoring: This begins with understanding all regulatory compliance standards applicable to your industry and setting up active monitoring of all connected systems
and cloud-based services to maintain visibility of all data exchanges between public, private, and hybrid cloud environments.

## Advantages of using Cloud Computing :
a.Reducing the cost of purchasing hardware, with cloud computing, the need for hardware can be reduced
b.Performance can be increased as needed, the flexibility of cloud computing, one of which specifications can be increased more easily
c.The software used is mostly open-source and has been used on various platforms
d.Easy and fast software upgrade
e.Virtually unlimited storage capacity
f.Data reliability, namely minimizing data loss, because there are many systems that back up data
g.It's easy to work with more than one individual
h.Access to cloud computing is very easy and can be done through any platform that supports it.

## Disadvantage of using Cloud Computing :
a.Does not work well when network speed is low
b.Available features may be limited
c.Requires an internet connection that is always connected
