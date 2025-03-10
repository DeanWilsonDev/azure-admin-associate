# Azure Virtual Network
- You can create a virtual network in the cloud dedicated to your Azure account. It is the fundamental building block where you can launch Azure resources.
- Azure VNet is the networking layer of Azure VMs
- A VNet spans all Availability Zones in the region. After creating a VNet, you can add one or more subnets in each Availability Zone.

## Cheat Sheet
[Azure Virtual Network (VNet) Tutorials Dojo Cheat Sheet](https://tutorialsdojo.com/azure-virtual-network-vnet/)

## Key Concepts
- A **virtual network (VNet)** allows you to specify IP address range for the VNet, add subnets, associate network security groups, and configure route tables.
- A **subnet** is a range of IP addresses in your VNet. You can launch Azure resources into a specified subnet. Use a **public subnet** for resources that need to connect to the Internet and a **private subnet** for resources that won't be connected to the Internet.
- To protect the Azure resources in each subnet, use **network security groups**

## VNet Use Case
- VNet with a single public subnet
- VNet with public and private subnets (NAT)

## Subnets
- You can add multiple subnets in each Availability Zone of your VNets region
- Types of subnets:
    - Public subnet
    - Private subnet
    - Gateway subnet
- There are 5 reserved addresses in each CIDR block.
- You can delegate a subnet to be used by a dedicated service.

## Security
- **Network Security Groups** - control the inbound and outbound traffic of Azure resources.
    - The rules are processed for lowest to highest numbers.
    - You can set a number between 100 and 4096
    - The rules can be applied to both inbound or outbound traffic
    - You can allow or deny incoming or outgoing traffic
    - When you create a network security group, Azure assigns default security rules for inbound and outbound traffic.
    - Can be attached to a subnet or a network interface. Refrain from attaching a network security group to both subnet and network interface.
- Augmented security rules allow you to create a single rule with multiple source and destination IPs.
- Application Security Group - allows you to define a VMs group network security group.
- You can use **IP flow verify** of Azure Network Watcher to check which network security rule allows or denies the traffic.
- With VNet service endpoint policy, you can filter the egress VNet traffic to Azure Storage.

## VNet Components
- Nat Gateway - Allows your virtual network resources to have an outbound-only connection
- Route Tables - determine where network traffic is directed
- VNet peering - allows you to connect VNets to eachother
- Azure Private Endpoint - allows you to connect privately to a service

## VNet Peering
- Allows you to connect two virtual networks seamlessly. You can:
    - Connect virtual networks in the same Azure region known as **virtual network peering**.
    - Connect virtual networks across different Azure regiions known as **global virtual network peering**.
- Ensure that your VNet address ranges do not overlap with one another. Plan accordingly before initiating the peer.

## Azure Virtual Network Pricing
- You are charged for the public IP address and reserved IP address inside your VNet
- You are charged for the ingress and egress data of VNet Peering.
- You are charged for the NAT gateway resource hours and data processed (per GB)
