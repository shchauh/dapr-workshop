# Building cloud native appplications with Distributed Application Runtime(Dapr)

This workshop is for getting started with building microservices applications with Distributed Application Runtime(Dapr)


## Workshop Overview & Goals
Learn how to build microservices applications using dapr. We will build sample microservices which will use dapr for implementing different scenarios like service to service invocation, pub-sub, state management, secret management etc.

## Target Audience
This workshop is for software developers and architects who wants to get started with building microservices applications with dapr. 

## Dapr

Microservices applications are a kind of "ditributed application". Microservices applications are made by a number of services communicating with each other with standard APIs like http or gRpc. These services can be stateless or stateful. 
 
Dapr is a portable, event-driven runtime for building microservices applications. It helps building resilient, stateful and stateless microservices applications. Each microservice application have some common challanges like state management, service to service invocation, secret managment etc. Dapr helps to solve these common challanges and let developer focus more on building business functionality, instead of implementing common scenarios.

For more information check [Dapr overview](https://github.com/dapr/docs/tree/master/overview)


## Workshop Structure

* [Background information](https://github.com/shchauh/dapr-workshop/blob/master/background.md)
* [Installing and configuring dapr](https://github.com/shchauh/dapr-workshop/blob/master/prerequisites.md)
* [HOL 1 - Hello Dapr](https://github.com/dapr/samples/tree/master/1.hello-world)
* [HOL 2 - Implementing service to service invocation with dapr](https://github.com/shchauh/dapr-workshop/blob/master/prerequisites.md)
* [HOL 3 - Implementing pub-sub with dapr]
* [HOL 4 - Implementing a distributed calculator]

## Feedback

Please let us know if you have any feedback about this workshop. We would love to hear back from you and improve this workshop

## References
Dapr website - http://www.dapr.io

[.NET Architecture Guidance](https://dotnet.microsoft.com/learn/dotnet/architecture-guides)

[Microservices architecture e-book](https://dotnet.microsoft.com/download/e-book/microservices-architecture/pdf)
