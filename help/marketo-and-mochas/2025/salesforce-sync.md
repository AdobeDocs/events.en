---
title: Marketo & Mochas - Salesforce Sync
description: Master the Marketo–Salesforce sync with expert guidance on permissions, field visibility, admin collaboration, and best practices to ensure smooth, optimized integration.
feature: Salesforce Integration
topic: Integrations
role: Admin, Developer, Leader, User
level: Beginner, Intermediate, Experienced
doc-type: Event
duration: 3547
last-substantial-update: 2025-08-07
jira: KT-18706
---

# Marketo & Mochas: Salesforce Sync

Marketo has very few native integrations, but Salesforce is the most powerful of them all. With around 90% of Marketo customers also utilizing Salesforce, Adobe is committed to advising customers on how to theorize, diagnose, and optimize syncing between the two. The Marketo sync with SFDC is largely based on the permissions in SFDC that are given to the Marketo Sync User. This can be difficult for customers because of multiple admins or different teams creating silos in communication around updates in the system. 

This webinar goes over the following as it relates to the Marketo <-> SFDC sync: 

• Explaining the birds-eye-view of how the sync works 
• Hiding fields and objects from the Marketo Sync User in SFDC 
• How to communicate with the SFDC admin 
• How to work effectively with Marketo Support 
• Things to avoid when syncing Marketo to SFDC

>[!VIDEO](https://video.tv.adobe.com/v/3470624/?learn=on&enablevpops)

## Best practices for using Salesforce Sync

To use Salesforce Sync with Marketo effectively, follow these best practices, explained step by step in simple terms:

1. **Understand the Sync Process**

    The sync connects Marketo and Salesforce, allowing data to flow between the two systems. Think of the "Marketo Sync User" as a bridge between the two platforms. This user has permissions to read and write certain data:

    * **Write Access** Leads and contacts (Marketo can update these in Salesforce).
    * **Read Access** Accounts, opportunities, custom objects, and activities (Marketo can view these but not change them).

    When data changes in Salesforce or Marketo, the sync updates the other system every five minutes. However, you can prioritize urgent updates using flow steps like "Sync to SFDC."

1. **Clean Up Fields**
 
    Only sync fields that are actively used. For example:

    * If you have old fields like "COVID-19 notes" that are no longer relevant, remove them from the sync. This reduces clutter and speeds up the process.
    * Avoid syncing formula fields (e.g., "lead age in days") because they don’t update timestamps, which can cause issues.

1. **Prevent Backlogs**
 
    A backlog happens when too much data is waiting to sync. To avoid this:

   * Limit Unnecessary Updates: For example, if an account score changes slightly (e.g., from 60 to 61), it can trigger updates for all related contacts. Instead, group scores into ranges (e.g., 0–25, 26–50) to reduce updates.
   * Batch Campaigns: Use batch campaigns instead of trigger campaigns to process data more efficiently.

1. **Manage Errors**

    Errors can occur when Marketo tries to update a field in Salesforce but doesn’t have permission. To troubleshoot:

   * Log in to Salesforce as the Marketo Sync User and try performing the same action. This helps identify permission issues or invalid data.
   * Set up recurring campaigns in Marketo to fix common errors, like standardizing country/state values (e.g., "CA" to "California").

1. **Use Custom Sync Filters**
 
    Custom filters help you control which records sync between Salesforce and Marketo. For example, create a field called "Do Not Sync to Marketo." If this field is marked "true" for a record, it won’t sync to Marketo. This is useful for excluding invalid email addresses or outdated contacts.

1. **Limit Task Creation**
   
    elm Salesforce. Focus on meaningful activities like "filled out form" or "clicked link in email."

1. **Collaborate with Your Salesforce Admin**

    Since the sync involves both systems, work closely with your Salesforce admin to:

    * Manage permissions for the Marketo Sync User.
    * Clean up unnecessary fields in Salesforce.
    * Troubleshoot sync issues together.

1. **Monitor Sync Performance**
 
    Regularly check the sync status in Marketo’s admin section:

    Look for spikes in the "Sync Backlog Trend" or "Sync Throughput" dashboards. These indicate delays or excessive updates.
    If you notice issues, investigate which fields or records are causing the problem.

1. **Use Custom Objects Wisely**

    Custom objects are special data structures that can store additional information (e.g., product details). Only sync custom objects that are necessary for your campaigns to avoid bloating your database.

1. **Plan for Scalability**
    
    When setting up the sync, think long-term:

    * Maintain a data dictionary to track which fields are synced and why.
    * Avoid syncing unnecessary fields or records to keep the system efficient.

By following these steps, you can ensure a smooth and efficient integration between Marketo and Salesforce, minimizing errors and maximizing the value of your data.
