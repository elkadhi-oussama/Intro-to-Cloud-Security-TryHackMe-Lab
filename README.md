# Intro to Cloud Security – TryHackMe

This project documents my learning from the **Intro to Cloud Security** room on TryHackMe.

The lab introduces the fundamental concepts of cloud computing and how to secure cloud environments.

Topics covered include:

- Cloud architecture
- Cloud security concepts
- Identity & Access Management
- Security policies
- Network security
- Storage security
- Disaster recovery and monitoring

---

# Task 1 – Introduction

## What is Cloud Computing?

Cloud computing means using computing services through the internet.

Companies do not need to buy physical servers or data centers.

Instead, they can use cloud services when they need them.

Examples of services:

- Storage
- Virtual machines
- Databases
- Applications

## Pay-As-You-Go Model

Cloud services use a **pay-as-you-go** model.

This means companies only pay for the resources they use.

Example:

If a company uses a server for 2 hours, it only pays for 2 hours.

---

# Task 2 – Cloud Architectural Concepts

## Cloud Characteristics

Cloud computing has several important characteristics:

### Scalability
Resources can increase or decrease depending on the needs of the organisation.

### Simplicity
Cloud services are easy to configure and use.

### Cost Effective
Companies do not need to buy expensive hardware.

### Automation
Cloud systems require less manual management.

---

## Cloud Service Models

### IaaS – Infrastructure as a Service

In this model, the **cloud provider manages the hardware infrastructure**.

Customers manage:

- Operating system
- Applications
- Software

Example services:

- Virtual machines
- Servers

---

### PaaS – Platform as a Service

In this model, the cloud provider manages:

- Infrastructure
- Operating system
- Platform

Customers only manage their applications.

---

### SaaS – Software as a Service

In this model, the cloud provider manages everything.

Users simply use the software through the internet.

Examples:

- Gmail
- Google Docs
- Microsoft 365

---

## Cloud Deployment Models

### Public Cloud

Resources are shared between many customers.

Examples:

- AWS
- Microsoft Azure

Risk:
Vendor lock-in.

---

### Private Cloud

Resources are dedicated to a single organisation.

This model provides higher security.

---

### Hybrid Cloud

Combination of **public cloud and private cloud**.

Example:

- Private cloud for sensitive data
- Public cloud for testing

---

# Task 3 – Cloud Security Concepts

## Data Classification

Data in the cloud must be classified by sensitivity.

### Confidential Data
Highly sensitive information.

Example:
Personal data or financial records.

### Internal Data
Information used inside the organisation.

### Public Data
Information available to everyone.

---

## Cloud Data Lifecycle

Data goes through several phases:

1. Create
2. Store
3. Use
4. Share
5. Archive
6. Destroy

Each phase requires security protection.

---

## Security Issues in Cloud

Some common cloud security risks include:

- Data confidentiality risks
- Insecure APIs
- Virtualisation vulnerabilities
- Malicious insiders
- Account hijacking

---

# Task 4 – Cloud Deployment Risks

Each deployment model has security risks.

## Private Cloud Risks

- Insider threats
- Natural disasters
- External attacks

---

## Public Cloud Risks

- Vendor lock-in
- Privilege escalation
- Competitors using the same infrastructure

---

## Community Cloud Risks

- Shared vulnerabilities
- Difficult policy enforcement

---

# Task 5 – Security Through Access Management

Access management ensures:

**Right user → Right permission → Right resource**

Important concepts include:

- Identities
- Roles
- Authentication factors
- Permissions

Example authentication factors:

- Password
- PIN
- Biometric
- FaceID

AWS implements access control using **IAM (Identity and Access Management)**.

---

# Task 6 – Security Through Policies

Policies define **what users are allowed or denied to do**.

Types of policies:

- Identity-based policies
- Resource-based policies
- Session policies

Policies help control access to services and resources.

Example:

Allow database access only during specific times.

---

# Task 7 – Security Through Network Management

Network security protects cloud infrastructure from attacks.

Important components include:

### Security Groups

Security groups allow specific traffic.

They work on the principle:

**Deny all unless allowed**

---

### Network ACLs

Network Access Control Lists allow both:

- Allow rules
- Deny rules

They protect the Virtual Private Cloud (VPC).

---

# Task 8 – Security Through Storage Management

Cloud storage must be secured to protect sensitive data.

Security measures include:

- Data encryption
- Role-based access
- Secure database connections
- Physical security of data centers

Example in AWS:

- Amazon S3
- Amazon RDS

---

# Task 9 – Additional Cloud Security Concepts

## Disaster Recovery

Disaster Recovery ensures systems can recover after a failure.

Types of DR:

### Cold DR
Cheapest but slowest recovery.

### Warm DR
Near real-time backups.

### Hot DR
Fast recovery but expensive.

---

## Monitoring and Logging

Cloud providers offer monitoring tools.

Examples in AWS:

- CloudTrail
- CloudWatch
- GuardDuty

These tools monitor activity and detect threats.

---

## Patch Management

Systems must be regularly updated to fix vulnerabilities.

AWS uses **Systems Manager** to manage patches.

---

# Conclusion

Cloud security includes several important areas:

- Access management
- Security policies
- Network protection
- Storage security
- Monitoring and logging

Cloud providers offer powerful tools to help organisations secure their environments.

Learning cloud security is essential for modern cybersecurity professionals.