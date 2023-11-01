https://medium.com/design-microservices-architecture-with-patterns/microservices-deployments-with-containers-and-orchestrators-c693292997f9

Microservices Deployments with Containers and Orchestrators
Mehmet Ozkaya
Design Microservices Architecture with Patterns & Principles
Mehmet Ozkaya




In this article, we are going to discuss Microservices Deployments with Containers and Orchestrators. As you know that we learned practices and patterns about Microservices Design patterns and add them into our design toolbox. And we will use these pattern and practices when designing e-commerce microservice architecture.


By the end of the article, you will learn how to deploy microservices in Microservices Architectures with applying Microservices patterns and principles.

Step by Step Design Architectures w/ Course

I have just published a new course — Design Microservices Architecture with Patterns & Principles.

In this course, we’re going to learn how to Design Microservices Architecture with using Design Patterns, Principles and the Best Practices. We will start with designing Monolithic to Event-Driven Microservices step by step and together using the right architecture design patterns and techniques.

Microservices Deployments with Containers and Orchestrators
Containers and orchestrators are very important when deploying microservices and they solve monolithic deployment problems. When we are deploying monolithic applications, they have deployed as a single unit and deploy whole application in one time.
So this will caused temporarily un-available time of application and if it has any defect that needs to rollback the whole deployment process. Also scaling is have to apply for the whole monolithic application, we can’t split modules and scale independently.


So these are the deployment problems which solved in microservices architecture with Containers and Orchestrators. Containers provide to decouple applications with their own os, dependencies and libraries. Also run applications on any system. This is perfect match to microservices deployments because containers isolate the applications.

With containers, microservices can deployed separately in a container. Each microservice can deploy independently with containers. Also its possible to scale independently, since we have deployed microservices separate container, these containers can scale as per their volume of traffics. And you don’t need to deploy whole application at once, with containers changes can be applied independently while other container stay not changed.

New features can be applied and rollback very easy with container deployments. Docker is defacto standart for containerization of microservices.

Microservices Orchestrators
In microservices architectures, containers need to orchestrate in order to manage lots of container in your application cluster. Orchestrators automates the deployment, scaling, and operational concerns of containerized workloads across clusters.


Kubernetes is defacto standart for orchestration of microservices.

Docker and Container
Docker is an open platform for developing, shipping, and running applications. Docker provides to separate your applications from your infrastructure so you can deliver software quickly.

Advantages of Docker’s methodologies for shipping, testing, and deploying code quickly, you can significantly reduce the delay between writing code and running it in production.

Docker provides for automating the deployment of applications as portable, self-sufficient containers that can run on the cloud or on-premises. Docker containers can run anywhere, in your local computer to the cloud. Docker image containers can run natively on Linux and Windows.

What is Kubernetes ?
Kubernetes (also known as k8s or “kube”) is an open source container orchestration platform that automates many of the manual processes involved in deploying, managing, and scaling containerized applications.

Kubernetes is a portable, extensible, open-source platform for managing containerized workloads and services, that facilitates both declarative configuration and automation. It has a large, rapidly growing ecosystem. Kubernetes services, support, and tools are widely available.

You can cluster together groups of hosts running Linux® containers, and Kubernetes helps you easily and efficiently manage those clusters.

Design the Architecture — Microservices Deployments with Containers and Orchestrators
We are going to design our e-commerce application with the Microservices Deployments with Containers and Orchestrators. We will iterate the architecture design one by one as per requirements.

Its good to add principles in our picture in order to remember them always.
Principles
— Containerization
— Orchestration

We are going to consider these principles when design our architecture.


Now lets decide to Technology Stack in this architecture.

Of course we should pick Docker for containerization and K8s for orchestration. These are the defacto standards of microservices deployments.

As you can see that we have designed our e-commerce microservices architecture with all aspects of design principles and patterns. Now you can ready to design your own architectures with these learning and know how to use these patterns toolbox in your designs.

So we should evolve our architecture with applying other Microservices Data Patterns in order to accommodate business adaptations faster time-to-market and handle larger requests.

Step by Step Design Architectures w/ Course

I have just published a new course — Design Microservices Architecture with Patterns & Principles.

In this course, we’re going to learn how to Design Microservices Architecture with using Design Patterns, Principles and the Best Practices. We will start with designing Monolithic to Event-Driven Microservices step by step and together using the right architecture design patterns and techniques.
