# Cloud Application Integration Reference Architecture

The IBM Cloud Application Integration Reference Architecture explores common patterns in enterprises and hybrid cloud environments. The distributed component-based architecture supports lightweight fine-grained integration services to enable microservices and on-demand runtime application-level composition and aggregation.  
The *Accelerator for Telco* asset is based on this reference architecture, with a special focus on modular design and flexibility to extend the architecture as needed.

The following diagram shows an example scenario that leverages all key components within the architecture.

![Ref Architecture](img/hybrid-ref-arch.png)

*Scenario description:*  
1. The user accesses a published service by using a mobile device.  
2. The cloud-native application is invoked.  
3. The application uses all the cloud services that are available on the cloud platform to enrich the user experience.  
4. The application accesses enterprise systems and system-of-record (SOR) data through an integration platform in a private cloud that provides all the integration patterns that are needed to run the transactions in line with business rules and approved processes.  
5. The requests go through a secure connectivity gateway that provides access to the private cloud network and the enterprise domain.  
6. Application integration logic is invoked and run on an integration flow runtime that orchestrates access to the back-end systems.  
7. Alternatively, the flows can be invoked by a set of managed APIs. In addition, the integration logic can also be orchestrated by the native application by using fine-grained API calls directly to the back-end system.  
8. Data between enterprise repositories and those in the cloud, such as software-as-a-service (SaaS) applications or database-as-a-service (DBaaS), can be synchronized through the integration platform with appropriate transformation and normalization.  
9. Asynchronous access to heterogeneous and closed systems can be done with enterprise messaging directly from native applications.  
10. Event-driven integration allows enterprise applications to consume and process events that are published by the native applications. It also allows for enterprise events to be published and consumed by cloud services such as analytics and cognitive.  
11. High-speed file transfer capabilities enable the quick synchronization of large content and data among cloud repositories and enterprise back-end systems across global geographies.  
12. The integration platform also integrates with enterprise nonfunctional aspects with a unified perspective on DevOps, logging and monitoring, and security.
