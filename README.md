# araclx.ENV

**araclx.ENV** stands for modularity, scalability and performance. This stack was designed to archive most performance followed by developer-friendly solutions provided by few programming languages and tools, it's focused to be tool-agnostic which makes it suitable for most companies and developers.

> Document under development, we're still thinking on right categories which will provide good readability and method to present all of important informations.

## Table of Contents

- [Application and Data](#application-and-data)
  - [Programming Languages](#programming-languages)
  - [API Management](#api-management)
  - [API Design](#api-design)
  - [Feature Management](#feature-management)
  - [Software Testing](#software-testing)
- [Infrastructure](#infrastructure)
  - [Infrastucture-as-a-Service (IaaS)](#infrastucture-as-a-service--iaas-)
  - [Hypercovered Infrastucture (HCI)](#hypercovered-infrastucture--hci-)
  - [Platform as a Service (PaaS)](#platform-as-a-service--paas-)
- [DevOps](#devops)
  - [Version Control System (VSC)](#version-control-system--vsc-)
  - [Containerisation](#containerisation)
    - [Container Engines](#container-engines)
    - [Container Management](#container-management)
    - [Container Orchestration](#container-orchestration)
    - [Container Registry](#container-registry)
- [Business Tools](#business-tools)
  - [Communication](#communication)
  - [Sales & Customer Service](#sales---customer-service)
  - [Marketing](#marketing)
  - [Analytics](#analytics)
  - [Collaboration](#collaboration)
  - [Human Resources](#human-resources)

## Application and Data

### Programming Languages

| Language       | Description                                                                                                                       | Purpose                                                                                     |
| :------------- | :-------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------ |
| **TypeScript** | Superset of JavaScript that provides a type-safe and scalable development. TypeScript is open-source and maintained by Microsoft. | We're using TypeScript literally everywhere because good performance and developer toolkit. |
| **Go**         | ...                                                                                                                               | ...                                                                                         |
| **Rust**       | Rust is low-end language which offers high-performance.                                                                           | ...                                                                                         |

### API Management

API management software allows users to monitor, control, and monetize their application program interfaces (APIs) in a secure development environment. These tools help administrators monitor connection consistency, traffic, errors, and security for their team’s published APIs.

- Postman

[⬆️ Back to Top](#table-of-contents)

### API Design

API design software allows users to plan, create, and make changes to application programming interfaces (APIs) in a secure development environment. These tools help handle the pre-production management for APIs by enabling developers to ideate, set design guidelines, and ultimately build APIs under one dashboard.

- SwaggerHub
- Postman

[⬆️ Back to Top](#table-of-contents)

### Feature Management

Feature management software facilitates the orchestration of feature rollouts and rollbacks for deployed applications. Developers use this software to manage feature flags, or “toggles," that control whether a given feature is live in an application. Feature management software relieves the logistical complexities of managing feature flags by providing a centralized hub for granular control and monitoring.

- Split

[⬆️ Back to Top](#table-of-contents)

### Software Testing

Software testing software gives development teams the methods and tools to determine the quality of their software creation and improvement projects. Development teams use software testing tools to assess whether software is usable, performs properly, meets development team goals, and meets overall requirements.

- UserTesting
- Postman
- Cypress
- SauceLabs
- LambdaTest

[⬆️ Back to Top](#table-of-contents)

## Infrastructure

### Infrastucture-as-a-Service (IaaS)

Infrastructure as a service (IaaS) describes the various ways in which third-party vendors provide cloud-driven, cloud-hosted infrastructure to businesses. This infrastructure comes in a variety of forms, including (but not limited to) public clouds, virtual machines (VMs), bare metal servers, and high-performance computing (HPC). Because of the incredible diversity of IaaS tools, any organization or user within a business could find benefit from the business employing IaaS.

| Service                 | Description |
| :---------------------- | :---------- |
| **DigitalOcean**        | ...         |
| **Vultr**               | ...         |
| **Google Cloud Engine** | ...         |

[⬆️ Back to Top](#table-of-contents)

### Hypercovered Infrastucture (HCI)

Hyperconverged infrastructure (HCI) solutions offer businesses the ability to virtualize storage, servers, and their connecting networks. Unlike converged infrastructure, hyperconverged infrastructure leans into software definition as opposed to hardware definition, enabling higher overall flexibility and better expense management over infrastructure use.

- Nutanix

[⬆️ Back to Top](#table-of-contents)

### Platform as a Service (PaaS)

Platform as a service, or PaaS, is cloud computing model that provides users with hosted development kits, database tools, and application management capabilities. Third-party vendors provide users with virtual resources to build, deploy, and launch software applications, reducing the need for back-end software development. Businesses utilize PaaS to outsource hosting, database construction, cloud security capabilities, and data storage.

| Service     | Description |
| :---------- | :---------- |
| Heroku      | ...         |
| Flynn       | ...         |
| Platform.sh | ...         |

[⬆️ Back to Top](#table-of-contents)

## DevOps

### Version Control System (VSC)

Version control systems, also known as revision control or source control systems, are used to track changes to software development projects, and allow team members to change and collaborate on the same files. Version control systems allow developers to work simultaneously on code and isolate their own work through branches.

- GitHub

### Containerisation

#### Container Engines

Container engines, often referred to as operating-system-level virtualization, are operating systems in which the kernel allows the existence of multiple isolated instances. Each instance is referred to as a container, virtualization engine, or jail. Developers use these to create secure, virtual hosting environments with isolated resources. Developers can also separate applications, programs, or segments of code for increased security.

- Docker

[⬆️ Back to Top](#table-of-contents)

#### Container Management

Container management platforms facilitate the organization and virtualization of software containers, which may also be referred to as operating-system-level virtualizations. Developers use containers to launch, test, and secure applications in resource-independent environments. Containers house components of applications, libraries, or groups of source code that can be executed on demand. The management platforms help users allocate resources to optimize efficiency and balance system workloads. Containers provide a flexible, portable platform to organize, automate, and distribute applications.

- WeaveWorks

[⬆️ Back to Top](#table-of-contents)

#### Container Networking

Container networking software creates a virtualized, defined network to facilitate container-to-container connectivity. These internally virtualized networks allow communication and integration between containers or applications powered by container sets. The networks create isolated regions to allow multiple containers to communicate with the same network independently.

- HashiCorp Consul
- Nginx
- Istio

[⬆️ Back to Top](#table-of-contents)

#### Service Discovery

Service discovery software helps automate the detection of services within a computer network. This type of software connects clustered containers to service providers by identifying their name, host, or link. Service discovery solutions allow applications within containers to communicate and integrate data with registered services.

- HashiCorp Consul
- Traefik
- linkerd

[⬆️ Back to Top](#table-of-contents)

#### Container Orchestration

Container orchestration software allows developers to deploy multiple containers for implementation within applications. These tools help IT administrators automate the process of running instances, provisioning hosts, and linking containers. These tools assist in optimizing orchestration procedures and extending the lifecycle of applications containing multiple containers. They can also facilitate deployment, identify failed container implementations, and manage application configurations.

- Kubernetes
- Nomad
- D2iQ
- Rancher

[⬆️ Back to Top](#table-of-contents)

#### Container Registry

Container registries allow users to manage containers distributed throughout their applications and networks. The registry controls privileges to individual containers and allows users to organize and govern their visibility and accessibility. These registries can come in the form of a hosted service or an on-premise solution using local infrastructure. Companies utilize container registries to manage container configurations, store container images, and access them for deployment.

- DockerHub
- GitHub Packages

[⬆️ Back to Top](#table-of-contents)

### CI/CD

#### Continous Integration

Continuous integration (CI) is the practice of frequently building and testing each change made to a codebase. Continuous integration involves developers uploading new code, or code changes, to a common code repository, which is then tested automatically at the time of upload to ensure changes do not cause issues or breaks.

- CircleCI

[⬆️ Back to Top](#table-of-contents)

#### Continous Deployment

Continuous deployment is software that automatically deploys built applications to production. Continuous deployment tools are often used by large companies that need to quickly, frequently, and easily release new changes to their customers’ applications. Continuous deployment tools are used by DevOps teams through a workflow called the deployment pipeline.

- CircleCI
- Ansible

[⬆️ Back to Top](#table-of-contents)

#### Continous Delivery

Continuous delivery, as a process, aims to help developers generate deployment-ready code as quickly and efficiently as possible. By facilitating short development cycles with automation, workflows, and more, continuous delivery solutions enable developers to write, test, and stage software and updates. Code written through continuous delivery must be deployed manually.

- BitRise
- Qovery (https://www.qovery.com/)
- https://humanitec.com/

[⬆️ Back to Top](#table-of-contents)

#### Infrastructure Automation

Cloud infrastructure automation technology is used to provision servers and computer data centers through metadata files, as opposed to physical configuration. The concept in practice can also be referred to implementing "infrastructure as code" or performing continuous configuration automation. Developers will create templated infrastructure to run their application code, review code, and integrate it. These templates can then be reused and generated automatically, minimizing a developer’s need to reconfigure infrastructure.

- Terraform
- Ansible
- SaltStack

[⬆️ Back to Top](#table-of-contents)

## Business Tools

### Communication

### Sales & Customer Service

### Marketing

### Analytics

### Collaboration

### Human Resources

#### Virtualization

- VMware
- Vagrant

### DNS

- NS1
- CloudFlare

## Business Tools

- Zoom
- Whereby
- Invision
- Miro
- Slab
- Slite
- Front
- Airtable
- Asana
- Jira
- Quickbooks
- Pipedrive
- Pleo.io
