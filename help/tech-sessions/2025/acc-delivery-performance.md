---
title: Adobe Campaign Classic Delivery Performance - Troubleshooting
description: This session covered key strategies to improve email and SMS delivery performance using Adobe Campaign. It addressed common challenges like delivery delays, low throughput, and transactional slowness, offering solutions such as batching optimization, SQL logging, and server performance monitoring. Deliverability best practices included proper email authentication (SPF, DKIM, DMARC), blacklist monitoring, and spam checks. For enhanced performance, experts recommended clean workflows, throttling rules, and avoiding shared containers. SMS delivery tips focused on proper external account setup and log analysis. The session also emphasized tracking validation, database maintenance using bloat reports, and applying pressure/fatigue rules to boost engagement. A session recording will be shared via email and posted on the Adobe Experience site.
solution: Campaign Classic v7
product: Adobe Campaign
feature: SMS, Deliverability, Troubleshooting
role: User
level: Beginner, Intermediate, Experienced
doc-type: Event
duration: 2257
last-substantial-update: 2025-04-25
jira: KT-17869
exl-id: a7e1e198-b63b-4a2a-9ffc-7f72bf4c61c1
---
# Tech Sessions: Adobe Campaign Classic Delivery Performance - Troubleshooting

In this session, we will explore common challenges faced when delivering optimal performance with Adobe Campaign Classic (ACC) and provide actionable strategies for troubleshooting and resolving issues. Participants will get to learn how to identify performance bottlenecks, address delivery preparation/configuration inconsistencies and implement best practices to ensure smooth communications. From optimizing deliveries to overcoming technical difficulties, this webinar will equip attendees with the knowledge and tools needed to enhance the efficiency of their ACC campaigns, drive better results, and deliver high-quality customer experiences.

>[!VIDEO](https://video.tv.adobe.com/v/3457826/?learn=on&enablevpops)

## Key takeaways

**Delivery Challenges and Solutions**

* Common issues include delivery delays, preparation failures, stuck deliveries, low success rates, low throughput, low engagement, and transactional delivery slowness.
* Solutions involve optimizing delivery batching, monitoring server performance, enabling SQL query logging, reviewing audit logs, and ensuring proper configuration of MTA and IP affinities.

**Deliverability Best Practices**

* Ensure proper email authentication (SPF, DKIM, DMARC).
* Monitor blacklist statuses and avoid spam-triggering content.
* Use spam checks to assess spam scores before sending emails.

**Optimizing Delivery Performance**

* Use clean targeting workflows and limit personalization fields.
* Implement throttling rules, batch processing, and topology rules for exclusions and filtering.
* Avoid sharing containers across multiple channels to prevent bottlenecks.

**Troubleshooting SMS Delivery Issues**

* Ensure external accounts are uniquely configured and SMS processes are running.
* Check SMS logs for errors and verify regular expressions in SMP settings.
* Engage the service provider for misconfiguration issues.

**Transactional Delivery Slowness**

* Monitor internal and total processing times.
* Ensure delivery size is within limits (60 GB for batch, 30 GB for event).
* Review typology rules and personalization settings.

**Tracking and Engagement**

* Validate tracking workflows and server logs.
* Test custom tracking formulas in lower environments before production.
* Ensure tracking servers are up and running.

**Database Maintenance**

* Use bloat reports to identify tables with high bloat and justify a DB vacuum.

**General Recommendations**

* Use pressure and fatigue rules to limit unnecessary emails.
* Segment large deliveries into smaller batches to optimize performance.
