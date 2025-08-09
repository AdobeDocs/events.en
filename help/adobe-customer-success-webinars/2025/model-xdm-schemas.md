---
title: Best Practices and Insights for Modeling XDM Schemas
description: Master data modeling in AEP with XDM schemas, identity management, and best practices for scalable, real-time personalization and segmentation.
solution: Experience Platform
topic: Personalization
role: Developer
level: Intermediate
doc-type: Event
duration: 3488
last-substantial-update: 2025-05-08
jira: KT-18019
exl-id: 3327dc51-b5e4-49bd-884a-4defea8664eb
---
# Best Practices and Insights for Modeling XDM Schemas

In this session, learn essential best practices and shortcuts for creating scalable, high-quality Adobe Experience Data Models (XDM) that align with Adobe Experience Platform standards. Gain insights into effectively mapping customer experience and use case data to XDM for seamless integration across Adobe and external tools. 

## Discussion Points

* How to define and organize XDM components to ensure scalable and flexible data models 
* Common challenges in XDM design, evolution, and maintenance

>[!VIDEO](https://video.tv.adobe.com/v/3458042/?learn=on&enablevpops)

## Key takeaways

**Data Modeling in Adobe Experience Platform (AEP)**

The XDM schema is the foundation for data modeling in AEP, enabling the integration and sharing of data across different systems. It defines the structure and meaning of data, such as profile attributes and event-based actions.

**Identity Management**

Proper identity management is crucial to avoid issues like profile collapse. Hashing sensitive data like email and using unique identifiers can help maintain data integrity. Identity maps are recommended for real-time segmentation and personalization.

**Schema Design Best Practices**

Keep schemas simple and focused on marketing use cases. Avoid overloading schemas with unnecessary attributes. Use standardized field groups and minimize customizations for scalability and future-proofing.

**Event vs. Profile Attributes**

Decide whether to model data as profile attributes or events based on marketing objectives. Profile attributes are suitable for real-time targeting, while events provide historical insights for time-based segmentation.

**Handling Collapsed Profiles and Scalability**

Collapsed profiles can only be fixed by Adobe support, but identity graph rules can prevent future collapses. For restructuring existing schemas, extracting necessary data and starting fresh with a clean schema is recommended.
