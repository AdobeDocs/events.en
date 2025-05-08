---
title: Mastering Sequential Logic in Adobe Analytics and Customer Journey Analytics - Starts and Stops
description: Master sequential logic in Adobe Analytics with advanced segmentation, scope controls, and derived fields to uncover customer behavior patterns and improve data accuracy.
solution: Analytics, Customer Journey Analytics
role: Developer
level: Intermediate
doc-type: Event
duration: 3370
last-substantial-update: 2025-05-08
jira: KT-18017
---

# Mastering Sequential Logic in Adobe Analytics and Customer Journey Analytics: Starts and Stops

In this session, we’ll explore how to configure sequences with the THEN operator in Adobe Analytics (AA) and Customer Journey Analytics (CJA). Learn to retrieve precise subsets of activity by combining ONLY AFTER/ONLY BEFORE SEQUENCE with EXCLUDE checkpoints.

## Discussion Points

* Quick review of standalone sequential logic operators and visual framework.
* Describe how EXCLUDE impacts the results of sequences using ONLY AFTER/BEFORE SEQUENCE.
* Present use cases and demos showing how you can adopt the methods for your business.

>[!VIDEO](https://video.tv.adobe.com/v/3458040/?learn=on&enablevpops)

## Highlights


1. Sequential Logic and Segmentation in Analytics

   * The session focused on advanced techniques for applying sequential logic in analytics, emphasizing the importance of understanding starting and stopping points in data sequences to analyze customer behaviors effectively.
   * Sequential operators were discussed as tools to identify patterns such as "web hit followed by email hit" or "application submission followed by subsequent sessions."
   * The greedy nature of segment logic was highlighted, explaining how it returns the largest possible data set unless constrained by additional conditions.
   * Techniques for defining scope, such as "only before" and "only after" sequences, were introduced to study subsets of data based on specific business questions.
   * The use of checkpoints, proximity conditions, and exclusion criteria was explained to refine data analysis and answer complex business questions.

2. Handling Multiple Points of Interest in Data Analysis

   * Andy discussed scenarios where customers have multiple application submissions and the need to analyze behaviors after each submission rather than just the first one.
   * Challenges such as overlapping application submissions and defining whether to include or exclude original points of interest were addressed.
   * The importance of clarifying assumptions and refining logic to handle multiple occurrences of a sequence was emphasized, ensuring accurate analysis of customer behaviors across their lifecycle.

3. Advanced Techniques for Stopping Data Matching

   * The session introduced methods to stop data matching at specific checkpoints using exclusion criteria, allowing analysts to study data between defined start and stop points.
   * Examples included analyzing behaviors between "web hit followed by mobile app interaction" and stopping at "email interaction."
   * The use of "within" and "after" conditions was explained to enforce stricter proximity rules and avoid unintended results from greedy logic.
   * Andy demonstrated how these techniques can be applied to study customer behaviors relative to specific events, such as application submissions.

4. Validating and Refining Data Analysis Logic

   * Andy emphasized the importance of validating assumptions and testing logic to ensure accurate results, as mistakes in segment building or data assumptions are common.
   * Examples of unexpected results due to greedy logic were shared, highlighting the need for strict conditions like "within one event" or "within one session."
   * Validation benchmarks, such as small data sets with known characteristics, were recommended to test and refine analysis methods.

5. Application of Sequential Logic to Real-World Use Cases

   * Andy provided examples of real-world use cases, such as analyzing customer behaviors after application submissions or identifying common actions following purchases or negative reviews.
   * The session demonstrated how sequential logic can be applied to study patterns like "first session after application" or "second session after application" across multiple occurrences.
   * The importance of scaling analysis to broader data sets while maintaining accuracy was discussed, with examples of cascading effects in session-level data.

6. Using Derived Fields for Flexible Analysis

   * Andy introduced the concept of using derived fields in Adobe Customer Journey Analytics (CJA) to define moments of interest dynamically, reducing the need to edit multiple filters for each analysis.
   * Derived fields allow analysts to build filters relative to a single field, enabling quick adjustments to study different points of interest, such as product-specific applications or other customer events.

7. Practical Applications and Future Plans

   * Andy shared plans for the next webinar session, which will focus on templates, cheat sheets, and practical applications of the concepts discussed, moving away from training to actionable use cases.
   * The session concluded with a call for feedback via a poll to determine interest in future topics and ensure alignment with attendees' objectives.
   * Andy highlighted the Ultimate Success team's micro-engagements, offering targeted coaching sessions to help businesses apply these concepts to their specific use cases.

8. Sharing Materials and Follow-Up Actions

   * Andy confirmed that webinar materials, including recordings and blog posts, will be shared with attendees, providing a documented form of the session's content.
   * Attendees were encouraged to reach out to their TAMs or CSMs for further assistance and to explore Ultimate Success licensing for personalized coaching sessions.
