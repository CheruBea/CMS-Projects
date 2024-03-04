# Contract_Management


BUSINESS REQUIREMENTS DOCUMENT

PROJECT NAME: CONTRACT MANAGEMENT SYSTEM
DATE: 23rd JANUARY, 2024.











TABLE OF CONTENTS
INTRODUCTION	3
Purpose of the Document	3
Purpose of the Contract Management System(CMS)	3
Product Scope	3
Objectives	3
Benefits of the CMS	3
FUNCTIONAL REQUIREMENTS	4
NON-FUNCTIONAL REQUIREMENTS	10
INTERFACES	12
Internal Interfaces	12
User Interfaces	12
Hardware Interfaces	12
External Interfaces	12





INTRODUCTION
Purpose of the Document
This document seeks to outline the system requirements of the Contract Management System (CMS).
Purpose of the Contract Management System(CMS)
Currently, there is a challenge in tracking the contract lifecycle, increased risk of non-compliance, and lack of a centralized repository of all the contracts due to manual contract handling. The CMS will simplify and digitalize the management of the contract-making process. The CMS will allow for the production, negotiation, execution, monitoring, renewal, termination, and storage of the contracts made.
Product Scope
Objectives
Creating & Organizing contracts.
Contract status tracking.
Managing workflows.
Escalation Matrix
Data Analytics & Generating reports.
Audit trail.
Performance Monitoring.
Collaboration and communication.
Data Security and Compliance.
Integration with Other systems.
Access Control.
Benefits of the CMS
Streamlined contract lifecycle management.
Reduced non-compliance risks.
Centralized repository for all contracts.
Enhanced performance monitoring and analytics.
Improved collaboration and communication.
Increased data security and compliance.
Seamless integration with other systems.
Efficient access control and electronic signatures.
Robust backup and recovery mechanisms.
FUNCTIONAL REQUIREMENTS
Creating & Organizing contracts
The user should be able to draft and edit contracts from the contract templates.
The user should be able to upload an original contract.
Contract Status Tracking
The user should be able to track the status of the contract e.g. draft, under review & approval.
The user should get notifications for the changes in status.
Managing Workflows
The user should be able to customize workflows for the different types of contracts.
The system automates the approval processes within a stipulated time and in accordance with the Service Level Agreements (SLA).
Escalation Matrix 
The admin draws the contract using the templates provided in the system or can upload the contract as a new document which is editable. The system allows the admin to assign roles such as the reviewer and approver. 

The Admin- Draws the contract and sends it to the other party


                                              
Party B- Reads the contracts and either agrees to the terms or makes suggestion on what to be changed


The Admin- Makes the changes and returns the contract to the other party for perusal and amelioration



The Contract is forwarded to the first reviewer who receives a notification  and then it is pushed to the final approver automatically who gets a notification as well.


NOTE: In case the contract is not approved within the stipulated time, the admin is allowed to appoint a different approver or reviewer for smooth running of operations.The system can allow the contract to be escalated to the next approver in rank in accordance to SLA while providing a notification to both approvers.
Data Analytics & Generating Reports
The system will have a dashboard that is used by the business to track & monitor their performance and extract actionable insights.
The system should be able to show the contracts terminated before maturity and the reasons why
List of Reports 
Contract Register:
   - Overview of all contracts in the system.
   - Includes contract names, parties involved, contract values, and key dates.

Contract Status Report:
   - Provides the current status of each contract (e.g., active, pending, expired).
   - Highlights any contracts nearing expiration or renewal.

Contract Summary Report:
   - Concise summaries of key contract details.
   - Useful for quick reference and high-level insights.

Key Dates and Milestones:
   - Lists important dates, such as contract start and end dates, renewal dates, and key milestones.
   - Helps in proactively managing deadlines.

Financial Reports:
   - Tracks financial aspects of contracts, including budget vs. actual spending.
   - Highlights any financial risks or opportunities.

Contract Compliance Report:
   - Assesses adherence to contractual terms and conditions.
   - Identifies potential areas of non-compliance.
Vendor/Supplier Performance Report:
   - Evaluates the performance of vendors or suppliers.
   - Includes metrics such as delivery times, quality of goods or services, and adherence to SLAs.

Risk Assessment Report:
   - Identifies and assesses potential risks associated with contracts.
   - Helps in developing risk mitigation strategies.

Contract Amendments Report
   - Lists all amendments made to existing contracts.
   - Provides insights into changes in contract terms.

Audit Trail Report:
    - Records all activities and changes made within the CMS.
    - Ensures accountability and transparency in contract management.

Expiring Contracts Report:
    - Highlights contracts that are nearing expiration.
    - Facilitates timely renewal or renegotiation.

Contract Search and Retrieval Report:
    - Enables users to search for specific contracts based on various criteria.
    - Enhances accessibility and usability of the CMS.

Document Versioning Report:
    - Tracks changes and versions of contract documents.
    - Ensures users are working with the latest and approved versions.

User Activity Report
    - Monitors user activities within the CMS.
    - Useful for security and compliance purposes.

Comprehensive Contract Analysis Report:
    - Offers in-depth analysis of contract performance, risks, and opportunities.
    - Supports strategic decision-making.
Custom Reports:
    - Allows users to create ad-hoc reports based on specific criteria.
    - Enhances flexibility in reporting.
List of Dashboards 
Overview Dashboard:
   - Summarizes key metrics and highlights.
   - Provides a quick glance at the overall contract management landscape.

Financial & Performance Dashboard:
   - Visualizes financial aspects of contracts.
   - Includes budget vs. actual spending, revenue, and vendor/supplier performance.

Contract Status & Expiry Dashboard:
   - Displays the current status of all contracts.
   - Highlights active, pending, and expired contracts.
   - Focuses on contracts nearing expiration.

Key Dates & Renewal Dashboard:
   - Focuses on important contract dates and milestones.
   - Alerts users to upcoming deadlines, renewals, and amendments.

Compliance & Risk Management Dashboard:
   - Highlights compliance with contractual terms and conditions.
   - Visualizes potential risks associated with contracts.

Amendments & Document Management Dashboard:
   - Summarizes all amendments made to existing contracts.
   - Tracks document versions and changes.

User Activity & Access Dashboard:
   - Monitors and visualizes user activities within the CMS.
   - Provides an overview of user roles, access levels, and permissions.

Customization & Custom Reports Dashboard:
   - Allows users to customize their dashboard view.
   - Offers a dashboard for users to create and access custom reports.

Audit Trail & Comprehensive Analysis Dashboard:
   - Summarizes the audit trail of activities within the CMS.
   - Integrates various metrics for in-depth analysis.

Vendor/Supplier Management Dashboard:
    - Focuses on vendor/supplier performance.
    - Includes metrics like delivery times, quality, and SLA adherence.

Audit Trail
The system should be able to give detailed track of user activities.
The system should show modifications, approvals, and expirations of the contracts
Performance Monitoring
The system should show whether the parties are meeting the key performance indicators, and operating within the contracts.
Collaboration & Communication
The system will integrate with email or SMS to allow real-time communication for all users for smooth operation.
The system should have in-app communication tools to allow commenting and direct messaging.
Data Security and Compliance
The data at rest and in transit will be encrypted.
The relevant data protection regulations will be complied with.
The system will have a robust security system that will protect it from malware attacks and viruses. 
Integration with Other Systems
The system will be able to integrate with a document management system, ERP, and CRM.
The system will synchronize data with the relevant databases.
Access Control
The user should be able to create a user profile.
The system will allow for two-factor authentication.
The system will provide role-based access control.
The roles can be decided by the admin and their tasks assigned to them. For instance:
 Administrator:
   - The Administrator has overall control and access to the entire Contract Management System.
   - Responsibilities may include user management, system configuration, and defining access levels for other roles.

Contract Manager/Human Resource :
   - Contract Managers are responsible for overseeing the entire contract lifecycle.
   - They will be involved in contract creation, negotiation, approval, monitoring, and renewal processes.

Legal Counsel:
   - Legal Counsel provides legal expertise and reviews contracts to ensure compliance with laws and regulations.
   - They will participate in the negotiation process and provide advice on legal risks.

Procurement Officer:
   - Procurement Officers are responsible for managing the procurement process.
   - They will be involved in sourcing vendors, creating purchase orders, and ensuring compliance with procurement policies.

Sales Representative:
   - Sales Representatives will  be involved in the contract creation process, especially when dealing with customer contracts.
   - They will input sales-related information and negotiate terms with customers.

Finance Officer:
   - Finance Officers will handle financial aspects related to contracts, such as invoicing, payment tracking, and financial reporting.
   - They will ensure that contracts align with budgetary constraints and financial policies.
Compliance Officer:
   - Compliance Officers will ensure that contracts adhere to internal and external compliance requirements.
   - They will  monitor contracts for adherence to industry standards, regulatory requirements, and organizational policies.
Risk Manager:
   - Risk Managers assess and mitigate potential risks associated with contracts.
   - They will  identify, evaluate, and manage risks to protect the organization from legal, financial, or operational challenges.
User/Contract Requestor:
   - Users or Contract Requestors initiate the contract creation process by submitting requests for new contracts or modifications.
   - They will  provide initial contract details and context for further processing.
Auditor:
    - Auditors will  review and assess the contract management process for compliance, efficiency, and effectiveness.
    - They will  perform periodic audits to ensure that contracts are properly executed and managed.

Vendor/Supplier:
    - Vendors or Suppliers will have restricted access to view and track their contracts within the system.
    - Their access will be limited to specific contract details and relevant communication.

Executive/Management:
    - Executives or members of the management team will have high-level access to monitor overall contract performance and make strategic decisions.

Electronic Signatures
After the approval process there should be a fast way to sign and execute contracts. You can automate document management systems, electronic signatures and digital signatures with security and compliance. 

Reporting and Dashboard Customization
The users will customize reports and dashboards according to their specific needs.

Search Criteria 
The system will allow the user to search a contract using the following parameters: 
Start Date of the contract
End Date of the contract
Name of the either parties
The type of contract
Keywords such as specific clauses , phrases or words in the contract
Contract Value
Contract Status 

Integration Testing
The CMS will be tested for integration with other systems to ensure seamless interoperability.

Download of Contracts
The CMS will enable users to effortlessly retrieve and download approved and signed contracts. This user-friendly feature streamlines access to crucial documents, ensuring efficient retrieval and utilization post-approval.

User Feedback Mechanism
There will be a system for users to provide feedback on their experiences, which can be used for continuous improvement.

Backup and Recovery
The system should  ensure that the data is backed up and available in case of failure.


NON-FUNCTIONAL REQUIREMENTS
1. Simplicity
The user interface should be intuitive and user-friendly, requiring minimal training. Navigation through the system should be straightforward and easily understandable. Unnecessary complexity in terms of features and options should be avoided.

Usability
The system should be user-friendly and easy to navigate. It should have a simple and intuitive interface that requires minimal training to use.

Performance
The system should be fast and responsive, with minimal lag time between user input and system response. It should be able to handle large volumes of data without slowing down. The system will have a response time of at least 0.1 second and a fast data throughput.

Interfaces
The system should be compatible with other systems and applications, allowing for seamless integration with other tools.

Device Coverage
The system should be accessible from a wide range of devices, including desktops, laptops, tablets, and smartphones.

Security
The system should be secure, with robust authentication and authorization mechanisms in place to prevent unauthorized access to sensitive data.

Reliability
The system should be reliable, with minimal downtime and high availability. It should be able to recover quickly from any failures or errors.

Scalability
The system should be scalable, able to handle increasing volumes of data and users without compromising performance or reliability.

Availability
The system should be available 24/7, with minimal scheduled downtime for maintenance or upgrades.

Operating Systems
The system should be compatible with a wide range of operating systems, including Windows, macOS, and Linux.

Maintenance Plan
The system should be easy to maintain, with clear documentation and well-organized code that is easy to modify and update. 

Legal and Regulatory Compliance
The CMS will comply with relevant legal and regulatory requirements, ensuring that it adheres to industry standards and laws governing contract management.

Training and Support
The system will have an interactive user guide manual for users to familiarize themselves with the CMS. There will be a support platform for users encountering issues or needing assistance.

Risk Management
Proactive risk management for the Contract Management System will involve mitigating implementation, operational, compliance, integration, vendor-related, change management, and external risks. Continuous monitoring, training, and adaptability strategies ensure system resilience and success.

Disaster Recovery
The system will have a disaster recovery plan outlining how the system will recover in the event of a catastrophic failure.

INTERFACES 
Internal Interfaces

User Interfaces
Backend software: .NET
Database software: MySQL
Front-end: .NET

Hardware Interfaces
Windows, iOS, Unix and Linux 

External Interfaces
APIs: REST
Standard Email Protocols: IMAP and SMTP
Notification through SMS: Twilio APIs


