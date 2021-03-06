---
layout: post
title: 3 Lessons Learned from Delivering Quality Software
date: 2014-06-12
description: Lessons learned from developing quality custom software and making clients happy. 
author: Byron Sommardahl 
excerpt: Lessons learned from developing quality custom software and making clients happy. 
image: https://acklenavenue.com/img/posts/lessons-from-quality.png
thumbnail: https://acklenavenue.com/img/posts/lessons-from-quality.png
imageCredit: Photo by [Ryan Graybill](https://unsplash.com/@graybill_) on [Unsplash](https://unsplash.com/)
type: article
keywords: custom software, Customer satisfaction, quality, QA testers, Clean Code, Automated testing, Bugs, software developer
tags: software_development
---

This article is about some lessons that my team has learned about developing custom software and making clients happy. We'll get to the lessons learned in a second, but I wanted to first emphasize the biggest and most important lesson of all. **Customer satisfaction is dependent on the quality of the product.** Any custom software development company depends on happy clients to survive. And if time has taught me anything, it's that clients deserve and expect quality. So, it is super important to do what it takes to ensure quality. The keys to quality is great developers (check) and great QA engineers (uh oh)!

I have seen QA done really poorly in the past. Power trippy QA managers, ignorant QA testers, attention to the wrong details, and an overall adversarial feel dominate my memories of QA while I was still working in a cubicle. So, when I started forming a team of developers a few years ago, there were several things I wanted to do better. Of course, mistakes have been made. I made the mistake of believing that we could save our clients money by asking them to do all the QA. I made a big mistake by saving all the feature testing until the end of the sprint, just before the demo. I even leaned too hard on automated testing, letting it give me a false sense of security. From years of successes and failures, I have learned a few valuable lessons. I hope my experiences can help you succeed in your next project!

## Lessons Learned


### 1. Customers should not do QA
Custom software is expensive. Our customers pay a lot for the products they entrust us to build. The truth is, we CAN build great software and do it REALLY well. Great architecture, clean code, maintainable, best practices, best technology, best everything... But if our customer sees even one bug, his confidence begins to erode. Bugs are a reality of software development. And customers will eventually see some bugs because it's humanly impossible to eradicate the all. But having a customer do QA is like hooking a firehouse up to someone's mouth and turning it on full blast. If one bug erodes a little trust, then seeing ALL the bugs is devastating. Customers, by no means, should be made to do their own QA.

### 2. Automated testing is not enough
Manual repetition, for a programmer, is like fingernails scraping a chalkboard. Programmers love to automate things, and nothing makes a programmer happier than when he can hand off a repetitious task to a piece of software. As we write software, we need to constantly test all previously written code to make sure the new code doesn't break anything. If we did this manually, it would be almost impossible to write any software because of the enormous amount of time it would take. So, we automate our tests. We can even maintain close to 100% test coverage, being able to run through hundreds of tests in seconds and excersizing every single line of code that we have written. We've found this process to be essential to reducing bugs and designing maintainable software. But, automation can only test what the programmers expect to happen. It can't cover misunderstood requirements, and it's unlikely to cover every possible success or failure outcome. Automated testing is awesome, but it's not enough!

### 3. Waiting until the end is not enough
What should you do after a car comes off the assembly line? Well, take it for a spin and look for any problems, of course! I've heard software development compared to car manufacturing many times. And there might be some overlap, but I like the analogy that one of our advisors gave better: "Software development is like a science experiment." The car manufacturing analogy falls down when it comes to testing. You see, writing software is a series of attempts, successes and failures. If we wait until the end of a sprint to test our theories, then we miss the opportunity to fix things before they affect their surroundings. We also risk having to delay a demo because of last minute fixes. If we have someone testing features immediately after they are "finished", the developers can get feedback on their work much faster and can fix bugs with the benefit of a fresh memory. Manual testing anytime is better than nothing, but software development is not the same as car manufacturing. Waiting to test until after the software comes off the assembly line is not enough.

### 3. Programmers are not enough
Programmers are awesome! But they suck at QA. The best programmers lose themselves in their code, getting their hands dirty in the tiniest details of software and, in the end, making it sing. They spend almost the entire day with their nose to the grindstone. They work hard to deliver their best understanding of a feature, trying to give the customer exactly what they want. When a programmer checks off the last box on a mental list of 1000 tasks for one feature, she feels accomplished and proud. If you ask her if it's done, she'll say confidently, "yes!" Problem is, she has spent all this time in one tree. She has no idea about the forest, nor her tree's affect on the forest. It takes someone else who has a good grasp on the forest, the big picture, the whole project, who can give a more informed answer. Don't ask programmers to do QA. It's not fair to them and it won't give you the results you need. Programmers are just not enough.

## Quality Should Not Be An Option
Whether you are a software developer, department director, or CEO, you should expect and demand quality. When working with a software development team, make sure that there are QA testers working alongside software developers, ready to quickly test developers' work and provide rapid and constant feedback. Bugs are the enemy of any software project, and the faster you can kill them, the less effect they have on your success. Great QA can get you there.
