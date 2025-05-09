---
title: Dispatcher Configurations in Adobe Experience Manager as a Cloud Service
description: Explore AEM Dispatcher best practices for caching, security, and performance to maximize AEM as a Cloud Service scalability and efficiency.
solution: Experience Manager as a Cloud Service
version: Experience Manager as a Cloud Service
feature: Dispatcher
role: Developer, Leader, User
level: Beginner, Intermediate, Experienced
doc-type: Event
duration: 4200
last-substantial-update: 2025-05-07
jira: KT-17903
---

# Tech Sessions: Dispatcher Configurations in Adobe Experience Manager as a Cloud Service

**Adobe Experience Manager (AEM) as a Cloud Service** offers scalability, flexibility, and improved performance for modern digital experience platforms. At the heart of this architecture lies the **AEM Dispatcher**—a vital component responsible for caching, security, and request management. When properly configured, the Dispatcher accelerates content delivery, safeguards backend systems, and boosts overall site performance.

This overview highlights key Dispatcher settings, including caching strategies, access control mechanisms, and request filtering. It also outlines best practices for maintaining a secure and high-performing AEM deployment in the cloud. Whether you're a developer, architect, or business decision-maker, a solid understanding of Dispatcher configurations is crucial to unlocking the full potential of AEM as a Cloud Service.

>[!VIDEO](https://video.tv.adobe.com/v/3457891/?learn=on&enablevpops)

## Key Takeaways

* **Dispatcher SDK for Validation** The AEM Dispatcher SDK is a powerful tool for static analysis of configurations. It allows quick validation of configurations, checks for immutability, and identifies errors, saving significant time compared to full pipeline deployments.

* **Rapid Development Environment (RDE)** RDE provides an interactive runtime environment for testing and debugging configurations beyond static analysis. It enables faster validation and debugging, reducing the time required for deployment and testing.

* **Advanced Networking with Mod Proxy** Advanced networking configurations, such as VPN and dedicated egress IPs, can be set up using Cloud Manager. The mod proxy module allows offloading transactions from AEM to external services, optimizing performance and reducing load on the JVM.

* **Best Practices for Dispatcher Configurations** Key recommendations include using relative paths, unique x-vhost headers, proper client headers, and leveraging cache control headers to manage caching effectively. These practices help avoid pipeline failures and improve debugging efficiency.

* **Web Tier Pipeline for Deployment** The web tier pipeline is a utility for deploying isolated dispatcher configurations. It includes additional tests like cache invalidation, ensuring content updates are reflected promptly and accurately in production environments.