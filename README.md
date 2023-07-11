# Architecture Patterns
Version: Summer-2023
> This document describes commonly applied patterns in the context of application architecture. None of these patterns were conceptualised or created by the authors of these articles. These are common and reusable patterns identified within already functioning real-world systems and applications. This article series serves the purpose of documenting those patterns for easy reference of application architects by breaking them down to fundamentals and listing many potential combinations.

## Introduction
**Architecture patterns** provide blueprints to structure information-driven systems and applications in an easily readable, composable, modular approach. These patterns also help architects communicate ideas easier and picture previously proven solutions within the context of similar or repetitive requirements. While the significance and benefits of such patterns are well known among architects, different parties may use their own terminolgy and definitions to describe them depending on where and how they apply them. This article series is a community-driven effort to bring architects around the globe together and get their contribution to standardise and to document commonly found architectural patterns.

#### This article series is presented in two main segments.
##### 1. Fundamentals 
   * [Proxy](basic-patterns/proxy.md)
   * [Connection](basic-patterns/connection.md)
   * [Service Chaining](basic-patterns/service-chaining.md)

##### 2. Reference implementations
   * [Gateway Router](reference-implementations/README.md)

<hr/>

##### The Icon Library
The following is a library of icons that will be improved iteratively. These will be free to use in any project even for commercial purposes and the source files are also provided in SVG format.

|Icon   |Category    |Description|
|-------|:------:|----|
|<img src="icons/application.svg" alt="application icon" width="110"/>|Application| Any type of a software application that acts as a client of the services, systems, assets exposed by a provider|
|<img src="icons/connector.png" alt="connector icon" width="110"/>|Connector| An agent designed specifically to act as a [remote proxy](./basic-patterns/proxy.md) of a specific system|
|<img src="icons/legacy.svg" alt="legacy application icon" width="110"/>|Legacy Application| Typically, an existing asset that was designed to serve a certain business purpose with less (or no) focus on integration with other systems.|
|<img src="icons/proxy.svg" alt="proxy icon" width="110"/>|Proxy| An intermediary component that facades  existing assets to provide a unified interface to modern applications. Please refer to [proxy pattern](./basic-patterns/proxy.md) for further details.|
|<img src="icons/service-endpoint.svg" alt="service endpoint icon" width="110"/>|Service Endpoint| This includes all possible backend systems including but not limited to Legacy Applications, Web Services, APIs, SoR *(e.g. CRM, ERP)* and Databases.|
|<img src="icons/sor.svg" alt="sor icon" width="110"/>|SoR| System of Record (SoR) -  A data source system/platfomr that maintains the master data for a particular domain or organization|