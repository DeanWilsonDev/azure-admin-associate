# Azure Basics

## Advantages of Azure Cloud Computing
  - **Cost** - Only pay for the resources you use
  - **Global Scale** - Easily add resources in different regions and deploy globally
  - **Performance** - Access powerful hardware globally and reduce the latency of your applications
  - **Security** - Cloud service providers offer controls, technologies and policies to help you protect your data and infrastructure against potential threats.
  - **Speed** - Provision new resources within minutes, allowing for flexibility for high-capacity planning
  - **Productivity** - Allows you to focus on more important things than acquiring more hardware to run your systems and applications
  - **Reliability** - Easily manage backup data and disaster recovery with high availability and redundancy.
## Azure Pricing
- Azure offers pay-as-you-go and reserved instances for pricing.
- Azure Pricing Factors:
    - Resource size and resource type.
    - Different Azure locations have different prices for services
    - The bandwidth of your services
    - Any data transfer between two different billing zones is charged.
        - **Ingress (data in)** = free
        - **Egress (data out)** = charged based on data going out of Azure data centres
- Cost reduction factors:
    - **Reserved Instances** (one-year or three-year terms) - reduce costs up to 72% compared to pay-as-you-go
    - **Reserved capacity** instances for SQL Databases
    - **Hybrid Benefit** allows you to use Windows Server and SQL server licences on Azure
    - *Spot virtual machines* can be used for interruptible workloads with discounts up to 90%
- All resources belong to a **subscription**
    - An Azure account can have multiple subscriptions
    - Organize your resources and subscriptions using **Azure management groups**.
- **Azure Cost Management** gives you a detailed view of current and projected costs.
- For new accounts, the **Azure Free Tier** is available.
    - Free Tier offers limited usage of Azure products at no charge for 12 months.
    - You also get a $200 credit that you can spend during the first 30 days.
    - More details at [https://azure.microsoft.com/en-us/free](https://azure.microsoft.com/en-us/free)
    - Estimate expected monthly costs using Azure Pricing Calculator
- **Azure Support Plans:**
    - **Basic** - included for all Azure customers.
    - **Developer** - recommended for non-production environments. Limited access to technical support during business hours by email only
    - **Standard** - appropriate for production work environments. 24/7 access to Azure technical support
    - **Professional Direct** - suitable for business-critical workloads. Has 24/7 access to all of Azure's Support options

