---
title: Tech Sessions - Adobe Campaign Subdomain and SSL management in the Control Panel
description: Learn how to delegate and configure subdomains within Adobe Campaign’s Control Panel, set up SSL certificates, and monitor configuration to ensure secure email deliverability.
solution: Campaign
feature: Subdomains and Certificates
role: Admin, Developer, Leader, User
level: Beginner, Intermediate, Experienced
doc-type: Event
duration: 3409
last-substantial-update: 2025-09-05
jira: KT-18866
exl-id: 2ccb1f70-17fe-444e-b819-2e6daeb8f79d
---
# Tech Sessions: Adobe Campaign Subdomain and SSL management in the Control Panel

In this session, we explore the concepts of subdomain delegation and configuration within Adobe Campaign, including the installation of SSL certificates to secure subdomains.

Learn what a subdomain is, its purposes, and the delegation methods that enable Adobe to use it effectively. The session also covers the principles of securing a subdomain through SSL certificates and best practices for maintaining a secure environment.

We provide step-by-step guidance on configuring subdomains using the self-service Control Panel, highlighting potential obstacles and how to address them. Participants gain practical knowledge to ensure smooth setup and secure management of their subdomains.

Whether you’re an administrator, developer, or platform owner, this session equips you with the skills to confidently configure and secure subdomains in Adobe Campaign.

>[!VIDEO](https://video.tv.adobe.com/v/3471391/?learn=on&enablevpops)

## Mastering Subdomain Management in Adobe Campaign

Unlock the essentials of subdomain delegation, configuration, and security for Adobe Campaign email communications:

* **Subdomain Delegation** Choose between full or CNAME delegation to control how Adobe manages your DNS and email deliverability.
* **DNS & SSL Setup** Proper configuration of MX, SPF, DKIM, DMARC, and SSL certificates is crucial for secure, reputable email sending.
* **Control Panel** Use Adobe’s self-service tool to streamline subdomain setup, monitor records, and manage SSL certificates.
* **Common Pitfalls** Avoid delays and errors by understanding audit timelines, record requirements, and troubleshooting steps.

Mastering these processes ensures your campaigns are secure, deliverable, and maintain your brand’s reputation.

## Delegation Methods** Full vs. CNAME

* **Full Delegation** Adobe manages all DNS records for the subdomain, ensuring optimal deliverability and security. Recommended for most users.
* **CNAME Delegation** Customer and Adobe share DNS responsibilities. Customer creates CNAME records pointing to Adobe-managed resources.
* **Key Differences:
* **Full** Adobe has full authority; less customer maintenance.
* **CNAME** Shared responsibility; more manual steps for customer.
* **Tip** Never delegate your root domain—only subdomains—to avoid losing control over your main domain.
