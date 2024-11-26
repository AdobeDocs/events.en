---
title: Roll Your Own HTML with Web Components
description: Learn Web Components basics with Raymond Camden, Sr. Developer Evangelist at Adobe, including custom elements, Shadow DOM, and HTML templates, with practical examples like embedding PDFs and building sortable tables to enhance your applications.
topic: Development
role: Developer
level: Beginner, Intermediate
doc-type: Event
duration: 2580
last-substantial-update: 2024-11-26
jira: KT-16579
---

# Roll Your Own HTML with Web Components

Join Raymond Camden, Sr. Developer Evangelist at Adobe, to learn Web Components basics, including custom elements, Shadow DOM, and HTML templates. Explore real-world examples like embedding PDFs and building sortable tables to enhance your applications with reusable, modern solutions.

>[!VIDEO](https://video.tv.adobe.com/v/3440406/?learn=on&enablevpops)

## Community Discussion

Continue the conversation in the Adobe Developers Live Community [discussion](https://adobe.ly/48PRE63).

## Key Takeaways

* **Introduction to Web Components** Web components allow developers to create custom HTML elements with their own look and interactivity, defined using JavaScript.
* **Core Technologies** Web components are built using three core technologies** custom elements, shadow DOM, and HTML templates.
* **Custom Elements** Custom elements enable the creation of new HTML tags. They must use kebab-case and include a dash. JavaScript classes are used to define their behavior.
* **Shadow DOM** The shadow DOM provides encapsulation for the DOM tree of a component, preventing CSS leakage and allowing for more controlled styling.
* **HTML Templates** HTML templates allow for the definition of HTML and CSS that can be cloned and appended to the DOM. However, the presenter prefers using slots over templates for better distribution and flexibility.
* **Attributes and Events** Custom elements can have attributes and event handlers, such as connectedCallback and disconnectedCallback, to manage their behavior when added or removed from the DOM.
* **Slots** Slots allow for the insertion of content into web components, supporting both default and named slots for more flexible content management.
* **Real-world Examples** Examples include a PDF embed viewer, image placeholders, and a table sorter, demonstrating practical applications of web components.
* **Progressive Enhancement** Web components can enhance existing HTML without breaking functionality if JavaScript fails to load.
* **Next Steps and Resources** The presentation suggests exploring form participation, declarative shadow DOM, custom HTML attributes, and server-side rendering. Resources include MDN, webcomponents.org, and the book "Web Components in Action" by Ben Farrell.