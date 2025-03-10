# Cloud Computing Concepts

## Cloud Service Modules
- Three cloud computing models are
  - Infrastructure as a Service (IaaS)
  - Platform as a Service (PaaS)
  - Software as a Service (SaaS)
- You can use serverless computing to eliminate the need to manage infrastructure
- Shared responsibility model:

| Azure                                                                                   | Customer                                                                            |
| --------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| Is responsible for protecting the infrastrucure such as hosts, network, and data center | Is responsible for protecting their data, endpoints, account, and access management |

- IaaS, PaaS, and SaaS have different level of managed services:

| IaaS                 | PaaS                 | SaaS                 |
| -------------------- | -------------------- | -------------------- |
| Application          | Application          | Application          |
| Data                 | Data                 | ***Data***           |
| Runtime              | Runtime              | ***Runtime***        |
| Middleware           | ***Middleware***     | ***Middleware***     |
| O/S                  | ***O/S***            | ***O/S***            |
| ***Virtualisation*** | ***Virtualisation*** | ***Virtualisation*** |
| ***Servers***        | ***Servers***        | ***Servers***        |
| ***Storage***        | ***Storage***        | ***Storage***        |
| ***Networking***     | ***Networking***     | ***Networking***     |

### Infrastructure as a Service (IaaS)
  - Most user management
  - You are responsible for managing the operating systems, data, and application.
  - IaaS helps you to extend resources rapidly to meet the spikes required for your application.
  - Used in the following scenarios:
    - **Migrating Workloads** - move existing applications to the cloud.
    - **Test and development** - quickly set up and dismantle test and development environments. IaaS makes scaling development and testing environments fast and economical.
    - **Storage, backup, and recovery** - simplify the planning and management of backup and recovery systems.
    - **Website hosting** - less expensive than traditional web hosting.
    - **High-performance computing (HPC)** - clusters of computers that help solve complex problems involving millions of variables or calculations.
    - **Big data analysis** - for massive data sets that require a huge amount of processing power.
### Platform as a Service (PaaS)
  - Less user management
  - The operating systems are managed by the cloud provider, while the user is responsible for the applications and data they run and store.
  - PaaS offers all the functionality you need to support the entire lifecycle of web applications:
  **building, testing the application, deploying the source code, managing**, and **updating** within the same integrated environment.
  - Used in the following scenarios:
    - **Development framework** - a framework for creating or customising cloud-based applications.
    - **Analytics or business intelligence** - find insights and patterns, and predict outcomes to improve business decisions.
### Software as a Service (SaaS)
  - Least amount of management
  - The cloud provider is responsible for managing everything, and the end-user just uses the software.

### Serverless Computing
  - Function as a Service (FaaS)
  - You simply deploy the code with a serverless platform, and it runs at high availability.
  - Dynamically scales up and down to meet the demands of each workload within seconds.
  - a pay-per-execution model that charges sub-second billing only for the time and resources required to execute the code.

