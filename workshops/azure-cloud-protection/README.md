## Welcome

Welcome to the Prisma Cloud Azure workshop! Prisma™ Cloud is the most comprehensive cloud security solution availableon the market today with capabilities ranging from Cloud Security Posture Management (CSPM); Cloud Workload Protection (CWP);  Cloud Infrastructure Entitlement Management (CIEM) and Cloud Network Security (CNS). It provides comprehensive visibility and threat detection across your organization’s hybrid, multi-cloud environment (Azure, AWS, GCP, Alibaba, Oracle Cloud, Kubernetes). 

![readme-prisma](./images/readme-prisma.png)

This workshop was created as a walkthrough for an in person or virtual workshop, however you may feel free to run through at your own pace.

### Pre-requisites

* An Azure Subscription
  * This can be any Azure subscription where you have the owner role assignment. We will also be performing some actions in Azure AD and other services that may require the Application Administrator or Global Administrator level of access on the tenant level.

* A Prisma Cloud Enterprise Account
  * Prisma Cloud will be used to protect your Azure environment and services
* An Azure DevOps Organization
* A JIRA Account
* A GitHub Account

>* The [first module](modules/0-prerequisites.md) contains instructions on setting up the required accounts but you can also use existing accounts that you may have.
### Agenda

The workshop is designed to take approximately 5-6 hours to complete. It can be spread out over a 1 day or 2 days workshop.

|    | Module                   | Format       |
|----|--------------------------|--------------|
| 00 | [Setup Pre-Requisites](modules/0-prerequisites.md)                         | Hands on Lab |
| 01 | [Prepare Your Azure Environment](modules/1-prepare-the-environment.md) | Hands on Lab |
| 02 | [Onboard Azure Subscription to Prisma Cloud](modules/2-onboard-azure-sub.md) | Hands on Lab |
| 03 | [Onboard Azure AD to Prisma Cloud](modules/3-onboard-azure-ad.md)                | Hands on Lab |
| 04 | [Configure JIRA integration in Prisma Cloud](modules/4-jira-integration.md) | Hands on Lab |
| 05 | [Remediate Security Risks and Compliance Violations with Prisma Cloud](modules/6-respond-and-remediate.md)  | Hands on Lab |
| 06 | [Enable auto-remediation and verify](modules/7-configure-auto-remediation.md) | Hands on Lab |
| 07 | Implement IaC scanning    | Hands on Lab |
| 08 | Wrap / Clean Up     | Hands on Lab |
----

[Next](full/1-create-aro-cluster.md)