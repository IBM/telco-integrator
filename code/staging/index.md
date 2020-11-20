![telco integrator](img/banner.png)
# IBM and the TMF API Ecosystem

The Telemanagement Forum, commonly referred to as "TM Forum" or "TMF", is a nonprofit industry association for service providers and their suppliers in the telecommunications and entertainment industries. Members of this association include telephone companies, cable operators, network operators, software suppliers, equipment suppliers and systems integrators. TM Forum members, including the world’s largest service providers and suppliers such as IBM, have been working to develop APIs that support the TM Forum API Ecosystem.

The TM Forum API Ecosystem is a family of over 50 REST APIs designed to make it easier to create, build and operate complex innovative services. This set of standard interfaces enables rapid, repeatable and flexible integration among operations and management systems. The APIs are based on the Business Process Framework (called eTOM), which is a critical component of Frameworx. Designed to enable end-to-end services for today’s digital economy, Frameworx is the TM Forum’s blueprint for successful business transformation.

In the digital economy age, services are typically delivered through a sophisticated partnering of multiple providers that all use different systems and interfaces. The TM Forum REST-based APIs are designed for uses ranging from Internet of Things (IoT) device management to complex B2B value fabrics. They apply to API-driven scenarios such as IoT, digital health, smart grids, big data, Network Functions Virtualization (NFV), next-generation operations support systems, business support systems (OSS/BSS) and more.

To date, 71 of the world’s leading communications service providers (CSPs) and technology ecosystem participants (including IBM) have signed the Open API Manifesto, publicly demonstrating their endorsement of TM Forum’s suite of Open APIs. 
!!! hint ""
    The IBM Executive Sponsor for the TM Forum Open API Manifesto is 
    
    **Marisa Viveros, VP Strategy & Offerings – Telecom, Media and Entertainment Industries**

This document describes the Open API Accelerator for Telco built by IBM Expertise Connect. The Accelerator is a Cloud-native asset based on [IBM Cloud Pak for Integration](https://www.ibm.com/cloud/cloud-pak-for-integration)  and leverages [IBM Cloud Pak for Data](https://www.ibm.com/products/cloud-pak-for-data) for AI infusion.

- The TM Forum APIs are exposed through API Connect and DataPower
- Routing and data transformation implemented in IBM App Connect for Enterprise (ACE).
- IBM Event Streams manages order history, in-flight order events and notifications
- Sterling Order Management pipelines are used for Order state management
- Order decomposition and execution build plan decision system is provided by IBM Operation Decision Manager (ODM)

The Open API Accelerator implements the TM Forum specifications for Product Ordering Management and provides consistent interactions with Order Negotiation systems such as Siebel and Salesforce Vlocity. Future releases will implement additional TM Forum Business Operations specifications.

This asset also provides a framework for existing customers who use the Telco Pack to move CSP workloads to the Cloud. Components of this Accelerator have already been used to speed up delivery of a Proof of Concept at Saudi Telco Company.
