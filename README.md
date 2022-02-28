# Azure Virtual Desktop and Horizon Cloud Training

## Azure Fundementals

### Governance
* [Management groups?](https://docs.microsoft.com/en-us/azure/governance/management-groups/overview)
* [Subscriptions](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/decision-guides/subscriptions/)
* [Resource groups](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/manage-resource-groups-portal#what-is-a-resource-group)
* [Resource naming](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/resource-naming)
* [Naming rules and restrictions](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/resource-name-rules)

### Regions
![image](https://user-images.githubusercontent.com/28941673/155907648-f90b1699-8aec-467a-bd90-06fb700fb8d9.png)

* [About Azure regions](https://docs.microsoft.com/en-us/azure/virtual-machines/regions)
* [Azure Regions](https://azure.microsoft.com/en-us/global-infrastructure/geographies/#geographies)
* [Products availabile by region](https://azure.microsoft.com/en-us/global-infrastructure/services/)
* [Azure regions decision guide](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/migrate/azure-best-practices/multiple-regions)

### Identity
* [What is Azure Active Directory?](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-whatis)
* [YouTube: Azure AD Overview](https://www.youtube.com/watch?v=EUVKEhiHYG0)
* [YouTube: The Line Between AD and Azure AD!](https://www.youtube.com/watch?v=uts0oy8NlUs)

#### Azure AD Connect
* [What is hybrid identity with Azure Active Directory?](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/whatis-hybrid-identity)
* [Choose the right authentication method for your Azure Active Directory hybrid identity solution](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/choose-ad-authn)

### Network
* [Azure network options](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/considerations/networking-options)
* [YouTube: Azure Virtual Network Overview](https://www.youtube.com/watch?v=7rzawA--r20)
* [YouTube: Azure Virtual WAN Overview](https://www.youtube.com/watch?v=f-GyAURZWzg)
* [YouTube: Azure Virtual Network and PaaS Network Controls](https://www.youtube.com/watch?v=MnARPRQ2kvk)

#### WAN Connectivity
* [Azure VPN Gateway](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-about-vpngateways)
* [Azure ExpressRoute](https://docs.microsoft.com/en-au/azure/expressroute/expressroute-introduction)
* [Choose between virtual network peering and VPN gateways](https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/hybrid-networking/vnet-peering)
* [YouTube: ExpressRoute Deep Dive](https://www.youtube.com/watch?v=oevwZZ1YFS0)

### Storage
* [Storage account overview](https://docs.microsoft.com/en-us/azure/storage/common/storage-account-overview)
* [Configure Azure Storage firewalls and virtual networks](https://docs.microsoft.com/en-us/azure/storage/common/storage-network-security)
* [Azure Storage redundancy](https://docs.microsoft.com/en-us/azure/storage/common/storage-redundancy)

### Compute
* [Sizes for virtual machines in Azure](https://docs.microsoft.com/en-us/azure/virtual-machines/sizes)
* [Azure virtual machine sizes naming conventions](https://docs.microsoft.com/en-us/azure/virtual-machines/vm-naming-conventions)

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

### FSLogix
* [FSLogix for the enterprise](https://docs.microsoft.com/en-us/azure/architecture/example-scenario/wvd/windows-virtual-desktop-fslogix)
* [FSLogix profile containers and Azure files](https://docs.microsoft.com/en-us/azure/virtual-desktop/fslogix-containers-azure-files)
* [Storage options for FSLogix profile containers in Azure Virtual Desktop](https://docs.microsoft.com/en-us/azure/virtual-desktop/store-fslogix-profile)
* [FSLogix Sizing Calculator](https://github.com/RMITBLOG/FSLogix)

### Golden Image
* [Create a golden image in Azure](https://docs.microsoft.com/en-us/azure/virtual-desktop/set-up-golden-image)
* [Virtual Desktop Optimization Tool (VDOT)](https://github.com/The-Virtual-Desktop-Team/Virtual-Desktop-Optimization-Tool)
* [Create an Azure Virtual Desktop image using Azure VM Image Builder and PowerShell](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/image-builder-virtual-desktop)

### Management
* [Use Azure Monitor for Azure Virtual Desktop to monitor your deployment](https://docs.microsoft.com/en-us/azure/virtual-desktop/azure-monitor)
* Direct link to Workbook deployment: https://aka.ms/azmonwvdi
* [What is MSIX app attach?](https://docs.microsoft.com/en-us/azure/virtual-desktop/what-is-app-attach)

## Horizon Cloud on Azure
* [Horizon Service Deployments and Onboarding Pods — Horizon Pods and Horizon Cloud Pods on Microsoft Azure](https://docs.vmware.com/en/VMware-Horizon-Cloud-Service/services/hzncloudmsazure.getstarted15/GUID-6E460805-C323-4200-9A45-45E7BFB31730.html)

