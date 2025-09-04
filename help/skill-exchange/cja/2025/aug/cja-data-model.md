---
title: The Architecture of Analysis - How to Approach Your Customer Journey Analytics Data Model
description: Learn how to structure CJA data models with event hierarchies, attribution, and KPIs to unlock deeper customer journey insights.
feature: Attribution
role: User
level: Beginner, Intermediate, Experienced
doc-type: Event
duration: 0
last-substantial-update: 2025-09-04
jira: KT-18813
---

# The Architecture of Analysis: How to Approach Your Customer Journey Analytics Data Model

One crucial aspect of building a CJA data model is understanding the hierarchical relationship between different touch points and interactions. This forms the foundation for meaningful analysis and insights.

Key considerations include,

* Identifying and mapping customer interaction points across all channels
* Establishing clear event hierarchies and relationships
* Defining consistent attribution models
* Creating standardized metrics and KPIs

By properly structuring these elements, organizations can better track and analyze the complete customer journey, leading to more actionable insights and improved decision-making capabilities.

>[!VIDEO](https://video.tv.adobe.com/v/3471111/?learn=on&enablevpops)

## Unlocking Data Modeling for Powerful Analytics

Discover how effective data architecture in Adobe Experience Platform (AEP) and Customer Journey Analytics (CJA) drives actionable insights and reporting.

* **Schema Design Matters** The choice between flat schemas, arrays, and arrays of objects directly impacts analysis capabilities and reporting flexibility.
* **Transformation Process** Data ingested into AEP must be thoughtfully structured to ensure seamless transformation and usability in CJA.
* **Container Hierarchy** Understanding event, session, and person levels is crucial for multi-level analysis and accurate reporting.
* **Practical Strategies** Upfront planning, schema governance, and leveraging platform features are key to scalable, future-proof implementations.

Mastering these concepts empowers teams to optimize their analytics workflows and unlock deeper business insights.

## Schema Types and Their Use Cases

* **Flat Schemas** Best for straightforward, one-to-one data relationships. Ideal for basic event tracking and simple metrics/dimensions.
* **Arrays** Useful for lists of related items (e.g., product categories, content tags). Each array element becomes an individual dimension for analysis.
* **Arrays of Objects** Designed for complex use cases like product purchases, where each object maintains its own properties and relationships. Enables detailed, object-level analysis.
* **Choosing Wisely** Select the simplest schema that meets your needs, but leverage arrays and objects for advanced scenarios requiring relationship preservation.