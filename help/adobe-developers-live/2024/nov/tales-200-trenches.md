---
title: Tales from 200 Trenches
description: Ensure web project success by prioritizing performance, using Google PageSpeed Insights, optimizing key metrics like LCP and TBT, managing resources efficiently, and following best practices for development and image optimization.
solution: Experience Manager, Experience Manager Sites
feature: Edge Delivery Services
role: Developer
level: Beginner, Intermediate
doc-type: Event
duration: 1321
last-substantial-update: 2024-11-27
jira: KT-16541
exl-id: 1104048d-4074-49aa-a0bc-0065fa2df505
---
# Tales from 200 Trenches

With over 200 Edge Delivery Services projects completed, Kiran Murugulla, Senior Engineer at Adobe, and Varun Mitra, Architect for Adobe Experience Manager Cloud, share key lessons learned. Discover the secrets behind delivering fast, high-performing experiences with exceptional Core Web Vitals.


>[!VIDEO](https://video.tv.adobe.com/v/3439424/?learn=on&enablevpops)

## Community Discussion

Continue the conversation in the Adobe Developers Live Community [discussion](https://adobe.ly/4fwWvvi).

## Key takeaways

* **Performance is Critical** Performance, particularly the speed of web pages, is emphasized as a key factor for successful web projects. Ensuring performance scores of 100 is a primary goal.
* **Development Practices**
  * Use Google PageSpeed Insights for continuous testing during development.
  * Start projects with boilerplate code that already scores 100 to maintain high performance.
  * Ensure pull requests (PRs) meet performance standards before merging.
* **Key Metrics** Focus on optimizing Largest Contentful Paint (LCP) and Total Blocking Time (TBT) as they significantly impact performance scores.
* **Resource Management**
  * Include necessary resources like fonts and third-party scripts within the project source.
  * Use font fallbacks to improve loading times.
  * Delay loading non-essential scripts to improve initial load performance.
* **Image Optimization** Prioritize loading of above-the-fold images and use high-priority fetch settings for critical images.
* **Case Studies**
  * ***CNN.com*** Optimized query indexes and delayed loading of Google ads to improve performance.
  * ***Herbert Homes*** Used Intersection Observer API to load data as users scroll, improving performance and user experience.
* **Best Practices**
  * Start with boilerplate code and use well-structured markup.
  * Utilize advanced CSS selectors and minimize JavaScript manipulation.
  * Focus on mobile-first development.
  * Ensure content structuring is intuitive for authors.
* **Tools** Use tools like Google Sheets and DSA for tracking site performance scores over time.
