---
title: "Introduction"
chapter: false
weight: 10
pre: "<b>1. </b>"
---

## What are Microservices?

Microservices are an architectural and organizational approach to software development where software is composed of small independent services that communicate over well-defined APIs. These services are owned by small, self-contained teams.

Microservices architectures make applications easier to scale and faster to develop, enabling innovation and accelerating time-to-market for new features.

With the accelerated shift to the cloud, enterprises are subsequently accelerating their development processes to maximize operational excellence. In order to efficiently handle customer and security needs, businesses are relying on container and serverless technologies for their scalability and cost-effectiveness when deploying and developing applications.


---

### Monolithic vs. Microservices Architecture

With monolithic architectures, all processes are tightly coupled and run as a single service. This means that if one process of the application experiences a spike in demand, the entire architecture must be scaled. Adding or improving a monolithic application’s features becomes more complex as the code base grows. This complexity limits experimentation and makes it difficult to implement new ideas. Monolithic architectures add risk for application availability because many dependent and tightly coupled processes increase the impact of a single process failure.

With a microservices architecture, an application is built as independent components that run each application process as a service. These services communicate via a well-defined interface using lightweight APIs. Services are built for business capabilities and each service performs a single function. Because they are independently run, each service can be updated, deployed, and scaled to meet demand for specific functions of an application.

![monolith](/images/introduction/monolith-break.jpg)

---- 

## What are the most prevalent security issues, and what is their impact?

#### Data Injection
**Impact:** Data injection vulnerabilities can lead to unauthorized access, data leaks, and system disruptions. Attackers can exploit these vulnerabilities to gain access to sensitive data, manipulate records, or execute malicious code within the system.

#### Vulnerable Images
**Impact:** Vulnerable container images can expose applications to a range of threats, including malware injection, data breaches, and unauthorized access. This can lead to compromised system integrity and reputation damage.

#### IAM Permissions
**Impact:** Improperly configured Identity and Access Management (IAM) permissions can result in unauthorized access to cloud resources. Attackers may gain control over critical infrastructure, compromising data security and system availability.

#### Misconfigured Cloud Resources
**Impact:** Misconfigured cloud resources can leave sensitive data exposed, disrupt services, and result in financial losses. Such misconfigurations may lead to data breaches, downtime, and compliance violations.

#### Code Review
**Impact:** Neglecting code review can result in undetected vulnerabilities, bugs, and potential exploits. Security weaknesses in code can be leveraged by attackers to compromise the system's integrity and confidentiality.

#### Unvalidated Third-party Packages
**Impact:** Using unvalidated third-party packages can introduce vulnerabilities into the application. Attackers can exploit these vulnerabilities to compromise security, steal data, or disrupt services.


---- 
