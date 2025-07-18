---
title: Adobe Experience Manager Rapid Development Environments
description: Facilitate rapid development and deployment in cloud environments with Adobe's new SDK, reducing deployment time significantly and supporting quick updates, live logs, and advanced configuration options, as discussed in DevOps Life 2024.
solution: Experience Manager as a Cloud Service, Experience Manager
feature: Developer Tools
topic: Development
role: Developer
level: Beginner, Intermediate
doc-type: Event
duration: 2427
last-substantial-update: 2024-11-27
jira: KT-16570
exl-id: 330d8be1-14a0-488a-aae0-ee90e1f7621e
---
# Adobe Experience Manager Rapid Development Environments

Explore best practices for Rapid Development Environments (RDEs) and the updated developer console. Natalia Angulo Herrera, Software Development Engineer at Adobe, and Remo Liechti, Software Development Engineer at Adobe, cover migration challenges, AIO CLI setup, deployment, testing, logging, and configuration management for a smoother Adobe Experience Manager workflow.

>[!VIDEO](https://video.tv.adobe.com/v/3440397/?learn=on&enablevpops)


## Community Discussion

Continue the conversation in the Adobe Developers Live Community [discussion](https://adobe.ly/3UJluDo).

## Key takeaways

* **Introduction to DevOps Life 2024** The session is hosted by Natalia and Remo from Adobe, focusing on rapid development environments.
* **Problem Statement** The challenge of local development environments working well locally but failing when deployed to the cloud.
* **Solution** Creation of a new SDK in the cloud to facilitate rapid development and deployment, reducing the time from 30 minutes to seconds or a few minutes.
* **Deployment Process** The new environment allows for quick updates and validations via a new API and CLI plugin, enabling faster feedback and deployment.
* **Infrastructure Differences** The cloud environment uses a single author and publish instance without high availability and does not use MongoDB.
* **Setup and Usage** Developers can set up a rapid development environment through the cloud interface, using npm and Adobe IO CLI for installation and configuration.
* **Basic Commands** Key commands include io amd --help, io login, io status, io install, io history, io delete, and io reset.
* **Logging and Debugging** The new environment supports live logs and changing log levels without redeployment, using commands like io am or d logs.
* **Advanced Topics** Support for front-end packages and configuration pipelines, allowing for quick deployment and iteration.
* **Upcoming Features** Plans to introduce snapshot functionality for easier environment resets and automatic updates without content loss.
* **Q&A and Feedback** The session encourages participants to join the Discord channel for live interaction and feedback with the development team.
