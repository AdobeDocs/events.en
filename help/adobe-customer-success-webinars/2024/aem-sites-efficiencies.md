---
title: AEM Sites Efficiencies - Performance optimization, Configuration, and Troubleshooting
description: essentials of troubleshooting Adobe Experience Manager (AEM) Sites. Whether you're facing performance issues or dealing with complex configurations, this session will provide practical skills to maintain and optimize your AEM environment. We’ll prioritize live demos over slides, offering hands-on experience in tackling real-world challenges.​Key Discussion Points:- Virtual host configuration & domain mapping- Performance Issues- Authorization, Identification, User Permissions
solution: Experience Manager
version: Cloud Service
role: Admin, Developer, Leader, User
level: Intermediate
doc-type: Event
duration: 3452
last-substantial-update: 2024-10-30
jira: KT-16353
---

# AEM Sites Efficiencies: Performance optimization, Configuration, and Troubleshooting

In this webinar, we’ll dive into the essentials of troubleshooting Adobe Experience Manager (AEM) Sites. Whether you're facing performance issues or dealing with complex configurations, this session will provide practical skills to maintain and optimize your AEM environment. We’ll prioritize live demos over slides, offering hands-on experience in tackling real-world challenges.​

>[!VIDEO](https://video.tv.adobe.com/v/3435114/?learn=on)

## Key Points

The webinar focused on AMP site efficiencies, including performance optimization, configuration, and troubleshooting.

### Dispatcher Configuration

* Importance of dispatcher in delivering performant websites.
* Key aspects of dispatcher configuration: virtual host configuration, domain mapping with cache structure, and regular reporting and redirects.

### Rights Management

* Best practices: apply rights to groups, avoid deny statements, and avoid overengineering.
* Use of the Netcentric ACL tool for managing rights through a Yaml file, ensuring easy deployment and traceability.

### Performance Issues

* Importance of identifying deltas in sync operations to avoid full cache flushes.
* Avoid large page operations during business hours.
* Simplify workflows to necessary steps.
* Be cautious with third-party system processes on author systems, especially with tools like ImageMagick.
* Avoid synchronized requests to third-party systems that can't handle the load.
* Manage heavy custom components to avoid performance degradation.
* Monitor for long-running sessions to prevent segment not found exceptions.