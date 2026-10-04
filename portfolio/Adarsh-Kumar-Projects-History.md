---
name: Project History for Adarsh Kumar
description: Detailed software engineering project records for resume generation and role-specific tailoring.
---

# Software Engineering Project History

Use this document to capture project-level details.

## JPMorgan India Services

### Feb 2025 to Present
- Grade: 603
- Location: Pune, India

#### Project 1: Loyalty Promo Management
- Project type / product domain:
  - Promotional offer management
  - Banking-card loyalty and travel booking
- Business problem and intended users:
  - Surface relevant promotions to eligible card customers during booking
  - Enable business teams to manage offers and review usage
  - Scale: 20+ million users
- Main features:
  - Create and manage promotions, and assign or provision offers according to card-customer eligibility.
  - Display eligible offers based on booking itinerary attributes.
  - Reissue promotions after order cancellation.
  - Report on promotion usage to support executive decision-making.
- My role, ownership, and team:
  - Role: Lead architect / engineering leader
  - Delivery scope, decision authority, team size, and partner teams: Confirm
- Solution, architecture, and key engineering decisions:
  - .NET microservices using REST and event-driven integrations
  - AWS Lambda, S3, batch processing, SQS, and Kafka
  - Asynchronous processing for offer provisioning and lifecycle events
  - Eligibility-rule source, event guarantees, and service boundaries: Confirm
- Technology stack:
  - Languages / frameworks: C#, .NET 8/10
  - Cloud / compute: AWS Lambda, S3, EKS
  - Data / messaging / APIs: Batch jobs, SQS, Kafka, REST
  - Delivery / observability / collaboration: GitHub, Jenkins, Kibana, Grafana, Copilot, Jira, Confluence, Kanban
- Security, testing, deployment, and operations:
  - Deployment: EKS
  - Security scanning: Snyk
  - Testing: xUnit
- Challenges and trade-offs:
  - Maintain consistent eligibility decisions across offer assignment, itinerary evaluation, cancellation, and reissue flows.
  - Balance timely offer updates and accurate reporting against asynchronous processing and duplicate or out-of-order events.
- Outcomes and evidence:
  - Intended outcome: Improve offer relevance and automate offer lifecycle handling
  - Reporting: Provide promotion-usage insights
  - Metrics to confirm: Adoption, transaction volume, reliability, and business impact
- Resume-ready achievement:
  - Architected a card-loyalty promotion service
  - Capabilities: Eligibility-based offer provisioning, itinerary-aware display, cancellation reissue, and executive usage reporting

#### Project 2: AWS Cloud Migration
- Project type / product domain:
  - Cloud migration
  - Enterprise application platform onboarding
- Business problem and intended users:
  - Move existing AWS-hosted applications to the Chase cloud platform
  - Meet Chase security and CI/CD standards
  - Maintain service continuity for application users
- Main features:
  - Migrate existing AWS applications to the Chase cloud platform.
  - Update application modules to meet Chase security and CI/CD requirements.
  - Plan and execute migration to target zero downtime.
- My role, ownership, and team:
  - Role: Lead architect / engineering leader
  - Applications owned, hands-on contribution, team composition, and stakeholder groups: Confirm
- Solution, architecture, and key engineering decisions:
  - Assess and update .NET services and AWS components for the target platform
  - Use Terraform and the required CI/CD pipeline
  - Plan staged deployment and workload transition to target zero downtime
  - Cutover and rollback strategy: Confirm
- Technology stack:
  - Languages / frameworks: C#, .NET 8/10
  - Cloud / compute: AWS Lambda, S3, ECS, EKS
  - Data / messaging / APIs: Batch jobs, SQS, Kafka, REST
  - Delivery / observability / collaboration: GitHub, Jenkins, Terraform, Kibana, Grafana, Copilot, Jira, Confluence, Kanban
- Security, testing, deployment, and operations:
  - Target platform: EKS
  - Security and CI/CD controls: Chase platform requirements
- Challenges and trade-offs:
  - Meet zero-downtime migration goals while handling deployment, configuration, and data differences between the existing AWS environment and the target cloud platform.
  - Balance migration speed with required security and CI/CD changes, minimizing unnecessary application changes while ensuring the new platform's standards are met.
- Outcomes and evidence:
  - Target outcome: Migrate applications to the Chase cloud platform with required controls and no service interruption
  - Metrics to confirm: Application count, downtime, security findings, and delivery lead time
- Resume-ready achievement:
  - Led migration of [number] AWS applications to the Chase cloud platform
  - Aligned services with security and CI/CD standards
  - Verified downtime / delivery outcome: [Add]

### Feb 2022 to Jan 2025
- Grade: 602
- Location: Pune, India

#### Project 1: Site Reliability Engineering
- Project type / product domain:
  - Site reliability engineering
  - Application observability for services on AWS EKS
- Business problem and intended users:
  - Give engineering and operations teams timely visibility into application health
  - Provide actionable signals for diagnosing service issues
- Main features:
  - Configure application monitoring and alerting.
  - Build Grafana dashboards to support service observability.
- My role, ownership, and team:
  - Role: Engineering lead / architect for observability improvements
  - Alert and dashboard ownership, participating teams, and operational stakeholders: Confirm
- Solution, architecture, and key engineering decisions:
  - Configure application monitoring, alerts, Grafana dashboards, and Kibana views on EKS
  - Select service-level indicators, alert thresholds, and operational dashboard views
  - Telemetry sources and escalation workflow: Confirm
- Technology stack:
  - Cloud / orchestration: AWS EKS
  - Observability: Grafana, Kibana, monitoring and alerting
- Security, testing, deployment, and operations:
  - Runtime platform: AWS EKS
  - Security controls and testing approach: Confirm
- Challenges and trade-offs:
  - Tune alerts to identify actionable service issues without creating excessive noise or alert fatigue.
  - Balance dashboard detail and diagnostic value against metric volume, cardinality, and ongoing maintenance.
- Outcomes and evidence:
  - Intended outcome: Improve issue detection and diagnosis
  - Metrics to confirm: Alert-noise reduction, detection / recovery times, service coverage, and incident trends
- Resume-ready achievement:
  - Improved observability for [number / type] of EKS-hosted services
  - Delivered: Application alerts and Grafana dashboards
  - Verified operational impact: [Add]

#### Project 2: Legacy Travel Engine Cloud Modernization
- Project type / product domain:
  - Legacy application modernization
  - Travel booking platform
- Business problem and intended users:
  - Move a travel-engine monolith from a private data center to AWS
  - Modernize services to support maintainability and scalability
  - Preserve service continuity for travel users and dependent systems
- Main features:
  - Migrate the legacy monolithic application from a private data center to AWS.
  - Modernize legacy services into microservices within a distributed architecture.
- My role, ownership, and team:
  - Role: Lead architect / engineering lead
  - Architecture ownership, delivery responsibilities, team size, and partner-system owners: Confirm
- Solution, architecture, and key engineering decisions:
  - Modernize the .NET application into cloud-hosted microservices
  - Candidate technologies: AWS, EKS, REST, Kafka, and SQS
  - Identify service boundaries and migrate incrementally to preserve existing behavior
  - Confirm which listed technologies were used in this project
- Technology stack:
  - Languages / frameworks: C#, .NET 8/10
  - Cloud / compute: AWS Lambda, S3, EKS
  - Data / messaging / APIs: Batch jobs, SQS, Kafka, REST
  - Delivery / observability / collaboration: GitHub, Jenkins, Kibana, Grafana, Copilot, Kanban
- Security, testing, deployment, and operations:
  - Runtime platform: EKS
  - Security and testing approach: Confirm
- Challenges and trade-offs:
  - Decompose a legacy monolith while preserving existing behavior and continuity for dependent systems.
  - Choose service boundaries and migration stages that allow incremental delivery without introducing excessive distributed-system complexity.
- Outcomes and evidence:
  - Intended outcome: Move the travel engine to AWS and reduce dependence on the private data center
  - Engineering outcome: Improve service modularity
  - Metrics to confirm: Migration scope, availability, performance, and cost results
- Resume-ready achievement:
  - Led modernization of a legacy travel-engine monolith from a private data center to AWS microservices
  - Designed and developed custom migration utility to automate migration of the legacy data to modern database saving ~450 SP effort

### July 2016 - Jan 2022
- Grade: 602
- Location: Pune, India

#### Project 1: Asset Configuration & Inventory Management System
- Project type / product domain:
  - Enterprise asset management
  - Configuration management
- Business problem and intended users:
  - Users: Employees and asset / IT operations teams
  - Need: Track hardware, software, configurations, provisioning, and physical-asset charges
- Main features:
  - Record and manage software, hardware, and configuration assets.
  - Provision and deprovision software on employee laptops.
  - Support physical-asset billing and reporting.
- My role, ownership, and team:
  - Role: Software architect / engineering lead
  - Specific component ownership, team size, and security / compliance partners: Confirm
- Solution, architecture, and key engineering decisions:
  - .NET / ASP.NET application for asset records and configuration data
  - Provisioning workflows, billing, and reporting
  - Hosting: IIS / Windows Server
  - Data sources, integrations, authorization model, and workflow design: Confirm
- Technology stack:
  - Languages / frameworks: C#, ASP.NET 4.x
  - Source control / collaboration: SVN, Bitbucket, Jira, Confluence
- Security, testing, deployment, and operations:
  - Hosting: IIS, Windows Server
  - Security controls and testing approach: Confirm
- Challenges and trade-offs:
  - Keep asset records accurate across software, hardware, configuration, and billing information, including changes from multiple systems or teams.
  - Balance flexible asset and provisioning workflows with consistent controls, traceability, and reliable handling of partial failures.
- Outcomes and evidence:
  - Intended outcome: Centralize asset visibility
  - Supported capabilities: Controlled software provisioning and physical-asset billing
  - Metrics to confirm: Asset / user scale, provisioning time, reconciliation accuracy, and operational savings
- Resume-ready achievement:
  - Delivered an enterprise asset and configuration management system
  - Capabilities: Hardware / software inventory, employee software provisioning, and physical-asset billing
  - Verified scale and impact: [Add]

#### Project 2: VDI Tools
- Project type / product domain:
  - Virtual desktop infrastructure
  - Employee provisioning automation
- Business problem and intended users:
  - Users: IT operations and employees
  - Need: Provision / retire employee virtual machines and manage software access through onboarding and offboarding
- Main features:
  - Provision virtual machines and manage employee onboarding and offboarding.
  - Provision and deprovision software on employee virtual machines.
- My role, ownership, and team:
  - Role: Software architect / engineering lead
  - Direct ownership, team composition, and service-management partners: Confirm
- Solution, architecture, and key engineering decisions:
  - VM lifecycle and software provisioning workflows
  - Integration with employee onboarding / offboarding
  - Virtualization platform, identity / access integrations, automation, and failure recovery: Confirm
- Technology stack:
  - Languages / frameworks, infrastructure, data, and tooling: Confirm
- Security, testing, deployment, and operations:
  - Security, test strategy, and runtime platform: Confirm
- Challenges and trade-offs:
  - Coordinate VM and software provisioning with employee onboarding and offboarding so that access and resources are applied or removed at the right time.
  - Balance provisioning speed and user experience with capacity constraints, policy compliance, and recovery from failed or delayed operations.
- Outcomes and evidence:
  - Intended outcome: More consistent employee VM and software access
  - Operational outcome: Reduce manual IT tasks
  - Metrics to confirm: Provisioning volume, turnaround time, and access-removal compliance
- Resume-ready achievement:
  - Designed VDI workflows for employee VM lifecycle and software provisioning
  - Supported onboarding and offboarding
  - Worked on security & compliance issues at year end with tight schedule for multiple project which saved the organization from financial and reputational damage.

#### Project 2: Application Compute Cloud
- Project type / product domain:
  - Internal application compute platform
  - Virtual-machine orchestration
- Business problem and intended users:
  - Users: Application teams or other internal users
  - Need: Managed VM cartridges and sessions, usable workflows, and operational / business reports
- Main features:
  - Orchestrate virtual-machine cartridges and sessions.
  - Manage virtual-machine workflows to support performance and usability.
  - Generate reports using multiple business criteria.
- My role, ownership, and team:
  - Role: Software architect / engineering lead
  - Platform components owned, team size, and consumer groups: Confirm
- Solution, architecture, and key engineering decisions:
  - Orchestrate VM cartridge and session lifecycles through workflow services
  - Provide reporting across business criteria
  - Compute / virtualization platform, workflow engine, capacity controls, and reporting data sources: Confirm
- Technology stack:
  - Languages / frameworks, infrastructure, data, and tooling: Confirm
- Security, testing, deployment, and operations:
  - Security, test strategy, and runtime platform: Confirm
- Challenges and trade-offs:
  - Coordinate VM cartridge and session workflows while maintaining responsive performance and a usable experience under varying demand.
  - Balance utilization and throughput against session isolation, resource availability, and the consistency of business reporting.
- Outcomes and evidence:
  - Intended outcome: Standardize VM / session management
  - Reporting: Provide business-oriented views
  - Metrics to confirm: Workload scale, provisioning time, utilization, and service quality
- Resume-ready achievement:
  - Designed application-compute workflows for VM cartridge and session orchestration
  - Added reporting across business criteria
  - Trained developers at Hyderabad Hub level for Cyber Security to ensure that they design & develop secure applications from start
  - Ensured the uninterrupted flow of business critical operations. Identified the application bottlenecks and reduced the error rate from 82% to 8% by optimizing the solution and applying best coding practices.

## NISC Export Services

### Aug 2014 to June 2016

#### Project 1: E Publishing Host
- Project type / product domain:
  - Enterprise digital publishing
  - Multi-tenant content delivery platform
- Business problem and intended users:
  - Users: Publishers and readers
  - Need: Discover, access, and receive updates about relevant articles
- Main features:
  - Search published articles and filter results by full text or peer-reviewed status.
  - Sort search results by date or relevance.
  - Create alerts for search terms and email results to the user or others.
  - Retrieve full-text articles in HTML or PDF.
- My role, ownership, and team:
  - Role: Senior software engineer
  - Contributions: Backend and React UI
  - Feature ownership, team composition, and publishing-stakeholder collaboration: Confirm
- Solution, architecture, and key engineering decisions:
  - ASP.NET and REST services supporting multiple tenants
  - React micro-frontend
  - Article search, filtering, full-text retrieval, and email alerts
  - Search / indexing technology and tenant isolation: Confirm
- Technology stack:
  - Languages / frameworks: C#, ASP.NET, ADO.NET, Entity Framework, ReactJS, JavaScript
  - APIs / architecture: REST APIs, micro-frontends
  - Versions and infrastructure: Confirm
- Security, testing, deployment, and operations:
  - Security, test strategy, and runtime platform: Confirm
- Challenges and trade-offs:
  - Support tenant-specific publishing needs while preserving tenant isolation and maintainability in a shared platform.
  - Balance search relevance and response time with content volume, full-text access, and dependable alert delivery without duplicate or missed notifications.
- Outcomes and evidence:
  - Profile notes: Improved maintainability, developer productivity, customer engagement, and responsiveness
  - Metrics to confirm: Users, tenants, engagement, and delivery outcomes
- Resume-ready achievement:
  - Built backend and React micro-frontend capabilities for a multi-tenant publishing portal
  - Delivered: Article search, full-text access, and email alerts
  - Worked on development of custom UI framework based on ReactJs reusable components
  - Designed & implemented Alert Systems for customers to make the application more valuable increasing its popularity resulting into increasing revenue

## Tavisca Solutions

### Apr 2013 to Aug 2014

#### Project 1: Rovia Travel Portal
- Project type / product domain:
  - Multi-tenant travel portal
- Business problem and intended users:
  - Users: Travelers across multiple client brands
  - Need: Book air, car, hotel, and cruise through a shared multi-tenant solution
- Main features:
  - Provide branded, configurable, multi-tenant portals for booking air, car, hotel, and cruise travel.
  - Compare travel deals across multiple vendors.
  - Process payments and track outcomes, including failed transactions that require compensation.
- My role, ownership, and team:
  - Role: Software engineer
  - Contributions: Portal backend and frontend development
  - Feature ownership and team composition: Confirm
- Solution, architecture, and key engineering decisions:
  - Configurable multi-tenant travel portal
  - Shared portal components support client branding
  - Vendor comparison and payment-status handling support booking
  - Payment and compensation design: Confirm
- Technology stack:
  - Languages / frameworks: C#, ASP.NET 4.x, Entity Framework, Backbone.js
  - Data / caching / monitoring: SQL Server, Redis Cache, New Relic
- Security, testing, deployment, and operations:
  - Hosting: IIS, Windows Server
  - Security and test approach: Confirm
- Challenges and trade-offs:
  - Normalize different supplier offerings and availability data while keeping travel comparisons timely and accurate across tenants.
  - Balance portal customization and shared-component reuse, and ensure payment retries or failures do not create inconsistent transaction outcomes.
- Outcomes and evidence:
  - Profile notes: Improved speed, scalability, user experience, and customer-facing flow reliability
  - Metrics to confirm: Booking volume, response time, conversion, and transaction reliability
- Resume-ready achievement:
  - Developed backend and frontend features for a configurable multi-tenant travel portal
  - Enabled branded air, car, hotel, and cruise bookings with vendor comparison and payment tracking
  - Designed & developed Payment module and did payment gateway integration
  - Re-designed Authentication/Authorization system to make it faster and enable to handle tens of thousands concurrent requests. It enabled clients to register a huge number of users during Boot Camp without any technical issue, resulting in good profit.

#### Project 2: Hotel Content Downloader
- Project type / product domain:
  - Travel
  - Hotel content aggregation
- Business problem and intended users:
  - Need: Download hotel content from multiple suppliers
  - Processing: Clean and aggregate supplier records
- Main features:
  - Download hotel content from multiple suppliers.
  - Clean, process, and aggregate supplier records.
  - Run content processing concurrently using the Task Parallel Library.
- My role, ownership, and team:
  - Role: Software engineer
  - Ownership: Hotel content processing module
  - Team composition and supplier coordination: Confirm
- Solution, architecture, and key engineering decisions:
  - Scheduled Windows Service downloads supplier feeds
  - Cleans and aggregates hotel records
  - Uses .NET Task Parallel Library concurrency
  - Deduplication, validation, retry, and persistence mechanisms: Confirm
- Technology stack:
  - Languages / frameworks: C#, .NET, Task Parallel Library
  - Runtime / scheduling: Windows Services, Scheduled Tasks
  - Framework version and storage / integration technologies: Confirm
- Security, testing, deployment, and operations:
  - Runtime / scheduling: Windows Services, Scheduled Tasks
  - Security and test approach: Confirm
- Challenges and trade-offs:
  - Process large supplier feeds with inconsistent formats and data quality while keeping aggregated hotel content accurate and current.
  - Balance concurrency and throughput against memory use, supplier limits, and safe recovery from failed or partially processed feeds.
- Outcomes and evidence:
  - Processing time: Reduced from 11 hours to 3.5 hours
  - Measurement scope and comparison period: Confirm
- Resume-ready achievement:
  - Owned and parallelized hotel content processing across supplier feeds
  - Reduced processing time from 11 hours to 3.5 hours
  - Developed the Multithreaded Hotel Content Downloader & Parser which resulted in 10 times faster download of the content from third party content providers


## Harbinger Systems

### Jan 2010 to Mar 2013

#### Project 1: Answer Source Interactive
- Project type / product domain:
  - Answer Source Interactive
  - Enwisen HR portal
- Business problem and intended users:
  - Users: HR managers
  - Need: Manage employee onboarding, offboarding, and related workflows
- Main features:
  - Support HR workflows for employee onboarding and offboarding.
  - Generate configurable, role-aware UI content from XML templates using XSLT.
  - Parse content to support application globalization and localization.
  - Manage user-group-role assignments through business rules.
- My role, ownership, and team:
  - Role: Software engineer
  - Contributions: Backend development, configurable UI generation, localization parsing, and user-group-role assignment
  - Team composition and ownership boundaries: Confirm
- Solution, architecture, and key engineering decisions:
  - Multi-tenant HR portal built with ASP.NET and ADO.NET
  - XML-configured templates transformed into dynamic HTML using XSLT
  - Parser supports globalization and localization
  - Business rules drive user-group-role assignments
  - Authorization and template-validation designs: Confirm
- Technology stack:
  - Languages / frameworks: C#, ASP.NET 4.x, ADO.NET, Ext JS
  - UI / configuration: XML, XSLT
  - Data / source control: SQL Server, SVN
  - Other: Globalization, localization
- Security, testing, deployment, and operations:
  - Testing: NUnit
  - Hosting: Windows Server, IIS
- Challenges and trade-offs:
  - Support configurable, role-aware pages and localization without making XML/XSLT templates and parsing rules difficult to validate or maintain.
  - Preserve correct user-group-role assignments at scale while balancing processing efficiency with authorization accuracy and workflow flexibility.
- Outcomes and evidence: 
  - User-group-role assignment: Reduced processing for thousands of users from approximately 14 hours to 3 hours
  - Measurement period and workload: Confirm
  - Other intended outcomes: Configurable UI and localization support
- Resume-ready achievement:
  - Developed backend and configurable XSLT-based UI capabilities for a multi-tenant HR portal, including XML parsing for globalization and localization.
  - Redesigned business-rule-based user-group-role assignment for thousands of users, reducing processing time from approximately 14 hours to 3 hours.
  - Developed UI Framework to Generate Dynamic HTML Content from configurable XML files by applying XSLT supporting multiple UI templates
  - Developed Parser to parse the XML content and enable Globalization/Localization for application framework
  - Redesigned the business rules based user-group-role assignment to reduce the processing time for thousands of users from around 14 hours to 3 hours
