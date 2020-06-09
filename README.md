# Building cloud native applications with Distributed Application Runtime(Dapr)

This workshop is for getting started with building microservices applications with Distributed Application Runtime(Dapr).

- [Overview & Goals](#overview--goals)
- [Target Audience](#target-audience)
- [What you will learn during this workshop](#what-you-will-learn-during-this-workshop)
- [Dapr](#dapr)
- [Workshop Structure](#workshop-structure)
- [Next Steps](#next-steps)
- [Feedback](#feedback)
- [References](#references)


## Overview & Goals
In this workshop you will learn how to build microservices applications using Dapr. We will build sample microservices which will use Dapr for implementing different scenarios like service to service invocation, pub-sub, state management, secret management etc.

#### This workshop is:
* An introduction to Dapr and how it enables developers to build resilient, stateful and stateless microservices applications
* Build microservices application with Dapr
* Learn how to set up a development enviornment for Dapr

> We will run all samples in self hosted mode. No kubernetes installation is needed as part of this workshop, but can be considered as stretch goal

#### This workshop is NOT:
* A Kubernetes workshop
* An introduction to microservices or containers, though some [background](https://github.com/shchauh/dapr-workshop/blob/master/background.md) is provided
* A way to learn new programming languages

> Ignore the Kubernetes section of each hands-on lab

## Target Audience
This workshop is for software developers and architects who wants to get started with building microservices applications with Dapr. 

### Prior knowledge
It is expectecd to have understanding of some of the following concepts
 - Distributed systems
 - Microservices architecture
 
 Working knowledge of 
 - Visual Studio Code or Visual Studio
 - Docker and containers
 
## What you will learn during this workshop
- Learn about Dapr
- Setup a development environment for using Dapr (self-hosted mode)
- Implement different scenarios like state management, service to service invocation, pub-sub, distributed tracing.

## Dapr
Microservices applications are a type of "distributed systems". Microservices applications are composed of a number of small services communicating with each other with standerd protocols like http or gRPC over well defined interfaces. These services can be stateless or stateful. 
 
Dapr is a portable, event-driven runtime for building microservices applications. It helps building resilient, stateful and stateless microservices applications. Each microservice application have some common challanges like state management, service to service invocation, pub-sub, secret managment etc. Dapr helps to solve these common challanges and let developer focus on building business functionality, instead of implementing common scenarios for microservices applications.

Dapr can be run either in self-hosted or Kubernetes modes. Running dapr runtime in self-hosted mode enables you to develop dapr applications in your local development environment and then deploy and run them in other supported environments. For example, you can develop Dapr applications in self-hosted mode and then deploy them to any Kubernetes cluster.

For more information check [Dapr overview](https://github.com/dapr/docs/tree/master/overview)

## Workshop Structure

> Ignore the Kubernetes section of each HOL. 

* [Prerequisites](https://github.com/shchauh/dapr-workshop/blob/master/prerequisites.md)
* [Source code](https://github.com/shchauh/dapr-workshop/blob/master/source-code.md)
* [HOL 1 - Hello Dapr - Implementing state management and service-service invocation](https://github.com/dapr/samples/tree/master/1.hello-world)   
* [HOL 2 - Implement distributed tracing](https://github.com/dapr/docs/blob/master/howto/diagnose-with-tracing/zipkin.md)
* [HOL 3 - Implementing pub-sub](https://github.com/dapr/samples/tree/master/4.pub-sub)
* [HOL 4 - Implementing a distributed calculator](https://github.com/dapr/samples/tree/master/3.distributed-calculator)

## Next Steps
- Learn more about Dapr at [dapr.io](dapr.io)
- Try out more samples [here](https://github.com/dapr/samples)
- Try .Net Dapr SDK [here](https://github.com/dapr/dotnet-sdk)
- [HOL 5 - ASP.NET core samples ](https://github.com/dapr/dotnet-sdk/tree/master/samples)

## Feedback

Please let us know if you have any feedback about this workshop. We would love to hear back from you and improve this workshop

## References
- Dapr website - http://www.dapr.io
- Get involved with Dapr community [here](https://aka.ms/dapr-community)
- [.NET Architecture Guidance](https://dotnet.microsoft.com/learn/dotnet/architecture-guides)
- [Microservices architecture e-book](https://dotnet.microsoft.com/download/e-book/microservices-architecture/pdf)
