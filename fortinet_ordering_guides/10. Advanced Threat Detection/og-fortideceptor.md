# og-fortideceptor

Ordering Guide
FortiDeceptor
Available in
Appliance Virtual Fortinet Cloud
Hosted
FortiDeceptor proactively detects attackers by deploying realistic decoys, deception tokens,
and attack lures throughout the environment. Rather than waiting for malicious activity to reach
production assets, FortiDeceptor exposes attackers early in the attack lifecycle, delivering high-
fidelity alerts and detailed forensic evidence.
Key capabilities:
• Early attacker detection using deception
• Automated asset discovery and decoy placement
• High-fidelity alerts with IOC and TTP analysis
• Flexible deployment across cloud and on-premises
• Security Fabric integration for automated response
Start here:
Follow these three steps to define the FortiDeceptor deployment.
1. Choose where it runs 2. Define what needs 3. Size the deployment
protection
Select the deployment model Identify the environments Determine the required
based on the customer’s and locations that require capacity based on:
infrastructure and operational deception: • Number of protected
requirements: • Data centers and campus VLANs
• FortiDeceptor DaaS networks • Number of sites or
• Virtual Appliance • Branch and remote offices branches
• Hardware Appliance • OT and industrial • Required deception
• Edge Appliance environments coverage
• Rugged Appliance • Cloud and virtual • Centralized management
environments requirements
• Isolated or critical network
segments

FortiDeceptor Ordering Guide
At-a-Glance Decision Guide
Use the customer’s requirements and deployment preferences below to quickly identify the appropriate FortiDeceptor
deployment model.
IF THE CUSTOMER SAYS… RECOMMEND
"I want the easiest deployment." FortiDeceptor DaaS
"I need an on-premises deployment." FDC-1000G or FDC-VM
"I need to protect branch offices or remote sites." FDC-100G Edge managed by a Central Manager
"We already have VMware or a private cloud." FDC-VM
"I have multiple sites that need centralized management." Central Manager with distributed FortiDeceptor appliances
"I need deception for OT, IoT, or critical infrastructure." Deploy SCADA, IoT, and Industrial Decoys
"I need to protect hundreds of network segments." Scale using additional VLAN subscriptions and multiple appliances
"I'm not sure how to size the deployment." Start with the number of VLANs and sites, then expand as needed
Once the deployment approach is identified, use the steps below to select the appropriate platform and size the deployment.
Step 1 – Select Deployment Model
Start by identifying where it should run based on customer infrastructure, compliance, and operational preferences.
OPTION WHEN TO CHOOSE KEY BENEFIT
DaaS Fastest deployment Fully managed, no infrastructure
Virtual Appliance Customer-managed virtualization Flexible deployment
Hardware Appliance Enterprise on-premises Maximum scale and control
Edge Appliance Branch offices and remote sites Extend deception to the edge
Rugged Appliance Industrial and OT environments Ruggedized for harsh environments
Step 2 – Size the Deployment
Finally, align the solution to the customer’s scale, performance needs, and SOC maturity.
ENVIRONMENT RECOMMENDATION
Small branch office / Lab FDC-100G with DaaS or FDC Manager
Single data center FDC-1000G or FDC-VM
Enterprise (multiple sites) FDC-1000G or FDC-VMS with Central Manager and FDC-100G or FDC-VME at each site.
Key Ordering Considerations
Use these factors to validate the deployment before finalizing the order.
CONSIDERATION WHAT TO DETERMINE
Number of sites How many branch, remote, or distributed locations require deception coverage?
Number of VLANs How many network segments require protection and monitoring?
Deployment model DaaS, VM, hardware appliance, edge appliance, or rugged appliance?
Central management Is centralized management required across multiple FortiDeceptor instances?
Environment Small office, enterprise, OT/IoT, data center, or other specialized environment?
Ordering tip: For distributed deployments, size each site independently based on its VLAN and deception requirements, then
add a Central Manager license if centralized administration is required.
2


**Table 2.1**

| IF THE CUSTOMER SAYS… | RECOMMEND |
| --- | --- |


**Table 2.2**

| OPTION | WHEN TO CHOOSE | KEY BENEFIT |
| --- | --- | --- |


**Table 2.3**

| ENVIRONMENT | RECOMMENDATION |
| --- | --- |


**Table 2.4**

| CONSIDERATION | WHAT TO DETERMINE |
| --- | --- |


**Table 2.5**

|  |  |  |
| --- | --- | --- |
|  |  |  |
|  |  |  |

FortiDeceptor Ordering Guide
DaaS Offering
DaaS at a Glance
FortiDeceptor DaaS (Deception-as-a-Service) delivers cloud-hosted deception capabilities without requiring customers to
deploy or maintain deception infrastructure. Fortinet operates and maintains the backend platform, while customers deploy
deception across their environments using centralized management and optional Edge Devices.
Key Benefits
CAPABILITY DESCRIPTION
Fully Managed Service No on-premises deception infrastructure to deploy or maintain. Only lightweight Edge devices are deployed at customer locations.
Rapid Deployment Protect new environments in minutes with cloud-hosted deception services.
Scalable Easily expand coverage by adding Edge Devices or protected networks.
How to Order DaaS
Ordering FortiDeceptor DaaS is straightforward. Select the appropriate DaaS subscription based on the required deployment,
then add Edge Devices where deception protection must be extended to remote sites or network segments.
Step 1 – Select a DaaS Subscription
Choose the FortiDeceptor DaaS subscription that matches the required deployment size and service tier.
ORDER INCLUDES
DaaS Subscription Cloud-hosted deception platform, centralized management, platform maintenance, FortiGuard services, and premium support.
Step 2 – Determine Remote Coverage
If deception services need to protect branch offices, remote locations, or isolated network segments, add FortiDeceptor Edge
Devices.
REQUIREMENT RECOMMENDATION
Single or multiple locations For single or multiple branches of protected network segments, add one Edge Device per site.
Hybrid deployment Combine DaaS with on-premises appliances and Edge Devices.
Step 3 – Add Required Subscriptions
Each deployed Edge Device requires the corresponding Deception Threat Intelligence Subscription to receive platform updates,
deception content, FortiGuard services, and FortiCare support.
Ordering Summary
Use this section when the customer wants a virtual or physical FortiDeceptor deployment under their control.
VM/HW APPLIANCE DECEPTOR EDGE VM DECEPTOR EDGE 100G
Base Unit FC-10-DCVME-248-02-DD FDC-100G
Protected VLANs via DaaS FC1-10-DCDAS-496-02-DD
FortiCare Premium Subscription (included in the base unit) FC-10-DC1HG-247-02-DD
DaaS requires a minimum of two protected VLANs.
3


**Table 3.1**

| CAPABILITY | DESCRIPTION |
| --- | --- |


**Table 3.2**

| ORDER | INCLUDES |
| --- | --- |


**Table 3.3**

| REQUIREMENT | RECOMMENDATION |
| --- | --- |


**Table 3.4**

| VM/HW APPLIANCE | DECEPTOR EDGE VM | DECEPTOR EDGE 100G |
| --- | --- | --- |


**Table 3.5**

|  |  |  |
| --- | --- | --- |
|  |  |  |
|  |  |  |

FortiDeceptor Ordering Guide
On-premise Deployment
On-premises FortiDeceptor at a Glance
FortiDeceptor On-premises provides complete control over your deception environment by deploying deception services within
your own infrastructure. It is ideal for organizations requiring local data residency, air-gapped deployments, or full administrative
control while protecting data centers, campuses, and critical networks.
Key Benefits
CAPABILITY DESCRIPTION
Complete Control Deploy and manage deception infrastructure entirely within your own environment.
High Performance Local deployment provides low-latency deception services for enterprise and critical networks.
Flexible Deployment Protect data centers, campus networks, cloud environments, and OT networks with centralized management.
How to Order On-premises FortiDeceptor
Ordering an on-premises deployment begins with selecting the appropriate appliance, followed by centralized management and
the required subscriptions.
Step 1 – Select the Deployment Appliance
Choose the FortiDeceptor appliance based on the deployment size and required deception capacity.
ORDER PURPOSE
FortiDeceptor Appliance Hosts decoys and deception services.
Step 2 – Add Centralized Management
Deploy FortiDeceptor Central Manager to centrally manage appliances, policies, incidents, reporting, and distributed
deployments.
REQUIREMENT RECOMMENDATION
Single appliance Central Manager recommended
Multiple appliances or sites Central Manager required
Step 3 – Extend Protection (Optional)
Add FortiDeceptor Edge Devices to extend deception into branch offices, remote locations, or isolated network segments
without deploying additional full appliances.
REQUIREMENT RECOMMENDATION
Headquarters only No Edge Device required
Branch or remote offices Add one Edge Device per protected location or network segment
Step 4 – Add Required Subscriptions
Each appliance and Edge Device requires a Deception Threat Intelligence Subscription for FortiGuard services, deception
content updates, FortiCare support, and ongoing enhancements.
4


**Table 4.1**

| CAPABILITY | DESCRIPTION |
| --- | --- |


**Table 4.2**

| ORDER | PURPOSE |
| --- | --- |


**Table 4.3**

| REQUIREMENT | RECOMMENDATION |
| --- | --- |


**Table 4.4**

| REQUIREMENT | RECOMMENDATION |
| --- | --- |


**Table 4.5**

|  |  |  |
| --- | --- | --- |
|  |  |  |
|  |  |  |

FortiDeceptor Ordering Guide
Ordering Summary
Use this section when the customer wants a full on-premises deployment with a single platform.
CRITERIA FORTIDECEPTOR-VMS FORTIDECEPTOR-RUGGED-100G FORTIDECEPTOR-1000G
Type VM Rugged HW
Base Unit FC1-10-DCVMS-496-02-DD FDR-100G FDC-1000G
Decoy VMs 20 8 30
VLANs 2-256 2-128 2-256
FortiGuard Subscription FC1-10-DR1HG-495-02-DD FC1-10-DC1KG-495-02-DD
(included in the base unit)
FortiCare Premium Subscription FC-10-DR1HG-247-02-DD FC-10-DC1KG-247-02-DD
MICROSOFT LICENSES
Windows 10 LIC-FDC-WIN
ADDON SUBSCRIPTIONS
Central Management FC1-10-FDCCM-497-02-DD
Full Deployment
Use this section when the customer wants a full on-premise deployment with Central Management and Edge Devices.
CRITERIA EDGE DEVICES CENTRAL MANAGEMENT + WORKER
VM/HW Appliance VM Edge 100G Edge 100H Edge VMS 100G Rugged 1000G
Base Unit FDC-100G FDE-100H FDR-100G FDC-1000G
Decoy VMs N/A N/A N/A 20 8 30
VLANs 2-128 2-128 2-128 2-256 2-48 2-256
FC1-10-DR1HG-495- FC1-10-DC1KG-495-
VLAN and FortiGuard Subscription N/A N/A
FC-10-DE1HH-1405- FC1-10-DCVMS-496- 02-DD 02-DD
FC-10-DCVME-248- FC-10-DC1HG-247- 02-DD 02-DD FC-10-DR1HG-247- FC-10-DC1KG-247-
FortiCare Premium Subscription
02-DD 02-DD 02-DD 02-DD
MICROSOFT LICENSES
Windows 10 LIC-FDC-WIN
ADDON SUBSCRIPTIONS
Central Management FC1-10-FDCCM-497-02-DD
5


**Table 5.1**

| CRITERIA | FORTIDECEPTOR-VMS | FORTIDECEPTOR-RUGGED-100G | FORTIDECEPTOR-1000G |
| --- | --- | --- | --- |


**Table 5.2**

| CRITERIA | EDGE DEVICES | CENTRAL MANAGEMENT + WORKER |
| --- | --- | --- |


**Table 5.3**

|  |  |  |
| --- | --- | --- |
|  |  |  |
|  |  |  |

FortiDeceptor Ordering Guide
Deployment Examples
1. Small office with cloud decoys
Customer Requirements: Five branch sites managed in the cloud. Each site has two VLANs.
Option A: with VM deployed on each branch site
ENTRIES SKU NOTES
5 FC-10-DCVME-248-02-DD 5 Branches with VM Edge Platform
2 VLANs per branch.
10 FC1-10-DCDAS-496-02-DD
Managed by Fortinet-hosted Central Management Platform
Option B: with 100G Edge Devices
ENTRIES SKU NOTES
5 FDC-100G A Deception Edge Platform per branch
5 FC-10-DC1HG-247-02-DD FortiCare Premium per Edge platform
2 VLANs per branch.
10 FC1-10-DCDAS-496-02-DD
Managed by Fortinet-hosted Central Management Platform
2. Small Office with on-premise decoys
Customer Requirements: Single office with fewer than 20 VLANs. All deception services are hosted on-premises.
ENTRIES SKU NOTES
1 FDC-1000G Central FortiDeceptor appliance hosting decoys and deception services
1 FC1-10-DC1KG-495-02-DD Deception Threat Intelligence Subscription for the FDC-1000G
1 FC-10-DC1KG-247-02-DD FortiCare Premium Subscription for the FDC-1000G
3. Enterprise with Branch Offices
Customer Requirements: Headquarters with centralized deception services protecting 20 branch offices. Branches do not
require local deception infrastructure.
Option A Using hardware-based:
ENTRIES SKU NOTES
1 FDC-1000G Central FortiDeceptor appliance hosting deception services
1 FC1-10-FDCCM-497-02-DD Central Manager license for centralized management
1 FC1-10-DC1KG-495-02-DD Deception Threat Intelligence Subscription for the FDC-1000G
1 FC-10-DC1KG-247-02-DD FortiCare Premium Subscription for the FDC-1000G
20 FDE-100H One 100H Edge Device deployed at each branch office
20 FC-10-DE1HH-1405-02-DD Deception Threat Intelligence Subscription for the 20 FDE-100H Edge Devices
Option B: Using VM-based:
ENTRIES SKU NOTES
1 FC1-10-DCVMS-496-02-DD Central FortiDeceptor appliance hosting deception services
1 FC1-10-FDCCM-497-02-DD Central Manager license for centralized management
20 FC1-10-DCVME-248-02-DD FortiDeceptor appliance hosting deception services
4. OT Environment
Customer Requirements: Protect an operational technology (OT) network with centralized management while keeping
deception services isolated from the corporate IT environment.
ENTRIES SKU NOTES
1 FDR-100G FortiDeceptor appliance for OT/industrial environments
1 FC1-10-DR1HG-495-02-DD Deception Threat Intelligence Subscription for the FDR-100G
1 FC-10-DR1HG-247-02-DD FortiCare Premium Subscription for the FDR-100G
6


**Table 6.1**

| ENTRIES | SKU | NOTES |
| --- | --- | --- |


**Table 6.2**

| ENTRIES | SKU | NOTES |
| --- | --- | --- |


**Table 6.3**

| ENTRIES | SKU | NOTES |
| --- | --- | --- |


**Table 6.4**

| ENTRIES | SKU | NOTES |
| --- | --- | --- |


**Table 6.5**

| ENTRIES | SKU | NOTES |
| --- | --- | --- |


**Table 6.6**

| ENTRIES | SKU | NOTES |
| --- | --- | --- |


**Table 6.7**

|  |  |
| --- | --- |

FortiDeceptor Ordering Guide
Fortinet Training and Certification
Other Technical – FortiDeceptor Administrator Training
Learn how to deceive, expose, and eliminate threats early in the attack kill chain using FortiDeceptor. FortiDeceptor lures
attackers into revealing themselves by engaging with a range of deception assets distributed throughout the network
environment.
Course Details
For prerequisites, agenda topics, and learning objectives, visit FortiDeceptor Administrator.
Training Offering
For training SKUs, purchasing, and delivery options, visit Purchasing Process.
7

FortiDeceptor Ordering Guide
Frequently Asked Questions
Getting Started and Deployment
Which deployment model should I recommend?
Select the deployment model based on the customer’s infrastructure and operational requirements.
• DaaS – Fastest deployment with no infrastructure to manage.
• FDC-VM – Customer-managed virtual environments.
• FDC-1000G – Enterprise on-premises deployments.
• FDC-100G – Branch offices and remote sites.
• FDR-100G – Industrial and harsh environments.
Can I deploy both FortiDeceptor hardware and virtual appliances in the same environment?
Yes. FortiDeceptor supports mixed deployments of hardware and virtual appliances.
Can FortiDeceptor DaaS manage all FortiDeceptor appliances?
No. FortiDeceptor DaaS can manage only Edge devices (e.g. FDC-100G and FDC-VME).
Can FDC-VME or FDC-100G work with a local FortiDeceptor Manager?
Yes. Use the on-premises VLAN subscription associated with the hardware or virtual FortiDeceptor Manager instead of the
DaaS subscription.
When do I need a Central Manager?
A Central Manager is recommended whenever the deployment includes more than one FortiDeceptor appliance. A Central
Manager license is not required for DaaS-only deployments.
Sizing and Scalability
How do I size a FortiDeceptor deployment?
Start by determining:
• Number of protected network segments (VLANs)
• Number of branch offices or sites
• Centralized management requirements
• Desired deception coverage
What are the minimum and maximum VLANs supported per appliance?
Depending on the deployment model and subscription, the number of supported VLANs varies as follows: 2 to 128 VLANs on
edge devices (VME, 100G, and 100H), 2 to 256 VLANs on VMs and the 1000G, and 2 to 48 VLANs on the 100G Rugged.
How many decoys can one appliance deploy?
The FortiDeceptor VMS, 1000G, and 100G Rugged appliances support up to 20, 30, and 8 Decoy VMs, respectively. The
previous-generation 1000G supports up to 20 Decoy VMs.
Each Decoy VM can support up to 24 IP addresses, allowing a single appliance to represent hundreds of decoy IP addresses.
The total number of decoy IP addresses can be estimated by multiplying the number of supported Decoy VMs by the number of
IP addresses assigned to each VM. For example, a 1000G appliance can support up to 30 × 24 = 720 decoy IP addresses.
Actual deployment capacity may vary depending on deployment requirements and best practices.
How do I expand the deployment?
Deploy additional FortiDeceptor appliances and manage them centrally using a FortiDeceptor Central Manager.
Licensing
How is FortiDeceptor licensed?
FortiDeceptor subscriptions are primarily licensed by the number of protected network segments (VLANs).
8


**Table 8.1**

|  |  |  |
| --- | --- | --- |
|  |  |  |
|  |  |  |

FortiDeceptor Ordering Guide
How are VLAN licenses calculated?
A single Class C (/24) network requires one VLAN license. Larger networks (/23, /22, etc.) require two VLAN licenses per
network segment.
How are AWS VPCs and Azure VNets licensed?
Each cloud network (such as an AWS VPC or Azure VNet) is treated as a single VLAN license.
When do I need Windows Decoy Licenses?
Windows Decoy Licenses are required when deploying the built-in Windows decoys on hardware or virtual appliances.
Can I use my own Windows licenses?
Yes. Customers may deploy custom Windows decoys using their own Windows licenses. Built-in Windows decoys require
FortiDeceptor Windows Decoy Licenses.
How many Windows decoys are included with one Windows Decoy License?
Each LIC-FDC-WIN license provides two Windows licenses, allowing deployment of two Windows Decoy VMs.
Do Linux, IoT, SCADA, and other decoys require additional licenses?
No. Linux, IoT, SCADA, Cloud, and other built-in decoys are included with the subscription.
Note: Red Hat-based custom decoys require customer-supplied Red Hat subscriptions.
Are Deception Tokens licensed separately?
No. Deception Tokens are included with the FortiDeceptor subscription.
Centralized Management
How is the Central Manager licensed and ordered?
The Central Manager license is based on the total number of FortiDeceptor appliances managed by the Central Manager,
including the appliance hosting the Central Manager. Order one Central Manager license for each managed FortiDeceptor
appliance. The license is uploaded only to the Central Manager.
Which license should I use when deploying a Top Manager (TM)?
Top Manager uses the same Central Manager license model. Order one Central Manager license per managed Central
Manager.
Best Practices
What is the recommended deployment for multiple branch offices?
Deploy FDC-100G Edge appliances at each branch and manage them centrally using an FDC-1000G or FDC-VM.
Should I start with a single appliance?
Yes. Customers can begin with a single appliance or DaaS deployment and expand by adding VLAN subscriptions or additional
appliances as the environment grows.
How should I order licenses for multiple appliances?
Subscriptions and seat-based licenses should be ordered separately for each FortiDeceptor appliance to simplify deployment
and license management.
What is the best way to expand a deployment?
Scale horizontally by adding additional FortiDeceptor appliances while managing them through a Central Manager.
www.fortinet.com
Copyright © 2026 Fortinet, Inc. All rights reserved. Fortinet®, FortiGate®, FortiCare® and FortiGuard®, and certain other marks are registered trademarks of Fortinet, Inc., and other Fortinet names herein may also be registered and/or common law trademarks of Fortinet. All other product or
company names may be trademarks of their respective owners. Performance and other metrics contained herein were attained in internal lab tests under ideal conditions, and actual performance and other results may vary. Network variables, different network environments and other condi-
tions may affect performance results. Nothing herein represents any binding commitment by Fortinet, and Fortinet disclaims all warranties, whether express or implied, except to the extent Fortinet enters a binding written contract, signed by Fortinet’s SVP Legal and above, with a purchaser
that expressly warrants that the identified product will perform according to certain expressly-identified performance metrics and, in such event, only the specific performance metrics expressly identified in such binding written contract shall be binding on Fortinet. For absolute clarity, any
such warranty will be limited to performance in the same ideal conditions as in Fortinet’s internal lab tests. Fortinet disclaims in full any covenants, representations, and guarantees pursuant hereto, whether express or implied. Fortinet reserves the right to change, modify, transfer, or otherwise
revise this publication without notice, and the most current version of the publication shall be applicable.
October 2, 2026 7:43 AM
FDC-OG-R30-20261001
