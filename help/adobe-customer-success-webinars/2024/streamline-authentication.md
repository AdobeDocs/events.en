---
title: Streamline Authentication - Migrating from Service Account (JWT) to OAuth Server-to-Server Credentials
description: The Adobe webinar, led by senior field engineers Jeff Homequest and Marco Lara, focused on migrating from service account JWT to OAuth server-to-server credentials, highlighting the deprecation deadline of January 2025, migration steps, benefits of OAuth, and special considerations for AEM, with extensive support and documentation provided for the process.
role: Admin, Developer, Leader, User
level: Intermediate
doc-type: Event
duration: 3292
last-substantial-update: 2024-12-06
jira: KT-16629
exl-id: 97e2a2de-1cb4-4f2f-8c9b-47ee40227625
---
# Streamline Authentication: Migrating from Service Account (JWT) to OAuth Server-to-Server Credentials

This webinar will guide attendees through migrating from the deprecated Service Account (JWT) credentials to the new OAuth Server-to-Server credentials. As the Service Account (JWT) credentials will cease to function after January 27, 2025, it's crucial for developers and organizations to understand the migration process to avoid potential service disruptions. The webinar will also highlight the benefits of OAuth Server-to-Server credentials and how to ensure a zero-downtime migration.

>[!VIDEO](https://video.tv.adobe.com/v/3440936/?learn=on&enablevpops)

## Key takeaways

* **Meeting Recording and Slides** The meeting was recorded, and a link to the recording will be available at the end.
* **Introduction of Speakers** Jeff Homequest and Marco Lara, both senior field engineers at Adobe, led the webinar.
* **Webinar Focus** The webinar focused on migrating from service account JWT to OAuth server-to-server credentials.
* **Deprecation Deadline** Adobe is deprecating JWT credentials, and they must be migrated by the end of January 2025.
* **Target Audience** The webinar was aimed at application developers, technical leads, and integration architects using JWT credentials in Adobe applications.
* **Migration Steps** The webinar included a step-by-step migration guide and a demo.
* **Q&A Session** Questions were taken throughout the meeting, with a dedicated Q&A session at the end.
* **Benefits of OAuth** OAuth simplifies development, enhances security, and streamlines maintenance compared to JWT.
* **Timeline for Migration**
  * May 1, 2023 - Announcement of future deprecation.
  * June 2, 2024 - Last date to create new service account credentials.
  * January 27, 2025 - End of life for service accounts, and APIs using them will cease to function. 
* **​Special Considerations for AEM** The webinar addressed how the migration affects AEM cloud and on-prem customers, including specific authorization patterns and configurations.
* **Auto-Generated Integrations** Auto-generated integrations will be migrated automatically by Adobe before the deadline.
* **Support and Documentation** Adobe provides extensive documentation and support for the migration process. Customers can reach out to Adobe representatives or professional services for assistance.
* **Testing and Validation** It is recommended to thoroughly test integrations after migration and before deleting old JWT credentials.
* **Custom Integrations** Customers with custom integrations should identify and plan for migration as soon as possible, especially if third-party vendors are involved.
