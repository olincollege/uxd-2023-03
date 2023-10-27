---
layout: single
title:  "Feature Idea Description"
date:   2023-10-16 11:17:00 -0400
permalink: /phase-2/feature-idea-description
categories: phase-2
excerpt: "One of our core featuers is that our app will display information that's relevant to what the user is doing. Here's how we figured that out."
---
## The Feature

Display information that is relevant to what the user is doing.


## Why We Chose It

In any medium we develop, it's vital that users can access and use information relevant to their tasks.

This is important because users open a new app or website with a specific task in mind. For a cheat sheet to be effective, it must assist them in achieving that particular goal and reduce any confusion in their experience.

If we provide cheat sheets, they should either contain enough information to cover most use cases or they should be tailored to the specific actions the user currently wants to take. We can intuit the user’s desires through pattern matching (after selecting the title and mousing around, most users want to change the font), or we can provide a simple search bar with common task suggestions.

For example, if we have an AI sidebar assistant, it should not try to help you write a letter (eg. Microsoft’s discontinued Clippy) every time you start typing in a document. Unwanted information popping up on screen spoils the point of trying to make software less complicated.

Our feature needs to strike the right balance in the information we offer: it should be both relevant and unobtrusive to provide a streamlined and user-friendly experience. 


## A Potential Implementation

One way this feature could be implemented on an iPad is with smart tooltips that point to the UI elements that the user should click in order. The tooltips can be activated with a small button that triggers a menu where users can ask a question or browse suggested features.

{% include figure image_path="/images/feature-idea-description/1.png" alt="" caption="" %}
{% include figure image_path="/images/feature-idea-description/2.png" alt="" caption="" %}
{% include figure image_path="/images/feature-idea-description/3.png" alt="" caption="" %}

