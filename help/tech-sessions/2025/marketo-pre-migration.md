---
title: Marketo Migration to the Adobe Admin Console - (Pre-Migration)
description: Adobe is migrating Marketo Engage to the Admin Console for better user management. Learn about auto and self-migration types, prerequisites, post-migration changes, best practices, common pitfalls, and support. Access the session recording on Adobe's Experience League website.
role: Admin, Developer, Leader, User
level: Beginner, Intermediate, Experienced
doc-type: Event
duration: 2280
last-substantial-update: 2025-03-14
jira: KT-17483
exl-id: 9c3da83f-9e02-4a2e-9784-10213facf056
---
# Marketo Migration to the Adobe Admin Console - Pre-Migration

Join Us for a Seamless Marketo Migration with Adobe Experts!

Get ahead of your Marketo migration with Adobe’s Customer Experience & Identity Team in this informative webinar. We’ll walk you through key steps, best practices, and common challenges to ensure a smooth transition to the Adobe Admin Console.

What You’ll Learn,

* A step-by-step roadmap for your pre-migration process
* Best practices to simplify your transition and avoid pitfalls
* Expert answers to common migration concerns

Whether you’re just starting your migration or preparing for the final steps, this session will equip you with the knowledge and tools to navigate the process with confidence. Don’t miss this opportunity to get ahead and make your Marketo migration seamless!

>[!VIDEO](https://video.tv.adobe.com/v/3449712/?learn=on&enablevpops)

## Key takeaways

### Purpose of Migration and overview

Adobe is migrating Marketo Engage to the Admin Console to consolidate all products into one hub for better user management and access.  The Admin Console will serve as the central hub for managing Adobe products, user roles, permissions, and support access. URLs for accessing Marketo Engage will change to Adobe's Experience Cloud platform.

### Migration Types

* **Auto Migration** For organizations with fewer than 75 users and no SSL setup. Adobe handles the migration.
* **Self Migration** For organizations with SSL setup. Admins manage the migration process using the Migration Console.

### Prerequisites for Migration

* System admins must complete the consent email.
* SSL must be set up in the Admin Console (not the Marketo instance).

### Post-Migration Changes

* Users will log in using Adobe ID or federated ID (SSL).
* Admin roles and permissions will determine access levels in the Admin Console.

### Best Practices

* Verify user emails and resolve locked-out accounts before migration.
* Ensure proper admin roles are assigned.
* Disable ad blockers or use incognito mode to avoid login issues.

### Common Pitfalls

* Incorrect admin permissions can limit access.
* Browser extensions and ad blockers may interfere with access.
* IP whitelisting is not yet supported in the Admin Console but is being developed.

### Impact on Functionality

* Automated emails, API users, and munchkin codes will not be affected by the migration.
* The migration primarily impacts user authentication and management.

### Support

* Users experiencing issues should open a support case with Adobe Customer Care.
* Include the IMS org ID in support cases for faster resolution.
