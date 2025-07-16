---
title: Adobe Pass - new REST API v2
description: This session focuses on introducing Adobe's new REST API v2 and guiding users through its migration process.
role: Developer
solution: Pass
level: Beginner, Intermediate, Experienced
doc-type: Technical Video
duration: 3230
last-substantial-update: 2025-04-07
jira: KT-17685
hidefromtoc: true
exl-id: 745411bb-48d7-4410-a236-d02c2927ac1b
---
# Adobe Pass - new REST API v2

This session focuses on introducing Adobe's new REST API v2 and guiding users through its migration process.

>[!VIDEO](https://video.tv.adobe.com/v/3457461/?learn=on&enablevpops)

## Key Highlights

* **Overview and Benefits**

  * REST API v2 is designed for modern, flexible, and scalable authentication, catering to high-demand events and multi-device scenarios.
  * Key improvements include enhanced encryption, session consistency, cross-device SSO, and extended error information for faster debugging.

* **Migration Steps**

  * Users must create new registered applications with REST API v2 scopes.
  * Existing configurations like device identification and MVPD mappings can be reused.
  * Migration involves phases like registration, configuration, authentication, pre-authorization, and authorization.

* **Functional Enhancements**

  * Unified RESTful API replaces Access Neighbor SDKs, simplifying implementation across platforms.
  * Support for multiple authentication profiles within the same session and seamless cross-device transitions.
  * Pre-authorization and authorization flows remain mandatory for content access.

* **Timeline**

  * REST API v1 will stop receiving updates by December 2025 and be fully retired by the end of 2026.
  * Users are encouraged to complete migration well before these deadlines.

* **Resources and Support**

  * Documentation, cookbooks, and FAQs are available on Adobe Experience League.
  * Adobe offers sandbox environments, Zendesk tickets, and migration meetings for support.

* **Q&A Highlights**

  * REST API v2 requires re-authentication as it is not backward-compatible with v1.
  * Pre-authorization is for UI purposes, while authorization is needed for media tokens.
  * SSO is supported via a new Adobe service token.
