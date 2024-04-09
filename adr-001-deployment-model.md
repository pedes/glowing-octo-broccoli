# ADR 001: Choosing Deployment Model for Mule Applications

## Context

Acme Insurance is in the process of deploying a new set of mule applications, aimed at providing new services to their customers, for system IT standardization. 
The organization requires scalability, high availability, ease of deployment, fast time to market and less IT operational effort in deployment to being able to release 
new applications into market.

## Decision

Our decision was driven by several key considerations:

- Rapid Development and Deployment: Cloudhub 2.0 provides out-of-the-box features for deploying and scaling mule applications quickly. This accelerates our time to market, a crucial factor for the success of our application.
- Reduced Operational Overhead: By abstracting away the underlying infrastructure, CH 2.0 allows our team to focus on application development without worrying about system or software maintenance. This significantly reduces our operational burden.
- Scalability: The selected iPaaS (Cloudhub 2.0) solution offers seamless scalability, allowing us to easily adjust resources to match demand without downtime or performance degradation. This is critical for handling peak loads and growing user bases.
- Cost-Effectiveness: With iPaaS (Cloudhub 2.0), and the UBP licensing we pay only for what we use, which optimizes our costs, especially compared to the significant upfront investment required for on-premise deployment and the ongoing costs associated with managing IaaS.

## Status

Accepted

## Consequences

- Vendor Lock-in: Choosing Cloudhub 2.0 and MuleSoft as the provider introduces a degree of vendor lock-in, potentially making it challenging to migrate to another service in the future.
- Customization Limitations: While iPaaS (Cloudhub 2.0) offers significant advantages in terms of speed and simplicity, it may limit our ability to customize the underlying infrastructure or software stack to our exact needs.

## Related documents

[List any related documents, such as requirements or design documents, that influenced the decision.]
