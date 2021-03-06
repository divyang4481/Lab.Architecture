
# Cloud Nativie Computing Resources


## Reference
- https://en.wikipedia.org/wiki/Cloud_native_computing
  + "Cloud native computing is an approach in software development that utilizes cloud computing to its fullest due to its use of an open source software stack to deploy applications as microservices"
  + "Typically, cloud native applications are built as a set of microservices that run in Docker containers, orchestrated in Kubernetes and managed and deployed using DevOps and Git Ops workflows."
  + "The advantage of using Docker containers is the ability to package all software needed to execute into one executable package. The container runs in a virtualized environment, which isolates the contained application from its environment."

- https://en.wikipedia.org/wiki/Native_cloud_application
  + "A type of computer software that natively utilizes services and infrastructure from cloud computing providers such as Amazon EC2, Force.com, or Microsoft Azure. NCAs exhibit a combined usage of the three fundamental technologies:"
    * "Computational grid - loosely, e.g. MapReduce"
    * "Data grids (e.g. distributed in-memory data caches)"
    * "Auto-scaling on any managed infrastructure"

- [Cloud Native Computing Foundation (CNCF)](https://www.cncf.io/)
  + https://www.cncf.io/certification/training/
  + https://github.com/cncf/toc/blob/master/DEFINITION.md
    * "Cloud native technologies empower organizations to build and run scalable applications in modern, dynamic environments such as public, private, and hybrid clouds. Containers, service meshes, microservices, immutable infrastructure, and declarative APIs exemplify this approach."
    * "These techniques enable loosely coupled systems that are resilient, manageable, and observable. Combined with robust automation, they allow engineers to make high-impact changes frequently and predictably with minimal toil."


- https://12factor.net/
- I. Codebase
  + One codebase tracked in revision control, many deploys
- II. Dependencies
  + Explicitly declare and isolate dependencies
- III. Config
  + Store config in the environment
- IV. Backing services
  + Treat backing services as attached resources
- V. Build, release, run
  + Strictly separate build and run stages
- VI. Processes
  + Execute the app as one or more stateless processes
- VII. Port binding
  + Export services via port binding
- VIII. Concurrency
  - Scale out via the process model
- IX. Disposability
  + Maximize robustness with fast startup and graceful shutdown
- X. Dev/prod parity
  + Keep development, staging, and production as similar as possible
- XI. Logs
  + Treat logs as event streams
- XII. Admin processes
  + Run admin/management tasks as one-off processes


## Background Reading 
- https://www.forbes.com/sites/forbestechcouncil/2019/05/21/what-does-it-mean-to-be-cloud-native/#601a923d5ecc

- https://docs.microsoft.com/en-us/dotnet/architecture/cloud-native/introduction
  + https://docs.microsoft.com/en-us/dotnet/architecture/cloud-native/
  + https://azure.microsoft.com/en-us/overview/cloudnative/

- https://newrelic.com/resource/cloud-native-is-new-normal

- https://www.ibm.com/cloud/learn/cloud-native

- https://about.gitlab.com/cloud-native/

- https://www.chef.io/solutions/cloud-native/

- https://www.informationweek.com/cloud/platform-as-a-service/cloud-native-what-it-means-why-it-matters/d/d-id/1321539
  + https://www.slideshare.net/CloudFoundryFoundation/cloud-foundry-ceo-sam-ramji-2015-oscon-keynote
  + https://www.linkedin.com/pulse/cloud-native-foundry-docker-kubernetes-sam-ramji/

- https://medium.com/walmartlabs/cloud-native-application-architecture-a84ddf378f82
  + "Cloud-native is about how applications are created and deployed, not where"
  + Cloud Native Design Principles
    * "Designed As Loosely Coupled Microservices"
    * "Developed With Best-of-breed Languages And Frameworks"
    * "Centred Around APIs For Interaction And Collaboration"
    * "Stateless And Massively Scalable"
    * "Resiliency At The Core Of the Architecture"
    * "Packaged As Lightweight Containers And Orchestrated"
    * "Agile DevOps & Automation Using CI/CD"
    * "Elastic — Dynamic scale-up/down"

- https://www.infoworld.com/article/3281046/what-is-cloud-native-the-modern-way-to-develop-software.html
  + "Cloud-native computing takes advantage of many modern techniques, including PaaS, multicloud, microservices, agile methodology, containers, CI/CD, and devops"

- https://www.redhat.com/en/topics/cloud-native-apps
  + "Cloud-native applications are a collection of small, independent, and loosely coupled services. They are designed to deliver well recognized business value, like the ability to rapidly incorporate user feedback for continuous improvement."
  + "If an app is "cloud-native," it’s specifically designed to provide a consistent development and automated management experience across private, public, and hybrid clouds"

- https://pivotal.io/cloud-native
  + "Cloud-native is an approach to building and running applications that exploits the advantages of the cloud computing delivery model. Cloud-native is about how applications are created and deployed, not where."
  + "Organizations require a platform for building and operating cloud-native applications and services that automates and integrates the concepts of DevOps, continuous delivery, microservices, and containers"
  + Benefits:
    * Predictable
    * OS abstraction
    * Right-sized capacity
    * Collaborative
    * Continuous delivery
    * Independent
    * Automated scalability
    * Rapid recovery

- https://thenewstack.io/10-key-attributes-of-cloud-native-applications/
  1. "Packaged as lightweight containers"
  2. "Developed with best-of-breed languages and frameworks"
  3. "Designed as loosely coupled microservices"
  4. "Centered around APIs for interaction and collaboration"
  5. "Architected with a clean separation of stateless and stateful services"
  6. "Isolated from server and operating system dependencies"
  7. "Deployed on self-service, elastic, cloud infrastructure"
  8. "Managed through agile DevOps processes"
  9. "Automated capabilities"
  10. "Defined, policy-driven resource allocation"



## Suggested Books (in order suggested reading...)

- [Cloud Native Transformation: Practical Patterns for Innovation, 1st Edition](https://www.amazon.com/Cloud-Native-Transformation-Practical-Innovation/dp/1492048909)

- [Cloud Native Data Center Networking: Architecture, Protocols, and Tools, 1st Edition](https://www.amazon.com/Cloud-Native-Data-Center-Networking-dp-1492045608/dp/1492045608/)
- [Cloud Native: Using Containers, Functions, and Data to Build Next-Generation Applications, 1st Edition](https://www.amazon.com/Cloud-Native-Containers-Next-Generation-Applications-dp-1492053821/dp/1492053821/)

- [Cloud Native Patterns: Designing change-tolerant software, 1st Edition](https://www.amazon.com/Cloud-Native-Designing-change-tolerant-software/dp/1617294292/)

- [Cloud Native DevOps with Kubernetes: Building, Deploying, and Scaling Modern Applications in the Cloud, 1st Edition](https://www.amazon.com/Cloud-Native-DevOps-Kubernetes-Applications/dp/1492040762/)

- [Cloud Native Infrastructure: Patterns for Scalable Infrastructure and Applications in a Dynamic Environment, 1st Edition](https://www.amazon.com/Cloud-Native-Infrastructure-Applications-Environment/dp/1491984309/)

- [Infrastructure as Code: Managing Servers in the Cloud, 1st Edition](https://www.amazon.com/Infrastructure-Code-Managing-Servers-Cloud/dp/1491924357/)

- [Terraform: Up and Running: Writing Infrastructure as Code, 1st Edition](https://www.amazon.com/Terraform-Running-Writing-Infrastructure-Code/dp/1491977086/)

- [Cloud Native Go: Building Web Applications and Microservices for the Cloud with Go and React (Developer's Library), 1st Edition](https://www.amazon.com/Cloud-Native-Applications-Microservices-Developers-dp-0672337797/dp/0672337797/)



