---
title: Best practices migrating to Adobe Customer Journey Analytics from Adobe Analytics
description: Learn the essential steps and best practices for migrating from Adobe Analytics to Customer Journey Analytics (CJA), including XDM schema design, data mapping, and data view setup.
solution: Analytics, Customer Journey Analytics
topic: Migration
role: Developer
level: Beginner, Intermediate
doc-type: Event
duration: 3654
last-substantial-update: 2025-07-16
jira: KT-18535
---

# Best practices migrating to Adobe Customer Journey Analytics from Adobe Analytics

Learn about the migration from Adobe Analytics to Customer Journey Analytics (CJA). Hosted by Nicolina Picone and Maurizio Corò from Adobe's Ultimate Success team, the session provides an in-depth overview of CJA, its capabilities, and best practices for migration. 

## Key Topics Discussed

* differences between Analytics and CJA
* the importance of strong identity identifiers, aligning data structures, and creating customizable data views
* covers strategies for importing historical data, managing marketing channel attribution, and leveraging CJA's flexibility for tailored reporting

>[!VIDEO](https://video.tv.adobe.com/v/3464911/?learn=on&enablevpops)

## Key Takeways

* **Customer Journey Analytics (CJA) Overview** CJA is an evolution of Adobe Analytics, focusing on the full customer journey across multiple touchpoints (e.g., mobile, web, CRM, call centers) rather than single-track events. It allows for real-time data processing and manipulation.

* **Migration Readiness** Key steps for migrating from Adobe Analytics to CJA include ensuring a strong identity identifier (e.g., person ID), aligning variables and dimensions, and mapping data to the XDM schema. Historical data can be imported with validation steps.

* **Data Views and Flexibility** CJA enables the creation of customizable data views with adjustable session durations, segmentation filters, and attribution settings. This flexibility allows for tailored reporting and analysis.

* **Best Practices for Historical Data Migration** Validate CJA data by comparing it with Adobe Analytics data within an acceptable range (e.g., 10% difference). Start with a short backfill window (e.g., one month) and scale up gradually.

* **Marketing Channel Attribution** CJA offers enhanced capabilities for marketing channel attribution, eliminating limitations like the "first page of visit" function and enabling more dynamic session configurations.
