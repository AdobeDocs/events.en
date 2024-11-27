---
title: Assets Migration Blueprint
description: Learn how to migrate a legacy DAM to Adobe Experience Manager Assets with insights from Achim Koch, covering stakeholder analysis, resource planning, data transformation, and best practices like using CSV files for data handling.
feature: Migration
topic: Migration
solution: Experience Manager, Experience Manager Assets
role: Developer
level: Beginner, Intermediate
doc-type: Event
duration: 1690
last-substantial-update: 2024-11-26
jira: KT-16576
---

# Assets Migration Blueprint

Join Achim Koch, Principal Technical Architect at Adobe, to learn how to migrate a legacy DAM to Adobe Experience Manager Assets. Gain insights into stakeholder analysis, resource planning, data transformation, and best practices like using CSV files for data handling. Build a roadmap for your own Adobe Experience Manager migration projects.

>[!VIDEO](https://video.tv.adobe.com/v/3440403/?learn=on&enablevpops)

## Community Discussion

Continue the conversation in the Adobe Developers Live Community [discussion](https://adobe.ly/4hKHpnF).

## Key takeaways

* **No Out-of-the-Box Tool for Migration** There is no single tool that can migrate from various legacy systems to Adobe Experience Manager (AEM) due to the diversity of products and custom solutions.

* **Five Stages of Migration**

  * Project Planning
  * Implementation Planning
  * AEM Implementation
  * Migration Script Implementation
  * Migration Execution
  
* **Stakeholder Involvement** Identifying and involving stakeholders such as sponsors, business users, IT system administrators, and legacy system support is crucial.

* **Resource and Timeline Planning** Ensure that resources are available and plan around holidays, peak business times, and off-limit windows.

* **Technical Planning** This includes requirements analysis, data transformation, and infrastructure planning.

* **Iterative Process** Migration involves multiple iterations of script execution, analysis, feedback, and adaptation.

* **Use of CSV Files** CSV files are preferred for their ease of use and readability during the migration process.

* **Scripting Language** Node.js is recommended for its support of CSV, AWS, and HTTP, and for being a good opportunity to learn JavaScript.

* **Quality and Repeatability** Ensure high-quality data migration, keep original data and CSV files for reference, and make the process repeatable.

* **Content Freeze** Declare a content freeze during migration to prevent new data from being added after the snapshot is taken.

* **Tools and Tips** Use tools like VS Code with the Rainbow CSV extension, and consider the byte order marker (BOM) for UTF-8 text files.

* **Business Approval** Reserve time for testing and obtaining official business approval post-migration to lift the content freeze.