# Building cloud native applications with Distributed Application Runtime(Dapr)

This workshop is for getting started with building microservices applications with Distributed Application Runtime(Dapr). You can check more about dapr at [dapr.io](https://dapr.io/)

## Overview & Goals
Learn how to build microservices applications using dapr. We will build sample microservices which will use dapr for implementing different scenarios like service to service invocation, pub-sub, state management, secret management etc.

#### This workshop is:
* An introduction to Dapr and how it enables developers to build resilient, stateful and stateless microservices applications
* Build microservices application with Dapr

#### This workshop is not:
* A Kubernetes workshop
* An introduction to microservices or containers, though some [background](https://github.com/shchauh/dapr-workshop/blob/master/background.md) is provided
* A way to learn new programming languages


## Target Audience
This workshop is for software developers and architects who wants to get started with building microservices applications with dapr. 

## Prerequites
It is expectecd to have understanding of some of the following concepts
 - Distributed systems
 - Microservices architecture
 
 Working knowledge of 
 - Visual studio code or visual studio
 - Docker and containers
 

## Dapr

Microservices applications are a type of a "ditributed applications". Microservices applications are composed of a number of small services communicating with each other with standerd protocols like http or gRpc over well defined interfaces. These services can be stateless or stateful. 
 
Dapr is a portable, event-driven runtime for building microservices applications. It helps building resilient, stateful and stateless microservices applications. Each microservice application have some common challanges like state management, service to service invocation, secret managment etc. Dapr helps to solve these common challanges and let developer focus more on building business functionality, instead of implementing common scenarios.

For more information check [Dapr overview](https://github.com/dapr/docs/tree/master/overview)


## Workshop Structure

* [Cloud Native Applications](https://github.com/shchauh/dapr-workshop/blob/master/background.md)
* [Setup](https://github.com/shchauh/dapr-workshop/blob/master/prerequisites.md)
* [Source code](https://github.com/shchauh/dapr-workshop/blob/master/source-code.md)
* [HOL 1 - Hello Dapr](https://github.com/dapr/samples/tree/master/1.hello-world)
     * HOL 1.1 - State management 
     * HOL 1.2 - Service to service invocation
* [HOL 2 - Implementing pub-sub with dapr](https://github.com/dapr/samples/tree/master/4.pub-sub)
* [HOL 3 - Implementing a distributed calculator](https://github.com/dapr/samples/tree/master/3.distributed-calculator)
* [HOL 4 - Implement distributed tracing on HOL 3(https://github.com/dapr/docs/blob/master/howto/diagnose-with-tracing/zipkin.md)

## What you have learned ??
- What is Dapr and how to use it

## Feedback

Please let us know if you have any feedback about this workshop. We would love to hear back from you and improve this workshop

## References
Dapr website - http://www.dapr.io

[.NET Architecture Guidance](https://dotnet.microsoft.com/learn/dotnet/architecture-guides)

[Microservices architecture e-book](https://dotnet.microsoft.com/download/e-book/microservices-architecture/pdf)
