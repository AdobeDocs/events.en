---
title: Best Practices for Performant Delivery
description: Optimize media delivery and performance with Dynamic Media by leveraging adaptive streaming, custom video profiles, SEO best practices, image optimization, bulk content management, viewer presets, cache invalidation, and smart imaging.
feature: Dynamic Media, Video, SEO Optimization, Smart Imaging, Viewer Presets, Best Practices
topic: Content Management
solution: Experience Manager, Experience Manager Assets
role: Developer
level: Beginner, Intermediate
doc-type: Event
duration: 1596
last-substantial-update: 2024-11-26
jira: KT-16572
---

# Best Practices for Performant Delivery

Join Riya Midha, Sr. Product Manager at Adobe, to explore the best practices for setting up Adobe Experience Manager Assets Dynamic Media. Learn how to optimize asset delivery, enhance video streaming, configure viewers, and measure and improve performance.

>[!VIDEO](https://video.tv.adobe.com/v/3440399/?learn=on&enablevpops)

## Community Discussion

Continue the conversation in the Adobe Developers Live Community [discussion](https://adobe.ly/3YGedpb).

## Key takeaways

* **Dynamic Media Capabilities** Dynamic Media enables fast and flexible delivery of high-quality, personalized media across devices, handling over 9 trillion media deliveries annually and daily peak volumes of up to 69 billion assets.
* **Adaptive Streaming** Using adaptive streaming for video delivery significantly reduces buffering. A test showed a reduction in buffer count from 50 to 5 on a 60-second video with a constrained bandwidth of 5 Mbps.
* **Video Profiles** Creating custom video profiles with diverse quality encodes ensures optimal video performance across varying network conditions.
* **SEO Best Practices**
  * Use rule sets to create descriptive URLs for better SEO.
  * Add alt text and title attributes to images.
  * Utilize smart imaging and the latest image formats like WebP for better search rankings.
* **Image Optimization**
  * Use scale parameters to adjust image resolution based on screen size.
  * Avoid using 100% quality for images; instead, use a range of 80-90% to reduce file size without noticeable quality loss.
  * Apply sharpening parameters to enhance text clarity in images.
* **Bulk Content Management**
  * Segregate content meant for dynamic media delivery from other content.
  * Use selective sync to optimize processing times and improve time to market.
* **Viewer Presets** Customize viewer appearance and behavior using viewer presets without code changes. Examples include editing play/pause buttons, enabling autoplay and loop, and adding image overlays.
* **Cache Invalidation** Use cache invalidation to immediately reflect changes made to already published assets, bypassing the default 10-hour TTL.
* **Monitoring and Debugging** Use tools like the AEM desktop app and Query debugger page to track processing jobs and identify unprocessed assets.
* **Smart Imaging** Smart imaging is enabled by default on all domains, reducing image file sizes and improving load times.
