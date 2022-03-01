# Azure Virtual Desktop and Horizon Cloud Training

## Azure Fundementals

### Governance
* [Management groups](https://docs.microsoft.com/en-us/azure/governance/management-groups/overview)
* [Subscriptions](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/decision-guides/subscriptions/)
* [Resource groups](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/manage-resource-groups-portal#what-is-a-resource-group)
* [Resource naming](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/resource-naming)
* [Naming rules and restrictions](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/resource-name-rules)

### Regions
![Azure regions](https://user-images.githubusercontent.com/28941673/155907648-f90b1699-8aec-467a-bd90-06fb700fb8d9.png)
* [About Azure regions](https://docs.microsoft.com/en-us/azure/virtual-machines/regions)
* [Azure Regions](https://azure.microsoft.com/en-us/global-infrastructure/geographies/#geographies)
* [Products availabile by region](https://azure.microsoft.com/en-us/global-infrastructure/services/)
* [Azure regions decision guide](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/migrate/azure-best-practices/multiple-regions)

### Identity
* [What is Azure Active Directory?](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-whatis)
* [[YouTube] Azure AD Overview](https://www.youtube.com/watch?v=EUVKEhiHYG0)
* [[YouTube] The Line Between AD and Azure AD!](https://www.youtube.com/watch?v=uts0oy8NlUs)

#### Azure AD Connect
* [What is hybrid identity with Azure Active Directory?](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/whatis-hybrid-identity)
* [Choose the right authentication method for your Azure Active Directory hybrid identity solution](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/choose-ad-authn)

### Network
* [Azure network options](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/considerations/networking-options)
* [Hub-spoke network topology with Azure Virtual WAN](https://docs.microsoft.com/en-us/azure/architecture/networking/hub-spoke-vwan-architecture)
<img src="https://user-images.githubusercontent.com/28941673/155910127-f313093b-322d-4796-b47d-e11a42705bb4.png" width="768">

* [[YouTube] Azure Virtual Network Overview](https://www.youtube.com/watch?v=7rzawA--r20)
* [[YouTube] Azure Virtual WAN Overview](https://www.youtube.com/watch?v=f-GyAURZWzg)
* [[YouTube] Azure Virtual Network and PaaS Network Controls](https://www.youtube.com/watch?v=MnARPRQ2kvk)

#### WAN Connectivity
* [Azure VPN Gateway](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-about-vpngateways)
* [Azure ExpressRoute](https://docs.microsoft.com/en-au/azure/expressroute/expressroute-introduction)
* [Choose between virtual network peering and VPN gateways](https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/hybrid-networking/vnet-peering)
* [[YouTube] ExpressRoute Deep Dive](https://www.youtube.com/watch?v=oevwZZ1YFS0)

### Storage
* [Storage account overview](https://docs.microsoft.com/en-us/azure/storage/common/storage-account-overview)
* [Configure Azure Storage firewalls and virtual networks](https://docs.microsoft.com/en-us/azure/storage/common/storage-network-security)
* [Azure Storage redundancy](https://docs.microsoft.com/en-us/azure/storage/common/storage-redundancy)

### Compute
* [Sizes for virtual machines in Azure](https://docs.microsoft.com/en-us/azure/virtual-machines/sizes)
* [Azure virtual machine sizes naming conventions](https://docs.microsoft.com/en-us/azure/virtual-machines/vm-naming-conventions)

---

## Azure Virtual Desktop
* [What is Azure Virtual Desktop?](https://docs.microsoft.com/en-us/azure/virtual-desktop/overview)
* [Azure Virtual Desktop for the enterprise](https://docs.microsoft.com/en-us/azure/architecture/example-scenario/wvd/windows-virtual-desktop)

### Network
* [Understanding Azure Virtual Desktop network connectivity](https://docs.microsoft.com/en-us/azure/virtual-desktop/network-connectivity)

#### Sizing
* [Remote Desktop workloads](https://docs.microsoft.com/en-us/windows-server/remote/remote-desktop-services/remote-desktop-workloads)
* [Remote Desktop Protocol (RDP) bandwidth requirements](https://docs.microsoft.com/en-us/azure/virtual-desktop/rdp-bandwidth)
* [Network guidelines](https://docs.microsoft.com/en-us/windows-server/remote/remote-desktop-services/network-guidance)

#### Latency
* [Determine user connection latency in Azure Virtual Desktop](https://docs.microsoft.com/en-us/azure/virtual-desktop/connection-latency)
* [Azure Virtual Desktop RDP Shortpath for managed networks](https://docs.microsoft.com/en-us/azure/virtual-desktop/shortpath)

### Compute
* [Virtual machine sizing guidelines](https://docs.microsoft.com/en-us/windows-server/remote/remote-desktop-services/virtual-machine-recs)

### Profile Management
* [FSLogix for the enterprise](https://docs.microsoft.com/en-us/azure/architecture/example-scenario/wvd/windows-virtual-desktop-fslogix)
* [FSLogix profile containers and Azure files](https://docs.microsoft.com/en-us/azure/virtual-desktop/fslogix-containers-azure-files)
* [Storage options for FSLogix profile containers in Azure Virtual Desktop](https://docs.microsoft.com/en-us/azure/virtual-desktop/store-fslogix-profile)
* [FSLogix Sizing Calculator](https://github.com/RMITBLOG/FSLogix)

### Deployment
* [Create a profile container with Azure Files and AD DS](https://docs.microsoft.com/en-us/azure/virtual-desktop/create-file-share)
  * [Storage account AD join script](https://github.com/argiesen/CloudVDI/blob/main/StorageAccountADJoin.md)
* [Set up email discovery](https://docs.microsoft.com/en-us/windows-server/remote/remote-desktop-services/rds-email-discovery?context=/azure/virtual-desktop/context/context)

#### Golden Image
* [Create a golden image in Azure](https://docs.microsoft.com/en-us/azure/virtual-desktop/set-up-golden-image)
* [Virtual Desktop Optimization Tool (VDOT)](https://github.com/The-Virtual-Desktop-Team/Virtual-Desktop-Optimization-Tool)
* [Create an Azure Virtual Desktop image using Azure VM Image Builder and PowerShell](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/image-builder-virtual-desktop)

### Management
* [Use Azure Monitor for Azure Virtual Desktop to monitor your deployment](https://docs.microsoft.com/en-us/azure/virtual-desktop/azure-monitor)
* Direct link to Workbook deployment: https://aka.ms/azmonwvdi
* [What is MSIX app attach?](https://docs.microsoft.com/en-us/azure/virtual-desktop/what-is-app-attach)

---

## Horizon Cloud on Azure
* [VMware Horizon Cloud Service Documentation](https://docs.vmware.com/en/VMware-Horizon-Cloud-Service/index.html)
* [Horizon Service Deployments and Onboarding Pods — Horizon Pods and Horizon Cloud Pods on Microsoft Azure](https://docs.vmware.com/en/VMware-Horizon-Cloud-Service/services/hzncloudmsazure.getstarted15/GUID-6E460805-C323-4200-9A45-45E7BFB31730.html)
* [VMware Hands-on Labs - HOL-2054-01-ISM](https://docs.hol.vmware.com/HOL-2020/hol-2054-01-ism_html_en/)

High level architecture  
  <img src="https://user-images.githubusercontent.com/28941673/155908495-0fbadf2b-5fd6-4b4b-b7dc-b814a58dcc03.png" width="768">

Detailed architecture  
  <img src="https://user-images.githubusercontent.com/28941673/155908510-9fff6f71-f6d6-40ff-ad82-28579d8a6b00.png" width="768">

### Network
* [Horizon Cloud on Microsoft Azure Architecture - Network Design](https://techzone.vmware.com/resource/horizon-cloud-on-microsoft-azure-architecture#network-design)
* Single VNET  
  <img src="https://user-images.githubusercontent.com/28941673/155909348-93e97e4e-1432-43b5-aa44-e75244fdb702.png" width="680">  
* [Separate UAG VNET](https://techzone.vmware.com/resource/horizon-cloud-on-microsoft-azure-architecture#deploying-unified-access-gateways-into-a-different-vnet)  
  <img src="https://user-images.githubusercontent.com/28941673/155909357-69e91b56-9cbd-4a17-99f7-44993daaffe0.png" width="680">

### Compute
* [Microsoft Azure Virtual Machine Requirements for a Horizon Cloud Pod in Microsoft Azure](https://docs.vmware.com/en/VMware-Horizon-Cloud-Service/services/hzncloudmsazure.getstarted15/GUID-BA0CD5F3-4805-4C21-866F-93CCC9976EDC.html)
* [Microsoft Azure Capacity Requirements](https://docs.vmware.com/en/VMware-Horizon-Cloud-Service/services/hzncloudmsazure.getstarted15/GUID-5F69086E-E061-48F3-93D9-9705B8B5FD8A.html#microsoft-azure-capacity-requirements-4)

### Deployment
* [Horizon Cloud on Microsoft Azure - First Pod Deployment - High-Level Workflow](https://docs.vmware.com/en/VMware-Horizon-Cloud-Service/services/hzncloudmsazure.getstarted15/GUID-F2A692EB-25B7-4208-AF89-23691F5B85D8.html)
* [[YouTube] From Zero to Hero: A Step by Step Guide How To Deploy Horizon Cloud Service on Azure](https://www.youtube.com/watch?v=qIWum9JtLHk)
* [Configure the Required Virtual Network in Microsoft Azure](https://docs.vmware.com/en/VMware-Horizon-Cloud-Service/services/hzncloudmsazure.getstarted15/GUID-919E6477-7506-46CF-B8BC-D4D47A4CC301.html)
* [Create a Horizon Cloud App Registration in the Pod's Subscription](https://docs.vmware.com/en/VMware-Horizon-Cloud-Service/services/hzncloudmsazure.getstarted15/GUID-DC011997-CE9E-4B38-9C4F-57104226218C.html)
  * Create app registration
  * Assign role to app registration
  * Register resource providers
* [Convert a Certificate File to the PEM Format Required for Pod Deployment](https://docs.vmware.com/en/VMware-Horizon-Cloud-Service/services/hzncloudmsazure.getstarted15/GUID-CB9FCC7C-4EDD-4252-871B-6A259F1DEA95.html)

Deployment Wizard steps  
  <img src="https://user-images.githubusercontent.com/28941673/155908448-8b5fafcc-8cb6-4446-ad6a-527f12cbeea1.png" width="768">
