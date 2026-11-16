---
unique-name: rfqdealerxtechnicalappendix
display-name: RFQ DealerX Technical Appendix
category: GENERAL
description: The uncertain and changing situation the Stellantis Group is living, as a global car manufacturer, is an opportunity to promote and adopt new tools based on data, digital solutions & Lean/Agile method
---

RFQ

Technical Appendix

DealerX Portal

Objective of the document / Summary

This document describes the Functional and Technical Specifications of the DealerX Sales Portal to build from scratch.

TABLE OF CONTENTS

- 1 General presentation 2
- 1.1 General Description 3
- 1.2 Strategic Approach 4
- 1.3 Perimeter of needs 5
- 1.4 Where are we now? 6
- 2 Business Glossary 7
- 3 Functional needs 8
- 3.1 Introduction 9
- 3.2 “High level” features of the Platform 9
- 3.3 User/Business requirements 9
- 3.3.1 Brief 9
- 3.3.2 Proof of Value structure 10
- 3.3.3 Focus on the main modules/needs 11
- 4 Technical requirements 15
- 4.3.1 Development framework 16
- 4.3.2 Stellantis Dealer and Repairer master data interface 16
- 4.3.3 Dealer and HQ access (Single Sign on) 16
- 4.3.4 Search engine 16
- 4.3.5 Back-office users & user roles 17
- 4.3.6 KPI and Analytics 18
- 4.3.7 Integration Layer 19
- 4.3.8 DevSecOps & DealerX SDK concept 19
- 4.3.9 Ticketing tools 21
- 4.2 Onboarding phase 21
- 4.2.1 Parts and services Use Cases 22
- 5 Non-functional requirements 23
- 5.1 DICT / AICT 24
- 5.2 Data Availability 24
- 5.3 Observability 24
- 5.4 Geographical coverage 24
- 5.5 Users 25
- 5.6 Data Privacy 25
- 5.7 Project and Service Language 25
- 5.8 Execution report 25
- 5.9 Project plan 25
- 5.10 Security Attachment 26
- 6 Appendix for Integrators 26
- 6.1 Platforms to be used for the solutions proposal 27
- 6.2 Expected feedback 27
- 6.3 SLAs 29

# 1 General presentation

## 1.1 General Description

The uncertain and changing situation the Stellantis Group is living, as a global car manufacturer, is an opportunity to promote and adopt new tools based on data, digital solutions & Lean/Agile methodologies at a Stellantis level. With constantly evolving and competitive markets and optimizing resources, it is also necessary to review how we animate our networks to be more efficient.

That is why, we are pursuing its transformation and launch a project which purpose is to change the way we collectively work. At the same time, Stellantis wants to strengthen the relationship between the brands and their network via a community platform called Business Community.

The main target of the new Digital backbone is to allow synergies, simplification and efficiency through a unique platform for dealers and field force with personalized contents to know very quickly what you need to know and what you have to do. Thus, this platform aims to replace existing tools and functionalities, which are today duplicate for several brands and countries.

This new version of DealerX platform will be at the same time a business social network, which will allow top-down and bottom-up communications and a digital workplace, which will improve the efficiency of the Stellantis Network Operations.

To improve the productivity and the user experience, the provider will have to work on 3 pillars:

- 1. ONLY ONE TOOL
- For all profiles & all activities (one user may also mix several profile & activities) to access all the process
- With Contents, Social interactions, Documentation, Ticketing and Application bookmark (incl. Single Sign on)
- Visualization & Personalization according to the profile (Adapt content to user & to management level).
- Authorization to contents and documents managed centrally.
- Enabling “Dealer&Repairer SDK” concept to allow Continuous Integration and Delivery of Applications / Features proposed to End users. Allowing them to have “AppStore like” experience customizing as deep as required by local context.
- Replace fragmented communication portals with one common DealerX experience.
- 2. TO SIMPLIFY DAILY LIFE
- Assist Stellantis network in their daily tasks.
- Display customized information and functionalities.
- Deliver the messages at the right person, at the right time.
- Make all processes accessible from one single portal.
- Make processes faster and more robust.
- Provide a flexible platform for dealer-facing features across business units
- 3. USE FULL POWER OF DIGITAL
- Get quick answers to problems.
- Allow the rapid creation of contents link to users ‘issues.
- Improve the collaboration through social communication tools.
- Integrate different technologies to harmonize processes.
- Agentic AI implementation
- AI Driven DevOps

## 1.2 Strategic Approach

Linked to process improvement and internal reorganization, the Digital Platform will be an enabler of the collective transformation and will boost the business performance.

The new strategy is built on:

- A New digital interface: Common entry point for all actors (Central, NSC, Field Staff, Business coaches (BC), Dealers, Importers) which allows direct access to different information and processes (Access to applications, Useful Contents, Social communication, Ticket creation, Documentation, Harmonized user journey...)
- A Multi activities and multi brands approach for the Business coach.

The purpose of this tender is to select one or more partners capable of supporting the Stellantis Group in the evolution and enhancement of the current DealerX platform, enabling its rollout across multiple countries within the Enlarged Europe region and supporting the Group’s strategic objectives.

Partner(s) is/are expected to demonstrate how their proposed solution meets Stellantis business and technical requirements, aligns with the target vision for the platform, and provides a scalable and sustainable foundation for future growth. In addition, bidders shall demonstrate their capability to deliver and manage the program in close collaboration with Stellantis teams, including their proposed delivery methodology, governance model, organizational structure, and the skills and experience of the proposed resources.

A key requirement of the target solution is the adoption of a reusable SDK-based approach that supports the development of portable features, facilitates reuse across markets and business domains, and enables long-term transferability and maintainability of the platform.

The current DealerX platform should be considered the baseline for the proposed solution. Providers are not expected to replace the platform from scratch; instead, they are encouraged to leverage and enhance existing capabilities wherever appropriate. Where the current architecture, processes, or components do not meet target requirements or industry's best practices, Partner(s) may propose improvements or alternative approaches. Any recommended architectural evolution, modernization activities, or platform enhancement initiatives should be clearly described within the tender response, including associated effort estimates, resource requirements, dependencies, and budget implications.

The quality of all the documents and work produced by the Provider in the pre-selection phase are fundamental.

The Requirements we have put down are not exclusive of any improvements and additional features that the Provider may propose.

The project and partnership between Stellantis and the tender will be based on agile methodology, with content co-construction, MVPs, iterations, feedbacks and adaptation: workshops on the field with main actors will be paramount.

A Planning milestone proposal is detailed here below which remains an estimation which could be reviewed by Stellantis, as well as any content of this RFQ.

RFQ timeline

From RFQ issue to awarding to end of roll out including deliverables

| By 8 Oct 2026 | By 15 Oct 2026 | By 20 Oct 2026 | By 27 Oct 2026 | By 4 Nov 2026 | By 13 Nov 2026 |
|---|---|---|---|---|---|
| 01 | 02 | 03 | 04 | 05 | 06 |
| RFQ issue | RFQ questions<br>deadline | Webinar with<br>bidders | Proof of Value<br>delivery & pitch | RFQ answer<br>deadline | RFQ awarding |

[Immagine]

## 1.3 Perimeter of needs

The implementation of this future tool will be for all Stellantis Brands, all activities and all the markets from Enlarged Europe, including Importers inside EE) .

Digital platform shall manage a complex matrix organization of several users’ communities (internal & external of the group) linked to hierarchical & functional organizations: outlets, groups or outlets, projects, areas, countries (in country language), dealers & users, single brand, dealers & users multi brand, single/multi activities, different maturity levels.

To do so:

- Portal will be displaying Content, Applications, Documentation, Social interactions, Ticket cases, based on the user profile (Country, Brand, type of profile, etc..). It must be possible for the user to modify his settings to highlight dominant posts rather than others. Allowing flexibility as well to the local context and diversity.
- From the user’s perspective, it must be possible to find each content very easily through the search engine. It must allow a word search on content, comments, users and file attachments and inside different part of the content (title, body of the content, text, video…)
- Contents recommendations must also be proposed according to the searches performed.
- View restrictions must also be possible.
- Access to the tool should be made using the STELLANTIS user IDs.
- The Portal must be fully integrated within the Stellantis IT landscape, as well as also with 3rd parties ecosystems.
- Meet all legal and regulatory requirements in the countries/regions the user is located
- AI Driven DevOps

Administration of DealerX will be managed by central team, with support from the supplier, but delegation to local or functional teams will be possible to increase the appropriation by end-users. Granting Dev flexibility and autonomy to leverage SDK concept and integrate specific “widget”/promotion/etc… for specific national event.

DealerX will have to adapt to market evolutions and stay agile.

## 1.4 Where are we now?

Existing Platform and Strategic Direction

The vision, principles, and strategic direction described throughout this document represent the foundation upon which the future portal ecosystem shall evolve. These elements define the long-term objectives, key architectural pillars, and overall approach that must remain central throughout the implementation and subsequent evolution of the solution.

However, it is important to emphasize that a platform already exists today and is currently operational. Therefore, the scope of this initiative is not the development of a completely new platform from scratch, but rather the design, implementation, and industrialization of the new portal experience, including all required functionalities, widgets, services, integrations, and user-facing features.

While the existing platform provides a solid foundation, it should not be considered immutable. Suppliers are expected to review the current landscape and identify opportunities for continuous improvement, optimization, and enhancement wherever these can generate measurable business value.

A key aspect of the initiative is the fact that the backend platform is already shared across multiple business solutions and portals within the ecosystem, including the Single Repairer Portal (SRP). This approach enables consistency, scalability, and operational efficiency across multiple services and user journeys.

Platform Reusability as a Core Requirement

One of the primary objectives of this RFQ is to maximize platform reusability and accelerate future service adoption.

The target vision is based on the following principles:

- High component reusability, targeting approximately 80% reuse of platform capabilities across current and future portals.
- Standardized services and shared business capabilities that can support multiple use cases with minimal customization.
- Scalable architecture capable of supporting the progressive onboarding of additional services and business domains.
- Reduced implementation time and lower total cost of ownership through the reuse of existing assets and components.
- Evolution towards a service marketplace approach, where new services and functionalities can be rapidly integrated and made available to users through a common platform.

Existing Capabilities Already Available

Several key capabilities have already been implemented and are available within the current platform, including but not limited to:

- User notifications and alert management.
- Mass email campaigns triggered by the publication of new content or communications.
- Integration with external systems through Single Sign-On (SSO) mechanisms.
- Configuration and personalization of news and content carousels.
- Content management capabilities for FAQs and knowledge-base sections.
- Existing content publishing and administration functionalities.
- Core platform services and backend components already leveraged by other portals within the ecosystem.

Supplier Expectations

For clarity, Stellantis does not expect the selected Supplier to replace or rebuild existing capabilities where these are already available and fit for purpose.

Instead, the Supplier shall:

- Leverage the existing platform as the primary foundation.
- Maximize reuse of available functionalities and shared services.
- Identify gaps and implement the additional capabilities required by the target vision.
- Enhance, optimize, and industrialize the solution where necessary.
- Deliver a fully operational, scalable, and future-ready portal that can support business growth and the onboarding of new services over time.

Ultimately, the objective is to capitalize on the investments already made, accelerate delivery through reuse, and transform the existing platform into a robust and extensible ecosystem capable of supporting a growing portfolio of digital services.

[Immagine]

# 2 Business Glossary

- AFS: After sales
- AI: Artificial intelligence
- AR: Authorized Repairer – also used the word “dealer”
- Assigned stock: Vehicle owned by a dealer
- BC: Business Coach
- « Blocking Incident» means any absence of function, non-compliance of the Deliverables with the Technical and Functional Specifications and/or with the Documentation, causing indifferently the complete or partial unavailability of an essential function of a Deliverables and/or a problem of consistency and / or integrity of the Data.
- CEC : Customer Engagement Center
- DMS: Dealer Management System
- « DICT or AICT» : The AICT of an application or an infrastructure service corresponds to the evaluation of the criteria Availability Integrity Confidentiality Traceability for this application or infrastructure service.
- EE: Enlarged Europe
- KPI : Key Performance Indicator
- « Minor Incident» mean all effect altering the operation pf the Deliverable, all degradation or any non-conformity of the Deliverables, but does not prevent the normal use of the Deliverable.
- « Major Incident » means any absence of function, non-compliance of the Deliverables with the Technical and Functional Specifications and/or with the Documentation, any error, bug, hidden defect or malfunction, any discrepancy or inadequacy of performance with the Technical and Functional Specifications and/or with the business best practices.
- NSC: National Sales Company
- NV: New Vehicle
- PR: Spare Parts
- UC: Used Car
- UI: User Interface (Series of screens, pages & visual)
- VIN: Vehicle Identification Number
- PSA: Part of Stellantis Group responsible for the following Brands: Peugeot, Citroen, Opel, Vauxhall and DS
- FCA: Part of Stellantis Group responsible for the following Brands: Fiat, Fiat Professional, Alfa Romeo, Lancia, Abarth, Jeep, Chrysler, Dodge, Ram

Other Stellantis Brands: MOPAR, Eurorepar Car Service, Free2Move, Leasys, Spoticar, and several others

# 3 Functional needs

## 3.1 Introduction

To be clear on the need of Stellantis, working sessions have been performed, in order to provide here:

- Elements and explanations of Business, End User and ICT needs.
- Target tool’s mindset/way of working.
- Assessment criteria which are key for Stellantis; to select the best tool but as well.

## 3.2 “High level” features of the Platform

The tool is an essential point of access to network animation.

- Access to the tool should be made using the STELLANTIS user IDs. A link to the new portal tool will be included in other Stellantis main activity portals (Service Box, Service Box Muti brand, C1ST, Link Entry, and to 3’rd party vendor applications.
- For a better User eXperience, SSO connectivity is the target. A user should not have to retype user and password to access from/within this portal to other Stellantis tools that are SSO enabled.
- The tool/interface needs to support responsive design, enabling the users any device experience.
- The tool needs to be accessible anytime.
- Multilingual: The tool must be available in the language of all the countries. The user will have the tool and therefore the texts translated into his mother tongue by default but can decide to change it if necessary.
- Content audience targeting and view.

To quickly adapt to changes in the market and needs, the tool and its development must remain agile.

It will provide a quick access to general and most up-to-date information through a homepage and will then allow to deep dive through specific tabs and accurate contents.

## 3.3 User/Business requirements

It will be the same Platform for the dealers, corporate staff, and people in charge to animate them but with different features according to the profile.

The solution should offer a smooth and pleasant navigation system.

These following elements describe End User and Business requirements that Stellantis is awaiting from the tool.

### 3.3.1 Brief

To ensure the best UX possible, we should expose One Door URL concept which (by authenticating the user) is setting up a Homepage based on the Roles of the user, with relevant and customized content.

Each user may have different needs; thus this homepage can be fully personalized for a better experience of the user:

- Position/content of the element can be changed.
- Tools/applications can be added in widgets.
- Etc.

Access to different sections of the tool must be possible with one click, regardless of the page displayed.

When necessary, a vertical scrolling system to access the various elements of the displayed page can be set up. In case of vertical scrolling, a button to go back to the top of the page must be present. Also, with corporations owning dealer groups we will require the capability for the dealer user to toggle between ‘allowed’ dealer entities / Dealer id’s.

Whatever the page, it must be possible to return to the home page and this possibility must be visible (dedicated button)

Except for the home page, a system for returning to the previous page must be in place (dedicated button)

[Immagine]

### 3.3.2 Proof of Value structure

#### 3.3.2.1 PoV Context & RFQ Impacts

This RFQ includes a Proof of Value (PoV) phase based on the platform technology proposed by the Supplier.

The Supplier shall prepare and deliver a PoV within a one-month timeframe, demonstrating the proposed solution against the business use cases defined by Stellantis.

The primary objective is to enable Stellantis to assess how effectively the proposed platform technology addresses its business and technical requirements, while demonstrating its ability to accelerate digital solution delivery through a flexible, scalable, and maintainable architecture.

As part of the PoV activities, the Supplier shall review the current Stellantis environment and provide recommendations to ensure that the proposed platform can support easy and flexible software integration, while effectively meeting current and future business requirements.

The Supplier shall provide the necessary development framework components and integration approach to demonstrate the ease, flexibility, and effectiveness of adopting the proposed solution within the Stellantis ecosystem. The PoV should clearly highlight the added value of the platform capabilities when applied to real business scenarios.

The PoV shall be delivered as a real, operational portal rather than as a conceptual presentation, wireframe, or static prototype. Suppliers may adopt the architecture they deem most appropriate for the demonstration;

however, the solution must be fully accessible, interactive, and navigable, enabling Stellantis stakeholders to actively explore, test, and evaluate its features and user experience.

The PoV must provide both a technical and visual demonstration of the platform capabilities. It should showcase user journeys, business functionalities, integration opportunities, and overall user experience, while evidencing how the platform supports the identified use cases.

The PoV should be sufficiently detailed to demonstrate the value, flexibility, and capabilities of the proposed platform, while avoiding extensive custom development efforts. The focus should be on illustrating the platform's native capabilities and its suitability for Stellantis needs.

The outcomes of the PoV will support Stellantis in selecting the most suitable platform technology. Following the technology selection, which will be formally communicated to the Suppliers, the final RFQ response shall be submitted accordingly.

All PoV activities, deliverables, and related efforts shall be provided free of charge and are intended solely for evaluation purposes. The PoV solution and deliverables are not intended for production use or deployment as the target platform.

.

### 3.3.3 Focus on the main modules/needs

#### 3.3.3.1 Application Bookmark (incl. Single Sign On)

This new platform will allow Stellantis to deliver an All-in-One Portal integrating as smooth as possible applications / features/ widgets in there to allow perfectly clear UI/UX.

In order to allow dealers to easily find the different applications that Stellantis provide them to perform their daily activities, the dealer portal will include an application bookmark section where dealer and Stellantis users will find links to these applications.

The applications proposed to the user should be configurable by Stellantis and based on the user profile.

The portal should allow for single sign on access to these applications, to prevent the need for the users to enter multiple times their user and password, in the case that these applications are also including the single sign on capability.

#### 3.3.3.2 Content (NEWS)

##### 3.3.3.2.1 Golden rules

To add as much value as possible, we need to rethink the way we share information.

Thanks to quality contents, DealerX shall help Stellantis to manage simultaneously, on a tailor-made basis for the end-user, and automatically the steps of Change Management like:

- Kick-Off: launch of a new car or a new project on transversal approach
- Set-up: know-how on vehicle and services, adoption of processes & tools to improve the performance of the dealer
- Sustainment: ensuring long-term engagement, continuous learning, and ongoing support for services, programs, and business initiatives to maximize value realization and operational effectiveness.

In addition, the proposed platform should demonstrate the following strategic capabilities:

- Reusability by Design: the solution shall maximize the reuse of components, templates, content assets, integrations, and development artifacts across multiple business initiatives, brands, markets, and user journeys, reducing implementation effort and total cost of ownership.
- AI-Driven DevOps: the platform should leverage Artificial Intelligence capabilities to enhance development, testing, deployment, monitoring, and operational activities, improving productivity, quality, release velocity, and overall platform governance.
- Seamless Integration with Business-Critical Applications: the solution shall provide robust and scalable integration capabilities with Stellantis core enterprise systems and business-critical applications, ensuring efficient data exchange, process orchestration, and a connected digital ecosystem.
- Best-in-Class Content Management System (CMS): the platform shall provide advanced content management capabilities, including content authoring, governance, workflow management, personalization, multi-channel publishing, localization support, and content reuse, enabling business teams to manage and distribute content efficiently with minimal IT dependency.

The proposed solution should clearly demonstrate how these capabilities contribute to faster business adoption, improved operational efficiency, enhanced user experience, and long-term platform scalability.

Stellantis will provide strategic inputs on a very regular basis (daily, weekly, or monthly depending on the timeline and sensitivity). Stellantis will provide the goal to be aimed and the items / assets.

With the material and goals, the Platform and the Provider shall support Stellantis in the following tasks:

- Propose marketing strategies adapted to context, brand, perimeter by using all functionalities of the Global Dealer Dev Tool. Those strategies will be aligned on the capacity of Stellantis entities, the maturity of the targets etc.
- Deploy this strategy through the Global Dealer Dev Tool
- Monitor & measure the impact of this deployment and strategy by performing regular return of experience and by applying a strong tagging plan for all posts

The platform should allow for easy upload and management of contents with attractive look and feel to allow the following features:

  - Easy to understand / straight to the point : main information in 2 lines
  - Easy to find: centralize at the same place with a powerful search engine (on the content basis),
  - Classification of contents by Brand / Country / theme / project (generic sense) / keywords.
- Personalized according to the priorities of the activity and to the performance
- Notifications + highlight on main priorities
- Help to improve business: better knowledge and better knowhow

It should drive behaviour:

  - Contents is linked to user profile and preferences
  - Every user gets the attention on what they need to know, based on Stellantis published content

##### 3.3.3.2.2 Contents management

Content Management shall be based on Adobe Experience Manager (AEM), which is already implemented and actively used across other corporate portals. The existing Adobe-based architecture and toolset should be considered the current baseline for the solution, ensuring consistency, reuse of established capabilities, and alignment with the Stellantis digital ecosystem.

Suppliers are expected to leverage the existing AEM platform and architecture as the starting point for their proposed solution. However, the current architecture should not be considered an inflexible requirement.

Where the proposed use cases would benefit from alternative approaches, architectural enhancements, optimizations, or recommendations may be proposed, provided that they clearly demonstrate added value, improved scalability, maintainability, integration capabilities, or business benefits. Stellantis remains open to evaluating architecture improvements as part of the overall proposal.

The proposed solution shall support business-user autonomy in content management activities. In particular, the availability of intuitive authoring capabilities, including support for the Adobe Universal Editor or equivalent functionality, is considered a key requirement to enable distributed content creation and maintenance by business users without reliance on centralized development or support teams.

Suppliers should adopt modern development principles and best practices, focusing on component reusability, platform alignment, standardization, scalability, and AI-driven development capabilities. Rather than adhering to predefined control rules, proposals should demonstrate how the solution promotes efficient delivery, long-term maintainability, and the ability to evolve in line with future business and technology requirements.

Any proposed enhancements, evolutions, or changes should therefore balance compliance with the existing platform foundation and the ability to introduce innovative improvements that further strengthen the overall digital experience and operational efficiency.

The Creation:

  - Created locally or centrally at a region level but accessible for all the NSC, Corporate Staff, ICT, Business folks and additional users base with no added cost. Both ICT and Business / Corporate staff / NSC have access/capability to modify content.
  - Creator is free to choose the language of the content and this content should be easily or automatically translate in other languages to be able to publish the same contents in multiple countries.
  - The content editor is already pre-configured to help respect the overall layout and graphic style of the portal
  - All kind of supports can be published on the platform: article, videos, PDF, PPT, Excel, Word, HTML, photo gallery, external links
  - Use Universal Editor needs to be a must. Business users should be autonomous

The Publishing:

  - Full Autonomy of Stellantis for publishing & editing contents
  - Possible delegation of communication rights to animators (local, internal, or external)
  - The recipients of the publications can be chosen:
    - According to the profile: brands, business community, dealers, functions, project
  - The content can be saved at different stage:
    - As a draft, to see what it would like without being visible for the community
    - Save and posted: immediately visible on the platform
    - Save and delay: only visible in the future at a date specified by the user
  - Interaction with the content is possible:
    - Ability to comment
    - Ability to share
    - Ability to like or vote

The follow up:

  - Monitoring of the contents should be possible thanks to reports
  - Linked to the most frequent search in the search engine and the content with the most social interaction, the provider will recommend new contents to create.

#### 3.3.3.3 Documentation (File Repository)

Dealers will be able to find a structure repository of documentation that they will be able to view online or download.

The access to find and view the documents will be based on the user profile parameters.

##### 3.3.3.3.1 File Volumes and file types

The solution should allow for big files like high-definition images and videos to be uploaded and downloaded.

It should not be constraint in terms of scalability of content volumes to hundreds of Terabytes of data,

A preview of the content must be available for the final customer.

The provider has to describe how the big file management will be managed, what is the technical solution has to put in place, what are the licence needed, in case of an external repository the supplier has to provide a high level estimation of external costs (using price list).

#### 3.3.3.4 Ticketing Solution (Dealer Case/Inquiries/Claims)

Whenever Dealers will not find within the portal or in the application behind the answer to what they are looking for, the portal should allow the dealer to be able to open a case or ticket where the dealer will ask for support to Stellantis teams.

The solution should allow the creation of different type of tickets, including specific forms, with different type of fields. It also should allow the possibility to attach files to the tickets, both by the dealers or by Stellantis users, to help on the understanding and resolution of the problem that trigger the creation of the ticket.

The ticketing capabilities of the tool should be able to be ingested by Stellantis made solution but being as well fully operational and integrated with ServiceNow ticketing solutions, which will be the target Stellantis solution for ticketing.

The solution should integrate with DIGITALME system to support the creation of tickets in Sales business processes. The ability for the user to create/update/view the tickets in DigitalMe. The tool should automatically collect the context of the page the user is in and include the details in the ticket. The user should have the ability to create the tickets from within the Portal.

The solution should allow for an easy management of the ticket queue, including bulk modification features, possibility to download information on the tickets, reassignment of ticket, and reporting tools to understand different KPIs associated to the creation and response of the tickets.

The solution should allow the easy integration with external sources to be able to import useful data to be used in the ticket creation or management (i.e: import applicable commercial campaign in the case of a dealer incentive claim, or the dealer order portfolio for the creation of a ticket related to problems in the delivery of one of the vehicles ordered by a dealer) or for other use cases (e.g. to support aftersales parts ordering).

Additionally moving from a session to another, it’s important that the solution keeps the main data (eg VIN, customer info, etc) to smooth the user navigation and avoid retyping data.

#### 3.3.3.5 Social Interactions

The solution should allow for users to interact easily between them, empowering the community of dealers and Stellantis users to help each other, and stay connected.

##### 3.3.3.5.1 Forum

The solution should optionally allow any user (Dealer, Stellantis NSCs, Central users), to interact, that will be visible by the applicable community of that user (based on user profile parameters, like country, brand, etc..), and will allow for other users to react.

The main purpose of this feature is not only to allow a Bottom-up communication, from dealers to Stellantis, but also to create the feeling of being part of an Stellantis community, where any part of the community could share views, help each other, and talk openly.

Nevertheless, this forum should allow Stellantis Community management users to apply restrictions to the interactions in case users make an abusive use of this forum.

[Immagine]

##### 3.3.3.5.2 Comments and feedback on content

The solution should also allow the comments of all users on the content that is being shared and published by Stellantis, either in the form of News or also in other formats like knowledge articles visible through ticket deflection and Self-help, and Documentation uploaded to the portal.

# 4 Technical requirements

### 4.3.1 Development framework

The solution will be the entry point to connect all back-office functions exposed via Integration Layer supporting dealer and repairer business: since the current landscape foresees a wide variety of applications, framework integration capabilities are customize the connection and ensure a smooth transition is needed. This development framework should be accessible to multi-providers and ensure the SW robustness of the platform. It will allow continuous integration and delivery (leveraging Stellantis DevSecOps chain tools). The concept is to enhance and extend a “DealerX SDK” where any Integrator/ IT Dev would be able to smoothly build and implement features for the portal. We currently use multiple environments, namely, Dev, Test, Stage and Prod. The solution should allow for the applications to utilize standard style sheet and common components.

Standard Stellantis Development Guidelines are provided in the ‘Development_Standards_Stellantis.pdf’ available with this RFQ.

### 4.3.2 Stellantis Dealer and Repairer master data interface

Dealer masterdata is handled in specific Stellantis applications: a daily interface has been used to keep the dealer master data up to date. Stellantis has previously used ARCAD and WEBDAC as sources of dealer master data, and from December 2026 the new Stellantis Network Referential (SNR) will be the primary source of dealer master data.

### 4.3.3 Dealer and HQ access (Single Sign on)

The user authentication and profiling solution is already in place and validated for Dealerx platform. It will be the same across all EE Region.

The Stellantis Group has decided to move to the exFCA solution to authenticate and authorize the Stellantis dealers:

- Stellantis PingFed for user authentication (+ MFA for HQ users)
- Mypeople application for user authorization (profile management)

### 4.3.4 Search engine

From the user’s perspective, it must be possible to find each content very easily through the search engine. It must allow a word search on content, comments, users and file attachments and inside different part of the content (title, body of the content, text, picture and video). Search tool should incorporate AI to generate meaningful search results based on the context, as well as “assistance companion chatbot” capabilities.

The search feature automatically takes into account the view permission in phase of proposition results.

This allow the search engine to be completely configured and customized to address any kind of needs, and specifically:

- Personalize search results based on user profile
- Apply and combine any type of filters
- Customize scoring to boost specific items (i.e: most red articles)
- Enrich search results with recommendations

Some users will have direct access to and easy search inside:

  - Tools and applications
  - News
  - Documentation
  - Ticket creation

Seamless connection to other tools:

  - IMPORTANT allow connection to new STELLANTIS apps and tools, in a transparent way for end-user to increase end-users experience depending on needs (interface with LMS, Quality Portal, CRM, ERP, self-evaluation tools, Service box, MyMarque etc.)
  - Access to these other applications will depend on the applicative services associated with the user profiles. The tool should not manage the access rights to other applications, but should allow for the applications to be displayed/highlighted based on the user profile
  - Connections to 3’rd party or externally hosted applications need to be through Single Sign on and does not require the dealer (repairer) to provide a second logon / id.

Some other users will have additional access as:

  - Content management system ( to create/upload content, articles, etc..)
    - Including Bulk upload of content/articles
  - Upload of Documentation
    - Including bulk upload of documents
  - Community management
    - To allow management of social interactions
  - Ticketing admin/fulfiller module
    - To be able to manage and respond to dealer tickets, reassign them within Stellantis or to external teams.

Reduce non-productive time:

  - Simple workflow
  - Personalize contents
  - Easy reuse of contents
  - Automatic translation of contents
  - Easy management of dealer social interactions
  - Fast and easy response to dealer tickets/cases/inquiries
  - Notifications

Audit

  - Reports of most common search criteria
  - Reports for tickets
  - Reports for Most read articles
  - Reports of most downloaded or viewed documents

### 4.3.5 Back-office users & user roles

The Provider Back-Office solution comes with a standard user management framework to handle a multitude of users and roles.

- Access: A user from a specific user group can access the feature or not
- View only: A user from a specific user group has ‘view only’ mode
- Modify: A user from a specific user group has ‘modify’ mode

The access can also be restricted per feature or per functionality inside the platform.

Lists of user groups will be managed during set-up phase as well as the back office. There is no limitation on the number of groups that can be created, and user groups can be fully defined by Stellantis and brand teams.

The platform is flexible enough to cater for all levels of visibility – from brand specific users (e.g. Vauxhall UK) to market groups (e.g. PCD UK, OV UK, FCA UK) to global views and access (e.g. Stellantis Global).

Back-office user access will be also able to restrict by the following dimensions:

- Brand
- Country

There will also be a Super Admin User who will be able to manage functionality across those brand/country dimensions.

A System Administrator will be able to create a user with a permission to only access content management for a specific brand in a specific country or the user will be able to manage contents for a specific brand.

[Immagine]

Due to the fact that the Digital platform shall manage a complex matrix organization of several users communities from different brands and activities, user should be able to choose his dominant profile on the platform. So that, he will be targeted with only the contents linked to his dominant profile.

For some regions, there may be a need for ‘super admin’ the capability to ‘impersonate a user’. That is the ability to logon as that user to see what that user is seeing on the screen.

### 4.3.6 KPI and Analytics

The Global DealerX Dev Platform must have an analytics integration with necessary Analytics tools already widely used in Stellantis (as PowerBI FOR DASHBOARDS, Foundry, etc.) as well as ensuring page tagging which will allow to track overall navigation, sales and conversion performances by country/dealers/sales and aftersales categories. Each page should have the same data collection to get a unified analytics system to include DynaTrace and other technologies as appropriate.

### 4.3.7 Integration Layer

The application must be able to integrate with backoffice applications through an integration layer supporting sync and async data exchange, batch file, API and webservices.

New Platform should be able to support complex API integration capability to ensure the flow between Platform and Legacy App backends is fluent and robust.

Here below you can find STELLANTIS API topology & consumer guidelines, with additional elements to be shared if required. The core documentation associated with API, Integration and Data Platform usage within Stellantis is available here: [API, Integration and Data Platforms](https://shiftup.sharepoint.com/sites/COEAPI/SitePages/Home.aspx)

[Immagine]

### 4.3.8 DevSecOps & DealerX SDK concept

As previously shared, Stellantis is having a DevSecOps toolchain and requirements to leverage and respect.

DevOps chain should be the way to continuously deliver and maintain the portals product, ensuring flexible and easy integration of new features /components/ widgets into portals with no bottlenecks.

DevSecOps chain architecture in a nutshell is presented on the drawing below as well as requirements for the usage:

[Immagine]

The core documentation associated with Dev Ops and Dev Sec Ops in Stellantis is available here: [Cloud DevOps Foundation](https://shiftup.sharepoint.com/sites/GDP_CCOE/SitePages/Cloud-DevOps-Foundation.aspx)

Here below is illustrated the New Global Platform structure and how DevSecOps & other parts allow to create a DealerX SDK which will be leveraged to deliver software via this platform by anyone.

[Immagine]

### 4.3.9 Ticketing tools

The need of Stellantis is to use, fully integrated Legacy ticketing tool or target ServiceNow based ones, which are not the same between Sales and Aftersales for instance.

## 4.2 Onboarding phase

Here detailed are the use cases Stellantis will use to assess technical & functional capabilities of the platforms. We are stressing out the goal of that: Demonstrate to Stellantis End Users, Business and ICT that technologies could deliver the added value each stakeholder is expecting : “best UX/UI and features” for End Users, “best and easiest way to address business Use cases” for Business users, and for ICT “best technology to continuously and smoothly deliver SW to end users, all by remaining integrated in Stellantis infra and tools (DevSecOps toolchain, API Integration Layer, AWS Cloud, etc..) allowing any IT dev around the world to be able to build SW on this STLA Platform by leveraging the “DealerX SDK”.

### 4.2.1 Parts and services Use Cases

#### 4.2.1.1 Landing Page

Users access the Global Stellantis Landing page, where content is tailored according to their profiles. They can easily navigate to specific Landing pages and have the option to return to the Global Landing from any portal section.

The Global Landing Page should offer:

- Bulletin board for general communications to Dealers and a separate one for targeted messages.
- Highlights of promotional events, Marketing campaigns, ongoing/upcoming Recall programs.
- Dealer-specific dashboard featuring key metrics, KPI gauge charts, sales performance, backorders, VORs, and Retail Inventory levels.
- Links to standard Reports, Customizable Reports, Performance analytics, and AI Assisted forecasting tools.
- Document management system.
- Ticket Management tool, central helpdesk, chatbot, learning, and certification management link.
- Portal search engine with auto prompts and suggestions.
- Intra-dealer communication tools, Dealer 2 Dealer applications for sales and aftersales activities.
- Link to Customer vs Dealer feedback systems and forums.
- Display of all user-created tickets and cases on the global landing page.
- Notifications for ticket updates and more.

To demonstrate content management capabilities, data is generated as needed with minimal integration to Stellantis applications.

Common elements across all Landing pages include:

- Standard header structure.
- Subscription display.
- Administration and settings, language settings, translations, legacy application management, and Dealer General Configuration.
- View notifications and promotional messages.
- Context-based search bar providing relevant results based on user role.
- Seamless navigation between pages with essential information carried forward.
- Vehicle selection functionality.

# 5 Non-functional requirements

## 5.1 DICT / AICT

| DICT SELECTED |  | Criterion |
|---|---|---|
| D / Availability Criteria | 4 | Recover system in less than 4 hours |
| I / Integrity Criteria | 2 | This criterion is analyzed in view of the importance of resources in the identical replacement or to the resetting of Informational Assets subject to alteration, destruction, disappearance, as well as with respect to consecutive immaterial damages (such as loss of production, of profit, etc…). |
| C / Confidentiality Criteria | 3 | Disclosure of the information would have a critical impact for the Group (loss of competitive elements, regulatory breach, significant loss of image or trust, etc.).<br>The information is only accessible to a limited number of persons identified by name or role in the Group's activities |
| T / Traceability Criteria | 2 | The needs for surveillance and control are operational requirements that impose a systematic action (periodic publication or onto event of a state of certain actions or situations): then it is therefore necessary to form and maintain data (date, hour, identities, etc…). |
| DCP Presence (Personal data) | Yes |  |

## 5.2 Data Availability

The application must be designed to provide a greater than 99.75% availability (based on 24/7, 365 days / year).

This means that all data treatments in the platform should be finished by then. This point should also be assessed in the technical requirements.

## 5.3 Observability

The solution should be natively integrable with Leading Observability (Dynatrace) . All to allow Stellantis to easily and with flexibility monitor and prevent any issue on the Platform.

## 5.4 Geographical coverage

The solution must be able to work Worldwide considering different time zones, languages, regional settings. The Portal needs the capability for ‘Maintenance Windows’ to perform non application related change management with a focus on reducing outages during regional key business hours.

## 5.5 Users

Number of users declared per profile type:

- Dealer (global): 500.000-600.000

The platform should be able to handle the above estimated user volumes, including peak period with up to 80% users’ connection with different profiles at the same time. This number can evolve at any time in positive or negative.

## 5.6 Data Privacy

If the platform manages personal data (customer data), so it must take care of all rules about personal data storage and usage, all across the WW Countries where Stellantis operates.

All data related to the customer are covered by the GDPR rules for data privacy, including VIN number, address, phone number and the link between the client and its orders.

Concerning customer personal data, the platform should only expose the necessary data (objective: minimize personal data as much as possible).

The technical solution will need to be reviewed during the project and go through an Stellantis Technical Committee.

## 5.7 Project and Service Language

English will be the main language of the platform support and project documentation. Operative languages are all those of local countries where Stellantis and solution would operate.

## 5.8 Execution report

An execution report should be generated in order to review the loading process of each data set:

- Processing time of the loading process
- Treatment: successful or not
- Errors
- Missing data (data not loaded)

## 5.9 Project plan

This is the Stellantis conservative plan hypothesis, this plan has to be review accordingly with the supplier better proposal and context of the RFQ.

[Immagine]

## 5.10 Security Attachments

Documents included in this RFQ related to Security include “STELLANTIS CLOUD SECURITY

CONTROLS GUIDELINE” (SSIT-S009-G001), the “Cloud Security Control Checklist” and the “Technical Requirements for Solution Architectures in the Cloud”

In response to the evolving landscape of cybersecurity threats and to strengthen our supply

chain’s resilience, Stellantis is updating its Information Security Requirements for all

suppliers globally. Beginning in Q3 2026, all suppliers supporting Stellantis must hold a

valid TISAX (Trusted Information Security Assessment Exchange) label for each location

involved in delivering goods or services to Stellantis.

It is anticipated that all suppliers are aware of this requirement as it pertains to Indirect Material Suppliers and a copy of the associated communication is also provided in this RFQ for review as “Global TISAX Communication Q4 2025 5.pdf”

If the supplier sees an opportunity to improve the security posture of the existing DealerX platform, this should also be contained within the response. This may include web security protections such as policy management, vulnerability detection, web attacks, DoS attacks, scanning tools, web scrapers and purging in addition or in co-ordination with the defined DevSecOps toolset referenced previously.

# 6 Appendix for Integrators

## 6.1 Platforms to be used for the solutions proposal

The integrator should use the technology solution prosed in the RFI response to demonstrate the same using the POV use cases to allow Stellantis to identify the technology to support global portal for dealers, independent repairer, and central users (HQ + field)

## 6.2 Expected feedback

Please provide your

- Technical solution to adopt as Stellantis Global DealerX Dev Tool
- Proposal for implementation (live in 1 year in EE for independent repairers and dealers who buy from importers on behalf of Stellantis) following agile methodology (biweekly sprint). To estimate sprint capacity.
- High level evaluation for the solution implementation
  - Project costs (including development, test, setup, post-golive support of 2months, etc)
  - Licenses
  - Application Maintenance Support Costs High level estimation
- Quotation for the Knowledge Transfer to another Integrator for the Platform RUN.
- Quotation separation Build and Run of the platform with capability to have it as optional package for Stellantis.

Below table as example for this type of work in the platform. The actual work will be expected by the integrator, please include here the platform provider estimation for this work.

| Title section | Out of the box (mandays and capacity) | Customization needed (mandays and capacity) | Note |
|---|---|---|---|
| Stellantis Dealer master data interface |  |  |  |
| Stellantis Dealer authorization & profiling integration: NA + other regions |  |  |  |
| Application bookmark |  |  |  |
| Content (NEWS) |  |  |  |
| Documentation (File repository) |  |  |  |
| Ticketing solution |  |  |  |
| Social interactions |  |  |  |
| Development Framework |  |  |  |
| Integration Layer |  |  |  |
| Observability |  |  |  |
| KPI |  |  |  |

Project costs:

| COSTS (k euro) | 2026 | 2027 |
|---|---|---|
| SETUP COSTS (included post go live support (2 months as indicated in the plan) |  |  |
| Application Maintenance Support Costs High level estimation (based on potential levels of 3000 to 6000 ticket per year) |  |  |

Platform costs, please specify when the licence has to be paid, from setup phase or from go live phase.

| COSTS (k euro) | 2026 | 2027 | 2028 | 2029 | Note |
|---|---|---|---|---|---|
| Dealer licence |  |  |  |  |  |
| NSC read only licence |  |  |  |  |  |
| NSC ticketing/document management |  |  |  |  |  |
| Additional user package (please provide different options for each license type:<br>- Unit additional licence<br>- +10’% vs As-is<br>- +20% vs As-is |  |  |  |  |  |
| External repository licenses |  |  |  |  |  |
| Setup cost and running costs to add a new integration trough integration layer |  |  |  |  |  |

Please specified in case of different SLA/application availability/RTO/RPO the different options/prices

Please indicate for each license, any constraints applicable (i.e: in term of use, document size etc...)

Please indicate if platform what level of post Go Live is covered by the licenses. If additional level of support is optional, please indicate the costs

Please indicate if automatic translation will require additional costs

## 6.3 SLAs

The following SLA will be in place starting from the pilot phase. The trouble ticketing tool use to manage the incident will be provided by Stellantis.

Any Incident, by definition, should be satisfied as soon as possible. Anyway, in order to be able to prioritize them according to the related urgency for the business operations, each of them is identified by the requester through a particular attribute called User Impact (1, 2, 3, 4)

The agreed Impact Levels, that will be used through this agreement are listed in the following table:

[Immagine]

In order to take in count “external” elements that could possibly affect the Impact, as perceived by the end user, e.g. the criticality of the particular software application used when the incident occurred, or the particular day of the month, etc., a prioritization matrix will be used, in order to match the Impact attribute with a second one, called “Urgency”, outputting the final Ticket Priority (1, 2 or 3).

Stellantis standard Priority Matrix

[Immagine]

The rules for defining the ticket urgency and/or the user impact level will be agreed for any single in-scope functionalities.

The following indicators will be used to prove the compliancy of the Incident Management Service with the needed customer’s requirements:

[Immagine]

[Immagine]

(*) for P1 only

[Immagine]

## Commenti

- (DILETTA SCHILLACI (EXTERNAL)) Should we follow DealerHub landing page structure for this?
- (Diletta Schillaci (HBS)) We did not discuss about this. Should we mantain this functionality? If not for Pamir, at least the widget for DriveIT/Digital Me tickets?
- (DILETTA SCHILLACI (EXTERNAL)) remove pamir DigitalMe integration
- (MATT REGAN) Is this list accurate (for the original technical appendix)? Given the current design (except for SNR/Ping et al) our intention should be to enforce standard API/widget integration rather than directly connecting to back-end legacy systems (and ensuring API/widget integration is as painless as possible for all possible NSC needs)
- (MATT REGAN) Having read further - assume the 'legacy' technologies are primarily referring to Aftersales backend systems and can likely be dropped from this section.
- (MATT REGAN) Not sure I see the purpose of the second image on this page 'API STLA STARSHIP' although the first is reasonably coherent with what we're trying to do.
- (Diletta Schillaci (HBS)) I think we should modify this image, can we use DealerHub homepage as example or should I take DealerX currently view and make some changes?
- (MATT REGAN) Which one most closely represents the end product? Probably safer to use DealerX (with highlights to expected changes/optimisations/etc) rather than DealerHub
- (MATT REGAN) Might also be the best place to reference the other existing Portals (NUC, SRP, Spanish Dealer Portal)?
- (Diletta Schillaci (HBS)) This TBC
- (MATT REGAN) This should probably be explicitly DynaTrace
- (MATT REGAN) To be updated and supplemented with the Roadmap.