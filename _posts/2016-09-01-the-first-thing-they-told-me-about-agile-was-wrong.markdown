---
published: true
title: The first thing they told me about Agile was wrong.
layout: post
---
I remember my first Agile and Scrum training (both in one session). The trainer started with convincing comparison. ‘You’re lucky’, he said. ‘You are not building a house. When one is building a house, once a decision is made, it cannot be undone. Once fundaments are ready, there is no changing and no going back. It takes time and costs a lot, and there is no option to tear down a house and start over, again, from scratch’. ‘And with software, you  have the luxury of working in iteractions, making incremental changes and incremental progress. Each iteration, you can create better product than in previous iteration’. At that time, we all nodded our heads. Then, he spent rest of the training explaining us what Scrum is and what are its necessary practices and meetings.

He made it sound like you can be agile, from day 0, working on any software project in the world - just divide your work in 2-weeks iterations, you will be fine.
He was obiously wrong. 

He said, it’s not like building a house. But if you are working on legacy product or a system, which will be released in one year, doesn’t it sound like a timeframe to build a house - or at least, a hut? If it takes 2 years, from the moment you make changes in code, until someone actually uses it and (hopefully) benefits from it, isn’t it similar to when a person could expect moving to newly built house? If you work on a project that has become a tangled hell of dependencies, while there is no longer anyone understanding it around, change comes at a cost… isn’t it somewhat similar to the cost of moving a wall, or changing existing electrical installation?
If you work on such project and someone comes and make you implement Scrum (or Kanban or SAFE), it won’t make you any tiny bit more agile. 

The necessary conditions for being agile are quick feedback loop and decent design, that actually supports responding to change.  No number of Scrum meetings or discussions on supperiority of a whiteboard over the cork board with notes for your Kanban will make you more agile. There are two technical means that will make you agile - good design and continous deployment.

As I see it today, the main role of agile evangelists in the team should be making sure that there is technical focus on those two, instead of curiosities like training people how to express their thoughts in non-offensive manner during retrospective meetings. There must be time for knowledge crunching, looking for better design and refactoring. There must be discipline in creating contious deployment enviornment and zero tolerance to manual hacks and "just logging to the server to fix this small issue". 

What makes me so nervous about some attempts to introduce/improve agile and what I suspect is the source of alleged hatred to agile among programmers, is lacking the connection with technical reality. There is a codebase and there is time that passes before newly written line of code can affect user’s life. If the codebase is written in a way not supporting changes, you won’t be agile, even if you try implement Scrum. It’s the codebase and its deployment that needs to change and that should be the first focus of any agile transformation. Yet, sadly, I have never been to agile training that would mention those technical aspects of agility. 

You cannot be agile, when working on a house. Same way, you cannot be agile, when working on a software product, which is not agile. The product itself and technical environment can be - and often is - a restriction. 