---
title: CDN & WAF Configuration in Adobe Experience Manager as a Cloud Service
description: Enhance the performance and security of Adobe Experience Manager as a Cloud Service applications with customizable CDN rules, WAF protection, and the Config Pipeline, as shared by Adobe experts.
feature: Security
topic: Performance, Security
role: Developer
level: Beginner, Intermediate
doc-type: Event
duration: 2211
last-substantial-update: 2024-11-26
jira: KT-16574
exl-id: a9f38e79-c707-443d-8b2f-e534ce4dd43d
---
# CDN & WAF Configuration in Adobe Experience Manager as a Cloud Service

Unlock the full potential of Adobe Managed CDN with customizable CDN Rules, WAF protection, and the Config Pipeline. Marius Petria, Sr. Computer Scientist at Adobe, Quentin Vecchio, Software Development Engineer at Adobe, and Florian Froese, Software Development Engineer at Adobe, share strategies to enhance the performance and security of Adobe Experience Manager as a Cloud Service applications.

>[!VIDEO](https://video.tv.adobe.com/v/3440401/?learn=on&enablevpops)

## Community Discussion

Continue the conversation in the Adobe Developers Live Community [discussion](https://adobe.ly/3O0TyYa).

## Key points

* **Introduction of New Configuration Capabilities** The presentation introduces new configuration capabilities for the CDN in a cloud service, focusing on the ability to configure the CDN for various use cases.
* **CDN Configuration Options** The new options allow for interaction with HTTP requests and responses, such as adding/removing headers, rewriting request paths, blocking traffic, redirecting clients, and proxying to different origins.
* **Security Enhancements** The new capabilities include traffic filter rules to block or log traffic based on request patterns, and the introduction of M WAF for advanced protection against web attacks like SQL injection and XSS.
* **Declarative Configuration** The configuration is done using YAML files and deployed through a configuration pipeline in Cloud Manager, making it a quick and straightforward process.
* **Request and Response Transformations** The new features allow for request transformations to normalize URLs and remove unnecessary query parameters, and response transformations to set headers before sending responses to clients.
* **Traffic Filters and Rate Limiting** Traffic filters can block specific IPs or countries and implement rate limiting to protect against DDoS attacks. Rate limiting can be configured based on various criteria like client IP, user agent, and request path.
* **Monitoring and Analysis Tools** Adobe provides tools like Elasticsearch/Kibana and Splunk dashboards to analyze traffic and usage, helping to identify and mitigate potential security threats.
* **Practical Demo** The presentation includes a demo showing how to deploy CDN configurations using Cloud Manager and how to handle errors and validate configurations locally using AEM.
