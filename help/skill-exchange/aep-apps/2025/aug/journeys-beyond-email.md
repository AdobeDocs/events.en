---
title: Solving Adobe Journeys Beyond Email
description: Learn to design and test multichannel journeys with Adobe Journey Optimizer, using test profiles, event data, and real-world scenarios for optimal engagement.
feature: Email, Direct Mail, Journeys
role: User
level: Beginner, Intermediate, Experienced
doc-type: Event
duration: 0
last-substantial-update: 2025-08-28
jira: KT-18850
exl-id: e611a377-0e3c-4ccd-ac9c-280638b6ea36
---
# Solving Adobe Journeys Beyond Email

This session explores solving real-world challenges in Adobe Journey Optimizer through a tangible example. It highlights strategies for building multi-touchpoint journeys across email, voice, and direct mail to create cohesive customer experiences. Attendees will gain actionable insights and approaches from a product owner perspective to optimize journeys.

## Key Takeaways

* Break down real-world problems using specific, cross-channel journey mapping.
* Multiple valid solutions exist for each problem—flexibility is key.

>[!VIDEO](https://video.tv.adobe.com/v/3471331/?learn=on&enablevpops)

## Apply Real-World Journey Scenarios

* **Recurring Payment Decline** When a donor’s monthly payment fails, trigger a multi-channel response to resolve the issue and maintain relationships.
* **Channel Selection** Use email first, then direct mail or calls if the email bounces or isn’t acted on.
* **Personalization** Adjust messages based on donor data, such as child sponsorship details, to make communications relevant.
* **Scalability** Design journeys to minimize team involvement and make future updates easier.

## Design Multi-Channel Journeys Stepwise

* **Identify the Event** Start by recognizing a recurring credit card decline. This triggers the journey.
* **Send Data to AEP** Batch the decline event into a custom dataset in Adobe Experience Platform.
* **Break Down the Journey** Create three microjourneys—email notification, direct mail, and outbound calls. Each uses different data and timing.
* **Personalize Communication** Use event data for emails, profile data for print and calls. Plan ahead so the right data is available for each channel.
* **Monitor Responses** Adjust the journey based on customer actions (e.g., email opens, clicks, or payment resolution) to decide next steps.
