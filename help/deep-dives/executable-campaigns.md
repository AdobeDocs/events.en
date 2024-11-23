---
title: Executable Campaigns - Learn how executables can drive efficiency & impact
description: Join Chris Willis, Courtny Edwards-Jones, and Jane Musatova in this Adobe Champion Deep Dive to learn how executable campaigns in Marketo can streamline processes, ensure data accuracy, and automate complex workflows, with practical examples and a focus on minimizing errors and backlogs.
role: Developer, User
level: Intermediate, Experienced
doc-type: Event
duration: 3778
last-substantial-update: 2024-03-07
jira: KT-15098
thumbnail: 3427704.jpeg
exl-id: cfea1a1a-2d29-4cf6-b633-aa2a2523114e
---
# Executable Campaigns - Learn how executables can drive efficiency and impact

>[!VIDEO](https://video.tv.adobe.com/v/3427704/?learn=on)

**Moderated by** Chris Willis
**Speakers** Courtny Edwards-Jones and Jane Musatova

## Overview

In this edition of the Adobe Champion Deep Dive, we discuss the use of executable campaigns in Marketo and provides examples of how they can be used to streamline processes and ensure data accuracy. Executable campaigns are a type of smart campaign that run flows in a synchronous manner, allowing for dependencies between different steps. They can be used to automatically retry failed processes, such as data standardization or lead qualification, before moving on to the next step. The document also covers the use of parent campaigns and nested executables, as well as the limitations of executable campaigns, such as the inability to use webhooks or wait steps.

## What are the purpose of using executable campaigns? 

The purpose of using executable campaigns is to streamline and automate complex workflows in Marketo. Executable campaigns allow you to define a sequence of actions that need to be completed before moving on to the next step in a campaign. This ensures that each action is fully executed before proceeding, reducing the risk of errors or incomplete processes. Executable campaigns can be used to retry failed processes, standardize and enrich data, qualify leads, capture interesting moments, and more. They provide a more efficient and organized way to manage and automate your marketing operations.

## What is an executable campaign and how does it function?

An executable campaign is a type of smart campaign in Marketo that allows for the sequential execution of multiple flows within a single campaign. It is designed to ensure that each flow is fully executed before the next one begins. This is different from a request campaign, which runs flows asynchronously and can have multiple flows running in parallel.

To create an executable campaign, you need to check the "Executable" box when creating the campaign. Once created, you can add flow steps to the campaign, such as changing data values, sending emails, or updating program statuses. However, there are some limitations to executable campaigns. You cannot use triggers, webhooks, or wait steps within an executable campaign.

Executable campaigns are useful for processes that have dependencies on each other, where one flow needs to be completed before the next one can begin. They can help streamline operational processes, simplify data processing, and minimize the risk of errors or backlogs. By using executable campaigns, you can ensure that each step in a process is completed before moving on to the next one, improving efficiency and accuracy in your marketing operations.