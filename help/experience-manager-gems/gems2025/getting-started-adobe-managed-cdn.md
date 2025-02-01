---
title: AEM GEMs - Getting started with Adobe Managed CDN
description: Learn how to configure Adobe Managed CDN in AEM Cloud Service to enhance performance and security with new CDN configuration capabilities.
role: Developer, User
level: Intermediate
doc-type: Event
duration: 3438
last-substantial-update: 2025-01-30
jira: KT-17227
exl-id: 4cd0332f-95bf-45f4-a765-aba020c0d7b0
---
# AEM GEMs - Getting started with Adobe Managed CDN

Learn about the Adobe Managed CDN in AEM Cloud Service and how it can be configured. Join us to explore the new CDN configuration capabilities that can be used to enhance both performance and security of your AEM as a Cloud Service applications. In this session you will discover,

* What is the Adobe CDN
* Relevant topologies for AEMaaCS and Edge Delivery Services
* Typical use cases that can be implemented with CDN rules
* How to use RDEs to quickly test and deploy CDN configurations

>[!VIDEO](https://video.tv.adobe.com/v/3443168/?learn=on&enablevpops)

*Recorded on 22 January, 2025*

Have a question, maybe a comment?  Join the discussion in the [Experience League Communities](https://adobe.ly/4haufPK)!

## Key takeaways

### Key Features of Adobe Managed CDN

* **Custom Domains and Certificates** Essential for hosting custom domains and certificates to establish secure connections.
* **Caching** Delivering HTTP responses from cache is significantly faster (under 10 milliseconds) compared to fetching from the origin (hundreds of milliseconds).
* **Out-of-the-Box and Custom CDN** Adobe provides an out-of-the-box managed CDN, but users can also bring their own CDN.

### Configuration Options

* **Request Transformations** Modify headers, rewrite paths, block traffic, and redirect requests.
* **Traffic Filters** Block or allow traffic based on specific rules.
* **Authentication** Support for edge key, punch key, and basic authentication.
* **Origin Selectors** Proxy requests to different origins based on defined rules.
* **Response Transformations** Modify response headers and status.

### Deployment and Customization

* **Configuration Pipeline** Deploy YAML files to configure CDN rules.
* **Traffic Protection** Use traffic filter rules to block, log, and alert traffic based on patterns.
* **Rate Limiting** Protect against DDoS attacks by limiting the number of requests per IP.

### Tools and Analysis

* **Elasticsearch Kibana Stack** Analyze usage and traffic with provided dashboards.
* **Log Forwarding** Forward logs to a Splunk instance for analysis.

### Demo Highlights

* **Deploying Configurations** Demonstrated deploying traffic filter rules and redirects.
* **Authentication and Origin Selection** Showed how to set up basic authentication and proxy traffic to different origins.

### Best Practices

* **Fast Responses** Ensure fast responses from origins to avoid vulnerabilities.
* **Good Caching** Leverage caching to handle traffic efficiently.
* **Use Dashboards** Analyze traffic and usage to set appropriate rate limits.
* **Combine Strategies** Use different rate limiting strategies for better protection.
* **Set Alerts** Get notified when the site is under attack.
* **Test Rules** Start with logging actions before blocking to ensure rules work as expected.

### Contact and Feedback

* **Feedback and Use Cases** Reach out to the team for advanced use cases and feedback.
* **Future Sessions** Participate in polls to suggest topics for future sessions.
