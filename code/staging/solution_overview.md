# Accelerator Solution Overview

![Order Management](img/solution-overview.png)

- The TM Forum APIs are exposed through API Connect and DataPower
- Routing and data transformation implemented in IBM App Connect for Enterprise (ACE).
- IBM Event Streams manages order history, in-flight order events and notifications
- Sterling Order Management pipelines are used for Order state management
- Order decomposition and execution build plan decision system is provided by IBM Operation Decision Manager (ODM)

As a realization of the Hybrid Reference Architecture, this asset implements an end-to-end Order Management process of a telco Communications Service Provider. Applications such as the Product Catalog, Order Management System, Database and Messaging, run in isolated Kubernetes deployments and can reside in the Provider or Private Cloud. The external API Gateway serves TMF Open APIs to omni-channel consumers and provides the necessary security and governance. Data transformation and routing are handled by App Connect Enterprise.

Order Management process events are exposed through a Hub/Listener event model. Topics in Event Streams listens to events generated during the execution of the order process which are then forwarded to an analytics engine to provide insights and dashboards.

Other components like Order Management pipelines for Sterling Order Management, decomposition rules for ODM, TMF OPen API mapping templates, pre-built data transformation and routing logic all serve to accelerate customer implementations.