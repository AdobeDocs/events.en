---
title: Essential Tips and Best Practices for AEM Lucene Search
description: Boost digital engagement with advanced AEM search tools like filters, facets, auto-suggest, NGram, and spell check. Learn from real-world demos.
solution: Experience Manager
feature: Search
role: Admin, Developer
level: Intermediate, Experienced
doc-type: Event
duration: 3630
last-substantial-update: 2025-11-13
jira: KT-19550
exl-id: 53d83139-90f4-4e6c-ba6d-66638c02b4c3
---
# Essential Tips and Best Practices for AEM Lucene Search

Discover how to enhance your digital presence and improve customer engagement with cutting-edge search features, including filters, facets, auto-suggest, NGram, and spell check. Learn from real-world demos and gain insights into optimising your search capabilities with AEM and Lucene. This webinar provides you the opportunity to elevate your search experience and stay ahead in the digital landscape.

>[!VIDEO](https://video.tv.adobe.com/v/3476410/?learn=on&enablevpops)

## Unlocking Powerful Search in Adobe Experience Manager

Adobe Experience Manager (AEM) leverages Lucene search to deliver fast, relevant results across content, assets, and metadata. This session explores how Lucene indexes work, how to configure them, and the best practices for maximizing search performance.

* **Lucene Search is Everywhere** Powers search in AEM author, publisher, and portals, handling auto-suggestions, filters, facets, and pagination.
* **Index Definitions Drive Performance** Customizing Oak index definitions is crucial for efficient, targeted search.
* **Best Practices Matter** Copy existing index definitions, limit indexed properties, and use the right flags for full-text and property searches.
* **Advanced Features Enhance UX** Facets, auto-suggest, spellcheck, boosting, and stemming can be enabled for richer search experiences.

Understanding these principles helps ensure stable, high-value search capabilities in AEM, supporting both technical and business goals.

## Lucene Index Building Blocks

AEM Lucene index definitions are the foundation of search performance and accuracy. Key components include:

* **Type** Specifies index kind (Lucene, property, etc.).
* **Node Type Restriction** Targets specific content types (e.g., dam:Asset, cq:Page).
* **Path Restriction** Limits indexing to defined repository paths for efficiency.
* **Aggregate Rules** Controls depth and scope of indexed content, ensuring relevant properties are searchable.
* **Index Rules** Core configuration; sets flags like nodeScopeIndex (broad full-text search) and analyzed (tokenization/normalization).

Careful configuration of these elements ensures that search queries are fast, relevant, and resource-efficient.

## Optimizing Search Performance

Effective search optimization in AEM Lucene involves strategic configuration and adherence to best practices:

* **Start with Existing Indexes** Always copy and modify out-of-the-box definitions, never build from scratch.
* **Limit Indexed Properties** Only include necessary properties to keep indexes lean and performant.
* **Use Flags Wisely:
  * **nodeScopeIndex** true for broad full-text search
  * **analyzed** true for property-level tokenization
  * **evaluatePathRestriction** true for path-based queries
* **Property Indexing** Prefer property restriction searches for best performance; use full-text only when needed.
* **Sorting & Facets** Enable propertyIndex and order for sorting; set facet** true for count-based filtering.

Applying these strategies leads to faster queries, reduced resource usage, and more relevant results.
