# Azure-Project-Documentation-From-Humber-Final-Project
Documentation for Humber College IT Infrastructure Azure Final project involving high availability, scalability, and security infrastructure


## Overview
This repository contains detailed documentation for the Azure project completed for Humber College. The project involved designing and implementing a highly available, scalable, and secure cloud infrastructure using Azure services across multiple availability zones and regions. The focus was on leveraging best practices in cloud architecture, security, cost management, and governance.

### Key Project Highlights
- Regions: The project utilized Azure resources across Australia East and UK South.
- Cost Efficiency: The total project cost was maintained under $20 over a 5-day period, demonstrating effective cost management.
- Duration: The project was completed within a strict timeline of 10 days.

## Project Components

### 1. Architecture and Infrastructure
   - Hub-and-Spoke Network Topology: Implemented a hub-and-spoke network architecture to centralize shared resources and services in the hub, while isolating workloads in individual spokes.
   - Virtual Machines (VMs): Deployed multiple Azure VMs to handle different workloads, ensuring high availability and redundancy.
   - Load Balancers: Configured Azure Load Balancers to distribute incoming network traffic across multiple VMs, enhancing fault tolerance and load distribution.

### 2. Identity and Access Management
   - Azure Active Directory (AD): Implemented Azure AD to manage identities, enabling secure access control and single sign-on (SSO) for users and applications.

### 3. Networking
   - Virtual Networks (VNets): Created and configured VNets to segment the network and improve security.
   - Virtual Network Peering: Established VNet Peering between VNets in different regions (Australia East and UK South) to enable seamless communication while maintaining isolation and low latency.
   - Private Endpoints: Configured Private Endpoints to securely connect to Azure services over a private link, ensuring that traffic remains within the Azure network and does not traverse the public internet.
   - Network Security Groups (NSGs): Deployed NSGs to control traffic flow to and from network interfaces, VMs, and subnets.

### 4. Security Measures
   - Azure Security Center: Utilized Azure Security Center to monitor security status, implement security best practices, and protect against threats.
   - Advanced Threat Protection: Enabled Advanced Threat Protection to identify and respond to potential security threats.

### 5. Storage and Container Solutions
   - Azure Blob Storage: Configured Blob Storage for scalable object storage, optimizing for large-scale data storage and retrieval.
   - Azure File Storage: Implemented File Storage for file shares accessible through the SMB protocol, supporting cross-platform file storage.
   - Private Endpoints for Storage: Used Private Endpoints to access Azure Storage services securely, keeping data traffic on the Azure backbone network.
   - Azure Container Registry (ACR): Set up an Azure Container Registry to store and manage Docker container images securely within the Azure environment.
   - Azure Container Instances (ACI): Deployed containerized applications using Azure Container Instances, ensuring fast and scalable deployment of containerized workloads.

### 6. Traffic Management
   - Azure Load Balancer: Configured both public and internal load balancers to manage traffic across VMs, ensuring high availability.
   - Traffic Manager: Used Azure Traffic Manager for DNS-based traffic routing, allowing for distribution of traffic based on performance and priority across regions.

### 7. Monitoring and Management
   - Azure Monitor: Deployed Azure Monitor to track the performance and health of the deployed services, providing actionable insights.
   - Log Analytics: Configured Log Analytics for centralized log collection and analysis, aiding in troubleshooting and performance optimization.
   - Application Insights: Integrated Application Insights to monitor application performance and diagnose issues in real-time.

### 8. Backup and Recovery
   - Azure Backup: Configured Azure Backup services to protect critical data and ensure recovery in the event of data loss.
   - Recovery Services Vault: Managed the Recovery Services Vault for centralized backup management and disaster recovery planning.

### 9. Governance and Compliance
   - Resource Tagging: Enforced a tagging policy to ensure that all resources are properly tagged for efficient management, cost tracking, and governance.
   - Azure Policy: Implemented Azure Policy to enforce organizational standards and assess compliance across the Azure environment.

## Documentation
The full documentation for the Azure project, including architecture diagrams, implementation steps, and detailed screenshots, is available in the PDF file below:

- [Download Azure Project Documentation PDF](https://github.com/assaymie/Azure-Project-Documentation-From-Humber-Final-Project/blob/main/Assay%20-%20Azure%20Final%20Project.pdf)

## Additional Information
For more information or inquiries about the project, please reach out to me via GitHub or LinkedIn.

---

This project was overseen by Professor Asghar Ghori, ensuring that it met the academic and professional standards expected at Humber College.


