---
layout: essay
type: essay
title: "A reflection of Design Patterns"
date: 2025-12-4
labels:
  - Software Engineering
  - Web Development
  - Nextjs
---
# Blueprints in Coding Spaces
Designing a good software system is very similar to finding the right apartment to live in. At first, you look at floor plans, noticing similar layouts and configurations. Some apartments have distinct kitchen spaces, others feature open concept areas. Even if you don't see these areas specifically labeled, you start to recognize the patterns as you go deeper into the search. After a while, you realize that certain designs cater to specific lifestyles, which allows you to make decisions based on what you need. Similarly, coding follows these recurring patterns, which sometimes isn't obvious unless you take a look at how all the pieces of code connect. In my group's final project, everyone started building features independently. This quickly led to  problems. For example, data sharing was unclear, and the logic that worked for each page separately didn't flow nicely across pages. The chaos wasn't practical and required solutions.

In order to create clear boundaries for different types of API functionality, we created distinct API routes. This helped avoid tangled code and kept each route's focus on a specific task in a pattern called separation of concerns. Our team also created smaller, reusable components with a pattern of component composition. Not only did this make it easier to construct more complex pages, but it also allowed us to modify individual parts without affecting the entire page. Our AI content also isn't generated up-front, but is instead deferred using hooks and conditional rendering using a lazy loading concept. This helped improve performance as it lowers the initial resource load needed for our pages with AI components.

Looking back, these patterns didn't come from any design document or WOD instruction, but were instead created as solutions to the problems we had in our app. Component composition gave us flexible parts, lazy loading helped performance, and separation of concerns helped clean data sharing and calls. Just like how floor plans make choosing the right apartment easier, design patterns are created to solve common problems in software. While this concept was taught in class, experiencing the creation of design patterns firsthand in my project helped me learn how to recognize them. And that's not because I'm forcing these patterns into my code, but rather because they're solutions created to solve the problems in my code.


Disclosure of AI: AI was used to help identify design patterns
