---
title: Optimizing Content Delivery - Unlocking the Power of Edge Services
description: ATM Edge Delivery Services (EDS) enhances ATM capabilities with composable services, fast development cycles, and high lighthouse scores, supporting document-based and WYSIWYG authoring, serverless architecture, quick site creation, and extensive customization options.
solution: Experience Manager, Experience Manager as a Cloud Service
feature: Edge Delivery Services
role: Admin, Developer, Leader, User
level: Intermediate
doc-type: Event
duration: 3589
last-substantial-update: 2024-12-06
jira: KT-16631
exl-id: 2057e491-9ec3-4bfe-b85a-6b74d70822bf
---
# Optimizing Content Delivery: Unlocking the Power of Edge Services

In this session, we will provide an overview of Edge Delivery Services (EDS) and its architecture. We’ll delve into how EDS integrates with document-based authoring and AEM-based authoring via the Universal Editor. A live demo will showcase EDS in action, followed by resources for further exploration and a Q&A session.

>[!VIDEO](https://video.tv.adobe.com/v/3440938/?learn=on&enablevpops)

## Key takeaways

### Introduction to EDS

* EDS is a set of composable services designed to enhance the capabilities of ATM. ​
* It aims to deliver exceptional experiences that drive engagement and conversions with fast development cycles and a 100% lighthouse score. ​

### Authoring Options

* **Document-Based Authoring** Uses familiar tools like Microsoft Word or Google Docs for content creation, allowing quick content creation without extensive training. ​
* **Universal Editor** Provides a WYSIWYG interface similar to traditional ATM sites, allowing for more detailed and visual content creation. ​

### Architecture

* EDS integrates within the Amazon Cloud Service framework. ​
* It supports serverless implementation and can work without a traditional author or publisher instance. ​
* Two levels of caching can be implemented: at the customer infrastructure level and the EDS level. ​

### Content Management

* Document-based authoring requires a GitHub account, Google Drive or Microsoft SharePoint, a sidekick plugin, and a code sync tool. ​
* EDS with IAM authoring requires a GitHub account, an IAM as a cloud service license, and a code sync tool.

### Development and Deployment

* The process of creating a site with EDS is quick, often taking less than a day. ​
* Local development can be done using the aem up command to create a local version of the website.
* Changes can be committed to feature branches for testing before merging into the main branch. ​

### Customization and Extensibility

* Custom components can be created using simple CSS and JavaScript. ​
* The architecture allows for third-party integrations and custom authoring sources.

### Best Practices

* It is recommended to use vanilla JavaScript and CSS to maintain high lighthouse scores.
* Any introduction of libraries like React should be carefully considered and tested to avoid performance degradation.

### Support and Documentation

* Comprehensive documentation is available to guide users through the setup and customization process. ​
* Users are encouraged to reach out to Adobe support for any unresolved issues. ​
