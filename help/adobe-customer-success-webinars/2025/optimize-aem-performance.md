---
title: Optimizing AEM Performance - Caching Strategies and Techniques
description: The session covered caching strategies and techniques, caching mechanisms and tiers, dynamic content handling, debugging caching issues, and synchronizing cache invalidation between the dispatcher and CDN.
topic: Performance
role: Admin, Developer, Leader, User
level: Intermediate
doc-type: Event
duration: 3764
last-substantial-update: 2025-02-21
jira: KT-17373
exl-id: 5606a250-ab06-417b-8abf-a30543cb5f16
---
# Optimizing AEM Performance: Caching Strategies and Techniques

In this session we explore various caching mechanisms—such as page, asset, and dispatcher caching—as well as how to implement caching at the CDN level to optimize content delivery and reduce load times. The discussion will cover best practices for each caching layer, troubleshooting common issues, and how to leverage CDN capabilities for maximum efficiency.

## Key Discussion Points

* Introduction to caching
* Types of caching, Caching best practices, cache invalidation and refresh
* Debugging techniques

>[!VIDEO](https://video.tv.adobe.com/v/3444452/?learn=on&enablevpops)

## Key takeaways

* **Caching Strategies and Techniques** The session focused on various caching strategies and techniques to optimize performance, including caching at different layers such as browser, CDN, and dispatcher.

* **Caching Mechanisms and Tiers** The discussion covered different caching mechanisms and tiers, including browser caching, CDN caching, and dispatcher caching, and how they can be configured and managed.

* **Dynamic Content Handling** Techniques for handling dynamic content on a page were discussed, including the use of Sling Dynamic Include (SDI) and Edge Side Includes (ESI) to ensure dynamic content is not cached while static content is.

* **Debugging Caching Issues** Various techniques to debug caching issues at different levels (browser, CDN, dispatcher) were explained, including the use of headers, logs, and specific configurations to identify and resolve caching problems.

* **Synchronization of Cache Invalidation** The session addressed the challenge of synchronizing cache invalidation between the dispatcher and CDN, recommending the use of shorter max-age values and CDN purge APIs to ensure both caches are invalidated simultaneously upon page activation.
