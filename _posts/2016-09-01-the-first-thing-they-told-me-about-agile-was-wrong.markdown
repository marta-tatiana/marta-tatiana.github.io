---
published: true
title: The first thing they told me about Agile was wrong.
layout: post
---
I remember my first Agile and Scrum training (both explained and done in one session). The trainer started with convincing comparison. ‘You’re lucky’, he said. ‘You are not building a house. When one is building a house, once a decision is made, it cannot be undone. Once fundaments are ready, there is no changing and no going back. It takes time and costs a lot, and there is no option to tear down a house and start over, again, from scratch’. ‘And with software, you  have the luxury of working in iteractions, making incremental changes and incremental progress. Each iteration, you can create better product than in previous iteration’. At that time, we all nodded our heads. Then, he spent rest of the training explaining us what Scrum is and what are its necessary practices and meetings.

He made it sound like 

* you can be agile, working on any software project in the world

* getting better is about starting from scratch, over and over.

And now I know, he was wrong. 
He said, it’s not like building a house. But if you are working on legacy product or a system, it takes 6 months or a year or 1.5 to release, doesn’t it sound like a timeframe to build a house? Worst case, a garage? If it takes 2 years, from the moment you put something to code, until someone actually uses it, isn’t it similar to when a person could expect moving to newly built house? If you work on a project that has become a tangled hell of dependencies, there is no longer anyone understanding it around, change comes at a cost… isn’t it somewhat similar to the cost of moving a wall, or changing existing electrical installation? Guess what, if you work on such project and someone comes and make you implement Scrum, it won’t make you any tiny bit more agile. 

The necessary conditions for being agile are quick feedback loop and decent design, that actually supports responding to change. If you don’t have one of them, change that. No number of Scrum meetings and discussions on supperiority of a whiteboard over the cork board with notes for your Kanban will make you more agile. What will make you more agile, is good design. If you don’t have it, refactor. Adapt good software craftsmanship practices and fight for a clean code. As I see it today, the main role of agile evangelists in the team should be making sure that there are technical means for being agile, instead of training people how to express their thoughts in non-offensive manner during retrospective meetings.

What makes me so nervous about some attempts to introduce agile and what I suspect is the source of alleged hatred to agile among programmers, is lacking the connection with reality. There is a codebase and there is time that passes before newly written line of code can affect user’s life. If the codebase is written in a way not supporting changes, you won’t be agile, even if you try implement Scrum. Worst case, it may not be possible to implement it at all because you won’t be able to get down to sensible sizes of tasks. In such case, it’s the codebase that needs to change and that should be the first focus of the agile transformation. Yet, sadly, I have never been to agile training that would focus - or even mention - technical aspects of agility. 

Dear manager, next time you want’t to pay for some agile training, train people to refactor.