---
layout: default
title: Overview
nav_order: 2
has_children: false
permalink: /docs/overview
---
## Why?
When planning & delivering OpenShift to deployment environments we typically think 
in terms of installing to standard [Public Cloud] providers such as IBM, Amazon AWS,
Microsoft Azure, etc. We may also look at private cloud platforms such as vmware,
openstack, or even bare metal. Delivery within the standard paradigm includes
access to public internet services & dependency artifact resources.

We may choose "[Installer Provisioned Infrastructure]" (IPI) or "[User Provisioned
Infrastructure]" (UPI) where the former is an opinionated all in one delivery mechanism 
that provisions and configures infrastructure and the latter provides more
flexibility by deploying OpenShift to User provisioned & configured
infrastructure at the cost of more deployment and lifecycle user responsibility.

Sparta delivers an alternate opinionated 'IPI' like OpenShift delivery
experience with restricted target environment support exposed by wrapping the
UPI process in an ecosystem of UPI delivery tooling.

## How?
Sparta leverages containerized runtimes for executing [Infrastructure as Code] (IAC)
automation plugins & opinionated enforcement of artifact collection and delivery 

[Public Cloud]:https://www.redhat.com/en/topics/cloud-computing/what-is-public-cloud
[Installer Provisioned Infrastructure]:https://github.com/openshift/installer#supported-platforms
[User Provisioned Infrastructure]:https://github.com/openshift/installer#supported-platforms
[IaC]:https://www.ibm.com/cloud/learn/infrastructure-as-code
[Infrastructure as Code]:https://www.ibm.com/cloud/learn/infrastructure-as-code

### Architecture Diagram
![Diagram](./web/sparta.png)

### [Bundle Creation Demo:](https://asciinema.org/a/BFb4Hq4h9q4tsNllfRT9K5OWC)
[![asciicast](https://asciinema.org/a/BFb4Hq4h9q4tsNllfRT9K5OWC.png)](https://asciinema.org/a/BFb4Hq4h9q4tsNllfRT9K5OWC)

{: .fs-6 .fw-300 }